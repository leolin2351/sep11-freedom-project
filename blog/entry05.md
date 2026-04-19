# Entry 5
##### X/X/XX

<h2>Context:</h2>
<p> So since blog 4, i had a goal of finishing my quiz about elderly scam. So I created a multiple choice button to show the age group of the user so I can ask questions if they see anyone like elderly who have been a victim of it. Although i was slacking off because there was assignment from different class and i had a hard time understanding how to plan out my time i found this break as a good time to do it. I used sources like ([chatgpt](https://chatgpt.com/)) and ([w3schools](https://www.w3schools.com/jquery/)) to help me out. W3school i should use because there are lines of code where they explain how to apply it and what it do. But Chatbot can be argued because many people say its not a source because people use it to cheat but i believe it is a source because i use it to learn because i need to know how to get the user to a different file based on the file their choice in age group. I thought of this idea because of SEP10 like hero's journey and cultural food projects. Ulitimaly in blog 5 i was able to finish my project and heres a important code that i needed for my system to work. :</p>
<h2>Code:</h2>

```js
$("#continue").click(function(){
                let choices = $("input[name='age']:checked").val(); //problem before was that it wasnt checking
                console.log(choices)
                if (choices) {
                    window.location.href = choices;
                } else {
                    alert("Select one of the following age group")
                }
            })
```
<h2>challege 1:</h2>
<p>So one problem i had was linking the files base on the users when they press the continue button. At first i was linking it manually rather than setting up a conditional for a loop. this is a important code for my project because this is how i am able to get the information of the user age choice to put them into correct files with questions base on their knowledge and experience. Without line 10 my project wouldnt work because i needed to check the users choice inorder to put them into the correct choices. And i needed to have the value of the users choice so when they press continue it would work. And i also added a alert that prevents the user from pressing next if they didnt have a radio selected. </p>
<h2>Challenge 2:</h2>
<p>So another problem i had was thinking i used chatgpt the wrong way throughout this project. So basically i had my 1 question setted up and got lazy to copy and paste the questions and answer choices into my html folders for each files. So i used chatgpt and threw in my model 1 and made it clone 18 questions and 3 multiple choice answers for each question with different answer order. So this step was the scary part because i didnt know if i would get in trouble of ai usage during a big project so i asked my friends and they said its ok but i didnt believe them. So i asked mr mueller if my way of using ai is correct or wrong because he said ai is like a chef knife, if you use it correctly u can make many delicious dishes but if you use it on the wrong hang it would cause alot of problems. But ultimaly he said it was alright.</p>
<h3>Takeaway/skills:</h3>
<p>So i was able to finish my mvp by developing skills like embrace failure and time management. I learned how to embrace my failure because i use to use chatgpt alot and get in trouble for using it the wrong way because i lie about not using it which got be in alot of trouble. I failed many time when i dont use chatgpt the right way but this time i was able to learn from my mistake because before i always ask chatgpt to gimme codes and include comments which basically helped me finish my work but this time i reflected on my mistake and started to argue with chatgpt because it was giving me bad answers. Ultimately i was able ti finish my project using chatgpt the right way. Another skill i learned was time management because as someone who is taking ap and hard course its hard to find a good time to finish a big proect so i was able to find a break to finish it. Although i was very lazy since the beginning of the year i was able to finish it with good time management. </p>
[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)
