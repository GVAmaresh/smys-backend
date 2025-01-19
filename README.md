
# SMYS

**Sri Madhwa Yuvaka Sangha** (SMYS) is an organization located in South Bengaluru, Karnataka. It provides hostel facilities for all Brahmins pursuing a degree. The organization conducts various festivals and ensures security through the installation of CCTV cameras. Additionally, there is a management team to oversee operations. The hostel offers three meals a day, along with clean rooms and common washroom facilities.

**TechStack** 

[![My Skills](https://skillicons.dev/icons?i=nextjs,typescript,fastapi,tailwindcss,firebase,netlify,vscode,windows)](https://skillicons.dev)

**This project is divided into two parts:**

1. **Frontend**: Handles all the contents, photos and information related to the organisation
2. **Backend**: Handles the photos add-update, information, authentication and even connected to g-Drive api for photos storage

Each part is managed in a separate repository for better organization and maintenance

**Please start with the Backend Repository first, followed by the Frontend Repository**.

- **Backend Repository**: [SMYS-Backend](https://github.com/GVAmaresh/smys-backend)
- **Frontend Repository**: [SMYS-Frontend](https://github.com/GVAmaresh/smys)


## Table of Contents

1. [Demo](#demo)
2. [Technology Used](#technology-used)
3. [Description](#description)
4. [Getting Started](#getting-started)
    1. [Prerequisites](#prerequisites)
    2. [Using CMD (Command Line)](#using-cmd-command-line)
5. [Meet the Team](#meet-the-team)
6. [License](#license)

## Demo
Watch Video Here

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/id-goes-here/0.jpg)](https://www.youtube.com/watch?v=id-goes-here)

## Technology Used

**Programming & Scripting Languages:**
- **Python**: It was supporting the G_Drive api better than node.js so it was suitable to use
- **Nextjs**: For interactive frontend design and backend logic
- **TypeScript**: Ensures type safety and robustness in the React components

**Frameworks & Libraries:**
- **MUI**: Used external resource for responsive frontend 
-- **Tailwindcss**: For the better css handling
- **React**: Frontend framework for building user interfaces.
- **FastAPI**: Lightweight Python framework for serving the backend.
- **Firebase**: It is used to store all the information of photos and contents of the organisation and for the authentication

## Description

This SMYS website is build using the Next.js + TypeScript + FastAPI + Firebase + GDrive

 * **Informative**
It provides all the information related to the organisation starts from the brief hostory to the current management

 * **Authentication**
There is a hidden authentication is given where only valid user can user to edit the contents and information related to the organisation without editing the source code which is again build by firebase-authentication

 * **Gallery**
In the gallery section, it provides all the activities done by the organisation till the date 

 * **Other photo collections**
There are other section like historical events and jnanabharathi which can explain how the culture of this organisation 

    

## Getting Started

**Prerequisites**

Before getting started, make sure you have the following installed and set up:


**1.Python**
Installing Python and Setting Up PATH on Windows
- Visit the [official Python download page](https://www.python.org/downloads/) and download the latest version for Windows.

- **Important**: Ensure the **"Add Python to PATH"** option is checked and click **"Install Now"**
- Open Command Prompt (`Win + R`, type `cmd`) and check Python version:  
```bash
python --version
  ```

---

**Running the Project**

**1. Using CMD (Command Line)**

First, clone the frontend and backend repositories using the following commands:

```bash
git clone https://github.com/GVAmaresh/smys-backend
```

Navigate into the project directory and install the necessary dependencies.

```bash
cd smys-backend
pip install -r requirements.txt

```
Set the environmental variables

```bash
TOKEN=
REFRESH_TOKEN=
CLIENT_ID=
CLIENT_SECRET=
```

To get these environmental variables refer this: [Youtube Link](https://www.youtube.com/watch?v=t0RKgHskYwI)

This is for the Google Drive API key. You can use your own drive to create it; it is not necessary to use drives that contain photos. This is just for developer verification for importing photos that exceed 100. Otherwise, I could have used gdown.


```bash
python index.py
```

Now you should be able to access the frontend on [http://localhost:8000](http://localhost:8000)


## Meet the Team

- **G V Amaresh**: [GVAmaresh ](https://github.com/GVAmaresh)

## License
This project is licensed under the MIT License - see the [LICENSE](https://github.com/GVAmaresh/smys-backend/blob/main/LICENSE) file for details.
