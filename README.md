# 🔐 Password Generator

A simple and responsive **Password Generator** built with **React.js** and **Tailwind CSS**.

This project generates random passwords based on the options selected by the user.

## 🚀 Features

* Generate random passwords
* Choose password length
* Include numbers
* Include special characters
* Responsive UI
* Built with React Hooks
* Styled with Tailwind CSS

## 🛠️ Technologies Used

* React.js
* JavaScript
* Tailwind CSS
* Vite

## 📚 React Concepts Used

This project helped me practice:

* `useState`
* `useCallback`
* `useEffect`
* Event handling
* Controlled inputs
* Conditional logic
* Random number generation
* String manipulation

## ⚙️ How It Works

The password generator starts with a basic set of characters:

```js
ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz
```

If the user enables **Numbers**, numbers are added:

```js
0123456789
```

If the user enables **Characters**, special characters are added:

```js
!@#$%^&*-_+=[]{}~`
```

The program then randomly selects characters from the available character set until the required password length is reached.

## 📦 Installation

Clone the repository:

```bash
git clone <your-repository-url>
```

Go into the project folder:

```bash
cd password-generator
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

The application will then be available on the local development server provided by Vite.

## 🖥️ Project Structure

```text
src/
├── App.jsx
├── main.jsx
├── index.css
└── assets/
```

## 🎯 What I Learned

While building this project, I practiced how React state can control form inputs and how changes in those inputs can affect the generated password.

I also learned about:

* `onChange`
* Checkbox state
* Range inputs
* `label` and `htmlFor`
* Conditional statements
* Loops
* `Math.random()`
* `Math.floor()`
* React state updates
* React Hook dependencies

## 🔮 Future Improvements

* Add a **Copy to Clipboard** button
* Add password strength indicator
* Add uppercase/lowercase options
* Add password history
* Add a button to regenerate the password
* Improve UI animations

## 👨‍💻 Author

**Sameed**

Built as a React practice project.
