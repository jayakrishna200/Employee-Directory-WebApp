# Employee Directory WebApp

A modern, responsive Employee Directory web application built with **HTML**, **TailwindCSS**, and **Vanilla JavaScript**. This app allows you to manage employee records with features like search, filter, sort, pagination, and CRUD operations—all on the client side, with a clean and intuitive UI.

---

## Features

- **Dashboard:**  
  View all employees in a responsive grid layout with details like name, email, department, and role.

- **Add/Edit Employee:**  
  Modal form for adding new employees or editing existing ones, with validation for all fields.

- **Delete Employee:**  
  Remove employees with a confirmation prompt.

- **Search:**  
  Real-time search by name or email.

- **Filter Sidebar:**  
  Slide-out sidebar to filter employees by first name, department, or role.

- **Sorting:**  
  Sort employees by first name or department.

- **Pagination:**  
  Choose how many entries to display per page (10, 25, 50, 100) and navigate between pages.

- **Responsive Design:**  
  Fully responsive and dark mode ready, thanks to TailwindCSS.

---

## Technologies Used

- **HTML5**
- **TailwindCSS** (via CDN)
- **Vanilla JavaScript**

---

## Project Structure

```
.
├── index.html
├── readME.md
```

---

## Getting Started

1. **Clone the repository:**

   ```bash
   git clone https://github.com/jayakrishna200/Employee-Directory-WebApp
   cd Employee-Directory-WebApp
   ```

2. **Open `index.html` in your browser.**  
   No build step or server required—everything runs client-side.

---

## How It Works

- Employee data is stored in a JavaScript array (mock data).
- All CRUD operations, search, filter, sort, and pagination are handled in the browser.
- The UI updates dynamically as you interact with the app.

---

## Improvements & Future Enhancements

- Persist data using LocalStorage or IndexedDB.
- Integrate with a backend API for real data storage.
- Add user authentication and role-based access.
- Improve accessibility and add keyboard navigation.
- Add unit tests for JavaScript logic.

---
