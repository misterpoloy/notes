# Stack ideas
### #chat #maps #mobile-app
These are some ideas with resources and technical material of the tools that are needed to develop a mobile application, Android or iOS.
I put links resources to their integrations with external services like maps, chat, and authentification.

## Backend
#### Infraestructure
For the infrastructure, as it is a message-oriented application. My suggestion is to make it as serverless as possible. Serveless means not having to manage the infrastructure for us. Instead, use tools that scale automatically like Google's Firebase or AWS's Amplify.
- [Firebase](https://firebase.google.com/docs/cloud-messaging)
- [Amplify](https://aws.amazon.com/es/amplify/)

#### Database
For the database, my suggestion is to go for a solution that allows us to scale automatically. If we continue with the serverless model, I see non-relational databases as good candidates. In general, they are good options for real-time information and messaging systems.
- [DynamoDB](https://firebase.google.com/docs/cloud-messaging)
- [Firebase Real time database](https://firebase.google.com/docs/database)

## Event driven design with Kafka
Having the advantage of building the application from scratch, the design pattern through events is an excellent alternative.
- [Kafka](https://www.confluent.io/lp/apache-kafka/?utm_medium=sem&utm_source=google&utm_campaign=ch.sem_br.nonbrand_tp.prs_tgt.kafka_mt.xct_rgn.latam_lng.eng_dv.all_con.kafka-general&utm_term=kafka%20apache&creative=&device=c&placement=&gclid=Cj0KCQjw1tGUBhDXARIsAIJx01lf6gTZ1h_DS-ip-doxUhT5BBtAyKZ19qOe2KPSSTc2MARK5MGL7EMaAmZ4EALw_wcB)
 
 ## Frontend (Product)
### Crossplatform
The advantage of an application of this type is that it is not demanding at the hardware level, which makes it an excellent candidate for hybrid options such as React native. React native will allow you to compile the native mood app for iOS and Android respectively. And it can be managed from a single repository.
- [React Native](https://reactnative.dev/)

## 3th Party services
- [Google](https://github.com/react-native-maps/react-native-maps) Maps to generate the UI
- [Apple signing](https://aws.amazon.com/es/blogs/mobile/enable-sign-in-with-apple-on-your-app-with-aws-amplify/)
- [Auth0](https://aws.amazon.com/es/blogs/apn/implementing-multi-factor-authentication-in-react-using-auth0-and-aws-amplify/#:~:text=Benefits%20of%20Integrating%20Auth0%20with,in%20any%20of%20your%20apps) is to manage the user authentification.

