# Google Developers Products Exploration

* Nama : Raihan Astrada Fathurrahman
* NIM : 13519113

So, in this repository, I would like to tell you about my exploration results of Google Developer Products. The product that I'm interested in exploring was **Firebase**, one of many Google Developer Products. I decided to explore *Firebase* because it is a pretty popular product to most of the people that work in Information Technology (IT). Another factor why I decided to explore *Firebase* is because I'm currently learning mobile app & web development where *Firebase* is pretty popular in those fields of study. 

![Firebase Logo](https://upload.wikimedia.org/wikipedia/commons/b/bd/Firebase_Logo.png)
## :thought_balloon: What Is *Firebase*?
If you say that *Firebase* has something to do with mobile app & web development, then you're on the right track! 
*Firebase* is a backend service development platform that was developed by Google for helping developers create mobile and web applications. It is a product that consists of many services that can help developers to focus more on creation rather than the side things such as backend servers, servers scaling, crash reporting, and many other services to help you build a successful app. Firebase aims to help the users to build a better app, improve app quality, and also help users grow their business. 

## :confused: What can we do with *Firebase*?
As stated before, *Firebase* is a platform that consists of many services. In this part, I would like to tell you about some of the services that we can use in *Firebase* that can help us develop mobile apps or web development. Note that I'm only going to write four services because there are a lot of services that we can use in *Firebase* (currently 18 services), and it all has different usage.

**1. Realtime Database :clock1:**

One of the main-services of *Firebase*, Firebase's **real-time database**. It is a service that let us store and sync data between our app user in real-time. This service can make users access data from any device and also helps users collaborate. That happened because whenever we update data in the real-time database, it stores the data in the cloud and simultaneously notifies all connected devices in a matter of milliseconds. 
The real-time database is also optimizable for offline use. Whenever a user loses their connection, the database will use a local cache on the device to store the changes so that when the users come back online, their data will be up-to-date. The real-time database also has user-based security in the forms of database security rules that specify who has access to what pieces of data and how the database is structured. These security rules are stored within the real-time database on the servers.

**2. Firebase Hosting :link:**

The next service is **Firebase Hosting**. Firebase Hosting is a developer-focused static web hosting provider. With Firebase Hosting, we can deploy a single-page web app, a mobile app landing page, or a progressive web app. Files deployed with Firebase Hosting are cached on SSDs at CDN edge servers around the world so that it affects the content to be delivered relatively fast. Firebase Hosting can also automatically configure an SSL certificate for each site deployed so we can get our websites verified easily. 

**3. Google Analytics for Firebase :bar_chart:**

**Google Analytics for Firebase** was made to provide all the data that mobile app developers need in one simple place. Using analytics, it automatically provides insight for our apps. We will receive demographic insights of our users, how regularly they use our app, how much time they spent, and how much money they spent on our app. We can also get detailed information about what our users are up to by logging events specific to our app, for example, added an item to the cart in an online shop app or when a user completes a workout in a fitness app. 
With Analytics, we can also define custom audiences based on device data and user behavior by utilizing events and user properties and then use those segments for notifications, A/B tests, and Google Ads remarketing.

**4. Firebase Machine Learning :computer:**

Last but not least, we have **Firebase Machine Learning**, which is a relatively new service, and by the time this was made it is currently on Beta. Firebase Machine Learning is a set of tools for bringing powerful machine learning features to our app. 
We can use Firebase ML model deployment to distribute models to users. This process will reduce the initial app installation size since models are downloaded by the device only when needed. Another Firebase ML uses are, we can use it to train our custom model. With AutoML Vision Edge, we can create custom image classification models suited for our needs. For example, we want the app to be able to identify different types of food or distinguish between species of animals. We can also integrate our ML model from other Google Developer Product such as the TensorFlow Lite Model.

## :heavy_plus_sign: Pros and Cons :heavy_minus_sign:
As a product Firebase also have a pros and cons. Here are some of the pros and cons of Firebase.

### Pros
1. Database
Firebase real-time database is cloud-hosted, NoSQL databases that are flexible and scalable in terms of size. Firebase real-time database can also work with offline mode.
2. Free for beginners
Firebase doesn't charge most of its services and requires paying after reaching a certain amount of database memory, so it's great for beginners who want to try first before paying for the services.
3. Community
Firebase has technical documentation that can help us to understand more of its services. Also, there are a lot of apps around the world that were built using Firebase. A lot of product will certainly bring benefit to newer developers that are looking for an answer for their problems.

### Cons
1. Inconvenient Data Storage
One of the downsides of using real-time database is that it has limited querying capabilities. We can't query for more than one key at a time and the Firebase doesn't provide a way for us to filter the data. The whole database format is saved in JSON format and it's so different from the storage format of SQL.
2. Limited data migration
Because all data are hosted on Firebase, it strongly limits data migration unless Firebase provides an easier way to transfer user's data. In the case of trying to change the backend base, there is no way for us to transfers the app to another source.
3. Focused on Android
Although Firebase supports both android apps and iOS apps development, Android still gets most of the dedicated services. For example, Test Lab can be easily integrated with android studio and supports a wide range of android devices for testing. Meanwhile, iOS was provided with closed beta support for iOS and included a basic range of testing.

To sum it up, Firebase is useful all in one product that includes many services to help us develops mobile app or web development. However, if we are making a project that uses large data in it, it is not recommended because of the limits of our action regarding the data storage and data migration. 

###### This article was made for DSC ITB Assignment and there are still a lot of things that I didn't cover. For more information, you can kindly visit the Firebase's website listed below!
[![Firebase Website](https://img.shields.io/badge/-Firebase_Website-orange?&link=https://firebase.google.com/)](https://firebase.google.com/)
