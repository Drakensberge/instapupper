# InstaPupper
## Send dog memes from instagram as text messages

Is someone you know sad? Do they like dogs? Of course they do! Send them a picture of a doggo!

This notebook queries instagram for a given hashtag feed using the *unofficial* API https://github.com/LevPasha/Instagram-API-python.

It extracts the image and the caption and sends it as a text message using the free trial version of https://www.twilio.com/console (more specifically, the SMS chatbot tool).

To use it, you'll need to set up a twilio account and an instagram account. You'll only be able to send messages to your phone and people who can send you a confirmation code.

Kudos to https://github.com/NourGalaby for his writeup here https://www.kdnuggets.com/2017/08/instagram-python-data-analysis.html

I highly recommend putting *NOT* saving all your sensitive variables in the notebook. One option is to use https://github.com/theskumar/python-dotenv. If you do that, don't commit/track your .env file!

You should
```
pip install -r requirements.txt
```
to get started.
