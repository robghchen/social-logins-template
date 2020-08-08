# social-logins-template

Your .env file would look like this:

```
FACEBOOK_CLIENT_ID='your-clientID-here'
FACEBOOK_CLIENT_SECRET='your-client-secret-here'
FACEBOOK_CALLBACK_URL='http://localhost:4000/api/auth/facebook/callback'
FACEBOOK_PROFILE_URL='https://graph.facebook.com/v2.5/me?fields=first_name,last_name,email'

TWITTER_CONSUMER_KEY='your-consumer-key-here'
TWITTER_CONSUMER_SECRET='your-client-secret-here'
TWITTER_CALLBACK_URL='http://localhost:4000/auth/twitter/callback'

GOOGLE_CLIENT_ID='your-consumer-key-here'
GOOGLE_CLIENT_SECRET='your-client-secret-here'
GOOGLE_CALLBACK_URL='http://localhost:4000/auth/google/callback'
```
