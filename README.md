# NLP Chatbot using GCP Dialogflow, FastAPI and MySQL (FullStack)

## Overview

The Food Ordering Chatbot is an intelligent conversational agent designed to streamline the food ordering process for a food delivery website. Built using **_GCP Dialogflow_** for natural language understanding and **_FastAPI_** for backend integration, the chatbot interacts with users, takes their orders, and stores order details in a **_MySQL_** database. The chatbot provides a seamless and user-friendly experience for customers to place their food orders. The chatbot is integrated with a frontend interface using **_HTML_** and **_CSS_**, offering a cohesive and engaging user experience.

## Technical Components and Libraries

-  **Python**: The primary programming language used for backend development and integration.
  
-  **Dialogflow**: Dialogflow is used for building conversational interfaces. It processes user inputs and matches them to intents, allowing the chatbot to understand and respond to user queries.

-  **FastAPI**: FastAPI is a modern web framework for building APIs with Python based on standard Python type hints. It's known for its high performance and ease of use.

-  **MySQL**: MySQL is a relational database management system used to store the order details from the chatbot.

-  **Uvicorn**: Uvicorn is an ASGI server implementation for Python. It's used to run the FastAPI application.

-  **Ngrok**: Ngrok provides secure introspectable tunnels to localhost, allowing you to expose a local server to the internet.

-  **HTML**: HTML is the standard markup language for creating web pages. It structures the content on your website.

-  **CSS**: CSS is used for describing the presentation of a document written in HTML. It controls the layout, colors, fonts, and overall visual style of the website.

## Workflow
### AI and Natural Language Processing (NLP)

-  **Dialogflow**: The core AI component of the project, Dialogflow enables the chatbot to understand and process user inputs. It uses advanced NLP techniques to parse user queries and respond appropriately.
-  **Intents**: Defined in Dialogflow, intents represent the actions that the chatbot can perform. Each intent corresponds to a specific user request, such as placing an order or querying the menu.

![image](https://github.com/amoljain2k/NLP-Chatbot-with-Dialogflow-FastAPI-MySQL-FullStack/blob/main/Chatbot%20SS/intents.PNG)

-  **Prompt Engineering**: Intents are trained with various user expressions to ensure accurate understanding and response to diverse queries.
  
![image](https://github.com/amoljain2k/NLP-Chatbot-with-Dialogflow-FastAPI-MySQL-FullStack/blob/main/Chatbot%20SS/Intents%20Training%20Phrases.PNG)

- **Entities**: Entities are data points extracted from user inputs, such as food items and quantities. They help the chatbot understand specific details within user queries.

![image](https://github.com/amoljain2k/NLP-Chatbot-with-Dialogflow-FastAPI-MySQL-FullStack/blob/main/Chatbot%20SS/entities.PNG)

### Integration with Frontend
- **Home Page with Chatbot Integration**: The chatbot is seamlessly integrated into the home page, offering users an intuitive way to start interacting and place orders directly from the main interface.

![image](https://github.com/amoljain2k/NLP-Chatbot-with-Dialogflow-FastAPI-MySQL-FullStack/blob/main/Chatbot%20SS/MainScreen.PNG)

### Chatbot in Action
1. **User Initiating Interaction**:
- User greets the chatbot and receives a welcoming response, User can either place a **New Order** or **Track an Order**

![image](https://github.com/amoljain2k/NLP-Chatbot-with-Dialogflow-FastAPI-MySQL-FullStack/blob/main/Chatbot%20SS/chatbot1.PNG)

2. **Menu Display via Chatbot**:
- User placing a New Order, the chatbot provides a detailed menu, showcasing its ability to retrieve and present menu items dynamically.
  
![image](https://github.com/amoljain2k/NLP-Chatbot-with-Dialogflow-FastAPI-MySQL-FullStack/blob/main/Chatbot%20SS/chatbot2.PNG)

3. **Order ID Generation and Confirmation**:
- The chatbot guides the user through the order placement process, capturing details such as item names and quantities in a conversational manner.
- After processing the user's order, the chatbot confirms the details directly in the chat interface, ensuring the user has a clear understanding of their order before finalizing.
- Upon successful order placement, the chatbot generates a unique order ID and confirms it with the user, enhancing the order tracking capability.
- The chatbot seamlessly interacts with the backend, storing order details in the MySQL database, ensuring data persistence and reliability.

![image](https://github.com/amoljain2k/NLP-Chatbot-with-Dialogflow-FastAPI-MySQL-FullStack/blob/main/Chatbot%20SS/chatbot%203%264.jpg)

4. **Error Handling and User Guidance** :
- User makes an ambiguous request and the chatbot asks for clarification.
- The chatbot showcases its robustness by handling ambiguous inputs gracefully, prompting the user for necessary clarifications to proceed with the correct action.

![image](https://github.com/amoljain2k/NLP-Chatbot-with-Dialogflow-FastAPI-MySQL-FullStack/blob/main/Chatbot%20SS/chatbot6.PNG)

5. **Order Tracking via Chatbot**:
- The chatbot allows users to track their orders by entering the order ID, demonstrating its ability to retrieve and display order status in real-time.

![image](https://github.com/amoljain2k/NLP-Chatbot-with-Dialogflow-FastAPI-MySQL-FullStack/blob/main/Chatbot%20SS/chatbot%205.PNG)
  
