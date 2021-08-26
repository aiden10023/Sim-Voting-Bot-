# Greenway Stack Voting
A discord bot that allows users to vote privately

# Features
  - Polls that allow members of a group to anonymously vote
    - Unlimited options
    - Votes are completely secret
    - ~~Raw results are displayed when all users have voted~~
    - Tallied results are displayed when all users have voted
    -Multiple voting systems
      -Single vote
      -Multiple vote

# Instructions
  ### Starting a Poll
  Enter command `!vote start @group [opt1,opt2,opt3,...] mode`
  This will send a private message to all members of the mentioned group

  ### Voting in a poll
  To vote in a poll, enter the command hinted in the poll message, replacing <opt> with the option number you want
  
# Setup
  To add the bot to your server, follow the instructions [here](https://discordapp.com/oauth2/authorize?client_id=404741828315709440&scope=bot&permissions=482368).

# Future
  - Allow users to change their vote
  - Ranked voting systems
  - Better syntax error messages
  - [~~Each user can have multiple polls running~~]
  - [~~Users can stop polls manually~~])
  - [~~Poll results are tallied~~]
  - [~~Shorter poll ids~~]
  - [~~Sort results by votes~~]
  - ~~Ability to mention multiple users without needing a group~~ (Cancelled)
  - ~~Polls that close after an amount of time~~ (Cancelled)

# settings.json
  In order to protect my disord token, I have it hidden in a gitignored settings.json file. In order to run the bot, create a file called `settings.json` that contains`{"token":"YOUR_TOKEN"}` in the root folder.
