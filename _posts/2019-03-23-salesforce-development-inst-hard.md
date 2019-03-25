---
published: true
---
I have been creating and developing systems for the past 16 years. I started with DBase and Pascal in secondary school, then Java and PHP in university. When I started working, I was doing Java and C#, creating mostly large scale systems. I am now in Tokyo, working for a Japanese company and primarily use Kotlin.

I encountered Salesforce development 2 years ago when I was tasked to integrate our internal system with Salesforce. I never knew nor saw how Apex and Visualforce looked like. I studied everything (development + debugging) on my own and eventually released the customized Salesforce.

Fast forward today, I am the only developer doing the development of my company’s Salesforce plugin. In my company, we usually do pair programming because the team avoids isolating any knowledge acquired through development to one developer. We rotate development to all members and see to it everyone knows the development. I tried teaching them but they couldn’t follow; there were too many steps needed just to create a customized object.

Probably biggest difference of developing in Salesforce compared to other programming languages is that there is no “local” environment in Salesforce. Everything is pushed to their cloud environment and is compiled there. Even running unit tests are done using their platform. It’s actually one of their advantages: developers don’t need setup local environments nor production servers. But this development practice is not common and may be difficult for new salesforce developers.

Modern IDEs have support for Salesforce development. Illuminated Cloud is a plugin for IntelliJ Idea, there is also the SFDX extension for Visual Studio Code. They are actually very powerful and they actually do the pushing/compiling/running codes in the Salesforce platform automatically. They make developers feel as if they were developing in a local environment. I run my unit tests through my IDE.

Another difference is that there are certain components (Salesforce’s standard objects, custom objects, custom settings) that needs to be created via their platform and then download the created metadata to the IDE so development would be smoother. Compared to just declaring a new class with your favorite language, there is a lot of steps needed when in Salesforce. 

Getting familiar with the developer platform might be a steep learning curve but everything else is just the same. Salesforce is also giving some tutorials/lessons via trailhead to help new Salesforce developers. The lessons are very thorough and well written. They’re probably better than just some programming language bloggers.
