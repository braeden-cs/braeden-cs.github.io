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
  <p>At the height of COVID-19, came the introduction of ChatGPT, an AI chatbot that answers prompts. Since then, the world has considerably shifted by incorporating AI into various aspects of society. Although AI has existed prior to this, it has continued to reach new peaks and has become more commonly used among the public. One of the major aspects that AI has been used for is education. Especially during distance learning, there was an increased worry that students would use AI to complete their assignments, thereby, not learning anything. At least for me, nowadays I have used AI, specifically ChatGPT, to help supplement my learning. In ICS 314, I use ChatGPT in a couple of ways. For instance, I have used ChatGPT to help create code given a certain prompt and functionality.  </p>

### II. Personal Experience with AI:
I have used AI in class this semester in the following areas:

  1. Experience WODs e.g. E18
     <p>For the various experience WODs, I have not used AI to aid my learning. I have not felt the need to use it as these assignments often came with a tutorial at the end that would explain the concepts and the process of solving the problem. In addition, the Experience WODs were not so challenging that it would prompt me to use ChatGPT or any other AI to help me complete the assignment.</p>
  2. In-class Practice WODs
     <p>From my perspective, the In-class Practice WODs were specifically made to gauge how well I understood the concepts and practices that I learned during the week. In this way, I would be able to know what I have to work on or practice more. For that reason, I chose not to use ChatGPT during those times as they were very low-stakes because these assignments were not for a grade.</p> 
  3. In-class WODs
     <p>I have used ChatGPT in a couple of instances during select In-class WODs. I used ChatGPT as my last resort option to help me solve the WODs. I would first try the WOD by myself. Only when I found that my code was not functioning properly or I had no clue on what I was doing would I rely on ChatGPT. However, my experience with using AI during WODs is not the best. Usually, the answers that I would get from the bot would not function as intended. For the cases where ChatGPT was able to provide me a correct block of code that function as explained by the prompt would be for the simpler concepts.</p>
     <p>In the cases that I would use ChatGPT to help me complete the WODs, my typical prompt that I would give is "(Provide assignment prompt) Create code to complete this assignment".</p>
  4. Essays
     <p>I specifically try to avoid using any AI to write my essays in this class. My reasoning behind this is because of my fear that I will be repremanded for any type of plagiarism or AI usage. Although I do know that AI usage is permitted in this class, I still try to avoid that situation altogether. I also don't use AI to write my essays because the writing style and vocabulary that ChatGPT uses often do not match my own. As perpetually warned in the essay prompts of this class, using AI to write your essay often leads to a lack of your voice being conveyed in your writing.</p>
     <p>I am unsure if Grammarly is counted as AI, but have used Grammarly to help me check my essays for any grammar or spelling mistakes. Although, I don't just rely on Grammarly to check if essays are ready for grading. I also proofread my essays a couple of times before I turn them in just in case.</p>
  5. Final project
     <p>For my final project, I used ChatGPT as a way to accelerate the process and help me learn how to implement certain concepts within my code. For instance, I used ChatGPT to come up with my group name, BrainBows. I really struggle to come up with creative and fun names. I also thought that this should be a task that my group and I should not be worrying about that much. As a result, I used ChatGPT to come up with a Study Buddy app group name that incorporated common themes and motifs correlated to UH Manoa. I also used ChatGPT once to help me debug one of my lines of code within my project. The issue that I encountered involved the React onClick event.</p>
     
     ``` cpp
      <Button className="fluid" variant="outline-danger" size="lg" onClick={removeNotif(urgentNotif._id)}>
     ```
     
     <p>I was thrown the error that the onClick listener is expecting a function but instead, it is receiving a 'number' type. With this issue I prompted ChatGPT to debug the code, providing the bot with the removeNotif function, the block of code, as well as the error that was being thrown. ChatGPT was able to provide me with an answer that functioned the way I wanted it to.</p>
        
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
        
     <p>As you can see, the solution was using an arrow function. Although the change may have been minute, it saved me a lot of time and frustration involved with this issue.</p>
  7. Learning a concept / tutorial
      <p>Throughout the semester, I have not felt the need to use ChatGPT to learn a concept or provide me with a tutorial on how to use the concepts. The screen casts provided at the end of the experience WODs or in the modules was enough for me to understand how to implement the topics discussed. My main usage of AI was to debug any of my code. I would much rather learn software engineering concepts from an actual professor as compared to AI which lacks the experience and sometimes even the knowledge to explain all of the concepts completely.</p>
  8. Answering a question in class or in Discord
      <p>Instead of using AI as a way to answer any of the questions that I possibly encountered in Discord or class, I would just search it up online instead. I find that in forums, specifically used to share common questions or issues within the coding community like StackOverflow, provided me with usable information to solve my problems.</p>
  9. Asking or answering a smart-question
      <p>I did not ask or answer any smart-question in the #smart-question discord chat so I have no relevant use of AI in this area. Besides, I would not use AI to ask or answer smart questions. The whole point of asking or answering a smart question is for you to explain your understanding/misunderstanding, as well as your experience. Using any AI to do this would take the whole meaning out of asking/answering the question. I might as well have just asked ChatGPT in the first place.</p>
  10. Coding example e.g. “give an example of using Underscore .pluck”
      One case where I have used AI, specifically ChatGPT, to create code for me was during an In-Class WOD. The prompt that I gave ChatGPT was just the entire prompt provided by the assignment. As a result, I was provided with this block of code:
      
      ```cpp
      const _ = require('underscore');

      function hasLove(strings) {
        return _.some(strings, str => str.includes('love'));
      }
      // Example usage:
      const helloLoveLyrics = ["hello", "world", "I love you"];
      console.log(hasLove(helloLoveLyrics));                     // prints true
      console.log(hasLove(helloLoveLyrics.slice(0, 4)));         // prints false
      ```
      
      <p>I do not remember whether I ended up completing this WOD in time, however, it did give me a starting point on which underscore function I should use. Given that there are so many underscore functions found in the documentation along with how ambiguous its implementations can be, I think using ChatGPT was beneficial, even if the code may not have worked properly.</p>
  12. Explaining code
      <p>For me, I place a major importance on actually understanding what is happening within a block of code and how it functions. Unintentionally, I dedicate time to read through the documentation of the code as well as try to play with the code so that I have an overall knowledge of how the block of code works. Within the scope of this class, the code provided was not that difficult to interpret. However, as we started to implement Meteor and MongoDB which encompassed bigger files and longer lines of code, I found myself dedicating more time to try the code for myself. As a result, I have never used AI to explain how a code functions in this class.</p>
  13. Writing code
      <p>I have used AI to help me write code. However, more often than not, I would find that the code that ChatGPT comes up with does not function the way that I want it to. I am unsure whether the issue was with the wording of my prompts or if I simply just did not include enough information for the bot to correctly create a functioning code. Although, the blocks of code that it did come up gave me somewhat of a guide of how I could approach this and the concepts I could use.</p>
      <p>One case where using ChatGPT actually contributed to my success was also for my final project. I was having a difficult time changing the background color on the project's landing page. No matter what I did, the background color would not change. After inspecting the page, I realized that another code had higher priority over the code I had written which was why the background was not changing. Even then, I still was not sure of how to fix this problem. After a while of deliberating, I asked ChatGPT, "Why isn't my background turning green?" and provided the code. Although it was not able to provide me an explanation on what code was exactly conflicting to cause this problem, it was still able to provide me with a solution </p>
      
      ```cpp
      body {
         background: #135213 !important;
      }
      ```
      
      <p> Using !important to override a CSS style was something that I learned about at the beginning of the semester. It completely crossed over my mind that I could use that to solve my problem. In this case, ChatGPT was  able to help me remember past topics I learned and forgot about.</p>
      <p> However, most of the time, ChatGPT is not the best at writing code. For instance, in one assignment, I prompted ChatGPT to "produce code that will center this text on an image using bootstrap. (code)". ChatGPT provided me with long and difficult-to-understand code that did not even work.</p>
  14. Documenting code
      <p>In this class, I have not had an issue with documenting code. For most of the class, the code that we used would often already be documented. With altering the code, my task would simply be to change a few words within comments. As a result, I have not used any AI to help me document  </p>
  15. Quality assurance 
      <p>In terms of quality assurance, I have not used any AI to help me. The main reason behind this is that IntelliJ would do all of the work for me. As an IDE, I find it to be very efficient and quick with spotting any ESLint errors. In addition, the fixes are very quick. I would just have to inspect the error and click the "Fix 'problem'" button and it would do all of the work for me. I have never tried using ChatGPT to find those errors because I did not need to.</p>
  16. Other uses in ICS 314 not listed above
      <p>Other than the discussed uses listed above, I have not ventured out into using AI for other aspects of ICS 314. </p>


