How to run: Task 2: Responsive Layouts
What you need
Node.js (version 18 or newer). Check with node -v in a terminal.
Steps
Open a terminal in this folder (in VS Code: right-click the folder > Open in Integrated Terminal).
Install the dependencies (first time only):
bash
   npm install
Start the development server:
bash
   npm run dev
Open the address it prints (usually http://localhost:5173) in your browser.
Press Ctrl + C in the terminal to stop the server.
Other commands
npm run build creates an optimised copy in the dist folder.
npm run preview serves the built copy so you can check it.
Testing the responsive design

Open your browser's developer tools (F12) and use the device toolbar to try the three target sizes: mobile (360px-720px), tablet (720px and up) and desktop (1024px and up).

Notes
Do not upload the node_modules or dist folders to GitHub. npm install recreates node_modules.
This file is separate from README.md, which contains the task specification.
