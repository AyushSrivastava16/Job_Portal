# Job_Portal

A full-stack web application that connects job seekers with employers. Built with the MERN stack (MongoDB, Express, React, Node.js).

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)

## Features

- User registration and login (job seeker and recruiter)
- Post, edit, delete job listings
- Browse and apply for jobs
- Application tracking
- Responsive UI

## Tech Stack

- Frontend: React, HTML, CSS
- Backend: Node.js, Express.js
- Database: MongoDB
- Authentication: JWT


## Installation

1. Clone the repo:
```bash
git clone https://github.com/YourUsername/Job_Portal.git
cd Job_Portal
```

2. Install backend dependencies:

```bash
cd backend
npm install

```


3. Create a .env file in the backend folder:
```bash
PORT=5000
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
```

4. Start the backend server:
```bash
npm start
```

5. In another terminal, install frontend dependencies:
```bash 
cd ../frontend
npm install
npm start
```

---

```markdown
## Usage

- Visit `http://localhost:3000`
- Register as job seeker or recruiter
- If recruiter: post jobs
- If seeker: browse and apply for jobs

```
## Contributing

1. Fork this repo
2. Create a branch: `git checkout -b feature/YourFeature`
3. Commit your changes: `git commit -m 'Add feature'`
4. Push and open a pull request


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

**Ayush Srivastava**  
GitHub: [@AyushSrivastava16](https://github.com/AyushSrivastava16)







