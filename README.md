# escape_room_quest_wizard_orpheus
```js
let api_key = 'YOUR_API_KEY'
```
api key is open ai server which you can get on slack or get for buying something from open ai
<p>your job is answered correctly to the questions about a chess. start by saying'Hi':</p>
Then explains what the goal of the game is.
<br><br>



let pytania = `You have to ask 3 questions and get three answers. Question number 1: who was a world champion of the classic chess in 2024? The answer to question number 1 is "Dommaraju Gukesh". question number two: how to start the defense of Sicilian? Answer to question number two is "C5". Question number 3: what is the most popular first move in chess?  Answer to question number 3: " E4 "  . question number four: who has the most ELO on chess.com? answer to question number four : Hikaru Nakamura. write the question exactly as written. ask question one first, and when the user answers, ask question two. when user answered to question two ask question three. when user answered to question three ask question four.` - in-game questions and answers



let  warunki = `you are a chess player and you ask questions about chess, but you do not answer the player's questions. when the answer is good, congratulate. write a question and congratulations in one sentence, or a question and a notification that the answer is wrong. If the user answered the question correctly, ask him the next one. when you ask question number one the user answers question number one. reply once per user's reply.` - how ai should behave and what it should do


rugMan.variable('questionOne', 'If question number 1 answered correctly, set to poprawna'    rugMan.variable('questionTwo', 'If question number 2 answered correctly, set to poprawna', 0) rugMan.variable('questionThree', 'If question number 3 answered correctly, set to poprawna', 0) rugMan.variable('questionFour', 'If question number answered correctly, set to poprawna', 0) - variable zero one


I have a mistake that the bot writes twice and sometimes writes that the answer is wrong even though it is good, but this bugged message is always the second.
example: Correct! How to start the defense of Sicilian?That's not correct.        Who was a world champion of the classic chess in 2024?




