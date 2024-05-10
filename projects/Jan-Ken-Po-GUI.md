---
layout: project
type: project
image: img/R.png
title: "Jan Ken Po GUI"
date: 2023
published: true
labels:
  - Java
  - GUI
summary: "Creating a GUI for a User vs Computer Rock Paper Scissors game"
---
<img class="img-fluid" src="../img/Screenshot 2024-01-26 143813.png">


During my second semester in my computer science degree, I created a rock paper scissors game, or Jan Ken Po as we like to call it in Hawaii. The game would be a user vs computer type of game. All of this code would be done using Java. The main focus was to create a simple game that could be played through a graphical user interface. In this way, we would have to be able to program functional buttons as well as learn strategies to make our interface look 'good'.

I first created the graphical user interface of the game which included the buttons and the text fields. Included in the GUI was an instruction button, which when clicked, will show a seperate window that explained the logic of the game. The user could then choose their move to go against the computer. For the game to function, I assigned each move a number from 0 to 2. To program the ' vs computer ' aspect of the game, I would have the computer randomly generate a number between 0 and 2. Based on the logic of rock paper scissors, it would then determine the winner based on the randomly generated number from the commputer as well as the move chosen by the user. Each result of the round would then be recorded onto a seperate text file that the user could look at. One snippet of how I approached programming the logic of Jan Ken Po is:

<hr>

<pre>
         // In the case that the button bRock is clicked
         // Defines the logic of the game
         // Each move will be represented as a number 
         // 0:Rock 1:Paper 2:Scissors
         // If the user chose 0:Rock
         if(e.getSource() == bRock){
            // randomly generates a number between 0-2
            Random r = new Random();
            int computerChoice = r.nextInt(3);
            // Determines what the computer chose and will declare the winner of the match 
            // This is based on the rules of RPS which can be found on the internet
            // In the case that the computer chose rock
            if(computerChoice == 0){
               // Displays the computers move and the results of the match
               computerMove.setText(" ROCK ");
               results.setText("IT IS A TIE");
               // Increases the tie score by 1 and displays it in the according label
               t++;
               labelTie.setText(Integer.toString(t));
               // Increases the amount of matches by 1
               matches++;
            }


</pre>

<hr>

From this project, I learned the basics of what a graphical user interface was and how to apply this through code. It was my first time creating a graphical user interface so there were many trials and tribulations with programming the game. The experience was extremely fufilling as it would be my first time creating a program where I could physically see my functional product. Although it took a while, I really enjoyed the process and it helped me realize why I decided to major in computer science in the first place. This project was so significant to me as it would teach me perserverance and determination despite being frustrated. There were many times where my code would not compile or simply not function correctly. I especially struggled with making the GUI look as aesthetic as possible. There were many things that I wanted to do with the interface, however, I lacked the skill. In those instances, I would want to give up. However, I decided to push through the frustation and become motivated to learn even more. In the end, I was able to create a program that I was proud of.
