# Development and Evaluation of a Chatbot - MediMate 


## Abstract
This project aims at providing a interactive surface for the international students via a chatbot. The one thing that every international student faces being in a different country is to find doctors and their details being new to a place. We tried to solve this problem by developing a simple chatbot that can find user a doctor and all the necessary information regarding it. The chatbot was developed using Google Dialogflow which is used to create intents for training using Natural Language Processing (NLP). We used Flask framework using Python to train the bot and fulfill responses based on the intents that get matched when a user expresses something over the chatbot. We also integrated Firestore database to fetch information about the doctors and to store information about users chat history. In order, for the Dialogflow and the application built using flask to work, we hosted it over PythonAnywhere and finally published on Telegram Platform. While building the bot we took into consideration few qualitative measures like usability, attractiveness and acceptance tests. For designing the intents, we made flow charts to get a sense of what was needed so that we could structure the flow of the chatbot. This made the chatbot efficient and easy to develop. After the deployment, we conducted a evaluation of the bot using a Google form to understand users perspective and improvising the chatbots functionality and future research. Due to its functionality and structure of data, the final product received generally positive reviews from users.

## Architecture Diagram
![Integration flow](https://user-images.githubusercontent.com/36732130/203413233-6cf3f813-f36e-4eea-ae7a-530c0e7b5553.png)

## Snippets from the bot

<img width="487" alt="5 1" src="https://user-images.githubusercontent.com/36732130/203413984-400b5736-648a-4b0b-8323-bd6ff7848b70.png">
<img width="481" alt="5 3 1" src="https://user-images.githubusercontent.com/36732130/203414053-2f653e0d-af4a-4479-8097-5d71b3d2b2b0.png">
<img width="413" alt="5 3 2" src="https://user-images.githubusercontent.com/36732130/203414238-f98e0ce0-eb6f-4fb0-bafc-fca9e808f7a6.png">
 
## Evaluation Results

Our research was mainly to accommodate all the necessary information tohelp international students in seeking information for medical help. In our benchmark evaluation, we see that our Dependability score comes under the category of Excellent with a mean of 2.162. It comprises all the necessary information such as the contact details, navigational routes , operational hours and filters according to the language of communication of the user. Although, our bot does not cover all symptoms and specializations, we have touched the most common specializations and also emergency data. This has therefore led users to depend on the bot in times of need. Despite the fact that some insurance companies have a feature to filter out with respect to specialization and language, they lack popularity. In addition, our bot also comforts the user by having an interactive conversation. Overall, we have included the main functionalities required but on adding more, our chatbot, Medimate, would prove to be more beneficial for the growing population of incoming international students in Germany

<img width="743" alt="scale benchmark" src="https://user-images.githubusercontent.com/36732130/203414547-9c76aa22-7476-4953-82b1-44e928fe63a0.png">
