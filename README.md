---
page_type: sample
languages:
- java
products:
- azure
description: "Azure Service Bus basic scenario sample."
urlFragment: service-bus-java-manage-queue-with-basic-features
---

# Service Bus Queue Basics (Java)


  Azure Service Bus basic scenario sample.
  - Create namespace with a queue.
  - Add another queue in same namespace.
  - Update Queue.
  - Update namespace
  - List namespaces
  - List queues
  - Get default authorization rule.
  - Regenerate the keys in the authorization rule.
  - Get the keys from authorization rule to connect to queue.
  - Send a "Hello" message to queue using Data plan sdk for Service Bus.
  - Delete queue
  - Delete namespace
 

## Running this Sample

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

```bash
git clone https://github.com/Azure-Samples/service-bus-java-manage-queue-with-basic-features.git
cd service-bus-java-manage-queue-with-basic-features
mvn clean compile exec:java
```

## More information

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
