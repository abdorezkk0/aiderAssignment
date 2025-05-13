# Enhanced React Calculator

An improved version of the original [React Calculator](https://github.com/ahfarmer/calculator) by Andrew H. Farmer. This project enhances functionality by adding a calculation history panel and theme switching capabilities. Built with React and assisted by Aider for AI-powered development.

---

## 🚀 Features

### 🧮 Calculation History
![History Panel Screenshot](./screenshots/history-panel.png)

- View a log of previous calculations
- Click on any entry to reuse the result
- Show/hide history panel via toggle button

**Implementation Details:**
- A new `History` component tracks and displays past expressions
- Click handlers pass selected results back to the display
- Uses React state management for logging and interactivity

---

### 🌗 Theme Switcher
![Theme Switcher Screenshot](./screenshots/theme-switcher.png)

- Toggle between light and dark themes
- Preferences saved in `localStorage`
- Enhances accessibility and user experience

**Implementation Details:**
- Added `ThemeToggle` component to manage UI theme
- CSS variables dynamically switch styles
- On load, saved theme preference is automatically applied

---

## 🛠️ Development Workflow

### 1. Setup & Initialization
- Forked and cloned the original calculator repository
- Installed dependencies and verified functionality

### 2. Feature Planning
- Designed the `History` and `ThemeToggle` components
- Identified existing structure for integration points

### 3. Aider Development
Used [Aider](https://github.com/paul-gauthier/aider) to:
- Generate new React components
- Handle logic and styling changes
- Troubleshoot issues iteratively

### 4. Testing & Refinement
- Verified UI behavior through manual testing
- Adjusted styles and edge-case logic
- Performed cleanup and UX polish

---

## 🧩 Challenges & Solutions

| Challenge                      | Solution                                                   |
|-------------------------------|------------------------------------------------------------|
| History panel overlapping UI  | Used `position: absolute` and `z-index` to overlay safely |
| Theme reset on refresh        | Stored preference in `localStorage`                        |
| Displaying readable logs      | Built logic for formatted expression history              |

---

## 🧪 Common Aider Commands

Some Aider commands used during development:

- `/add` – Add files to Aider context
- `/edit` – Request changes to specific code sections
- `/diff` – View file differences before applying
- `/run` – Launch the React dev server
- `/commit` – Save progress with commit messages

---

## 🌱 Future Enhancements

- "Clear History" button
- Additional color themes
- Keyboard shortcuts for input
- Export logs to file (CSV/JSON)

---

## 📦 Getting Started

### Clone the Repository

git clone https://github.com/your-username/react-calculator.git
cd react-calculator

### Install Dependencies

npm install

### Run the Development Server

npm start
