# React Custom Hook – Fetch Data Project

## 📖 Description

This project demonstrates how to **fetch external API data in React** using a **reusable custom hook (`useFetch`)**.
The goal was to practice clean component design, reusable logic, and dynamic rendering of data in the user interface.

Instead of repeating fetch logic in multiple components, a **custom hook** centralizes the data-loading process, making the code **simpler, scalable, and maintainable**.

---

## 🚀 Features

* Reusable **custom React hook** for API requests
* Data fetching using **fetch API**
* State management with **useState**
* Side-effects handled by **useEffect**
* Dynamic UI rendering with **array.map()**
* Clean component-based structure

---

## 🗂️ Project Structure

```
src/
 └── Components/
      ├── FetchData.jsx
      ├── UseFetch.jsx
      └── FetchData.css
```

---

## ⚙️ How It Works

### 1. Custom Hook (`useFetch`)

* Accepts a **URL parameter**
* Fetches data when the component mounts
* Stores the response in **state**
* Returns the fetched **data** for reuse in any component

### 2. FetchData Component

* Calls the **useFetch hook** with an API link
* Receives the **data array**
* Uses **map()** to loop through items
* Displays each item inside a **list element** on the page

---

## ▶️ Getting Started

### Prerequisites

* Node.js installed
* Basic knowledge of React

### Installation

```bash
npm install
```

### Run the App

```bash
npm start
```

Open the browser at:

```
http://localhost:3000
```

---

## 🧠 What I Learned

Through this project, I learned how to:

* Build **custom hooks in React**
* Use **useState** to store fetched data
* Use **useEffect** for side effects like API calls
* Fetch and handle **JSON data from external APIs**
* Render lists dynamically using **array.map() in JSX**
* Apply **conditional rendering** to avoid errors before data loads
* Write **clean, reusable, and maintainable React code**
* Organize files using a **component-based folder structure**
* Debug data using the **browser console**

---

## 🎯 Purpose of the Project

This project was created while **learning React hooks and reusable logic patterns**.
It serves as a **foundation for building real-world React applications** that consume APIs such as:

* dashboards
* data-driven websites
* REST API integrations

---

## 📌 Future Improvements

* Add **loading and error states**
* Improve **UI styling**
* Replace fetch with **async/await**
* Add **TypeScript or Prop validation**
* Deploy the project online

---

## 👤 Author

**Arthur Ndatimana**
*React learner building real-world frontend skills.*

---

## 📜 License

This project is for **learning purposes** and can be freely used or modified.
