# WebRTC Hello World Video
<a href="http://dev.bandwidth.com"><img src="https://s3.amazonaws.com/bwdemos/BW-VMP.png"/></a>

 # Table of Contents

<!-- TOC -->

* [WebRTC Hello World Video](#webrtc-hello-world-video)
* [Description](#description)
* [Pre-Requisites](#pre-requisites)
* [Environmental Variables](#environmental-variables)
* [Callback URLs](#callback-urls)
* [Running the Application](#running-the-application)
  * [Run](#run)
  * [Ngrok](#ngrok)

<!-- /TOC -->

# Description

A simple 1:1 WebRTC video application.

# Pre-Requisites

In order to use the Bandwidth API, users need to set up the appropriate application in their [Bandwidth Dashboard](https://dashboard.bandwidth.com/) and create [API credentials](https://dev.bandwidth.com/guides/accountCredentials.html#top). WebRTC must be enabled for your account to run this sample. Please check with your account manager to ensure you are provisioned for WebRTC.

To create an application, log into the [Bandwidth Dashboard](https://dashboard.bandwidth.com/) and navigate to the `Applications` tab.  Fill out the **New Application** form, selecting the service (Messaging or Voice) that the application will be used for.  All Bandwidth services require publicly accessible Callback URLs. For more information on how to set one up see [Callback URLs](#callback-urls).

For more information about API credentials see [here](https://dev.bandwidth.com/guides/accountCredentials.html#top).

# Environmental Variables

The sample app uses the below environmental variables.
```sh
BW_ACCOUNT_ID                        # Your Bandwidth Account Id
BW_USERNAME                          # Your Bandwidth API Username
BW_PASSWORD                          # Your Bandwidth API Password
```

# Running the Application
## Run
Use the following commands to run the application:

```sh
npm install
node index.js
```
