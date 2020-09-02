# IBMEventStreams
A sample Java application to produce and consume messages in Event Streams (Apache Kafka on IBM Cloud)

IBM Event Streams for IBM Cloud is a high-throughput message bus built with Apache Kafka. To get started with Event Streams and start sending and receiving messages, you can use the Java sample. The sample shows how a producer sends messages to a consumer using a topic. The same sample program is used to consume messages and produce messages.

## Step 1: Pre-requisites
a. An IBM Cloud account. [Register](https://cloud.ibm.com/registration)
The following needs to be installed:

-> [git](https://git-scm.com/)

-> [Gradle](https://gradle.org/)

-> Java 8 or higher

## Step 2: Create an Event Streams service instance.

a. Log in to the [IBM Cloud](https://cloud.ibm.com/) console.

b. Click the [Event Streams service](https://cloud.ibm.com/catalog/services/event-streams) in the Catalog.

c. Select the Lite plan on the service instance page.

d. Enter a name for your service. You can use the default value.

e. Click Create. The Event Streams Getting started page opens.

## Step 3: Create credentials for the Events Streams service instance.

To allow the sample application to access your topic, we need to create some credentials for it.

a. Go to Service credentials in the navigation pane.

b. Click New credential.

c. Give the credential a name so you can identify its purpose later. You can accept the default value.

d. Give the credential the Manager role so that it can access the topics, and create them if necessary.

e. Click Add. The new credential is listed in the table in Service credentials.

f. Click View credentials to see the api_key and kafka_brokers_sasl values.


