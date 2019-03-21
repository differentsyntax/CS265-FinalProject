```
temperature
```

## Description:

    Everytime I wake from a long nap (which usually happens every evening) and I have no idea what's it like outside and whether I should go out in my shorts or get layered up before heading out, I only think of how much better it would have been to get an automated notification on my phone every evening about the temperature outside so I wouldn't have to manually check it everybody and think over it. The final project script is titled temperature and as the name suggests, it will be getting the temperature data from an open-source URL. Now, once the current outside temperature is known to the script, it will send me a notification on a Slack channel in my workspace on whether it is too hot, too cold or just fine outside. This would entirely be based upon my preference. Slack app provides amazing integrations and features to play with and one such feature is incoming webhooks. Configuring them properly, a message can be sent on any channel in the workspace from any server. You can join the workspace using the following link: https://join.slack.com/t/ma3388cs265wi-kym5285/shared_invite/enQtNTgxNDU4Njk4MjcyLTQ3NjEzNjA3Y2Q3YjAyMjE4YzAyOTQwYTVmZmY2NDJjYjc0NTFkOWM2NTE4YjZkMjdlMTMxMjAzM2Q5ODBkNmE . The script would also have the potential to be set up to be executed everyday at a particular time using crontab but I figured it is not needed as it can be executed as and when required for demo or test purposes at this time.

## Tools Used:

    * curl
    * grep
    * sed
    * echo
    * slack incoming webhooks
    
## Link to Access Weather Data:

    wttr.in/<city>