### III. Impact on Learning and Understanding:
  <p>Overall, I would not say that AI has made a detrimental or profound impact on my learning and understanding in this class. Especially because this course is a foundational class within my major, I have found myself trying to stray away from relying on ChatGPT. In the beginning, I completely avoided using ChatGPT in any class. The main issue that I saw with using AI is that it would negatively impact essential aspects and skills that I am trying to develop. However, I slowly began to use ChatGPT in a way where I am not over-reliant on AI. The biggest differentiation that I made during my experience of using AI is that it should be the HELP, not the SOLUTION. Once I was able to understand this difference, I used AI to supplement my learning rather than becoming the foundation of my knowledge. Even with my periodic use of AI, I believe that I was still able to learn and develop the skills and concepts foundational for software engineering.</p>

### IV. Practical Applications:
  <p>From my perspective, the most practical appliation of AI in software engineering would have to be its debugging capabilities. Outside of just ICS 314, AI is being applied to increase efficiency. For instance, a lot of places like the airport and hospitals have implemented facial recognition as a way to quickly check in clients. There is also the aspect of text editors that many students use to help make writing easier. </p>
  <p>The future of AI concerning software engineering is quite murky. A lot of companies are putting precedence and priority over developing and incorporating AI into their products. The biggest sentiment that has been spreading around in the software engineering and tech industry is that AI will be taking a lot of people's jobs. There was even a recent breakthrough of AI that can produce entire functioning programs called Devin. Devin AI claims to be an AI software engineer. However, this breakthrough has been shrouded with controversy as its efficacy is still in question. </p>

