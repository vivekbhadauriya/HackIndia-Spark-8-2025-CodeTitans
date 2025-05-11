CampusCopilot is an AI-powered assistant tailored to simplify and streamline college life. 
- Designed for students and faculty, it offers a platform to manage academic schedules, deadlines, fee alerts, and FAQs.
- The system combines automation, natural language processing, and real-time data handling to make campus information accessible and actionable

Pre-requisite
- Download
1. Node.js from here [https://nodejs.org/en/download]
2. Update **npm --version** to at least 10.9.2
3. Update **nvm --version** to 0.40.3
4. Update **node --version** to v22.15.0

**Note :** 
1. Go to "Backend folder" at location "..CampusCopilotBackend" then create **.env** file, and add "GOOGLE_API_KEY = ", "HUGGINGFACEHUB_API_TOKEN = " api keys
2. Download "Backend folder" and "Frontend folder" **separately**, not in a single folder

# To run on Linux
1. Open "Backend folder" in VS code and Create a "New terminal" or **Ctrl + Shift + ~**
2. Navigate to "CampusCopilotBackend" by typing **cd CampusCopilotBackend** in terminal & then **source venv/bin/activate** to activate virtual environment
3. Again type **cd campuscopilot_backend** & then **uvicorn main:app --reload --port 8000**
4. Now backend will start running

# Start Frontend
1. Open "Frontend folder" in VS code and Create a "New terminal" or **Ctrl + shift + ~**
2. Navigate to "CampusCopliot" using command **cd CampusCopilot**
3. Type **npm run dev** to start localhost app at [http://localhost:5173/]
4. It will start **CampusCopilot** in your browser, ENJOY Chatting!
