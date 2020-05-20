# llSPS-INT-144-AI-Powered-News-Search-App-Level-1-
###### AI Powered News Search App (Level-1)<br/><br/>

Website: https://node-red-memna.eu-gb.mybluemix.net/ui/<br/>
Video Presentation:[Click to View](https://drive.google.com/file/d/1MWhQn3OP6v8qQgevassyZIZ-N2JO6x5Y/view?usp=sharing )  <br/><br/> 
## AI Powered News Search App using IBM Cloud Services<br/><br/>
The web is home to massive amounts of data, with more being created every day. Organizations can harness this constant stream of information to gain understanding, plan strategies, and find opportunities. Enriched news data can help your application make dynamic connections across current events faster.
<br/><br/>In this project, we built a NEWS mining web application starting with the basics, using Node-RED / Python Web App and the IBM Watson Discovery Service.
To do this we start by building a Server-Side Application using Node-RED then we use the pre-built Watson Discovery News collection and access the Watson Discovery Service through the Discovery API. Optionally, we can choose to use a Slack interface to query the data, push news alerts out to web notification and deploy the app on IBM Cloud. In this project, we’ll start with the basics and build our own news mining web application using Node-RED / Python Web App and the IBM Watson Discovery Service.
<br/><br/>
The project revolves around:
1. Building a Server Side Application using Node-RED 
2. Using the pre-built Watson Discovery News collection 
3. Accessing the Watson Discovery Service through the Discovery API 
 <br/>
Additionally, we include:<br/><br/>
1 Deploy the app on IBM Cloud.<br/>
2. Use a Slack interface to query the data <br/> 
3. Push news alerts out to web notification<br/>
We propose the use of IBM Discovery, IBM Watson and IBM Node-RED.
<br/><br/><br/>

![2 - Copy](https://user-images.githubusercontent.com/64114181/82390006-23b53100-9a5b-11ea-8c1f-5020e886c0b2.png)<br/>
1.	The user interacts with the app UI(Built with Node-RED or Cloud or Local) to request relevant news content.
2.	The app sends user requests to Watson Discovery News.
3.	The Watson Discovery Service is continually crawling the web to update its Discovery News collection.
4.	The Watson Discovery Service responds to Slack search requests.<br/>
•	Code is written in Node.js, with the server-side using the Express framework and the client using ReactJS.<br/>
•	The pre-built Watson Discovery News collection was used.<br/>
•	Access the Watson Discovery Service through the Discovery API.<br/>
•	Use a Slack interface to query the data<br/>

## FLOWCHART

![2 - Copy - Copy](https://user-images.githubusercontent.com/64114181/82390634-d89c1d80-9a5c-11ea-9de1-c6842535bab0.png)

## Result:
Node-Red Flow:
![1](https://user-images.githubusercontent.com/64114181/82389229-3595d480-9a59-11ea-9feb-9027bf5496fd.png)
<br/><br/>
Output: Main Search Page:<br/><br/>
![2](https://user-images.githubusercontent.com/64114181/82390065-49dad100-9a5b-11ea-8316-529a4f59e877.png)<br/><br/><br/>
![3](https://user-images.githubusercontent.com/64114181/82390134-827aaa80-9a5b-11ea-89e7-2e82df6a9d67.png)<br/><br/><br/>
![4](https://user-images.githubusercontent.com/64114181/82390458-61ff2000-9a5c-11ea-8e2f-d20c8863a1a5.png)<br/>
<br/>
Slack Integration:<br/><br/><br/>
![5](https://user-images.githubusercontent.com/64114181/82390484-75aa8680-9a5c-11ea-8803-58c4fc612459.png)</br>
<br/><br/>
![6](https://user-images.githubusercontent.com/64114181/82390490-7ba06780-9a5c-11ea-8f2f-eb92f9754d12.png)<br/></br>
![7](https://user-images.githubusercontent.com/64114181/82390497-80fdb200-9a5c-11ea-9e53-ddb897f96588.png)<br/><br/>

## Advantages and Disadvantages:<br/>
The following advantages and disadvantages are observed.<br/>
###### Advantages:<br/>
•	The app uses standard search UI components such as filter lists, tag clouds, and sentiment graphs, but also more complex Discovery options such as the passages and highlight features.
<br/>•	With these two features, the app identifies the most relevant snippets in your data based on your query and is more likely to return the data that you’re searching for.
<br/>•	News coming with sentiment analysis done and only singular commands are needed for slack to get the requested news.
<br/>•	The main benefit of using the Watson Discovery Service is its powerful analytics engine that provides cognitive enrichments and insights into our data. The app in this code pattern provides examples of how to showcase these enrichments through the use of filters, lists, and graphs.
<br/>•	The project makes use of slack that has multiple APIs to create bots and to create a connection to Slack. Any request to the bot user, to the bot directly, or from a Slack channel in which the bot is a member, is sent to the server that starts the connection. Slack uses the bot token as a means to authenticate and all of these works due to the use of the Real Time Messaging API
###### Disadvantages:<br/>
Application Programming Interface (API):
<br/>a.	One of the key problems that most of the developer’s encounter is the Application Programming Interface (API) keeps on changing at frequent intervals and does not remain stable.
<br/>b.	At times, a new API appears having a number of backwards-incompatible changes. As a result, the developers are forced to make changes in the accessible code bases to match the compatibility with the latest version of the Node.js API.
<br/>Sentiment Analysis:
<br/>a.	Sentiment analysis tools can identify and analyze many pieces of text automatically and quickly.<br/>
b.	But computer programs have problems recognizing things like sarcasm and irony, negations, jokes, and exaggerations.<br/>
## APPLICATIONS
•	A full fledged software or website with real-time applications
•	Can be used as an everyday-app to browse and get news real-time, anytime in the day
•	Sentiment analysis on the news articles and different types of data.
•	Getting news articles fast and reliable with score and other metadata information’s.
## CONCLUSION
This application uses individual out-of-the-box UI components to extract and visualize the enriched data provided by the Discovery analytics engine. The web application includes Sentiment analysis, slack integration and embedded using Node-Red. 
## FUTURE SCOPE<br/>
•	The future scope may include<br/>
•	Variations in phrasing<br/>
•	News search using audio and converting that using speech-to-text.<br/>
•	Tracking conversations<br/>
•	Adding language translator with audio to enable search and results in regional language.<br/>
•	Usage monitoring<br/>
•	Improving result relevance with the tooling<br/>
