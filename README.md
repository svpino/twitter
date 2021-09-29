# The Twitter Archive
Here is a compilation of the most relevant content I've posted on Twitter since the end of July 2020. Most of these are threads where I've tried to convey as much actionable and helpful ideas as possible. Some are just individual thoughts in the form of tweets. I pushed those to the bottom of the list.



 
* [The importance of learning curves](https://twitter.com/svpino/status/1369278050970525707?s=20) — Learning curves are a popular way to understand your data and your model. An underrated technique is to display the error of the model as we progressively increase the dataset size. This will allow us to determine whether we are overfitting or underfitting.

* [Baseline models](https://twitter.com/svpino/status/1369975138834395145?s=20) — Before you start building a machine learning model, a good approach to guide your progress is to create 3 **baselines** that will help you understand the problem and where you are headed.

* [Introduction to Dropout](https://twitter.com/svpino/status/1371108331922808832?s=20) — A good way to understand how things work is by breaking them down step by step. We are going to do this here with Dropouts and get to the bottom of what happens when we use them. 

* [Why do we use ReLU in deep learning?](https://twitter.com/svpino/status/1374086498455330819?s=20) — A quick summary of the reasons we prefer to use ReLU as the activation function when using deep learning instead of Sigmoid or TanH. 

* [25 True|False questions](https://twitter.com/svpino/status/1378340070709690372?s=20)

* [The backbone of a machine learning system](https://twitter.com/svpino/status/1379426242957438978?s=20) — There are a lot of moving pieces on a machine learning system, so this thread covers the core components of it.

* [11 key machine learning concepts](https://twitter.com/svpino/status/1342711745475973125?s=20)

* [When the validation loss is lower than the training loss](https://twitter.com/svpino/status/1423569964112429060?s=20). I built a machine learning model, and my validation loss is lower than my training loss. People asked me why. We're used to seeing the opposite, so this is definitely suspicious. Is this really a problem?


## Mathematics

* [Math is hard, but you shouldn't be scared](https://twitter.com/svpino/status/1343542479845531650?s=20) — I told everyone that I didn't care. _"Screw math! I've never been great with it, so I'm not starting with machine learning to fail at the end."_ That was many years ago. Math is still hard, but I don't think you should be scared at all. Here is why.

* [Math resources for machine learning](https://twitter.com/svpino/status/1381478444773609475?s=20) — If you are looking to get a background in math before starting with machine learning, here is all the material you need covering the following topics: _Probabilities & Statistics_, _Linear Algebra_, and _Multivariate Calculus_. More than enough to get started.


## Probabilities and Statistics

* [An introduction to the basic principles of probabilities](https://twitter.com/svpino/status/1435166402730672134?s=20) — If you want to become a better gambler, you need to learn probabilities. Let's talk about the basic principles of probabilities that you need to understand.

* [Probabilities in a continuous context](https://twitter.com/svpino/status/1438065219448803328?s=20) — Imagine I tell you this: _"The probability of a particular event happening is zero."_ Contrary to what you may think, this doesn't mean that this event is impossible. In other words, events with 0 probability could still happen! This seems contradictory. What's going on here?

* [De Méré's Paradox](https://twitter.com/svpino/status/1435890900895473670?s=20) — Antoine was born in France back in 1607. Despite not being a nobleman, he called himself "Chevalier De Méré," and spent his days as any other writer and philosopher at the time. But the Chevalier liked gambling, and was obsessed with the probabilities surrounding the game.

* [An introduction to Bayes' Theorem](https://twitter.com/svpino/status/1438789975227699200?s=20) — The doctor tested me, and I came back positive for a disease that infects 1 of every 1,000 people. The test comes back positive 99% of the time if the person has the disease. About 2% of uninfected patients also come back positive. Do I have the disease?

## Feature engineering

* [An introduction to Label and One-Hot encoding](https://twitter.com/svpino/status/1364923419922493444?s=20) — Encoding features from a dataset is a very common transformation that data scientists have to do before running machine learning algorithms. This is an explanation of Label and One-Hot encoding, how they work and how to use them.


## Fundamentals

* [Splitting your datasets](https://twitter.com/svpino/status/1359827674097672195?s=20) — I'm sure you've heard that we split our datasets into different subsets right before running our machine learning algorithms. This is an explanation of why we do that, the goal of each subset, and how to use them.

* [Random splits aren't always a good solution](https://twitter.com/svpino/status/1377975882179039232?s=20) — When we start with machine learning, we learn to split our datasets in testing and training by taking a percentage of the data. Unfortunately, this practice could lead to overestimating the performance of your model.

* [Everything you need to know about the batch size](https://twitter.com/svpino/status/1358286876822679552?s=20) — When using Gradient Descent, the batch size is one of the most consequential hyperparameters at our disposal. This is an explanation about the influence of the batch size.

* [Are you overfitting to the validation set?](https://twitter.com/svpino/status/1371433872869711872?s=20) — You aren't doing yourself any favors if you aren't throwing away your validation data regularly. It's painful, I know, but you are looking for trouble if you don't do it. Let's talk about what happens with your data and your model.

* [Metrics and imbalanced classification problems](https://twitter.com/svpino/status/1357302018428256258?s=20) — I built a model to predict whether you'll be involved in a crash next time you get in a car. And it's 99% accurate! Allow me to show you.
 
* [Cheating with a data leakage](https://twitter.com/svpino/status/1425019257449025536?s=20) — Can you identify the problem with this 3-step approach? 1. Prepare a dataset, 2. Split it (train, validation, and test sets), 3. Build a model. The issue is subtle, and unfortunately, many people build machine learning models this way. Let's talk about this.

* [Generalization and neural networks](https://twitter.com/svpino/status/1360462217829900290?s=20) — It takes a single picture of an animal for my son to start recognizing it everywhere. Neural networks aren't as good as we are, but they are good enough to be competitive. This is an explanation of how neural networks generalize.

* [An intuitive look into convolutions](https://twitter.com/svpino/status/1359107240519749637?s=20) — How the heck can a computer recognize what's in an image?
This is an introduction about convolutions, a key part of how Convolutional Neural Networks work.

* [Using PCA to remove a picture's background](https://twitter.com/svpino/status/1377255703933501445?s=20) — A really useful machine learning algorithm is PCA. You can do cool things with it, like completely removing the background of a picture (robust PCA).

* [An example of dimensionality reduction](https://twitter.com/svpino/status/1443168842335850497?s=20) — This is a great example of dimensionality reduction using single value decomposition on a dataset of images. We can go from 64 dimensions down to 5 dimensions and still recognize the images!

## Machine learning techniques

* [An overview of Active Learning](https://twitter.com/svpino/status/1365307434856820736?s=20) — Imagine you have a ton of data, but most of it isn't labeled. Even worse: labeling is very expensive. How can we get past this problem? Let's talk about a different—and pretty cool—way to train a machine learning model.

* [An introduction to Siamese Networks](https://twitter.com/svpino/status/1365683368030052355?s=20) — You want to build a face recognition system for your office, but getting many pictures from your coworkers is not a choice. Also, having to retrain the model for every new employee seems like a burden. How do we solve this?

* [An introduction to Transfer learning](https://twitter.com/svpino/status/1372532791922069511?s=20) — The ability to reuse the knowledge of one model and adapt it to solve a different problem is one of the most consequential breakthroughs in machine learning. This is a thread explaining Transfer learning and how we can use it in practice.

* [How to implement Transfer Learning](https://twitter.com/svpino/status/1376543596954984448?s=20) — With Transfer Learning you can reuse the knowledge from a different model to kick-start your new model. Practically, this is how you can do transfer learning.

* [An introduction to Autoencoders](https://twitter.com/svpino/status/1381253209163988998?s=20) — A lot in machine learning is pretty dry and boring, but understanding how autoencoders work feels different. This is a thread about autoencoders, things they can do, and a pretty cool example.


## Building a machine learning career

* [This is why you want to get into machine learning](https://twitter.com/svpino/status/1302107301424369664?s=20) — One of the best steps I’ve taken as a Software Engineer has been to get into machine learning. If you are looking for what's next in your career, here are some pointers to get you started

* [Takeaways about starting with machine learning](https://twitter.com/svpino/status/1379809571254976516?s=20) — 16 key takeaways about starting a career as a machine learning engineer.

* [12 skills for data scientists and machine learning professionals](https://twitter.com/svpino/status/1305365043673001989?s=20) — Here are 12 skills that you wanna add to your Data Science/Machine Learning resume. The first 6 are foundational and important. The other 6 are in crazy high demand, harder to build, and will set you apart.

* [Strategies to start with machine learning at your company](https://twitter.com/svpino/status/1379013206371397633?s=20) — Many people who want to start with machine learning think they can't do it at their current company. But more often than not, this is not the case. These are things you can do to get past this.

* [A step-by-step guide to start with machine learning](https://twitter.com/svpino/status/1304630248697483265?s=20) — A step-by-step guide to getting started with machine learning for beginners looking to get on it right away.

* [10 most frequently asked questions to get into machine learning](https://twitter.com/svpino/status/1302829097106767872?s=20) — I always get asked a ton of questions about machine learning. I decided to build a short FAQ to help you move forward. Here are my answers to the 10 most frequently asked questions about getting into machine learning.

* [You always need a combination of theory and practice](https://twitter.com/svpino/status/1442806742266560519?s=20) — _"You can't use an algorithm unless you understand how it works."_ That's what many people say. But I don't believe it. Here is how you can build expertise.

* [My Masters in Computer Science with a Machine Learning Specialization](https://twitter.com/svpino/status/1303535479929933825?s=20) — It took me 4 years to complete my Master's while I was working full time (2015 - 2019). It's a Master of Science in Computer Science with a Machine Learning Specialization. Here are all courses I had to complete to finish the program.


## Questions and projects

* [10 Computer Vision project ideas](https://twitter.com/svpino/status/1298468656725327872?s=20) — Do you wanna start getting your hands dirty with machine learning and Computer Vision? Here you have 10 projects to start practicing and improve your portfolio.

* [20 fundamental questions you need to ace](https://twitter.com/svpino/status/1303907685214154752?s=20) — Here are 20 fundamental questions that you need to ace before getting a machine learning job. Almost every company will ask these to weed out non-prepared candidates. You don't want to show up unless you are comfortable having a discussion about all of these.  

* [How to build a portfolio when looking for a job?](https://twitter.com/svpino/status/1440270119247048711?s=20) — One issue I see with people applying for a job: They struggle to highlight their experience in an effective way. If you are trying to get a job as a Data Scientist or Machine Learning Engineer, here is something you can do.


## Machine learning in the real world

* [Questions when building a machine learning project](https://twitter.com/svpino/status/1402188796066635778?s=20) — There are 4 stages in the machine learning project lifecycle. Here are 29 questions that you should ask at each step of the process.

* [A classification problem that turns ugly quickly](https://twitter.com/svpino/status/1369673069955080204?s=20) — Let's imagine a system where you submit a bunch of pictures of an object, and it recommends a price range in which the object could be sold. To identify the object, we could build a classification model. It turns out, however, that things can get complex really quick.

* [A day in the life of a Machine Learning Engineer](https://twitter.com/svpino/status/1293141577540538370?s=20) — Do you want to know what a day in the life of a Machine Learning Engineer looks like? I'm not gonna make this boring and talk about biking, coffee, or hipster stuff. Instead, I'll list some of the things that you may find yourself doing.


## Examples

* [Solving MNIST using a CNN](https://twitter.com/svpino/status/1364539168567746563?s=20) — Explaining a solution line by line is always fun. This thread goes to an excruciating amount of detail through a **Convolutional Neural Network** that solves the **MNIST** problem. An explanation for every single line of code. 

* [A few problems you can solve using KNN](https://twitter.com/svpino/status/1375813074054230016?s=20) — The perfect way to get into machine learning is to find an algorithm that improves your work right away without much drama. For software developers, KNN (K-Nearest Neighbors) is a perfect introduction. Here are five different problems where KNN could help.


----
----
----
----
## Machine Learning
A few years ago, I started focusing a big part of my efforts in applied Machine Learning. I'm specifically very interested in making Machine Learning applications work in real life and breaking down the walls that keep others from getting into the field.

* [The one about the problem that kicked off my interest in Machine Learning and changed my career](https://twitter.com/svpino/status/1308987528511401985?s=20). 
*Sep 23, 2020*.

* [The one where I mention that Machine Learning is usually not the right approach](https://twitter.com/svpino/status/1305891627248963584?s=20).  
*Sep 15, 2020*.

* [The one about understanding when we solved a Machine Learning problem](https://twitter.com/svpino/status/1304268407039315969?s=20).  
*Sep 10, 2020*.

* [The one with 6 high-profile projects that show algorithm bias](https://twitter.com/svpino/status/1303147115779108875?s=20).  
*Sep 7, 2020*.

* [The one about pursuing the "right" solution](https://twitter.com/svpino/status/1296185645673656321?s=20).  
*Aug 19, 2020*.

* [The one about 5 crazy cool Machine Learning projects I've been involved with](https://twitter.com/svpino/status/1295951164450770946?s=20).  
*Aug 18, 2020*.

* [The one about how I transitioned to the Machine Learning space](https://twitter.com/svpino/status/1294235627857248256?s=20).  
*Aug 14, 2020*.




## Software Engineering
Most of my writing revolves around general topics related to Software Engineering. Although there's a ton of technical stuff here, most of these aims to offer a more holistic view of the industry, and what I think matters to software developers.

* [The one about a good approach to get projects done](https://twitter.com/svpino/status/1310523646104961025?s=20).  
*Sep 28, 2020*.

* [The one about my interview process to hire Software Engineers](https://twitter.com/svpino/status/1309534720275832833?s=20).  
*Sep 25, 2020*.

* [The one about specializing in one thing or doing a little bit of everything](https://twitter.com/svpino/status/1307541246391595008?s=20).  
*Sep 19, 2020*.

* [The one about the approach I use to be as effective as possible when working on projects](https://twitter.com/svpino/status/1307178857968087041?s=20).  
*Sep 18, 2020*.

* [The one with 9 simple ideas to invest in your career](https://twitter.com/svpino/status/1302462025822547968?s=20).  
*Sep 5, 2020*.

* [The one where I share a letter to ask for a raise](https://twitter.com/svpino/status/1301385935330766849?s=20).  
*Sep 2, 2020*.

* [The one with a checklist to make sure your website doesn't suck](https://twitter.com/svpino/status/1301022040388808705?s=20).  
*Sep 1, 2020*.

* [The one about the metrics to measure developers](https://twitter.com/svpino/status/1300612293684756481?s=20).  
*Aug 31, 2020*.

* [The one where I talk about pricing strategies and charging money for your skills](https://twitter.com/svpino/status/1300269619513626626?s=20).  
*Aug 30, 2020*.

* [The one about good software design](https://twitter.com/svpino/status/1299943292793163776?s=20).  
*Aug 29, 2020*.

* [The one about reading your employment contract](https://twitter.com/svpino/status/1299693311658283009?s=20).  
*Aug 29, 2020*.

* [The one talking about two types of developers](https://twitter.com/svpino/status/1299188730729828352?s=20).  
*Aug 27, 2020*.

* [The one with the real conversation with the person that wants to grow their career](https://twitter.com/svpino/status/1298972475523567616?s=20).  
*Aug 27, 2020*.

* [The one about adding more people to a project](https://twitter.com/svpino/status/1298651526584569856?s=20).  
*Aug 26, 2020*.

* [The one about performance optimizations for computing at large scales](https://twitter.com/svpino/status/1298111119819714560?s=20).  
*Aug 24, 2020*.

* [The one where I talk about 16 different soft skills for every engineer](https://twitter.com/svpino/status/1297028799897403392?s=20).  
*Aug 21, 2020*.

* [The one about 10 side projects to improve your web development skills](https://twitter.com/svpino/status/1296648985957085190?s=20).  
*Aug 20, 2020*.

* [The one with the 50 sentences to become an amazing developer](https://twitter.com/svpino/status/1294494778399301632?s=20).  
*Aug 15, 2020*.

* [The one about evaluating if you are happy with your current job](https://twitter.com/svpino/status/1294016182450823169?s=20).  
*Aug 13, 2020*.

* [The one where I talk about all the problems of TDD](https://twitter.com/svpino/status/1293890835252236290?s=20).  
*Aug 13, 2020*.

* [The one where I talk about how to become a successful Software Engineer](https://twitter.com/svpino/status/1293680762106118144?s=20).  
*Aug 12, 2020*.

* [The one about splitting your time](https://twitter.com/svpino/status/1293511760323006464?s=20).  
*Aug 12, 2020*.

* [The one with some of the skills and tools that let me do my job](https://twitter.com/svpino/status/1293141584796700672).  
*Aug 11, 2020*.

* [The one about the importance of a portfolio](https://twitter.com/svpino/status/1292786063942070272?s=20).  
*Aug 10, 2020*.

* [The one about caching](https://twitter.com/svpino/status/1291336091182804992?s=20).  
*Aug 5, 2020*.

* [The one about getting good at estimates to make money as a Software Developer](https://twitter.com/svpino/status/1291068406704345089?s=20).  
*Aug 5, 2020*.

* [The one about whether you really need to learn algorithms and data structures](https://twitter.com/svpino/status/1290631063136542721?s=20).  
*Aug 3, 2020*.

* [The one about whether you need to get a Computer Science degree](https://twitter.com/svpino/status/1290468942142636032?s=20).  
*Aug 2, 2020*.

* [The one about getting you a better salary](https://twitter.com/svpino/status/1290104738436935680?s=20).  
*Aug 2, 2020*.

* [The one about multiplying your value and advancing your career](https://twitter.com/svpino/status/1289779816233947136?s=20).  
*Aug 2, 2020*.

* [The one about negotiating a salary doing an interview](https://twitter.com/svpino/status/1289431085525295105?s=20).  
*Aug 1, 2020*.

* [The one about using pre-browsing to make your websites faster](https://twitter.com/svpino/status/1288864175045914624?s=20).  
*Jul 30, 2020*.



## Python
I met Python in 2014, and I've never looked back. It's an incredibly versatile language with a huge, smart community backing it. How many of you can I convince to give it a try?

* [The one about virtual environments](https://twitter.com/svpino/status/1310665056544321536?s=20).  
*Sep 28, 2020*.

* [The one about 10 surprising Python features](https://twitter.com/svpino/status/1310439090073071617?s=20).  
*Sep 28, 2020*.

* [The one about the 10 libraries and tools that I use on every project](https://twitter.com/svpino/status/1309871516339798023?s=20).  
*Sep 26, 2020*.

* [The one about 10 simple programming exercises and their solutions](https://twitter.com/svpino/status/1309347657408753666?s=20).  
*Sep 24, 2020*.

* [The one about new features in Python 3 that you may not be using yet](https://twitter.com/svpino/status/1308632185113579522?s=20).  
*Sep 22, 2020*.

* [The one about building a script to schedule Twitter threads](https://twitter.com/svpino/status/1306987084612349958?s=20).  
*Sep 18, 2020*.

* [The one talking about Lambda functions in Python](https://twitter.com/svpino/status/1306905555181735936?s=20).  
*Sep 18, 2020*.

* [The one where I built the most outrageous giveaway selection process](https://twitter.com/svpino/status/1296280410343825408?s=20).  
*Aug 19, 2020*.

* [The one about pandas](https://twitter.com/svpino/status/1295573742387691520?s=20).  
*Aug 17, 2020*.

* [The one talking about Python for web development (Django, Flask, and FastAPI.)](https://twitter.com/svpino/status/1295209025156587521?s=20)  
*Aug 16, 2020*. 

* [The one with the script to clean up your Twitter feed](https://twitter.com/svpino/status/1293260942017527813?s=20).  
*Aug 11, 2020*.

* [The one about getting started with Python](https://twitter.com/svpino/status/1292085513311195137?s=20).  
*Aug 8, 2020*.

* [The one about Python being a great step if you want to get into Machine Learning](https://twitter.com/svpino/status/1291713199839084544?s=20).  
*Aug 7, 2020*.


## Less relevant stuff
I still like these threads. I think they are helpful, but they aren't technical, nor do they fit in any other category. 

* [The one with some strategies to improve the quality of the content you post on Twitter](https://twitter.com/svpino/status/1306070577841659904?s=20).  
*Sep 15, 2020*. 

* [The one where I share my essay to get into graduate school](https://twitter.com/svpino/status/1304081950060158977?s=20).  
*Sep 10, 2020*. 

* [The one where I show my setup at home](https://twitter.com/svpino/status/1299547364676579328).  
*Aug 28, 2020*.

* [The one about standing and speaking up](https://twitter.com/svpino/status/1298831177239887873?s=20).  
*Aug 26, 2020*.

* [The one about my Twitter strategy to get 8,000+ followers in less than a month](https://twitter.com/svpino/status/1297492897798004736?s=20).  
*Aug 23, 2020*.  


## Individual thoughts
These aren't threads. They are individual tweets that reflect on different technical topics, but I want to keep them separate to avoid drowning the more helpful, fully-fledged content.

* [The one about clean code and the relativity of things](https://twitter.com/svpino/status/1306261567369928704?s=20).  
*Sep 16, 2020*.

* [The one about the shortcut to improve as a software developer](https://twitter.com/svpino/status/1305527978370228226?s=20).  
*Sep 14, 2020*.

* [The one about writing code defensively](https://twitter.com/svpino/status/1304936083751198720?s=20).  
*Sep 12, 2020*.

* [The one about learning while building projects](https://twitter.com/svpino/status/1303048137976590336?s=20).  
*Sep 7, 2020*.

* [The one where I talk about focusing more on project management and less on estimates](https://twitter.com/svpino/status/1301602613272678400?s=20).  
*Sep 3, 2020*.

* [The one talking about irrelevant years of experience](https://twitter.com/svpino/status/1301271179064299520?s=20).  
*Sep 2, 2020*.

* [The one where I talk about project management being the issue with late projects](https://twitter.com/svpino/status/1301100303215816705?s=20).  
*Sep 2, 2020*.

* [The one about the mandatory step to write good code](https://twitter.com/svpino/status/1300726842337431562?s=20).  
*Sep 1, 2020*.

* [The one talking about how software is not linear](https://twitter.com/svpino/status/1299663084601081856?s=20).  
*Aug 29, 2020*.

* [The one talking about code being a means to an end](https://twitter.com/svpino/status/1299088802737205249?s=20).  
*Aug 27, 2020*.

* [The one about a good way of prioritizing your work](https://twitter.com/svpino/status/1298939546537807878?s=20).  
*Aug 27, 2020*.

* [The one about your agile process being too complicated](https://twitter.com/svpino/status/1298583470805934080?s=20).  
*Aug 26, 2020*.

* [The one about what you need to be a leader](https://twitter.com/svpino/status/1298290287798702080?s=20).  
*Aug 25, 2020*.

* [The one about the importance of solving problems above any titles](https://twitter.com/svpino/status/1298228489871675393?s=20).  
*Aug 25, 2020*.

* [The one about a question you can ask to determine what to do](https://twitter.com/svpino/status/1298198935811620864?s=20).  
*Aug 25, 2020*.

* [The one about surrounding yourself with smarter people](https://twitter.com/svpino/status/1297928754866552832?s=20).  
*Aug 24, 2020*.

* [The one about stopping learning when you get a job](https://twitter.com/svpino/status/1297861063279607809?s=20).  
*Aug 24, 2020*.

* [The one about the two rules that matter to end up with good code](https://twitter.com/svpino/status/1297585608211206145?s=20).  
*Aug 23, 2020*.

* [The one about being consistent with dates](https://twitter.com/svpino/status/1296576205194502146?s=20).  
*Aug 20, 2020*.

* [The one about multiplying yourself](https://twitter.com/svpino/status/1296467695584641028?s=20).  
*Aug 20, 2020*.

* [The one about simplicity versus flexibility](https://twitter.com/svpino/status/1295673083630686209?s=20).  
*Aug 18, 2020*.

* [The one about starting](https://twitter.com/svpino/status/1295443300032434178?s=20).  
*Aug 17, 2020*.

* [The one about every problem being your responsibility](https://twitter.com/svpino/status/1295332409962049539?s=20).  
*Aug 17, 2020*.

* [The one about my definition of good for a career in tech](https://twitter.com/svpino/status/1295107313838129152?s=20).  
*Aug 16, 2020*.

* [The one about those working from home that are just starting their careers](https://twitter.com/svpino/status/1295045645510770691?s=20).  
*Aug 16, 2020*.

* [The one about what you know being good enough for someone else](https://twitter.com/svpino/status/1294907245726248961?s=20).  
*Aug 16, 2020*.

* [The one about having access to all the knowledge in the world](https://twitter.com/svpino/status/1294698872497938432?s=20).  
*Aug 15, 2020*.

* [The one about being original](https://twitter.com/svpino/status/1293962149153382403?s=20).  
*Aug 13, 2020*.

* [The one where you decide whether your manager sucks](https://twitter.com/svpino/status/1293487393698242561?s=20).  
*Aug 12, 2020*.

* [The one about agile not being a silver bullet](https://twitter.com/svpino/status/1292599466327932931?s=20).  
*Aug 9, 2020*.

* [The one about technical debt](https://twitter.com/svpino/status/1291786757218893830?s=20).  
*Aug 7, 2020*.

* [The one about sacrificing quality not being a good trade-off](https://twitter.com/svpino/status/1291677967169531905?s=20).  
*Aug 7, 2020*.

* [The one about being in control as a developer](https://twitter.com/svpino/status/1291533303749771264?s=20).  
*Aug 6, 2020*.

* [The one about needing people to put models into production](https://twitter.com/svpino/status/1291464017626779648?s=20).  
*Aug 6, 2020*.

* [The one about not having time because you are writing bad code](https://twitter.com/svpino/status/1291450506729185280?s=20).  
*Aug 6, 2020*.

* [The one about not needing a Ph.D. or read papers to get into Machine Learning](https://twitter.com/svpino/status/1291352861067149312?s=20).  
*Aug 6, 2020*.

* [The one about optimizing your career for the long term](https://twitter.com/svpino/status/1291022459517501440?s=20).  
*Aug 5, 2020*.

* [The one about following the status quo](https://twitter.com/svpino/status/1290706326096576513?s=20).  
*Aug 4, 2020*.

* [The one about not needing to learn algorithms is a self-fulfilling prophecy](https://twitter.com/svpino/status/1290282768715280386?s=20).  
*Aug 3, 2020*.
