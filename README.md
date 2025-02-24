# **AI-Powered ATS Resume EvaluatorWith-Google-Gemini-Pro**

## **Overview**
Welcome to the **Gemini Pro Applicant Tracking System (ATS)**! This system utilizes the powerful **Gemini Pro model** to streamline the hiring process by analyzing job descriptions and resumes. It provides valuable insights such as **job description match, missing keywords, and profile summary.**

## **🚀 Demo of the Project**
(Include a link or screenshot of the working application here)

## **🔹 Features**
✔ **Job Description Match:** Evaluates how well a candidate's resume matches the provided job description, helping recruiters quickly identify suitable candidates.
✔ **Missing Keywords:** Identifies missing keywords or skills crucial for the job, enabling candidates to enhance their profiles.
✔ **Profile Summary:** Generates a concise profile summary highlighting key strengths and qualifications, offering a quick candidate assessment.

## **🛠 Requirements**
- Python **3.10**
- **Google Gemini Pro API Key** (Ensure you have the necessary credentials and permissions to access the API.)

## **⚙️ Installation**
### **Step 1: Clone the Repository**
```bash
git clone https://github.com/Shravani-CV/ATS-Resume-Compatability-Check-LLM-Project-using-Gemini-Pro.git
cd ATS-Resume-Compatability-Check-LLM-Project-using-Gemini-Pro
```

### **Step 2: Install Dependencies**
```bash
pip install -r requirements.txt
```

### **Step 3: Set Up Gemini Pro API Credentials**
1. Obtain API credentials from the **Makersuite platform**.
2. Create a **.env** file in the project root directory.
3. Add the following lines to **.env**:
   ```env
   GOOGLE_API_KEY="your_api_key"
   ```

## **🚀 Usage**
### **Run the Application:**
```bash
streamlit run app.py
```

### **Access the Application:**
Open your web browser and go to:
```
http://localhost:5000
```

### **Steps to Use:**
1. **Input** the job description and candidate's resume in the provided fields.
2. **Click** the "Submit" button to start the analysis.
3. **Review** the results, including:
   - **Job description match percentage**
   - **Missing keywords & recommendations**
   - **AI-generated profile summary**


---
🚀 **Happy Coding!** 🎯
