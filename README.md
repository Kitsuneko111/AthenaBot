# AthenaBot
This is the public repo for the AthenaBot project

## What is Athena?
Athena is a long term project designed to give users more interaction to a Discord Bot than normal

### Where is it now?
The code is currently under a seperate, private, repo where it is learning how to use DialogFlow to handle user input.

### Where did it start?
Athena started as a text-based python project to allow users to submit Q&A to a bot to recieve answers.

### Will the functionality continue?
Maybe sometime it will, once the basic Discord framework is down.

## History
- 0.0.0 - I wanted to make a program that could answer Q&A to see where it went. I used recursion for some reason.
- 0.0.1 - Changed to normal loops
- [Period of time with no significant additions or changes]
- 0.1.0 - After I discovered the Discord API I decided to try the project again, this time in JS
- [Period of time where I lost motivation]
- I joined a server with a bot that used Dialogflow to take user input, but required a keyword still and functioned to basic requests, such as info or memes.
- 0.2.0 - RASA got involved, I thought this was simpler than DialogFlow but I was wrong
- 0.2.1 - Changed to DialogFlow and now it is running basic commands smoothly.

## How do I use Athena?
### How do I get Athena?
Athena is currently under development, when it can do more it will be available for invites
### What can Athena do?
✔ Respond to a wake up call (e.g. `Athena, are you there?`)

✔ Tell you it's ping

✔ Ping another user [Current WIP]

✔ Confirm Actions [Current WIP]
### How does Athena Work in my server?
1. Wake Athena up by sending a message with `Athena` somewhere in it (e.g. `Hello Athena` or `Athena what is your ping?`)
> Note: Athena will only respond to messages it understands, but it will be awake
2. Give it a command it can recognise (e.g. `mute Timemaster111#xxxx`)
3. If Confirmation is needed, confirm
4. The action will be done!

Athena should go back to sleep after a few ignored requests, and won't interfere with conversations.