# NoteFlow

## 📝 Overview

NoteFlow is a modern, user-friendly note-taking application built with React and Appwrite. It provides an intuitive and seamless experience for managing notes, allowing users to organize their thoughts efficiently with features like draggable notes, autosave, and customizable colors.

![NoteFlow Demo](demo.gif)

## 🚀 Features

- **Production Database** – All notes are stored securely in a live production-ready database.
- **Draggable Notes** – Drag and drop notes anywhere on the screen for better organization.
- **Autosave Changes** – Changes to note content and position are automatically saved in real time.
- **Color Picker** – Customize notes by changing their colors anytime.

## 🏗️ Tech Stack

### Frontend:

- React JS
- Tailwind CSS (for styling)

### Backend:

- Appwrite (Database, Authentication, Storage)

## 📦 Installation

To run NoteFlow locally, follow these steps:

### 1️⃣ Clone the Repository

```sh
git clone https://github.com/nainee99/NoteFlow.git
cd note-flow
```

### 2️⃣ Install Dependencies

```sh
npm install
# or
yarn install
```

### 3️⃣ Set Up Appwrite

1. Install and configure [Appwrite](https://appwrite.io/docs/installation) on your server.
2. Create a new project and configure the necessary database and collections.
3. Set up authentication if required.
4. Add your Appwrite credentials to an `.env` file:

```sh
VITE_APPWRITE_PROJECT_ID=your_project_id
VITE_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
VITE_APPWRITE_DATABASE_ID=your_database_id
VITE_APPWRITE_COLLECTION_ID=your_collection_id
```

### 4️⃣ Run the App

```sh
npm run dev
# or
yarn dev
```

The application will be available at `http://localhost:5173` (if using Vite).

## 📌 Roadmap

Future enhancements may include:

- **Markdown Support** for rich-text notes.
- **Collaboration** to allow multiple users to edit notes in real time.
- **Search & Filter** functionality for better note organization.
- **Offline Mode** for taking notes without an internet connection.

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request.

## 🛡️ License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## 📬 Contact

For questions or feedback, reach out to [your-email@example.com] or open an issue in the repository.

---

Happy Coding! 🚀
