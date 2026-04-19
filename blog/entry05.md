# Entry 5
##### X/X/XX

<h2>Context:</h2>
<p> So since blog 4, I had a goal of finishing my quiz about elderly scam. So I created a multiple choice button to show the age group of the user so I can ask questions if they see anyone like elderly who have been a victim of it. Although I was slacking off because there were assignments from different classes and I had a hard time understanding how to plan out my time, I found this break as a good time to do it. I used sources like ([chatgpt](https://chatgpt.com/)) and ([w3schools](https://www.w3schools.com/jquery/)) to help me out. I should use W3school because there are lines of code where they explain how to apply it and what it does. But Chatbot can be argued because many people say its not a source because people use it to cheat but i believe it is a source because i use it to learn because i need to know how to get the user to a different file based on the file their choice in age group. I thought of this idea because of SEP10 like hero's journey and cultural food projects. Ultimately in blog 5 i was able to finish my project and here's an important code that i needed for my system to work. :</p>
<h2>Code:</h2>

```js
$("#continue").click(function(){
                let choices = $("input[name='age']:checked").val(); //problem before was that it wasn't checking
                console.log(choices)
                if (choices) {
                    window.location.href = choices;
                } else {
                    alert("Select one of the following age group")
                }
            })
```
<h2>challenge 1:</h2>
<p>So one problem I had was linking the files based on the users when they press the continue button. At first I was linking it manually rather than setting up a conditional for a loop. This is an important code for my project because this is how I am able to get the information of the user age choice to put them into correct files with questions based on their knowledge and experience. Without line 10 my project wouldn't work because I needed to check the users choice in order to put them into the correct choices. And I needed to have the value of the user's choice so when they press continue it would work. And I also added an alert that prevents the user from pressing next if they didn't have a radio selected. </p>
<h2>Challenge 2:</h2>
<p>So another problem I had was thinking I used chatGPT the wrong way throughout this project. So basically I had my 1 question setted up and got lazy to copy and paste the questions and answer choices into my html folders for each file. So i used chatgpt and threw in my model 1 and made it clone 18 questions and 3 multiple choice answers for each question with different answer order. So this step was the scary part because i didnt know if I would get in trouble with my usage during a big project so I asked my friends and they said it's ok but i didnt believe them. So i asked mr mueller if my way of using ai is correct or wrong because he said ai is like a chef knife, if you use it correctly u can make many delicious dishes but if you use it on the wrong hang it would cause a lot of problems. But ultimately he said it was alright.</p>
<h3>Takeaway/skills:</h3>
<p>So I was able to finish my MVP by developing skills like embracing failure and time management. I learned how to embrace my failure because I used to use chatbot alot and got in trouble for using it the wrong way because I lied about not using it which got me in a lot of trouble. I failed many time when i dont use chatgpt the right way but this time i was able to learn from my mistake because before i always ask chatgpt to gimme codes and include comments which basically helped me finish my work but this time i reflected on my mistake and started to argue with chatbot because it was giving me bad answers. Ultimately I was able to finish my project using chatbot the right way. Another skill I learned was time management because as someone who is taking an AP and hard course it's hard to find a good time to finish a big project so I was able to find a break to finish it. Although I have been very lazy since the beginning of the year, I was able to finish it with good time management. </p>
[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)


