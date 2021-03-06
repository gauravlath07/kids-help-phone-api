<img align="right" src="https://github.com/gauravlath07/kids-help-phone-api/blob/master/gift_the_code.png" height="100" width="100">
<img align="right" src="https://github.com/gauravlath07/kids-help-phone-api/blob/master/kids_help_phone.png" height="100" width="350">


# Kids Help Phone (Alegra)


# About
<p>This app was developed at Gift The Code 2017 a hackathon organized for charity.<br>

Alegra is a user friendly web dashboard which analyzes the mental state of a user according to their social media profiles using NLP and image classification.<br>

After diagnosing the person, Alegra recommends therapy and helplines according to the user's location.

This app was built for a charity called Kids Help Phone to diagnose depression and anxiety among teenagers. You can find out more about the charity by clicking <a href='https://kidshelpphone.ca/'>here</a>.
</p>


# Technologies Used
For NLP we used Python's NLTK library. Training data was picked up from stanford database of 20,000 tweets each of them classified according to sentiment. <br>
This model was deployed as an API on gunicorn and hosted on AWS EC2 instance.

P.S. This repository only holds the backend repository for sentiment analysis of twitter. For the front end and other repositories checkout the organization Kids Help Phone under my profile.

P.P.S The training file has not been included for ownership purposes. But the pkl file for the model has been pushed and is present in this repository.
