# llSPS-INT-2919-Intelligent-Customer-Help-Desk-with-Smart-Document-Understanding-master

## Overview
The typical customer care chatbot can answer simple questions, such as store locations and hours, directions, and maybe even making appointments. When a question falls outside of the scope of the pre-determined question set, the option is typically to tell the customer the question isn’t valid or offer to speak to a real person.

In this project, there will be another option. If the customer question is about the operation of a device, the application shall pass the question onto Watson Discovery Service, which has been pre-loaded with the device’s owners manual. So now, instead of “Would you like to speak to a customer representative?” we can return relevant sections of the owners manual to help solve our customers’ problems.

To take it a step further, the project shall use the Smart Document Understanding feature of Watson Discovery to train it on what text in the owners manual is important and what is not. This will improve the answers returned from the queries.

## Hardware and Software Designing
1. Create IBM Cloud services
   - Watson Discovery
   - Watson Assistant
   - Node Red App
2. Configure Watson Discovery
   - Import and Annotate the Document
3. Create IBM Cloud Functions action.
   - Configure Action script and parameters
4. Create a Node red flow to connect all the services together.
5. Configure Watson Assistant.
   - Create required Intents, Entities, webhooks and Dialog Skills.
6. Create flow and configure node
7. Deploy and run Node Red Chatbot App.

## Results
The chatbot was successfully made using Watson assistant and using SDU. All the services were
integrated using Node Red Application.

Chatbot URL - https://node-red-iiqmy.eu-gb.mybluemix.net/chat

Youtube Demo URL -  https://youtu.be/BK5MhrBRbKI

## For Detailed Information

[Documentation.pdf](https://github.com/AbhishekSoni98/llSPS-INT-2919-Intelligent-Customer-Help-Desk-with-Smart-Document-Understanding-master/blob/master/Documentation.pdf)

## Author

Abhishek Soni

Email: abhisheksoni1998@gmail.com
