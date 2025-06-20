# 🏗️ Construction-Bot

## Overview
**Construction-Bot** is an AI-powered platform designed to streamline construction management through a smart chat interface. From machinery rentals and labor hiring to project uploads and cost estimations, **Construction-Bot** makes managing construction projects faster, smarter, and easier.

Just chat with the AI—no complicated menus or interfaces. Whether you're a contractor, site manager, or project owner, this tool has everything you need in one place.

---

## ✨ Features

- **AI-Powered Q&A**: Ask anything related to construction—materials, safety, costs, timelines.
- **Machinery Rentals**: Rent equipment like excavators, bulldozers, cranes with simple voice/text commands.
- **Hire Skilled Labor**: Get electricians, plumbers, masons, and more based on your needs.
- **Project Gallery & Uploads**: Share your project details or images, and get matched with similar past projects.
- **Request Quotations**: Get accurate preliminary quotes for new projects via chat.
- **Admin Management**: Admins can manage users, resources, and settings using chat commands.
- **Mobile Ready**: Built with Flutter for seamless mobile experience.

---

## ⚙️ Tech Stack

### Backend
- **Framework**: [FastAPI](https://fastapi.tiangolo.com/)
- **AI Frameworks**: [LangChain](https://www.langchain.com/), [LangGraph](https://langgraph.ai/)
- **Database**: [PostgreSQL](https://www.postgresql.org/)
- **LLM**: [OpenAI GPT-4o](https://platform.openai.com/docs/models/gpt-4o)
- **Authentication**: Google Auth (via Firebase)

### Frontend
- **Framework**: [Flutter](https://flutter.dev/)

---

## 💡 How It Works

### 1. AI-Powered Construction Q&A  
Ask questions like:
- "What's the best concrete mix for foundations?"
- "How do I estimate the cost of a 2000 sqft building?"

The AI will pull knowledge from internal data, regulations, and best practices.

### 2. Machinery Rentals  
Just say:  
> "I need an excavator for 3 days."

The AI finds available machines, shows pricing, and helps complete the rental process.

### 3. Hire Skilled Labor  
Say:  
> "I need 5 electricians for a week."

The AI filters skilled workers by availability, location, and certifications.

### 4. Project Gallery & Uploads  
Ask:  
> "Show me similar projects."  

Or upload photos and descriptions directly in chat, and the AI will analyze and categorize them.

### 5. Project Requests & Quotations  
Type:  
> "I have a new project. Can I get a cost estimate?"  

The AI will ask clarifying questions and generate a detailed quote.

### 6. Admin & Super Admin Features  
Admins can:
- Manage users and permissions
- View analytics
- Control resource listings
All done via natural language chat commands.

---

## 🛠️ Installation Guide

### 1. Clone the Repository
```bash
git clone https://github.com/pinilDissanayaka/Construction-Bot.git
cd Construction-Bot
```

### 2. Backend Setup (FastAPI + LangChain + PostgreSQL)

#### Create virtual environment and install dependencies
```bash
cd Backend
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
pip install -r requirements.txt
```

#### Set up PostgreSQL and update `.env`
```env
DATABASE_URL=postgresql://username:password@localhost:5432/rise_construction_db
OPENAI_API_KEY=your-openai-key
```

#### Start FastAPI Server
```bash
python main.py
```

#### API Docs
Swagger UI: http://127.0.0.1:8000/docs

---

### 3. Frontend Setup (Flutter)

Navigate to the frontend directory and run:

```bash
cd Frontend
flutter pub get
flutter run
```

Ensure **Google Sign-In** is configured via **Firebase** before running the app.

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 🧑‍💻 Contributors
Contributions are welcome! Please read the [CONTRIBUTING.md](CONTRIBUTING.md) file for guidelines.

---

## 📬 Contact

For any issues or suggestions, feel free to open an issue or reach out to the project maintainer.

---

## 🚀 Let’s Build Together!

Just start typing in the chat—everything you need is there. No buttons, no tabs, just intelligent conversation.

Let’s bring AI into construction, one message at a time. 🏗️💬
