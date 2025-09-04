# AI-Resume-Analyzer


About the Project 🥱

screenshot

A tool which parses information from a resume using natural language processing and finds the keywords, cluster them onto sectors based on their keywords. And lastly show recommendations, predictions, analytics to the applicant / recruiter based on keyword matching.

Scope 😲
i. It can be used for getting all the resume data into a structured tabular format and csv as well, so that the organization can use those data for analytics purposes

ii. By providing recommendations, predictions and overall score user can improve their resume and can keep on testing it on our tool

iii. And it can increase more traffic to our tool because of user section

iv. It can be used by colleges to get insight of students and their resume before placements

v. Also, to get analytics for roles which users are mostly looking for

vi. To improve this tool by getting feedbacks

Tech Stack 🍻
Frontend
Backend
Database
Modules
Features 🤦‍♂️
Client: -
Fetching Location and Miscellaneous Data

Using Parsing Techniques to fetch

Basic Info

Skills

Keywords

Using logical programs, it will recommend

Skills that can be added
Predicted job role
Course and certificates
Resume tips and ideas
Overall Score
Interview & Resume tip videos
Admin: -
Get all applicant’s data into tabular format

Download user’s data into csv file

View all saved uploaded pdf in Uploaded Resume folder

Get user feedback and ratings

Pie Charts for: -

Ratings

Predicted field / roles

Experience level

Resume score

User count

City

State

Country

Feedback: -
Form filling
Rating from 1 – 5
Show overall ratings pie chart
Past user comments history
Requirements 😅
Have these things installed to make your process smooth
Python (3.9.12) https://www.python.org/downloads/release/python-3912/
MySQL https://www.mysql.com/downloads/
Visual Studio Code (Prefered Code Editor) https://code.visualstudio.com/Download
Visual Studio build tools for C++ https://aka.ms/vs/17/release/vs_BuildTools.exe
Setup & Installation 👀
To run this project, perform the following tasks 😨

Download the code file manually or via git

git clone https://github.com/deepakpadhi986/AI-Resume-Analyzer.git
Create a virtual environment and activate it (recommended)

Open your command prompt and change your project directory to AI-Resume-Analyzer and run the following command

python -m venv venvapp

cd venvapp/Scripts

activate
Downloading packages from requirements.txt inside App folder

cd../..

cd App

pip install -r requirements.txt

python -m spacy download en_core_web_sm
After installation is finished create a Database cv

And change user credentials inside App.py

AI-Resume-Analyzer/App/App.py

Line 95 in 17e1cdb

 connection = pymysql.connect(host='localhost',user='root',password='root@MySQL4admin',db='cv') 
Go to venvapp\Lib\site-packages\pyresparser folder

And replace the resume_parser.py with resume_parser.py

which was provided by me inside pyresparser folder

Congratulations 🥳😱 your set-up 👆 and installation is finished 😵🤯

I hope that your venvapp is activated and working directory is inside App

Run the App.py file using

streamlit run App.py
Known Error 🤪
If GeocoderUnavailable error comes up then just check your internet connection and network speed

Issue While Installation and Set-up 🤧
Check-out installation Video

Feel Free to Send mail

Usage
After the setup it will do stuff's automatically
You just need to upload a resume and see it's magic
Try first with my resume uploaded in Uploaded_Resumes folder
Admin userid is admin and password is admin@resume-analyzer
Roadmap 🛵
 Predict user experience level.
 Add resume scoring criteria for skills and projects.
 Added fields and recommendations for web, android, ios, data science.
 Add more fields for other roles, and its recommendations respectively.
 Fetch more details from users resume.
 View individual user details.
Contributing 🤘
Pull requests are welcome.

For major changes, please open an issue first to discuss what you would like to change.

I've attached the synopsis of the project

If you want the full report of project Email Me it's FREE

Acknowledgement 🤗
Dr Bright - (The Full Stack Data Scientist BootCamp)
Resume Parser with Natural Language Processing
pyresparser

