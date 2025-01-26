### Project Description: Personalized Cold Email Generator for Job Applications  

This project involves building a **Personalized Cold Email Generator** using **GROQ**, **LangChain**, and **Streamlit**. The tool is designed to streamline the job application process by generating tailored cold emails based on the job listings found on a company's careers page. 

#### Key Features:
1. **Job Listing Extraction**:  
   Users provide the URL of a company's careers page, and the tool utilizes GROQ to extract job listings automatically.

2. **Personalized Email Generation**:  
   For each job description, the tool crafts personalized cold emails that highlight the user's relevant skills and experience.

3. **Portfolio Integration**:  
   The tool retrieves links to the user's portfolio and relevant work samples stored in a **vector database**. These links are included in the email to demonstrate the applicant's suitability for the role.

4. **Streamlit-Based Interface**:  
   A user-friendly web interface built with Streamlit allows seamless interaction with the tool, including inputting the careers page URL and reviewing generated emails.

#### Setup Instructions:
1. **API Key Configuration**:  
   - Obtain an **API Key** from [GROQ Console](https://console.groq.com/keys).  
   - Update the `GROQ_API_KEY` variable in the `app/.env` file with your newly created API key.

2. **Dependency Installation**:  
   Install the required Python dependencies by running:  
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Application**:  
   Launch the Streamlit app with the following command:  
   ```bash
   streamlit run app/main.py
   ```

#### Use Case:  
This tool is particularly beneficial for job seekers aiming to stand out by sending highly relevant and customized cold emails for job openings, leveraging AI-driven insights and personalized content.
