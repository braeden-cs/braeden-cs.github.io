---
layout: essay
type: essay
title: "AI: A Friend or Foe?"
# All dates must be YYYY-MM-DD format!
date: 2024-04-30
published: true
labels:
  - AI
---
### I. Introduction


### II. Personal Experience with AI:
I have used AI in class this semester in the following areas:

  1. Experience WODs e.g. E18
     <p>For the various experience WODs, I have not used AI to aid my learning. I have not felt the need to use it as these assignments often came with a tutorial at the end that would explain the concepts and the process of solving problem. In addition, the experience WODs were not so challenging that it would prompt me to use ChatGPT or any other AI to help me complete the assignment.</p>
  2. In-class Practice WODs
     <p>From my perspective, the In-class Practice WODs were specifically made to gauge how well I understood the concepts and practices that I learned during the week. In this way, I would be able to know what I have to work on or practice more. For that reason, I chose not to use ChatGPT during those times as they were very low-stakes because these assignments were not for a grade.</p> 
  3. In-class WODs
     <p>I have used ChatGPT in a couple of instances during select In-class WODs. I used ChatGPT as my last resort option to help me solve the WODs. I would first try the WOD by myself first. Only when I found that my code was not functioning properly or I had no clue on what I was doing would I rely on ChatGPT. However, my experience with using AI during WODs is not the best. Usually, the answers that I would get from the bot would not function as intended. For the cases where ChatGPT was actually able to provide me a correct block of code that function as explained by the prompt would be for the simpler concepts.</p>
     <p>In the cases that I would use ChatGPT to help me complete the WODs, my typical prompt that I would give is "(Provide assignment prompt) Create code to complete this assignment".</p>
  4. Essays
     <p>I specifically try to avoid using any AI to write my essays in this class. My reasoning behind this is because of my fear that I will repremanded for any type of plagiarism or AI usage. Although I do know that AI usage is permitted in this class, I still try to avoid that situation altogether. I also don't use AI to write my essays because the writing style and vocabulary that ChatGPT uses often does not match my own. As perpetually warned in the essay prompts of this class, using AI to write your essay often leads to a lack of your own voice being conveyed in your writing.</p>
     <p>I am unsure if grammarly is counted as AI, but have used grammarly to help me check my essays for any grammar or spelling mistakes. Although, I don't just rely on grammarly to check if essays are ready for grading. I also proofread my essays a couple of times before I turn them in just in case.</p>
  5. Final project
     <p>For my final project, I have used ChatGPT as a way to accelerate the process and help me learn how to implement certain concepts within my code. For instance, I used ChatGPT to come up with my group name, BrainBows. I really struggle coming up with creative and fun names. I also thought that this should be a task that my group and I should not be worrying about that much. As a result, I used ChatGPT to come up with a Study Buddy app group name that incorporated common themes and motifs correlated to UH Manoa. I also used ChatGPT once to help me debug one of my lines of code within my project. The issue that I encountered involved the React onClick event.</p>
     
     ``` cpp
      <Button className="fluid" variant="outline-danger" size="lg" onClick={removeNotif(urgentNotif._id)}>
     ```
     
     <p>I was being thrown the error that the onClick listener is expecting a function but instead, it is receiving a 'number' type. With this issue I prompted ChatGPT to debug the code, providing the bot with the removeNotif function, the block of code, as well as the error that was being thrown. ChatGPT was able to provide me with an answer that actually functioned the way I wanted it to.</p>
        
     ``` cpp
      <Button
        className="fluid"
        variant="outline-danger"
        size="lg"
        onClick={() => removeNotif(urgentNotif._id)}
      >
      Remove Notification
      </Button>
     ```
        
     <p>As you can see, the solution was using an arrow function. Although the change may have been minute, it saved me a lot of time and frustration invovled with this issue.</p>
  7. Learning a concept / tutorial
      <p>Throughout the course of the semester, I have not felt the need to use ChatGPT to learn a concept or provide me with a tutorial of how to use the concepts. The screen casts provided at the end of the experience WODs or in the modules were enough for me to understand how to implement the topics discussed. My main usage of AI was to debug any of my code. I would much rather learn software engineering concepts from an actual professor as compared to AI that lacks the experience and sometimes even the knowledge to explain all of the concepts completely.</p>
  8. Answering a question in class or in Discord
      <p>Instead of using AI as a way to answer any of the questions that I possibly encountered in discord or in class, I would just search it up online instead. I find that in forums, specifically used to share common questions or issues within the coding community like StackOverflow, provided me with usable information to solve my problems.</p>
  9. Asking or answering a smart-question
      <p>I did not ask or answer any smart-question in the #smart-question discord chat so I have no relevant use of AI in this area. Besides, I would not use AI to ask or answer smart questionss. The whole point of asking or answering a smart question is for you to explain you understanding/misunderstanding, as well as your experience. Using any AI to do this would take the whole meaning out of asking/answering the question. I might as well have just asked ChatGPT in the first place.</p>
  10. Coding example e.g. “give an example of using Underscore .pluck”
      One case where I have used AI, specifically ChatGPT, to create code for me was during an In-Class WOD. The prompt that I gave ChatGPT was just the entire prompt provided from the assignment. As a result, I was provided with this block of code:
    ``` cpp
      const _ = require('underscore');

      function hasLove(strings) {
        return _.some(strings, str => str.includes('love'));
      }
      // Example usage:
      const helloLoveLyrics = ["hello", "world", "I love you"];
      console.log(hasLove(helloLoveLyrics));                     // prints true
      console.log(hasLove(helloLoveLyrics.slice(0, 4)));         // prints false
    ```
      <p>I do not remember whether I ended up completing this WOD in time, however, it did give me a starting point on which underscore function I should uswe. Given that there are so much underscore functions found in the documentation along with how ambiguous its implementations can be, I think using ChatGPT was beneficial, even if the code may not have worked properly.</p>
  12. Explaining code
      <p>For me, I place a major importance on actually understanding what is happening within a block of code and how it functions. Unintentionally, I dedicate time to actually read through the documentation of the code as well as try to play with code so that I have an overall knowledge of how the block of code works. Within the scope of this class, the code provided was not that difficult to interpret. However, as we started to implement Meteor and MongoDB which encompassed bigger files and longer lines of code, I found myself dedicating more time to actually try the code for myself. As a result, I have never used AI to explain how a code functions in this class.</p>
  13. Writing code
      <p>I have definitely used AI to help me write code. However, more often than not, I would find that the code that ChatGPT comes up with does not function the way that I want it to. I am unsure whether the issue was with the wording of my prompts or if I simply just did not include enough information for the bot to correctly create a functioning code. Although, with the blocks of code that it did come up, it gave me somewhat of a guide of how I could approach this and the concepts I could use.</p>
      <p>One case where using ChatGPT actually contributed towards my success was also for my final project. I was having a difficult time changing the background color on the project's landing page. No matter what I did, the background color would not change. After inspecting the page, I realized that another code had higher priority over the code I had written which was why the background was not changing. Even then, I still was not sure of how to fix this problem. After a while of deliberating, I asked ChatGPT, "Why isn't my background turning green?" and provided the code. Although it was not able to provide me an explanation on what code was exactly conflicting to cause this problem, it was still able to provide me with a solution </p>
      ``` cpp
      body {
        background: #135213 !important;
      }
       ```
      <p> Using !important to override a css style was something that I learned about in the beginning of the semester. It completely crossed over my mind that I could use that to solve my problem. In this case, ChatGPT was actually able to help me remember about past topics I learned and forgot about.</p>
      <p> However, most of the time, ChatGPT is not the best at writing code. For instance, in one assignment, I prompted ChatGPT to "produce code that will center this text on an image using bootstrap. (code)". ChatGPT provided me with long and difficult to understand code that did not even work.</p>
  14. Documenting code
      <p>In this class, I have not had an issue with documenting code. For most of the class, the code that we used would often already be documented. With altering the code, my task would simply be to change a few words within comments. As a result, I have not used any AI to help me document  </p>
  15. Quality assurance 
      <p>In terms of quality assurance, I have not used any AI to help me. The main reason behind this is because IntelliJ would do all of the work for me. As an IDE, I find it to be very efficient and quick with spotting any ESLint errors. In addition, the fixes are very quick. I would just have to inspect the error and click the "Fix 'problem'" button and it would do all of the work for me. I have never tried using ChatGPT to find those errors becuase I had no need to.</p>
  16. Other uses in ICS 314 not listed above
      <p>Other than the discussed uses listed above, I have not ventured out in using AI for other aspects of ICS 314. </p>


### III. Impact on Learning and Understanding:
  <p>Overall, I would not say that AI has made a detrimental or profound impact on my learning and understanding in this class. Especially because this course is a foundational class within my major, I have found myself trying to stray away from relying on ChatGPT. In the beginning, I completely avoided using ChatGPT in any class. The main issue that I saw with using AI is that it would negatively impact essential aspects and skills that I am trying to develop. 
The biggest differntiation that I made during my experience of using AI is that it should be the HELP, not the SOLUTION. Once I was able to understand this difference, I used AI to supplement my learning rather than it becoming the foundation of my knowledge.</p>

### IV. Practical Applications:


### V. Challenges and Opportunities:


### VI. Comparative Analysis:


### VII. Future Considerations:


### VIII. Conclusion:
