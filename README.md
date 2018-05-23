# Chatkit Command-Line Chat
> Command-Line chat application built with Pusher Chatkit!

## Environment Variables
I used ***.env*** file to store my environment varibales in it.

#### 1.  Environment Variables For Server
* `INSTANCE_LOCATOR`
* `CHATKIT_KEY`

#### 2. Environment Variables For Client
* `INSTANCE_LOCATOR`

## Requirements
To run this application, you will need a Chatkit instance. 

To create a new instance, navigate to the [Pusher Chatkit Dashboard](https://dash.pusher.com/), login or sign up if you are a new user. Once logged in, on dasboard click **`CREATE`**, enter some name for your new instance. After the new instance is created, you will see your **Instance Locator** and **Secret Key**, located under the **`CREDENTIALS`** section. You will need these credentials later to run you application.

## Run Application

To run this application you need to first start **SERVER** and then run **CLIENT**. You can run as many clients as you want. But before starting your application, install all the dependencies listed in ***package.json*** file. To install dependencies run following command:

```
> npm install
```

#### 1. For Server
After you are done installing all the dependencies, run following commands start server:

```
> node server.js
```

#### 1. For Client
***Note*** :  Create a user/room via the inspector in the [Pusher Chatkit Dashboard](https://dash.pusher.com/chatkit).

Now open another command line window and use following commands to run client:

```
> node client.js
```

You can can create as many clients as you want.