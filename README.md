# 🌟 Customer Support Agents Using Langflow
This project aims to create a multi-agent customer support system utilizing Langflow, Retrieval-Augmented Generation (RAG), and OpenAI's GPT-4o-mini. The system is designed to handle various customer inquiries by leveraging a combination of agents, each with specific roles and responsibilities.

<div style="text-align: center; margin-bottom: 20px;">
    <img src="https://github.com/user-attachments/assets/8e2bea86-d64c-40d8-8ce4-270932e91066" alt="Screenshot" width="600" style="border: 2px solid #4CAF50; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);"/>
</div>

## Project Overview

### **Architecture**

The architecture consists of three main agents:

### Agents Overview

1. **FAQ Agent**: 
   - **Role**: Answers general questions using information from a vector database derived from an FAQ PDF.
   - **Functionality**: Utilizes RAG to fetch relevant data points based on user queries.

2. **Manager Agent**: 
   - **Role**: Acts as a customer service manager and information router.
   - **Functionality**: Determines whether to engage the FAQ Agent or the Order Lookup Agent based on the user's question. It can look up order numbers, access product information, and answer FAQs related to shipping and returns.

3. **Order Lookup Agent**: 
   - **Role**: Specializes in analyzing customer orders.
   - **Functionality**: Looks up order numbers and product IDs to provide detailed order summaries. If an order ID is not found, it prompts the user to try again.

## 🎨 Work Flow

<div style="text-align: center; margin-bottom: 20px;">
    <img src="https://github.com/user-attachments/assets/e57e6dec-ad02-445f-a72a-c396bb52903f" alt="Work Flow" width="80%" style="border: 2px solid #4CAF50; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2); transition: transform 0.2s;" onmouseover="this.style.transform='scale(1.05)'" onmouseout="this.style.transform='scale(1)'"/>
</div>

---

### **Technologies Used**


  1. **Langflow**: For creating and managing the agents.
  2. **OpenAI GPT-4o-mini**: As the language model for generating responses.
  3. **Streamlit**: For building the web interface.
  4. **AstroDB**: For storing vectorized data and normal database entries.  


## Implementation

### **Code Repository**

For the complete implementation details, please refer to the [main code in the repository](https://github.com/Hemachandaran/Customer-Support-Agent/blob/main/main.py).

### **How It Works**

1. **User Input**: The user submits a question via the Streamlit chat interface.
2. **Flow Triggering**: Clicking "Run Flow" sends the query to the Langflow API after validating input.
3. **Agent Selection**: The Manager Agent analyzes the question to determine whether to use the FAQ or Order Lookup Agent.
4. **Data Retrieval**: The selected agent fetches relevant information from either the vector database or normal database.
5. **Response Generation**: The response is formulated and displayed back in the chat interface for user review.

## 📊 Output

<div style="display: flex; flex-wrap: wrap; justify-content: center; margin-bottom: 20px;">
    <img src="https://github.com/user-attachments/assets/7593518f-860b-4fe8-b0cb-05951b9edb39" alt="Output 1" width="30%" style="margin: 10px; border: 2px solid #4CAF50; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, .2); transition: transform .2s;" onmouseover="this.style.transform='scale(1.05)'" onmouseout="this.style.transform='scale(1)'"/>
    <img src="https://github.com/user-attachments/assets/17c6b489-aa90-4c64-bce2-d4a64e9daa47" alt="Output 2" width="30%" style="margin: 10px; border: 2px solid #4CAF50; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, .2); transition: transform .2s;" onmouseover="this.style.transform='scale(1.05)'" onmouseout="this.style.transform='scale(1)'"/>
    <img src="https://github.com/user-attachments/assets/83eb8898-6e10-417f-a780-29b3c7bab710" alt="Output 3" width="30%" style="margin: 10px; border: 2px solid #4CAF50; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, .2); transition: transform .2s;" onmouseover="this.style.transform='scale(1.05)'" onmouseout="this.style.transform='scale(1)'"/>
    <img src="https://github.com/user-attachments/assets/14f4ab24-46d2-49da-bcdb-3bdf32a23c25" alt="Output 4" width="30%" style="margin: 10px; border: 2px solid #4CAF50; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, .2); transition: transform .2s;" onmouseover="this.style.transform='scale(1.05)'" onmouseout="this.style.transform='scale(1)'"/>
    <img src="https://github.com/user-attachments/assets/5494d648-c55e-4103-826e-650686e21068" alt="Output 5" width="30%" style="margin: 10px; border: 2px solid #4CAF50; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, .2); transition: transform .2s;" onmouseover="this.style.transform='scale(1.05)'" onmouseout="this.style.transform='scale(1)'"/>
    <img src="https://github.com/user-attachments/assets/434f0c8d-53ee-4d25-a575-bc2c81438302" alt="Output 6" width="30%" style="margin: 10px; border: 2px solid #4CAF50; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0,. 2); transition:. 2s;" onmouseover="this.style.transform='scale(1.05)'" onmouseout="this.style.transform='scale(1)'"/>
    <img src="https://github.com/user-attachments/assets/49e40ab3-a522-47f9-92ab-51d7b9b826d9" alt="Output 7" width="30%" style="margin 10 px;border 2 px solid #4CAF50;border-radius 10 px;box-shadow 0 4 px 8 rgba(0,. 0,. 0,. 2);transition:. 2s;"onmouseover=this.style.transform='scale(1.05)'onmouseout=this.style.transform='scale(1)'/>
</div>

---

## 📅 Completion Date
<div style="text-align:center;">
    <strong>Saturday, January 11, 2025</strong><br>
    <small>12 PM IST</small>
</div>
