# RAG Challenge

## Overview

This readme describes the web-app we have created for the challenge.

```bash
streamlit run app.py

```

## Container setup

1. build the image. (see the ./deploy/docker-commands.ps1 file)
2. publish the container in ACR. (see the ./deploy/azure_commands.ps1 file)
3. create the container in Azure. (see the ./deploy/azure_commands.ps1 file)

## Screen captures

In each page there is an option button to consume the data from local postgres, or from Azure postgres PaaS. If using the local data, the application is not prepared to run the queries to the embeddings out of Azure postgres. This means that the chatbot would not work.

![alt text](../images/app/image-001.png)

Chatbot configuration options (detailed below in the chatbot section):

- Input tokens.
- Output tokens.
- model to use.
- Distance calculation algorithm (only cosine and inner product tested).
- Temperature.
- Top n.
- Role.System message.
- Role.User message.
- Showing logs (real data used for the answer).

TODO. Detail.

## The project

![alt text](../images/app/image-0.png)

## Competitions

![alt text](../images/app/image-1.png)
![alt text](../images/app/image-2.png)
![alt text](../images/app/image-3.png)
![alt text](../images/app/image-4.png)
![alt text](../images/app/image-5.png)

## Matches

![alt text](../images/app/image-6.png)
![alt text](../images/app/image-7.png)
![alt text](../images/app/image-8.png)
![alt text](../images/app/image-9.png)

## Teams

![alt text](../images/app/image-10.png)
![alt text](../images/app/image-11.png)
![alt text](../images/app/image-12.png)
![alt text](../images/app/image-13.png)

## Players

![alt text](../images/app/image-14.png)
![alt text](../images/app/image-15.png)

## Events

![alt text](../images/app/image-16.png)
![alt text](../images/app/image-17.png)
![alt text](../images/app/image-18.png)
![alt text](../images/app/image-19.png)

## Chat History

![alt text](../images/app/image-20.png)
![alt text](../images/app/image-21.png)
![alt text](../images/app/image-22.png)

## Chatbot

![alt text](../images/app/image-23.png)
![alt text](../images/app/image-24.png)

## Readme

![alt text](../images/app/image-25.png)