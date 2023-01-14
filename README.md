
# WeatherSMS !

  

An app that send you SMS to your phone number from your city using the Weather API and Twilio!

  <img  src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/7e/Twilio-logo-red.svg/512px-Twilio-logo-red.svg.png?20190613203915" alt="Markdown Monster icon" width="20%"/>
  <img  src="https://blog.weatherapi.com/wp-content/uploads/2020/02/cropped-Asset-62-1.png" alt="Markdown Monster icon" width="20%"/>

![screenshot from my cellphone](https://pbs.twimg.com/media/Fmc5LlXWYAMZUWe?format=png&name=small)





  

### Table of Contents

* [Installation and usage](#installation)

* [Libraries](#libraries)

  

## <a name="installation"></a> Installation and usage

Make sure you have:

  |        | CMD | DESCRIPTION
|:--------:| -------------:| -------------:|
| Twilio | `pip install twilio` |For SMS |
| Pandas | `pip install pandas` |For Dataframe |
| tqdm   | `pip install tqdm` |For progressbar|

  

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
>  **NOTE:** You have to buy a **PHONE NUMBER** and you have a free trial of **15 USD**.

  
  
  

This project was created only for testing & education purposes.