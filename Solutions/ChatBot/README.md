# ChatBot

The ChatBot is an OpenAI Enabled Chatbot which can be configured to answer how ever you would like.

## Prerequisites

To use the Chatbot, you will need an Open AI API Account.

### Account setup
First, create an [OpenAI account](https://platform.openai.com/signup) or [sign in](https://platform.openai.com/login). Next, navigate to the [API key page](https://platform.openai.com/account/api-keys) and "Create new secret key", optionally naming the key. Make sure to save this somewhere safe and do not share it with anyone.

### Secret Setup
1. In World of Workflows, Go to **Admin -> Workflows**. Click **Credential Manager**
2. Click **Add New**
3. Choose **Http Authorization**
4. Name it ```ChatGPT```
5. Enter the following in the Authorisation Field:
   ```<Secret Key>``` Where ```<Secret key>``` is the key from **Account Setup Above**
6. Click **Save**

## Getting Started

- Navigate to https://localhost:7063/chatbot