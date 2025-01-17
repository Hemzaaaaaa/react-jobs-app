# Jobs Website

This is a simple React project where users can browse, add, delete, and modify jobs. It uses the JSON Server package for a mock backend to handle job data.

## Features
- Browse available jobs.
- Add a new job listing.
- Delete existing job listings.
- Modify job details.

## Technologies Used
- **React**: Frontend framework.
- **JSON Server**: Mock backend for job data.
- **Tailwind CSS**: Styling.

## Installation

### Prerequisites
- [Node.js](https://nodejs.org/) installed on your machine.
- JSON Server installed globally or locally.

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/Hemzaaaaaa/react-jobs-app.git
   cd react-jobs-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the JSON Server:
   ```bash
   json-server --watch db.json --port 5000
   ```
   - Replace `db.json` with the name of your JSON file if different.

4. Start the React development server:
   ```bash
   npm start
   ```

5. Open your browser and navigate to `http://localhost:3000` to view the application.

## Sample `db.json`
You can use the following sample data in your `db.json` file:
```json
[
   {
      "id": "1",
      "title": "Senior React Developer",
      "type": "Full-Time",
      "description": "We are seeking a talented Front-End Developer to join our team in Boston, MA. The ideal candidate will have strong skills in HTML, CSS, and JavaScript, with experience working with modern JavaScript frameworks such as React or Angular.",
      "location": "Boston, MA",
      "salary": "$70K - $80K",
      "company": {
        "name": "NewTek Solutions",
        "description": "NewTek Solutions is a leading technology company specializing in web development and digital solutions. We pride ourselves on delivering high-quality products and services to our clients while fostering a collaborative and innovative work environment.",
        "contactEmail": "contact@teksolutions.com",
        "contactPhone": "555-555-5555"
      }
    },
    {
      "id": "2",
      "title": "Front-End Engineer (React & Redux)",
      "type": "Full-Time",
      "location": "Miami, FL",
      "description": "Join our team as a Front-End Developer in sunny Miami, FL. We are looking for a motivated individual with a passion for crafting beautiful and responsive web applications. Experience with UI/UX design principles and a strong attention to detail are highly desirable.",
      "salary": "$70K - $80K",
      "company": {
        "name": "Veneer Solutions",
        "description": "Veneer Solutions is a creative agency specializing in digital design and development. Our team is dedicated to pushing the boundaries of creativity and innovation to deliver exceptional results for our clients.",
        "contactEmail": "contact@loremipsum.com",
        "contactPhone": "555-555-5555"
      }
    },
]
```

## Folder Structure
```
.
├── public
│   └── index.html
├── src
│   ├── assets
│   │   └── logo.png
│   ├── components
│   │   ├── Card.jsx
│   │   ├── EditJobPage.jsx
│   │   ├── Hero.jsx
│   │   ├── HomeCards.jsx
│   │   ├── JobListing.jsx
│   │   ├── JobListings.jsx
│   │   ├── Navbar.jsx
│   │   ├── Spinner.jsx
│   │   └── ViewAllJobs.jsx
│   ├── layouts
│   │   └── MainLayout.jsx
│   ├── pages
│   │   ├── AddJobPage.jsx
│   │   ├── HomePage.jsx
│   │   ├── JobPage.jsx
│   │   ├── JobPages.jsx
│   │   └── NotFoundPage.jsx
│   ├── App.js
│   ├── index.js
├── db.json
├── package.json
├── tailwind.config.js
└── README.md
```

## Contributing
Feel free to fork this repository and submit pull requests with improvements or bug fixes.

## License
This project is licensed under the [MIT License](LICENSE).
