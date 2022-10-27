**# Encourage-bot_instructions**

## Getting an encouraging quote from the bot

As the name suggests, this bot, obviously, encourages the user. When the user types in `#inspire` (remember that "#" is activating the bot to repond to the user's typed in command) and hit Enter, the bot reponds to the command by giving a random encouraging quote everytime hte command is typed in and sent.


## Getting encouraging quotes on certain words

Well, let's say you are "sad" or "depressed" and you are tired of typing `#inspire` everytime to get an encouraging quote, and want to get an encouraging quote anyway. Well, I have resolved that too: just type in words like `sad`, `depressed`, `unhappy`, `angry`, `miserable`, `depressing` and boom, the Encorage Bot responds you with the encouraging quotes that are limited but random. <br/>
But what if you had to add your own encuraging quote? Well, I have found a [solution](https://github.com/kb0207/Encourage-bot_instructions/blob/main/README.md#adding-your-own-encouraging-quote) to that. <br/>

_(NOTE: This only works on some words that are stated above. I am working towards adding more relevant and suitable words to increase accessibility of the bot.)_

## Adding your own encouraging quote

Let's say you have got an amazing encouraging quote in your mind, but its not gonna teleport it to the bot's code. Hence I have added another command for people to add their own encouraging quote. Just type in `#add` and `type your own encouraging quote besides it` like this:- <br/>
`#add You are Amazing` and hit enter. This command hase added a customised encouraging quote that says **You are amazing** when you write words like `angry` or `sad`. The bot will notify you when the quote is added to the list. 

## To view the list of added encouraging quotes 

To add more functionality and accessibility to the user, I have added an option of viewing the list of all added encouraging quotes. Just type in `#list` and you'll see the added encouraging quotes. <br/>
_(NOTE: These are manually added by the user and are not the ones which you get when you type `#inspire`)_

## Deleting an encouraging quote

Let's assume you added a wrong or misspelled encouraging quote and you want to delete it. Well I have added another command to which the bot can repsond to by deleting the required quote. For this you'll need to have the list of the quotes to see which number of quote _(Numbering starts with 0)_ you want to delete as there might be many quotes already added. Go above to see how to [view the list of encouraging quotes](https://github.com/kb0207/Encourage-bot_instructions/blob/main/README.md#to-view-the-list-of-added-encouraging-quotes). Then type in `#del` and besides it, `add the number of the the quote from the list` we just retrieved. Enter the command and boom! your designated number of quote form the list is deleted by the bot. Here's an example for you to understand better:- <br/>
List is:
*(You are amazing, You are the best!, You will get through this phase)* <br/>
Numbering for the above list: *(0,1,2)* <br/>
**The numbering of the quotes starts with 0 (zero)** <br/>
Now assume you want to delete the quote *"You are the best!"* which is *"1"* as per the numbering.<br/> 
So to delete that quote, type - `#del 1` <br/>
and the quote- *"You are the best!"* is deleted from the list
<br/>

***For more accessibily, I will be adding more commands to the bot when I get free from my studies***
