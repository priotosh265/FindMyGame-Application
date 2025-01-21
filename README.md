# FindMyGame-Application

---

### FindMyGame Application 🎮

**FindMyGame Application** is a Python-based console application that helps users search for games using a **game search API**. The application is designed with a secure login system and various features to enhance user experience.

#### Key Features:
- **Secure Login System**: 
  - User credentials are securely stored in a CSV file using hashed passwords with bcrypt.
  - Password validation includes checks for at least 8 characters, one uppercase letter, one lowercase letter, one number, and one special character.
  - A **forgot password** feature allows users to recover their password using predefined security questions.
  - A limit of **5 login attempts** is enforced for security.

- **Game Search API Integration**:
  - Users can search for games by entering relevant keywords.
  - Fetches and displays detailed game information from the integrated API.

- **Password Recovery**:
  - Users can recover forgotten passwords by answering security questions.

- **User-Friendly Interface**:
  - A clean and intuitive console-based interface.

#### Technologies Used:
- **Python**: Core programming language.
- **bcrypt**: For password hashing.
- **CSV**: To store user credentials.
- **Game Search API**: To retrieve game data.
- **Regex**: For password validation.

#### Future Scope:
- Add a GUI interface for a better user experience.
- Enhance game search capabilities with additional filters and sorting options.
- Implement user-specific game libraries and preferences.

---
