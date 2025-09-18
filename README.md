Code Wizard

Code Wizard is a platform that combines real-time video/audio communication with a collaborative code editor. 
It is designed for coding interviews, online classrooms, pair programming, and remote collaboration.

Features
•	Video and audio conferencing with WebRTC
•	Collaborative code editor with live editing and debugging
•	Screen sharing support
•	User authentication (registration, login, profile)
•	File handling and management
•	Modern, responsive UI with React and Material UI

Tech Stack
•	Frontend: React.js, Material UI, Monaco Editor
•	Backend (Signaling): Node.js with Socket.IO
•	Real-time Communication: WebRTC
•	Build Tool: Vite

Installation and Setup
1.	Clone the repository
2.	git clone https://github.com/your-username/code-wizard.git
3.	cd code-wizard
4.	Install dependencies
5.	npm install
6.	Start the development server
7.	npm run dev
8.	Open in browser at http://localhost:5173

Usage
•	Register or log in to the application
•	Access the dashboard to create/join meetings or use the code editor
•	Use the editor to write and manage files
•	Join video meetings with screen sharing and chat

Limitations
•	Code editor and meeting cannot run simultaneously
•	Screen sharing disables the video stream
•	Basic authentication only (no OAuth/2FA)

Future Enhancements
•	Multi-user real-time collaborative coding
•	Advanced meeting features (AI transcription, gesture/emotion analysis)
•	Cloud storage integration (Google Drive, Dropbox)
•	Mobile app support

