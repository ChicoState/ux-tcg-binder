# Phase III: Prototypes and User Testing

## Introduction

TCG_Binder aims to provide a platform where trading card game players can effortlessly manage their physical trading card collections digitally. The focus for this phase of the project was to study real user interaction with our application. To do this we created a prototype of our application and we created a study protocol that we then used to gather information about our application and how people will use it. 

## Methods

### [Usability Test Protocol](https://github.com/ChicoState/ux-tcg-binder/blob/main/phaseIII/protocol/TCG-Binder%20Usability%20Protocol.pdf)

The protocol consists of three sections: **user background**, **tasks**, and **debrief.** 

The study took a formative approach having participants rate the ease of a task rather than the evaluators rate the performance of the participant. Additionally, participants were asked to think-aloud during each task. 

### User Background

The background section seeks to determine the participant's previous experience with trading card games and applications. Five questions were asked:

#### Q1: How long have you played trading card games (if at all)?
* Determining if a user has experienced playing trading card games is important because if the user is unfamiliar, they would likely not be able to provide useful insights into the design of the application. 

#### Q2: How serious are you about trading card games?
* Different ideas and viewpoints can come from participants who are inexperienced, casual, or competitive with trading card games. 

#### Q3: What trading card game applications have you used before if any?
* Participants that have experienced applications developed by competitors can provide useful insights into industry conventions, design, and features. 

#### Q4: What do you expect a trading card game application to provide to best serve your needs?
* Implementation of expected features is important to fulfilling user needs and staying consistent with industry conventions. 

#### Q5: What features would you expect to not see in a trading card game application?
* Participants can provide both positive and negative outlooks regarding unexpected features. A majority of competitors may be lacking a highly desired feature or, opposingly, all possess the same undesired one.

### Tasks
Tasks are designed to pinpoint potential caveats in the design of the prototype and observe participant behaviors as they navigate through the UI. Each task asks the participant to perform a function starting from the landing page. Afterwards, each task is determined a success or failure depending on the participant's completion of the task. Participants are then asked to rate the difficulty on a scale of “Very Difficult” (1) to “Very Easy” (5). 

#### Task 1
Imagine you use a tcg app to track your physical card collection digitally. You have received a handful of new magic the gathering cards and want to make sure that your digital collection reflects your physical collection. See if you can make your digital collection reflect the new cards that you have received.

* The first task aims to introduce the participant to the UI and, simultaneously, reveal the mental model constructed through its navigation. Additionally, recording interactions with key features such as the scanner sought to discover potential design flaws. 


#### Task 2
Most tcg applications allow users to post deck lists and share them with other users. See if you can figure out how to share a deck that you have created with other users of the application as well as making the deck visibility public. 

* With the participant better oriented with the prototype, the second task seeks to test the “create new deck” page/feature and use the dropdown options to make it public. Additionally, observations on the level of feedback provided by the prototype to the user were examined to see if there was enough to infer completion of the task. 

#### Task 3
You are looking to build a new deck to take to your local trading card game store to play against other players. Use the application to help you find a deck that you would like to create.

* This task aims to test if the user can navigate to the “Create New Deck” page and either manually add or scan in new cards to the new deck. 

#### Task 4
Many applications offer details about market listings and prices for cards. Examine what market/pricing details are provided to users. See if you can retrieve enough information to feel confident that you can sell your card if you so desired.

* The last task has the participant attempt to navigate to the “Market Listings” page and examine the market details of a selected card. 

### Debrief
The debrief section compiles participant's thoughts and opinions about their experience with the application. Seven questions were asked:

#### Q1: Did your experiences match your expectations of what a trading card game application should be?
* Staying true to industry conventions is important as straying too far can introduce confusing features or themes. 

#### Q2: Which tasks were satisfying to complete? Which ones were difficult?
* Understanding where participants were comfortable/dissatisfied with navigation, use of features, and the UI, depicts a better picture of where to make QoL (Quality of Life) adjustments. 

#### Q3: What was the best aspect of your experience using our app?
* Determining the best aspect of the prototype can help develop other parts by using similar conventions/designs. 

