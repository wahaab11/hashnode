## How To Choose the Best Platform for web Projects

AWS vs Azure vs Firebase vs Heroku vs Netlify—How To Choose the Best Platform for Web Projects 
Lots of factors go into deciding on the right platform.

Web and mobile development has come a long way in recent years. Modern web applications are often built based on powerful JavaScript features like Angular, React, and Vue.js. While you could host those web applications anywhere, you may need more than only hosting. Different big cloud companies like Google, Amazon, and Microsoft are offering practically anything you can ask for, while upcoming competitors like Netlify want to provide an impressive UX for building modern websites.

In this article, I want to focus on web-based projects. We will look at the following platforms:

Amazon Web Services (AWS)
Microsoft Azure
Firebase / Google Cloud Platform
Heroku
Netlify
Keep in mind that this is just a short look into this topic. There are many factors to consider depending on your project size and needs, such as:

Costs: some platforms are rather cheap at the beginning but become much more expensive when you use them more intensively
Performance: some platforms fare better than others
Features: while some platforms have a more dedicated focus (e.g. web projects), some larger platforms want to provide you a full-service solution to keep you in their ecosystem
Availability in your region (e.g. due to regulations like GDPR)
Compliance & IT security (e.g. ISO/IEC 27001 certified)
Support: when running into problems great customer support is highly appreciated
Let’s get started and have a look at what these platforms can do for us.


![1_In1LWtkXkp4xNo1tub4NqQ.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1601903573860/w8LPTMsrE.png)

Image source: Amazon

Amazon Web Services (AWS) 
Amazon Web Services has been in the cloud computing market for quite some time. No matter what you might need: AWS probably offers it. AWS offers many products with cool names like:

Amazon S3 (cloud storage)
Amazon EC2 (virtual servers)
Amazon DynamoDB (managed NoSQL database)
AWS Device Farm (test Android, iOS, and web apps on real devices in the AWS cloud)
Netflix, Unilever, and Samsung use AWS. You can get one free year, which should be plenty of time to get a grasp. However, since AWS has grown a lot over the years, the usage is not always intuitive.

AWS fulfils ISO 27001 and SOC2


![1_P8GgRLQaOTwd9JwLQAVr5A.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1601903550601/rQcINoRDh.png)

Image credit: Microsoft

Microsoft Azure 
Microsoft Azure is one of the top cloud computing platforms. Similar to AWS, Azure has everything you will need. Microsoft offers special programs for startups which provide free limited access to Azure services. Azure offers services like:

Azure Kubernetes Service (simplifying the deployment, management, and operations of Kubernetes)
Azure DevOps (services for teams to share code, track work, and ship software)
Web Apps (Quickly creating and deploying web apps at scale)
Azure Cosmos DB (globally distributed, multi-model database)
Leading companies like Adobe, BMW, and HP rely on Azure. Microsoft has a very good standing in B2B, which is why many large corporations prefer Microsoft Azure. Similar to Amazon, the Azure UI is rather complex, which can be challenging for new users.


![1_y7pEGBne39DTLnugCfruXg.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1601903529407/ZGpHP_ZNP.png)

Image credit: Firebase/Google

Firebase / Google Cloud Platform 
Firebase is a development platform owned by Google. Technically, Firebase is using the Google Cloud Platform. PayPal, Twitter, and Target are customers of Google Cloud. Thanks to the experience of Google, Firebase offers many useful services like:

Cloud Functions (running code without managing servers)
Test Lab (testing your app on devices hosted by Google)
Google Analytics (free and unlimited app analytics)
ML Kit (machine learning for mobile developers)
Many developers love Firebase because of its strong tooling and its powerful Google infrastructure. However, especially due to GDPR and increasing strict data protection policies, some companies want to avoid using Google infrastructure.

Being a Google product has its upsides and downsides which applies to Firebase as well. Even though Firebase seems to perform quite well, we all know what happens to Google products which don’t live up to expectations.


![1_C514ItaHTpeHtD_15tMD8Q.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1601903502944/XvtQWHIAn.png)

Image credit: Heroku

Heroku 
Heroku is a Platform as a Service owned by Salesforce, an American cloud-based software company which is mostly known because of their CRM solutions. The free version of Heroku is fine for experimenting, but the server will sleep after some time of inactivity. There are lots of free and paid add-ons which provide additional functionality like:

Apache Kafka
MongoDB
New Relic
Send Grid
While Heroku used to be rather unique when it started, it has slowed down when it comes to innovation and competition has caught up.

Heroku supports most popular languages like Java, Python, and JavaScript. Also, Heroku provides a CLI which you can use to deploy with one command. Citrix, Toyota, and Unsplash are known to use Heroku.

Fun fact: Heroku’s physical infrastructure and managed within Amazon’s secure data centers and utilize the AWS technology.


![1_6EwWSBknlxfk-zErn-d8DQ.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1601903479542/_3om3IFsF.png)

Image credit: Netlify

Netlify 
Netlify is a rather new contender. The free version is already quite generous and there is no sleeping, unlike with Heroku’s free version. The UX and the features Netlify provides make working with it seamless and intuitive. Some of the powerful add-ons Netlify provides are:

Analytics (GDPR compliant)
Functions (easy deployment of AWS Lambda functions)
Forms (management of forms and submissions without server-side code or JavaScript)
Identity (management of signups, logins, password recovery, and more without a custom authentication service)
The downside is that cloud providers like Microsoft and Amazon offer way more functionality beyond web projects. Besides, you also cannot use other programming languages like Java or C# since Netlify promotes the usage of JAMstack. However, you can use Functions as an alternative to server-side languages like Java or C#.

Companies like WeWork, Verizon, and Nike are users of Netlify. Also, some popular open-source projects like Vue.js and Kubernetes have decided to use Netlify.

I have previously written an article about how to deploy an Angular app on Netlify:

Conclusion 
As you can see, there are lots of options to choose from.

For hosting web applications, Netlify has become my favorite platform. It is fast, it has great support, and it is simple to use. Besides, the product is growing fast.
Heroku is my go-to platform when I need to host a Node.js based backend. I’d recommend Heroku if you want to spin easily up a microservice and have it deployed in a matter of minutes
Firebase is an interesting platform which I have yet to work with on larger projects. It’s a good choice for getting started, especially if you’re working on mobile apps for Android and iOS.
Azure and AWS are reasonable choices if you work either in a huge project or if you need the vast amount of features and products which both Azure and AWS offer. Both Azure and AWS also fare better when IT security is highly relevant for you (e.g. for banks) since they have higher security standards than younger competitors like Netlify.