# Twitch

The Twitch plugin allows you to view twitch chat and send messages from RuneLite.

## Usage

Messages will show up as a clan chat message, allowing you to filter them as you would regular clan chat messages. Messages can be sent to the channel by prefixing with `/t `. 

For example:
```
/t hi twitch
```

## Settings

### Username

Your Twitch username

### OAuth Token

Used to authenticate with Twitch, can be generated by using https://twitchapps.com/tmi

Once you've completed the login process on the above link, you'll be directed to the following page:
![twitchapps-post-login-token](img/twitch/twitchapps_post_login_token.png)  
Copy paste the code into the `Oauth Token` box. Do not alter the code, as the `oauth:` portion is required for login to work.


### Channel

The username of the channel you want to view the chat of.
