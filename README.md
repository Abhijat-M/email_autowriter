# **Email AutoWriter** 📨  

**Email AutoWriter** is an AI-powered tool that uses a **Large Language Model (LLM)** to generate highly personalized emails for job applications. Designed for professionals, this tool streamlines the process of writing tailored emails to hiring managers by leveraging job description links to craft contextually relevant and compelling correspondence.  

---

## **🌟 Features**
- **LLM Integration**: Uses **Llama 3.1-70B** for high-quality email generation.  
- **Personalized Emails**: Automatically tailors content based on the provided job description link.  
- **ChromaDB for Memory**: Employs ChromaDB for efficient storage and retrieval of context.  
- **LangChain for Workflow**: Chains tasks like parsing job descriptions, analyzing context, and generating email drafts.  
- **Groq for Speed**: Enhances LLM performance and processing speed.  
- **Streamlit Deployment**: Simple and interactive web interface for easy use.  

---

## **💻 Tech Stack**
- **Language**: Python  
- **Key Technologies**:  
  - **LLM**: Llama 3.1-70B  
  - **Database**: ChromaDB  
  - **Framework**: LangChain  
  - **Processing**: Groq  
  - **UI**: Streamlit  

---

## **🚀 How to Use**

### **1. Clone the Repository**
```bash
git clone https://github.com/Abhijat-M/email_autowriter.git
cd email_autowriter
```

### **2. Install Dependencies**
Set up a virtual environment and install the required libraries:
```bash
pip install -r requirements.txt
```

### **3. Set Up API Keys**
- Obtain access to **Llama 3.1-70B API**, **ChromaDB**, and **LangChain**.  
- Create a `.env` file in the project root and add your keys:
  ```env
  GORQ_API_KEY=your_gorg_api_key
  
  ```

### **4. Run the Application**
Launch the app using Streamlit:
```bash
streamlit run main.py
```

### **5. Interact with the Tool**
- Input a **job description link** and your details (e.g., name, skills, previous experience).  
- Receive a **personalized email draft** optimized for the job posting and hiring manager.  

---

## **📂 Folder Structure**
```
.
├── main.py       # Main application script
├── requirements.txt          # Python dependencies
├── README.md                 # Project documentation
├── utils/                    # Utility scripts for API handling and processing
├── .env                      # API keys and environment variables

```

---

## **🌟 Examples**
### **Input**  
- **Job Description Link**: `https://example.com/job-posting`  
- **Details**:  
  - **Name**: John Doe  
  - **Skills**: Python, Machine Learning, Cloud Computing  
  - **Experience**: 3 years as a Data Scientist  

### **Generated Email**  
```
Subject: Application for [Position Name]  

Dear [Hiring Manager’s Name],  

I hope this email finds you well. I am reaching out to express my interest in the [Position Name] role at [Company Name]. After reviewing the job description, I am excited about the opportunity to bring my [skills/experience] to your esteemed team.  

With [X years of experience] in [relevant field], I have successfully [achievements aligned with the job description]. I am particularly impressed by [specific company initiative or value mentioned in the job description] and would be thrilled to contribute to such endeavors.  

Please find my resume attached for your review. I look forward to the possibility of discussing how my skills align with your needs.  

Thank you for your time and consideration.  

Best regards,  
John Doe  
```

---

## **🔧 Customization**
- **Advanced Parsing**: Improve job description parsing for more nuanced understanding.  
- **Tone Options**: Allow users to choose between formal, semi-formal, and casual tones.  
- **Template Enhancements**: Add user-defined templates for repeated use.  

---

## **🌐 Future Enhancements**
- **Hiring Manager Insights**: Integrate LinkedIn scraping for additional personalization.  
- **Multi-Language Support**: Enable email generation in multiple languages.  
- **Feedback-Based Improvement**: Incorporate user feedback to fine-tune generated emails.  

---

## **🤝 Contributing**
Contributions are welcome! To contribute:  
1. Fork this repository.  
2. Create a new branch for your feature or bug fix.  
3. Submit a pull request with detailed information.  

---

## **📜 License**
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.  

---

**Developed with 💡 by Abhijat**  
_"Streamlining job applications, one email at a time."_  
