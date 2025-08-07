📝 Intelli Letter Studio
A Streamlit-based web application that automates the creation of professional Motivation Letters and Cover Letters using CVs (Word, Text, or PDF), a job/program advertisement, and recruiter details. Built with integration to OpenAI’s GPT-4, this tool supports real-time generation and multi-format downloads (TXT, DOCX, PDF).

🔍 Features
📤 Upload CVs in .docx, .txt, or .pdf format

🧠 AI-generated letters using GPT-4 based on job description, CV, and user goals

✍️ Generate both Motivation and Cover Letters

🔄 Convert a Motivation Letter into a Cover Letter

📥 Download output in multiple formats: .txt, .docx, .pdf

💡 Simple, user-friendly interface using Streamlit

🎯 Use Cases
Academic applications (Masters, PhD programs)

Job applications for professionals

Automated document preparation for career services

Integration with AI-based career counseling tools

🚀 Demo Preview

🛠️ Tech Stack
Technology	Description
Streamlit	Web app framework for Python
OpenAI GPT-4	AI letter generation
python-docx	DOCX file creation
PyMuPDF	PDF file parsing
ReportLab	PDF generation from text

📦 Installation
Clone the Repository

bash
Copy
Edit
git clone https://github.com/mrmshahidsardar/Intelli_Letter_Studio.git
cd Intelli_Letter_Studio
Create a Virtual Environment

bash
Copy
Edit
python -m venv venv
source venv/bin/activate   # or venv\Scripts\activate on Windows
Install Dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the Application

bash
Copy
Edit
streamlit run app.py
🧪 Requirements
Python 3.8+

OpenAI API Key: Get it here

🧾 Usage Guide
Paste the job or academic program advertisement

Add profiles of decision-makers (optional)

Upload your CV in .docx, .txt, or .pdf

Input your personal interests and goals

Click Generate Motivation Letter or Generate Cover Letter

Download the result in .txt, .docx, or .pdf format

📂 File Structure
bash
Copy
Edit
academic-application-generator/
│
├── app.py                    # Main Streamlit app
├── requirements.txt          # Python dependencies
└── README.md                 # Project documentation
🔐 OpenAI API Key Setup
You need to enter your OpenAI API Key in the Streamlit sidebar to enable letter generation.

📄 Example Output
Motivation Letter: 500–700 words (academic tone)

Cover Letter: 300–500 words (professional tone)

✅ To Do / Enhancements
 Add custom formatting templates

 Support multiple languages (i18n)

 Integrate email-sending feature

 Add authentication for multiple users

🤝 Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements.

📜 License
This project is licensed under the MIT License. See the LICENSE file for details.

👤 Author
Muhammad Shahid Sardar
Data Specialist | Data Scientist | Streamlit Developer
LinkedIn: (https://www.linkedin.com/in/muhammad-shahid-sardar/)
