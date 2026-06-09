# Online Job Portal Web Application

A robust, full-stack web application built with Python and Django that connects job seekers with employers. This platform simplifies the recruitment process by allowing employers to post job vacancies and candidates to search and apply for jobs seamlessly.

---

## 🚀 Features

### For Job Seekers
* **User Profiles:** Create and update a professional profile, including uploading resumes/CVs.
* **Job Search & Filters:** Search for jobs by keywords, category, or location.
* **Application Tracking:** Apply to jobs with a single click and track the status of applications.

### For Employers
* **Job Management:** Post, edit, and delete job listings.
* **Applicant Tracking:** View and manage applications received for posted jobs.
* **Company Profile:** Build a company profile to attract top talent.

### For Administrators
* **Admin Dashboard:** Full control over users, job listings, categories, and site settings via the built-in Django Admin.

---

## 🛠️ Tech Stack

* **Backend:** Python, Django Web Framework
* **Database:** SQLite (Default for development)
* **Frontend:** HTML5, CSS3, Bootstrap, JavaScript
* **Media Handling:** Django File Storage (for resumes and profile images)

---

## 💻 Getting Started

Follow these steps to set up and run the project locally.

### Prerequisites
Make sure you have Python installed on your system (Python 3.8+ recommended).

###  SET UP ENVIRONMENT :
```bash
git clone [https://github.com/2300030292/online-job-portal-web-application.git](https://github.com/2300030292/online-job-portal-web-application.git)
cd online-job-portal-web-application

# Windows
python -m venv venv
venv\Scripts\activate

# macOS/Linux
python3 -m venv venv
source venv/bin/activate

pip install -r requirements.txt

python manage.py migrate

python manage.py createsuperuser

python manage.py runserver

online-job-portal-web-application/
│
├── job/                   # Main application app logic (views, models, templates)
├── jobportal/             # Core project configuration directory
├── media/                 # User-uploaded files (resumes, profile pictures)
├── manage.py              # Django command-line utility
├── db.sqlite3             # Local development database
└── requirements.txt       # Project python dependencies
