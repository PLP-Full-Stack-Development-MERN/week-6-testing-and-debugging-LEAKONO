## Bug Tracker 🐞
A simple bug-tracking application built with React, Tailwind CSS, and Express.js for managing and reporting bugs.

### 🚀 Features
- Report Bugs  – Users can submit bug reports with a title and description.
- View Bug List  – All submitted bugs are displayed in a structured list.
- Responsive UI – Styled with Tailwind CSS for a clean and modern look.
- REST API– Communicates with a backend Express.js server.
###  Project Structure

📦 bug-tracker  
├──  public  
├──  src  
│   ├── components  
│   │   ├── BugForm.jsx  
│   │   ├── BugList.jsx  
│   │   ├── BugItem.jsx  
│   ├──  pages  
│   │   ├── Home.jsx  
│   ├── App.jsx  
│   ├── main.jsx  
├── tailwind.config.js  
├── postcss.config.js  
├── package.json  
├── README.md  
### Tech Stack
- **Frontend**: React, Tailwind CSS
- **Backend**: Express.js, MongoDB (API Endpoint: http://localhost:5000/api/bugs)
- **HTTP Requests**: Axios
📦 Installation
Clone the repository

```sh
git clone https://github.com/your-username/bug-tracker.git
cd bug-tracker
```
**Install dependencies**

```bash
npm install
npm run dev
```
**Run the backend (Make sure Express.js server is running)**

```sh
cd backend
npm install
npm start
```
###🌟 Usage
- Open the app in your browser at http://localhost:5000 (default Vite URL).
- Enter a bug title and description in the form and click "Add Bug".
- Bugs will appear in the list dynamically.
### Styling with Tailwind CSS
Tailwind CSS is used for styling components. Example:
```sh
<button className="w-full bg-blue-500 text-white py-2 rounded-md hover:bg-blue-600 transition duration-300">
  Add Bug
</button>
```
Ensure Tailwind is configured properly in tailwind.config.js:

```sh
export default {
  content: ["./index.html", "./src/**/*.{js,ts,jsx,tsx}"],
  theme: {
    extend: {},
  },
  plugins: [],
};
```

### License
This project is open-source and available under the MIT License.