# WeatherSMS !

An app that send you SMS to your phone number from your city using the Weather API and Twilio!

![enter image description here](https://pbs.twimg.com/media/Fmc5LlXWYAMZUWe?format=png&name=small)![enter image description here](data:image/jpeg;base64,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)   ![enter image description here](data:image/png;base64,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)

### Table of Contents
  * [Installation and usage](#installation)
  * [Libraries](#libraries)

## <a name="installation"></a> Installation and usage

Make sure you have: 

|                |CMD                          |Description                       |
|----------------|-------------------------------|-----------------------------|
|Twilio          |`pip install twilio`            |For SMS            |
|Pandas          |`pip install pandas`            |For Dataframe            |
|tqdm			 |`pip install tqdm`			  |For progressbar|

## <a name="libraries"></a> Libraries
  * [twilio-rest](https://github.com/twilio/twilio-python)
  * [twilio-config](https://github.com/twilio/twilio-python)
  * [tqdm](https://github.com/tqdm/tqdm#readme)





# twilio_config.py

twilio_config.py will be the file that connect your app with twilio.

```console
TWILIO_ACCOUNT_SID ='abcdabdcabcdabdcabcdabdcabcdabdc'
TWILIO_AUTH_TOKEN ='abcdabdcabcdabdcabcdabdcabcdabdc'
PHONE_NUMBER ='+123456789101112'
API_KEY_WAPI = 'abcdabdcabcdabdcabcdabdcabcdabdcab'
```

> **NOTE:** You have to buy a **PHONE NUMBER** and you have a free trial of **15 USD**.



This project was created only for testing & education purposes.