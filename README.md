# William E. Carter School Website

This repository contains the source code for the official website of the **William E. Carter School**, a Boston Public School serving students with significant cognitive disabilities and complex medical needs.

## About the School
The William E. Carter School provides a supportive, student-centered learning environment with an interdisciplinary approach. The school offers specialized programs such as:
- **Aquatic Therapy**
- **Adapted Physical Education**
- **Music Therapy**
- **Vocational Training**
- **Assistive Technology Integration**

## Technology Stack
- **Static Site Generator:** [11ty (Eleventy)](https://www.11ty.dev/)
- **Template:** [11ty Plain Bootstrap 5](https://github.com/mandrasch/11ty-plain-bootstrap5)
- **Hosting:** GitHub Pages
- **Styling:** Bootstrap 5

## Project Structure
```
/                    # Root directory
├── src/             # Source files for 11ty
│   ├── _includes/   # Reusable templates and components
│   ├── _layouts/    # Layout templates
│   ├── assets/      # CSS, JS, images, and fonts
│   ├── pages/       # Individual page files
│   ├── index.md     # Homepage
├── .eleventy.js     # 11ty configuration file
├── package.json     # Dependencies and scripts
├── README.md        # Project documentation
└── .gitignore       # Files to ignore in Git
```

## Installation & Development
To contribute or modify the website, follow these steps:

### Prerequisites
Ensure you have the following installed:
- [Node.js](https://nodejs.org/) (LTS recommended)
- [npm](https://www.npmjs.com/) (Comes with Node.js)

### Setup
1. **Clone the repository**
   ```sh
   git clone https://github.com/YOUR_GITHUB_USERNAME/carter-school-website.git
   cd carter-school-website
   ```
2. **Install dependencies**
   ```sh
   npm install
   ```
3. **Run the local development server**
   ```sh
   npm run dev
   ```
   This will start a local server at `http://localhost:8080/` with live-reloading.

4. **Build for production**
   ```sh
   npm run build
   ```
   This will generate the static files in the `_site/` directory, ready for deployment.

## Deployment
The site is deployed via **GitHub Pages**. Push changes to the `main` branch, and the site will be automatically updated.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For questions or feedback, please contact the William E. Carter School at [official email/contact info].
