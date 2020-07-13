# Trade Assistance Web Application with Django and TD Ameritrade
A Web Based Trade Assistance - Create Website watchlist with real-time quotes from  TD ameritrade API & CNBC data
                             - Display put/call option strike prices, DTE, Calculate premium%, desired%, Fulfuilment%, Sort filter
                             - Sort the list of eligible stocks and provide actions. e.g position size, risk based on account value.
                             - Send eligible list of stocks to user's email, and allow user to place trade via website  with TD API.
                             - completion of project with no bugs, website must be user friendly and athentically pleasing.
It uses [Argon Django Template](https://github.com/app-generator/django-dashboard-argon)

###### Live Demo
Visit [here](http://93.190.138.32:8000/) to see the live demo

### Technologies Used

#### Web Technologies
Html , Css , JavaScript , Bootstrap , Django

#### Database
SQLite

##### Requirements
```
python 3.6

pip3

virtualenv
```
##### Setup to run

Extract zip file in your computer

Open terminal/cmd promt

cd to the following path, edit ``` django_findata-master/app/td/config.py ``` to add your own TD Ameritrade credentials

Go to that Path

Example

```
cd ~/path to your folder/django_findata-master
```
Create a new virtual environment on that directory

```
virtualenv .
```

Activate Your Virtual Environment

for Linux
```
source bin/activate
```
for Windows
```
cd Scripts
then
activate
```
To install Dependencies

```
pip install -r requirements.txt
```

### Creating Local Server

Goto src directory, example

```
cd ..your own path/pstrader/
```
To run
```
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```
Now open your browser and go to this address
```
http://127.0.0.1:8000
```
Thank you for visiting my repository.
Skype id : live:.cid.73af65b7d0073a91
Telegram : @Volo

Don't forget to give star!!

