# Send Text Messages

This is a Geotab API console example of sending text messages. It illustrates how to send a basic message, canned response message and location message.

Steps:

1. Process command line arguments: Server, Database, Username and Password.
1. Create Geotab API object and Authenticate.
1. Send a basic text message.
1. Send a canned response Text Message.
1. Send an GPS location Text Message.

## Prerequisites

The sample application requires:

- [.Net core 2.0 SDK](https://dot.net/core) or higher

## Getting started

```shell
> git clone https://github.com/Geotab/sdk-dotnet-samples.git sdk-dotnet-samples
> cd sdk-dotnet-samples
> cd TextMessage
> dotnet run "my.geotab.com" "database" "user@email.com" "password"
```

### Parameters

`dotnet run <server> <database> <login> <password>`
Name | Description | Required
--- | --- | ---
server | The server name (Example: my.geotab.com) | true
database | The database name (Example: G560) | true
username | The MyGeotab user name | true
password | The MyGeotab password | true