#### Q4: What was the worst aspect of your experience using our app?
* Determining the worst aspect helps determine what feature/design may be missing or poorly implemented. 

#### Q5: What are some changes you would recommend?
* Recommended changes can help fulfill user needs and create a better, more feature-rich application.

#### Q6: Does the organization and navigation between pages make sense?
* Evaluating the ease at which participants can navigate the UI is crucial to developing an application that feels easy to use and flow through. 

#### Q7: Are there any other features you would like to see implemented?
* Discovering any missing or desired features can help fulfill user desires tremendously. 

## Findings

[Spreadsheet](https://docs.google.com/spreadsheets/d/1FlTyiP67pJ-ljnRgTW1rIga5I1qpTcU1yYDeksrWwbk/edit?usp=sharing)

### <ins>Quantatative and Qualitative Summary</ins>

### Background
Half of all participants (n=6) reported having prior experience using a TCG application. Although, all participants had some level of experience with TCGs most often as a child. No participants reported currently playing TCGs or collecting cards.

### Tasks
Nearly all participants had a 100 percent success rate with each task with one failure during task 3. No task took more than 3 minutes to complete. Task ratings were generally high with tasks 2 through 4 all having an average rating of 4.5/5. Task 1 had the lowest average rating of 3/5. 
The means and standard deviations for each task’s ratings are as follows:

* T1 (M=3, SD= 0.632455532)
  * Participants generally reported initial confusion with the navigation and lack of user feedback scanning and/or manually adding cards.

<img width="568" alt="image" src="https://github.com/ChicoState/ux-tcg-binder/assets/84484268/06a5846f-5044-402f-b4e1-5e60ff62ecc3">

* T2 (M=4.5, SD= 0.8366600265)
  * Most participants found it simple to locate the "my collections" page from the home page and set a deck to public. However, the lack of a back button made navigating back to the homepage tedious for some participants.
 
<img width="623" alt="image" src="https://github.com/ChicoState/ux-tcg-binder/assets/84484268/c6148f60-d3ba-4677-a6fe-0e855b87dac5">

* T3 (M=4.5, SD= 0.8366600265)
  * Almost all of the participants were able to navigate to the "shared collections" page and like a shared deck. However, one participant ultimately failed to complete this task due to the lack of feedback when liking a shared deck.
 
<img width="496" alt="image" src="https://github.com/ChicoState/ux-tcg-binder/assets/84484268/27c70a0f-ddd9-49bd-81a9-01cca03bfa60">

* T4 (M= 4.5, SD = 0.5477225575)
  * All participants found navigating to the marketplace page and examining the market details of a card simple and intuitive. One participant, however, voiced that the button to take users to the marketplace page was not obvious to the eye due to the bland color palette.
 
<img width="524" alt="image" src="https://github.com/ChicoState/ux-tcg-binder/assets/84484268/791cedcc-cb6f-45d1-8c53-6ab3b01c8432">

### Debrief 
Some trends gathered from the feedback of the participants included a desire for a button to take you back to the previous page, more user feedback when submitting a new card or deck, and more vibrant UI colors. Participants especially voiced difficulty with adding new cards to their collection or deck. Due to a lack of feedback from the prototype, participants were confused about whether their card was added or not. 

## Conclusions

Using our prototype and the study that we ran we were able to gather crucial information about how users interacted with our application. Our study was designed to make the participants interact with different areas of our application and provide feedback on how well we incorporated the different useability principles. During this phase we learned that providing feedback to users is an area that our application can focus on in the future and would greatly improve the user experience. 

## Caveats

There were numerous caveats that were associated with this phase of the project. Firstly, like the previous phase, our team is inexperienced when it comes to using Figma. As a result, there might have been some components of the prototype that were implemented ineffeciently that could cause headaches for users. Secondly, all our users were usability students. These users will have more knowledge and biases when it comes to using digital interfaces, which may result in non-representative feedback regarding tasks and the prototype in general. Thirdly, some participants may have been fatigued due to being a participant for other groups. This could result in incorrect or insincere feedback being returned due to participants not being able to perform at their full potential.
