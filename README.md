---
page_type: sample
languages:
- java
products:
- azure
extensions:
- services: Servicebus
- platforms: java
---

# Getting Started with Servicebus - Service Bus Publish Subscribe Advance Features - in Java #


  Azure Service Bus basic scenario sample.
  - Create namespace.
  - Create a service bus subscription in the topic with session and dead-letter enabled.
  - Create another subscription in the topic with auto deletion of idle entities.
  - Create second topic with new Send Authorization rule, partitioning enabled and a new Service bus Subscription.
  - Update second topic to change time for AutoDeleteOnIdle time, without Send rule and with a new manage authorization rule.
  - Get the keys from default authorization rule to connect to topic.
  - Send a "Hello" message to topic using Data plan sdk for Service Bus.
  - Delete a topic
  - Delete namespace
 

## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/service-bus-java-manage-publish-subscribe-with-advanced-features.git

    cd service-bus-java-manage-publish-subscribe-with-advanced-features

    mvn clean compile exec:java

## More information ##

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.