# .NET Core Port of simple-websockets-chat-app

This is a .NET Core port of the [simple-websockets-chat-app](https://github.com/aws-samples/simple-websockets-chat-app) sample for AWS Lambda. For more information [Announcing WebSocket APIs in Amazon API Gateway](https://aws.amazon.com/blogs/compute/announcing-websocket-apis-in-amazon-api-gateway/) blog post.

## Deploy

To deploy this sample use the the [AWS Lambda .NET Core Global Tool](https://aws.amazon.com/blogs/developer/net-core-global-tools-for-aws/).

To install the global tool execute the command. Be sure at least version 3.1.0 of the tool is installed.

```
dotnet tool install -g Amazon.Lambda.Tools
```

Download the [AWS Toolkit for Visual Studio](https://aws.amazon.com/visualstudio/)

Deploy the WebsocketChat project using the "Deploy to AWS Lambda..." context option. This will guide automatically create all relevant AWS resources.