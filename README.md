# Azure Text Analytics with Streamlit

This project demonstrates how to create a simple web application using Streamlit that integrates with Azure Cognitive Services for Text Analytics. The application performs sentiment analysis on user-inputted text using Azure's Text Analytics API.

## Prerequisites

Before running the application, ensure you have the following:

- An Azure account with a Text Analytics resource. You can create one [here](https://portal.azure.com/).
- The `endpoint` and `subscription key` for your Text Analytics resource.

## Setup

1. **Clone the Repository**

   Clone this repository to your local machine:

   ```bash
   
   git clone https://github.com/yourusername/azure-text-analytics-streamlit.git
   cd azure-text-analytics-streamlit
#STEPS TO RUN THE PROJECT

1.INSTALL REQUIRED PACKAGES
 ```bash
pip install streamlit azure-ai-textanalytics azure-storage-blob
  ```

2.EDIT YOUR KEY AND ENDPOINT IN THE CODE
->HOW TO GET ENDPOINT AND KEY FROM AZURE AI SERVICE-
To integrate Azure AI services into your project, follow these steps to retrieve the endpoint and key from the Azure AI portal:

Log in to Azure Portal: Go to Azure Portal and sign in with your credentials.

Navigate to Your Resource: From the dashboard, search for your AI service (e.g., Azure Cognitive Services, Language, or Vision service) in the search bar and select your deployed resource.

Access Keys and Endpoint:

![image](https://github.com/user-attachments/assets/2bc8b692-7092-444e-b76a-262556a3f48d)


In the resource's overview page, select the "Keys and Endpoint" section from the left-hand menu.
Copy the Endpoint URL and Key provided. These will be used for authenticating API requests in your project.
Use in Project: Add the retrieved Endpoint and Key into your application configuration or code to authenticate API calls to Azure AI services.

This ensures your project securely connects to the Azure service.

![image](https://github.com/user-attachments/assets/e5e2bea0-a6eb-42d6-8c39-300419682624)

3.RUN THE PROGRAM USING FOLLOWING COMMAND

 ```bash
   streamlit run filename.py
  ```
![image](https://github.com/user-attachments/assets/53b5382d-774c-49ab-8668-3604f69e023a)

4.PROJECT RUNNING
![image](https://github.com/user-attachments/assets/dee39bf7-c564-4f6e-818a-204fc8a0aff5)
![image](https://github.com/user-attachments/assets/b8ed6b6d-963a-4950-a6db-8be63f702f8b)
![image](https://github.com/user-attachments/assets/121a7ad6-2bfc-403e-97d2-eff3bcc0a0ed)
![image](https://github.com/user-attachments/assets/d8a1bf29-c5f8-4ca1-8641-05895f07147b)