### V. Challenges and Opportunities:
  <p>The biggest challenge that comes with using AI happens to be one of its main functionalities. As I discussed in the prior sections, using AI does not mean you will get a definitive or correct answer. Instead, a lot of the time, especially for writing code, I end up getting garbage code that either does not satisfy the prompt given or is horribly written and difficult to understand. As a result, I have not relied on ChatGPT to create an entire program</p>
  <p>Another issue that I have come across when using AI, especially for ChatGPT, is that it can sometimes be difficult to craft an effective prompt that will garner an optimized solution. As the files got bigger, the prompts became even more difficult to create as I was not going to provide ChatGPT with thousands of lines of code just to give it the proper context to solve the problem. In all honesty, creating good prompts for ChatGPT could be taught as a class in itself.</p>
  <p>Despite all of these challenges, I do see the appeal and opportunities found in AI. I believe that software engineering and AI could work hand in hand together to educate the new generation of software engineers. I say this because, from my experience, using ChatGPT in some cases has made writing code more efficient. Specifically, I found that ChatGPT helped with debugging code. I already had the knowledge of how to implement the code so that my program would function properly. However, I would sometimes have small details that I neglected. Using ChatGPT, I would be able to find those bugs within my code with relative ease.</p>

### VI. Comparative Analysis:
  <p>A lot of the time, traditional teaching methods can feel quite overwhelming and boring. In my case, the typical lecture-style teaching method leaves much to be desired. I often find myself not being able to focus. Retaining all of the information can also be quite difficult as well. With these implications, AI can be incorporated into education to enhance the experience for the student. One example of this was discussed in section 2 where ChatGPT was able to remind me of certain old topics that I completely forgot about. In this way, AI improved my learning experience.</p>
  <p>It is difficult to decipher whether traditional teaching methods or AI-enhanced teaching is better. Each approach comes with its benefits as well as its consequences. The determining factor would be based on how the student uses AI in their education. If the student uses AI to write code without putting in the effort to comprehend the concepts behind it, then the consequence will be that they are not developing the necessary skills. Also, since they are relying on AI for the answers, they most likely will not retain the information the AI explained. However, if the student periodically uses AI to check their code or their understanding, then I would say that incorporating AI into teaching methods would be beneficial.</p>

### VII. Future Considerations:
  <p>As AI continues to develop and become even more sophisticated and human-like, it will have major implications for a student's education. The possibilities are both enticing and frightening. If AI is truly able to accurately create functioning code, the students may possibly become dependent on AI. This will negatively impact their education as they are not learning what they are supposed to. Rather, they are becoming more proficient in creating prompts. I think the biggest challenge will be determining when to use AI. For me, this is something that I struggle with myself. I try my best to stay away from AI and only use it when I am extremely frustrated. However, it could quickly spiral into a dependency on AI. Even now, as I analyze my relationship with AI, I see that sparingly using AI as my final-resort solution is quite scary. It is slowly becoming integral in my life as well as in society. </p>

### VIII. Conclusion:
  <p>I still feel quite split about my opinion on using AI. On one end, I see AI as scary because it has so much potential. On the other, I acknowledge how AI could be beneficial for my learning. In my experience with using AI, I have placed importance on understanding what AI is to me. Ideally, AI should supplement my learning rather than be my basis for it. I have tried to showcase this through my implementations of AI throughout the course. I would like to limit myself to this ideal because I think if I were to go any further, I would not be gaining any value out of my education. In order to optimize the integration AI into courses, it would be beneficial for both the teachers and the students to define an explicit line between using AI to supplement your learning and dependency on using AI. In this way, students can become software engineers who can still strive even without AI.</p>
