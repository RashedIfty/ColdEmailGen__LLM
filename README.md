**LLM-StreamEmail: AI-Powered Cold Email Generator with Job Scraping, Portfolio Integration, Vector-Based Personalization, and Streamlit Interface**

### Project Description:  
LLM-StreamEmail is an advanced tool designed to generate personalized cold emails for job applications by leveraging the latest in AI technologies. The system utilizes **Large Language Models (LLM)** and **Streamlit** to offer an intuitive interface, while also integrating **job scraping** and **portfolio personalization** to create tailored, compelling emails for job seekers. The tool not only extracts job listings from career pages but also links relevant portfolio items based on specific job requirements, providing a seamless and personalized application experience.

#### Key Features:
1. **Job Listing Extraction**:  
   Users can input the URL of a company's career page, and the tool scrapes and extracts relevant job listings using advanced web scraping techniques.

2. **Personalized Email Generation**:  
   The system generates customized cold emails by analyzing job descriptions and highlighting the applicant's relevant skills and experience, powered by LLMs.

3. **Portfolio Integration**:  
   Using a **vector database**, the tool automatically selects portfolio items most relevant to the job description, increasing the chances of standing out to recruiters.

4. **Streamlit Interface**:  
   A user-friendly interface developed using **Streamlit** provides an easy way to input URLs, review job listings, and modify the generated emails before sending.

5. **Ongoing Development**:  
   - Continuous improvements to optimize the scraping process and refine the email generation model.
   - Contributions from **YouTube tutorials**, **ChatGPT**, and **GitHub repositories** have significantly helped in overcoming challenges during development.
   - Personal contributions include the integration of a **PDF Job Descrption Ppload** feature, allowing users to upload PDFs and scrape data from them as part of their job application materials.

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
This tool serves as an invaluable resource for job seekers, enabling them to craft personalized, AI-enhanced cold emails with minimal effort. By automating job listing extraction, portfolio matching, and email generation, users can apply more effectively and increase their chances of securing interviews.
