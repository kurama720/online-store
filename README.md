# Online store

___

## What does it use?
___
- **Python 3.8** 
- **Django 3** 
- **Celery** 
- **Braintree** 
- **HTML/CSS** 
- **Git** 

## How to install?
___
1. ```$ git clone git@github.com:kurama720/online-store.git```
2. Install requirements.
3. Install and run rabbitmq-server.
4. Sign up at _https://www.braintreepayments.com/sandbox_.
5. Fill in _Merchant ID_, _Public Key_ and _Private Key_ at the bottom of _/myshop/myshop/settings.py_.   

## How to run?
___
1. ```$ python manage.py migrate``` at the project root.
2. ```$ python manage.py runserver```
3. Visit localhost:8000/

## Description
___
This project is an online store where users can filter products by their category and look through them. 
They can choose quantity and add products into their own cart, which calculates the sum of added items.   
The payment system is implemented with Celery and Braintree.