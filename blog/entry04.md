# Entry 4
##### X/X/XX
<h2>COntext</h2>
<p>In this blog we continued from blog 3 where i finished learning my tool. So in this blog ill be showing you the back page of the slacking I did but also the challenge I faced. So in the preview I was trying to make a quiz for elderly scam which mostly targeted elderly but I realized that I should also include teenagers and adults because they might also have experienced it. Scams do not only apply to only elderly but also many other people. So I created a multiple choice button to show the age group of the user so I can ask questions if they see anyone like elderly who have been a victim of it. Although i was slacking off because there was assignment from different class and i had a hard time understanding how to plan out my time i found sunday on march 3/15 a good time to do it. I used sources like ([chatgpt](https://chatgpt.com/)) and ([w3schools](https://www.w3schools.com/jquery/)) to help me out. W3school i should use because there are lines of code where they explain how to apply it and what it do. But Chatbot can be argued because many people say its not a source because people use it to cheat but i believe it is a source because i use it to learn because i need to know how to get the user to a different file based on the file their choice in age group. I thought of this idea because of SEP10 like hero's journey and cultural food projects. heres my current code </p>

```js
<!DOCTYPE html>
<html>
    <head>
        <!-- Required meta tags -->
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">

        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet" />
        <link href="style.css" rel="stylesheet" type="text/css" />
        <style>
            /* CSS */

        </style>

        <title>Title</title>
    </head>
    <body>
        <!-- HTML -->

        <input type="radio" name="age" value="Teenager"> Teenager<br>
        <input type="radio" name="age" value="Adult"> Adult<br>
        <input type="radio" name="age" value="Elderly"> Elderly<br>
        
        <button id="continue">continue</button>

        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
        <!-- <script src="script.js"></script> -->
        <script>
            // JS

            <!-- 3 choices -->
            document.querySelector("#continue").addEventListener("click",function(event){
            var ageCheck = document.querySelectorAll("input[name='age']");
                ageCheck.forEach(function(ageCheck){
                    ageCheck.addEventListner("click",function(event){
                        if (ageCheck.value == "Teenager"){
                            window.location.href = "teenager.html";
                        } 
                    })
                })
            }
        </script>
    </body>
</html>
```
<p>so on line 43 there's this code window.location.href so this is something from chatgpt because i needed to make sure the user is sended to the correct file but i didnt know how to because i didnt know about window.location</p>
<h2>EDP:</h2>
<p>I'm on EDP step 5 because I need to create my project first in order to continue to the next EDP which would take 1-2 more blogs depending on how complex I want it to be. So create is the average EDP step we as SEP students should be on because we all have to create our project in order to move on. So I'm trying to create my 3 choices first in order to move on to making new questions for each file. I feel like creating is the perfect pace for me because I used blog 1-3 to learn my tool and now I'm using 4-6 to create and the rest to make my project look good.</p>
<h2>Skills:</h2>

* how to use AI

* time management

<p>How to use AI is a skill I continue to practice because I really want to get my work done so I would search up how to finish my project and I would finish it but also learn nothing which lets me continue not using AI to do my project for me but use it as a helper. Time management is so important to me and it's not a skill i mastered because i had so little of time to force on my project and which let me have only 1 day to make some progress in it which is very bad for me if i want to add more stuff into it.</p>
[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)

