 # 💻 Virtual Interview Platform
![Screenshot 2025-03-21 000515](https://github.com/user-attachments/assets/3ea87d0e-5466-4f4c-8063-1415ea39465a)


A modern browser-based **virtual interview platform** built with **Next.js**, **React**, **TypeScript**, and **Tailwind CSS**. It enables seamless remote interviews with live video, collaborative coding, feedback collection, and candidate evaluation.

---

## ✨ Core Features

- 🔐 **User Login & Role-Based Access** via Clerk  
- 📅 **Schedule Interviews** with calendar integration  
- 📧 **Send Invitations & Notifications**  
- 🎥 **Join & Conduct Video Interviews** using Stream  
- 👨‍💻 **Live Code Editor** for technical rounds  
- 🖥️ **Screen Sharing & Recording**  
- 💾 **Save & Retrieve Recorded Sessions**  
- 📝 **Collect Feedback** from interviewers  
- ✅ **Select/Reject Candidates** with status tracking

---

## 🛠️ Tech Stack

- **Frontend**: Next.js (App Router), React, TypeScript, Tailwind CSS  
- **Authentication**: Clerk  
- **Database**: Convex  
- **Video Calling**: Stream (Stream.io)  
- **Live Code Editor**: Monaco / CodeMirror

---

## 🚀 Getting Started

```bash
git clone https://github.com/your-username/virtual-interview-platform.git
cd virtual-interview-platform
npm install
cp .env.local.example .env.local
# Add Clerk, Convex, and Stream keys to .env.local
npm run dev
---

## 📁 Project Structure
/app         - Pages and routing (Next.js App Router)
/components  - UI components
/convex      - Convex backend functions
/lib         - Clerk/Stream integrations
