### SlackBot

SlackBot sends the output of the commands typed in the bash shell to your slack channel.

#### Steps :

* Download the slackbot executable and run chmod +x ./slackbot.

* Add config file in the user directory as /home/${USER}/.slackbot.conf with two entries <br />
  WEBHOOK='xxxxxxxxxxx' ( https://api.slack.com/incoming-webhooks ) <br />
  CHANNEL='xxxxxxxxxxx' ( Name of the channel you need to receive the output ) 

* Run your command as `slackbot COMMAND` and see the slack.
