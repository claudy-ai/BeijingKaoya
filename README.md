# BeijingKaoya
National AI Student Challenge 2022
1 minute video: https://youtu.be/dL04S4Sj8XU


# Steps to use BeijingKaoya Solution to chase birds away :) 
1. Install PeekingDuck on your computer 
- follow this https://peekingduck.readthedocs.io/en/stable/getting_started/02_standard_install.html#install-peekingduck

2. Ensure you have a webcamera installed to your computer 

3. Git clone this repo by pressing on the green button at the top right indicated as "code"

4. Navigate to the Yml file in the repo using "cd" command in your terminaland run the command 'peekingduck run; 



# Problem Statement : 

*Design and build a tool (app, dashboard, analysis) with AI Singapore’s AI Brick PeekingDuck (Computer Vision) and/or SGnlp (Natural Language Processing), that can help, assist, inform or entertain Singaporeans or businesses.*

A seemingly small issue yet faced daily during our 3 meals per day at hawker centers is Mynahs taking a bite of our food when we take our eyes off it. Therefore we aim to make the process of detecting birds in Hawker Centers simple and easily replicated using the AI Brick Peeking Duck in a easily repeatable solution using an application. 


# Category B Submission
AI Brick chosen: PeekingDuck (Computer Vision), using “Heilmeier Catechism” framework: 

![image](https://user-images.githubusercontent.com/93199737/216832404-8b82849a-4bce-4eb2-bedb-8c1a9fbd3b6e.png)
(Image taken from Asia One) 

Mynahs are a species of bird that are often seen in hawker centers in Southeast Asia, including Singapore and Malaysia. They are often attracted to food and the bustling activity in hawker centers. While they can be entertaining to watch, they can also be a nuisance to vendors and customers, and steps are sometimes taken to discourage them from congregating in hawker centers.

## What are You trying to do? Articulate your objectives using absolutely no jargon.
We are trying to build an AI pest detector for hawker centres in Singapore. Birds and mice are common nuisances that scavenge for food in open hawker centres and sometimes, even leaving their waste. These occurrences reduce the cleanliness and level of satisfaction of eaters in hawker centres. 


## How is it done today, and what are the limits of current practice? 
Today, we see reflective CDs along the entrances of some hawker centres and the usual daily cleanliness work by cleaners. However, some hawker centres may experience a higher frequency of disturbances by birds and mice which would require more regular and/or deeper cleaning processes or even implementations of tougher measures against these hawker pests. 

## What is new in your approach and why do You think it will be successful? 
Our approach introduces a real-time AI approach to monitor the frequency of appearance of birds and mice. When our AI pest detector detects a higher-than-usual occurrence of pests within the hawker compounds, it will send a report to NEA authorities for decision-making. As we want to prioritise the repeatability of our solution using a simple webcam that day-to-day hawkers own, therefore we utilise PeekingDuck; a Computer Vision approach of using object counting over time which involves detecting and tracking of Mynahs in hawker centers, and incrementing the count when new Mynahs appear. We think it would be successful as the solution is repeatable and scalable. So for larger hawker areas such as the wide span of Tampines Hub hawker center, we could indicate a wider zoning coordinate in the Peeking Duck code to accommodate for more birds to be captured by the web camera. 

## Who cares? 
The Singapore hawker culture has been recognised with a UNESCO status since 2020 and this culture has been instrumental in providing affordable food for local residents. Maintaining the cleanliness of our hawker centres encourages local residents to continue patronising hawker centres and support the livelihoods of current and aspiring hawkers.

## If You are successful, what difference will it make? 
We will lessen the vulnerability of hawker businesses to pests and improve the experiences of hawker goers. In the macro level if technology could be used to solve a seemingly small yet real problem of pests in hawker centers, we could save the trouble of implementing manual solutions which would cut down on the costs and manpower needed.

## What are the risks? 
The risks lies mainly in psychosocial comfort levels when using a camera and also the potential misuse of information obtained through the web cam. 
Firstly because we are using a camera of ordinary hawkers to allow for the ‘repeatability’ of our solution, this means that we may need to prepare to explain to hawker goers who notice the camera of our reason in detecting pests. As such this is the main risk as the psychosocial comfort of hawker goers is hindered by their consciousness of a camera watching their actions, of course apart from regular CCTVs around. 
Secondly, because we are using the model.efficientdet node for Mynah and pest detection, the upstream object detector needs to produce predictions which are as accurate as possible. And hence the videos we capture of the mynahs might be used for future improvement of our model for custom training if or when new pests are in the area. Therefore this means that the recorded videos and data might have a potential risk of falling into the wrong hands and as such intensify the first risk of the psychosocial comfort of customers.

## How much will it cost? 
The cost is widely free of charge as it is a simple application where the only pre-requisite for hawkers is a web camera they can even use on their phones. However the time cost of explaining our solution to customers and the potential risk of PDPA laws being infringed due to the videos might be the main cost to consider prospecting the use of the application in future. However this cost can be avoided with careful and vigilant use of hawkers by merit of honesty where they keep their word in deleting the videos if there are any recorded and stored in the web cam. 

## How long will it take? 
For hawkers to use the app, it takes about 5 seconds to click on the app icon and turn on the webcam. However in terms of the post deleting of videos taken and the signalling of pests appearance followed by necessary action to chase them away takes longer as there is human delay. 

## What are the mid-term and final “exams” to check for success? 
Mid-term checks:
Evaluate an AI detector for its functionality in the real-life setting after 1 month of implementation. We can do this by reviewing the recordings of our AI detector and determining its success in accurately detecting passing birds and mice. 

Final “exams” checks:
Conduct feedback surveys among hawkers and hawker goers. 
