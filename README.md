# END to END NLP Chat Bot :FOODPANDA
I have successfully created a chatbot for a food delivery system using Dialogflow. This project involved working with Dialogflow's fundamental concepts such as intents, entities, contexts, actions, and fulfillments. I also had to develop the backend using Python and FastAPI, and interact with a MySQL database.

## Demo video 
[Demo video on linkedin](https://www.linkedin.com/posts/manojjprabakaran_chatbotdevelopment-dialogflow-nlp-activity-7179176630962069504-jyp3?utm_source=share&utm_medium=member_desktop)
## How to RUN
1. create conda environment
2. Install requirements.txt
```
pip install requirements.txt
```
3. run this command
```
uvicorn main:app --reload
```
4. since google dialogflow fullfillment is accecpt only the https so download the ngrok exe and run this command in cmd to change http protocol into https
   ```
   ngrok http 8000
   ````
   
