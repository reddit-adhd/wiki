Mel-bot is our friendly #/r/ADHD bot.  For the technically inclined, she is an instance of the [Limnoria](https://github.com/ProgVal/Limnoria) bot, which is forked from [supybot](http://sourceforge.net/projects/supybot/).

All commands to mel-bot can be performed in chat by prefixing the command with an **!** (e.g. `!remind ...`) or by talking to her directly in a private message

**If you abuse the bot, bot privileges can and will be taken away on a per-user basis.**

She can do a few neat things (list is wildly incomplete):

## Web Page Title Fetching
Mel-bot will do her best to display the title of web pages linked in the chat.  There are some instances where it won't work:

* Direct image links
* Pages that use funky encoding in their titles
* Probably more

## Reminders
Have something you need to do but not right away?  Let mel-bot keep track of it for you!  Great for reminding you to get back on task after taking a short break, or to research a topic, or to.. well, anything!

**Syntax:** `remind <user> in <number> <time units> to/about <thing>`

**Example:** `remind me in 75 minutes to check on the roast`  

*or* `remind sugardeath in 15 minutes to check out that post on the subreddit`

*Please be courteous and do not spam reminders for other users.*

## Message Queuing
Is someone not online (e.g. one of the mods) but you need to message them?

**Syntax:** `later tell <user> <message>`  
**Example:** `later tell sugardeath I don't see my post, did it get caught in the spam filter?`

