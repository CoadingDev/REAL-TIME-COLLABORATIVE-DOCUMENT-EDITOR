# REAL-TIME-COLLABORATIVE-DOCUMENT-EDITOR

**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: Tushar Mishra

**INTERN ID**: CT06DF1763

**DOMAIN**: FULL STACK WEB DEVELOPMENT

**DURATION**: 6 WEEKS -- JUNE 5th,2025 to JULY 20th, 2025

**MENTOR NAME** : NEELA SANTHOSH KUMAR

# DESCRIPTION OF TASK PERFORMED :
During my internship at CODTECH, I built a project named SmartNotes, a real-time collaborative document editor designed to allow multiple users to simultaneously edit and interact with shared text content. The objective was to develop a full-stack application capable of handling live updates, synchronized collaboration, and efficient document management.

The frontend was developed using ReactJS, a JavaScript library known for building dynamic and responsive user interfaces. I used React’s component-based architecture to structure the UI, enabling modular and manageable code. The interface includes a real-time text editor where changes are immediately visible to all active users. Features such as live typing indicators, cursor tracking for each user, and active user presence were implemented to make the collaboration experience interactive and user-friendly. React Hooks and Context API were utilized for efficient state management and to ensure consistent data across components.

For the backend, I used Python in combination with WebSockets to manage real-time, bidirectional communication between the server and connected clients. This setup ensured that whenever a user made a change to a document, the update was broadcast instantly to all other users viewing the same document. The WebSocket protocol was crucial for maintaining persistent connections and enabling seamless data flow with low latency. Alongside real-time functionality, I also implemented RESTful API endpoints for user authentication, document creation, and data retrieval using Python-based frameworks.

User authentication and authorization were incorporated into the backend to restrict access to only registered users. Secure login and registration systems were built using hashed passwords and session tokens. This provided a controlled and protected environment for collaboration, ensuring that documents were only accessible by authorized individuals.

For the database, I used MongoDB, a NoSQL document database. Its flexible schema was ideal for storing document content, user information, editing history, and versioning data. Each document stored in the database was linked to a user and included metadata like last modified time, collaborators, and a history of edits. The use of MongoDB allowed for efficient data retrieval and storage, supporting fast loading and saving of documents. I also created mechanisms to track and save each change made to a document, allowing for version control and rollback if needed.

Concurrency handling was a critical part of this project. I implemented logic on both client and server sides to manage simultaneous edits. Document states were synchronized using operational transforms and real-time broadcasting logic to prevent conflicts between multiple users editing the same section. The system maintained consistency and stability even under simultaneous operations by multiple users.

The complete stack combined ReactJS (frontend), Python with WebSockets (backend), and MongoDB (database). This setup allowed the application to deliver a smooth and reliable collaborative experience. The architecture supported real-time data updates, user management, secure access, and scalable storage for multi-user document editing.

SmartNotes functioned as a complete web-based collaborative editor, integrating frontend interface design, backend communication protocols, real-time synchronization logic, and database structuring to support simultaneous multi-user editing with live data reflection.

# OUTPUT OF THE TASK :
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/31718201-5d85-4bf5-9517-9f0f3538f46c" />

<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/a69a8114-f900-4ec8-b067-be368619ef95" />
