# BlogEra🎯

Welcome to BlogEra🎯!

---
## Table of Contents📄

- [Demo](#demo)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

---
## Demo💻

<img width="914" alt="Home Page" src="https://github.com/Arunabh0409/BlogEra/assets/77263686/fe47316d-25cb-4403-b3e5-60eb348b449c"><br><br>
<img width="912" alt="Add Post" src="https://github.com/Arunabh0409/BlogEra/assets/77263686/0d6db873-9883-481e-aec8-4a3c6aa0017e">

---

## Features💫

### User Authentication

BlogEra offers a robust user authentication system that ensures secure access to the app.

- **Register**: Users can register their accounts using a unique email address and password.
- **Login**: Subsequently, log in with their credentials.
- **Authentication**: Implemented with JWT tokens. The user remains signed in until they close the tab.
- **Form Validation**: Various checks on login and register forms to ensure robustness.

### Application Walkthrough

Once logged in, users gain access to their personalized dashboard. From here, they can easily:

- **Add Posts**: Create new Posts by specifying Posts details.
- **Update Posts**: Modify existing Posts.
- **Read all Posts**: View a comprehensive list of all their Posts.
- **Delete Posts**: Remove obsolete Posts from their list, keeping their dashboard clutter-free.

### Redux Toolkit for Effective State Management of the Application 

### Real Time Editor Functionality + Toggling Feature ( Active/Inactive ) 

### Form Validation

- **Form Validation**: Validation checks prevent users from setting completion times earlier than the current date or a negative priority, ensuring data consistency.
- **React-Hook-Form**: Leveraged 3 Party Form Validation Package (npm react-hook-form)

## Installation🛠️

To run GoalSetter locally, follow these steps:

1. Clone the repository: `git clone https://github.com/Arunabh0409/BlogEra.git`
2. Navigate to the project directory: `cd BlogEra`
3. Install server dependencies: `npm install`
4. Navigate to the client directory: `cd client`
5. Install client dependencies: `npm install`
6. Go back to the main project directory: `cd ..`
7. Create a `.env` file and add the following:
8. NODE_ENV: development
9.  PORT: desired_port_number / 5000
10. MONGO_URL: MongoDB_connection_URL
11. JWT_SECRET: a_string_used_for_encrypting_tokens
12 Run the app: `npm run dev`

## Usage💻

1. Register an account using your name, unique email address, and password.
2. Log in to access your personalized dashboard.
3. Add your Posts.
4. Update or delete Posts as needed.

Stay motivated, track your progress, and achieve your dreams with BlogEra !

## License📄

This project is licensed under the MIT License. Please feel free to use, modify, and distribute this code according to the terms of the license.

We hope BlogEra helps you stay focused and accomplish your aspirations.
Feel free to star the repository if you find it useful, and don't forget to share it with others who might benefit from this tool.
Happy Blogging! 🎯


