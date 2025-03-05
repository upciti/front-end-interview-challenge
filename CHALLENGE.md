# 🚀 Front-end interview challenge

Welcome to our front-end challenge!

## 📋 Overview

Your mission is to conceive an elegant, high-performing way to present the provided data to the end user. We encourage you to be creative in how you display this data—just remember to keep things simple and intuitive. You'll be building a user interface that interacts with the provided backend, but the ultimate goal is to show us how you structure, design, and implement a front-end solution from the ground up.

Try to show us what you would love to deliver as an app to a client—an app you’d be proud of both for its visible UI/UX and for its invisible technical excellence, including clean code and best practices. You only have a small amount of time to deliver your dream app, and during the tech test restitution you must be able to justify your choices. Feel free to use any tool you want to be as efficient as possible (e.g., genAI, boilerplates, UI templates, libraries, etc.). We care about open-source and collaboration rather than reinventing the wheel, though sometimes it’s worth rewriting parts when you need a customized behavior.

If you need to go further to demonstrate mastery of higher-level concepts by using placeholders or making assumptions, do not hesitate—but remember to explain your approach.

---

## 📌 Requirements

### 📡 Data fetching

- Use the Docker Compose setup ([docker-compose.yml](./docker-compose.yml)) to run the API.
- If you need to change the CORS configuration, adjust the [`FRONT_URL`](./docker-compose.yml) environment variable in the [docker-compose.yml](./docker-compose.yml) file. By default, it is set to http://localhost:5173.
- Retrieve data from the provided API. Explore the Swagger documentation at http://localhost:3000/docs.

### 📊 Charts & KPIs

- Include at least one chart (e.g., bar, line, pie) to display the API data.
- Show at least two KPIs (Key Performance Indicators) derived from the API data.
- Feel free to choose any layout, styling, or charting library.

### 🏗️ Application structure

- Organize your front-end application in a way that is easy to navigate and maintain.
- Follow best practices for folder structure, component organization, and state management (if applicable).

### 📚 Documentation

Provide a `README.md` with:

- **Project setup instructions** (how to run, how to test).
- **Design decisions** (why you chose specific libraries or patterns).
- **Limitations** or known issues.
- **Future improvements** (what you would do if you had more time).

### 🧪 Testing

- Include at least a basic testing setup.
- Demonstrate you can write and run tests.

### 🧹 Code quality

- Apply coding standards, linting, or formatters.
- Write clean, readable, well-documented code.

### 🎨 Creativity & polish

- You are free to use any charting library.
- UI styling is up to you.
- This is an opportunity to show your personal approach to user experience and design.

### 🐳 Containerization

- Containerize your solution using Docker (we will use it to review your project).

---

## 📝 Notes

- Use your best judgment for any unspecified details (e.g., data limits, error handling, etc.).
- If some parts are **not** fully implemented, mention them in your documentation.
- If you have remarks or want to add clarifications, put them in the `README.md` as well.

---

## 🚀 Getting started

1. **Clone** the repository

   ```bash
   git clone git@github.com:upciti/front-end-interview-challenge.git
   ```

   > Or click on "Use this template" on GitHub.

1. Start the API

   ```bash
   docker compose up
   ```

1. **Your turn to complete the challenge!**

1. **Submit** your solution : please provide a tarball or a link to the Git repository.
   > If you wish to keep your GitHub / GitLab repository private, let us know, we'll provide you with a user to invite to contributors, so we can review the code.

---

We look forward to reviewing your project. Good luck, and have fun!
