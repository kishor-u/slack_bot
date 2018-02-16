### SlackBot

SlackBot sends the output of the commands typed in the bash shell to your slack channel.

#### Steps :

* Download the slackbot exectable and make it executable.

* chmod +x ./slackbot

* Add config file in the user directory as /home/${USER}/.slackbot.conf with two entries 
WEBHOOK='xxxxxxxxxxx'
CHANNEL='xxxxxxxxxxx'

* Run your command as slackbot COMMAND and see the slack.
