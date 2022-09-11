# Azure

Just a snapshot of brain for continously learning and reference.

### Product Domain
| Product | Domain |
| ------- | ------ |
| App Service | *.azurewebsites.net |
| App Gateway | *.azure-api.net |
| B2C Tenant | *.onmicrosoft.com |
| Storage Account (Blob) | https://\*.blob.core.windows.net/\* |\

### Event
| Product | Similar Product(s) | Features |
| ------- | --------------- | ---------- |
| Event Grid | Redis (Pub/Sub) | Low cost. Event Grid delivers event to subscribed client (Function App, Web hook or Event Hub, etc.) rather than actively subscribe by program. Event Grid = Topic
| Event Hub | Kafka | High cost. Just like Kafka with partition, but Namespace = Cluster, Event Hub = Topic. Support Kafka client to connect.
| Service Bus | ActiveMQ, RabbitMQ | |

### Serverless
| Production | Similar Product |
| ---------- | --------------- |
| Logic App | Activiti, BPM |
| Function App (Azure function) | |
| App Service | Heroku |

<br /><br />
**_Author: Steve Mak_**
_Last Update: 9/11/2022, 5:23:05 PM_