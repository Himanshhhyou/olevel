# 📚 LearnAngle - O-Level Learning Platform

Welcome to **LearnAngle**, a comprehensive learning platform designed for O-Level students to learn, practice, and test their knowledge in web technologies and computer fundamentals.

## 🌟 Features

- **Online Tests**: Chapter-wise practice tests with filtering options (Today, Upcoming, Past)
- **Class Codes**: Browse through 40+ HTML/CSS coding examples and projects
- **Study Materials**: Access PDF notes and resources
- **Mini Projects**: Interactive projects including animations, forms, and designs
- **Multilingual Support**: Tests available in Hindi (हिन्दी) and English

## 📂 Project Structure

```
olevel/
├── index.html              # Main dashboard page
├── online-test.html        # Chapter-wise online tests
├── pdfs.html              # Study materials page
├── codes.html             # Code examples page
├── style.css              # Global styles
├── html-class-codes/      # HTML/CSS class examples
│   ├── class-codes/       # 40+ HTML examples
│   └── mini-projects/     # Interactive mini-projects
└── files/                 # PDF resources and images
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic understanding of HTML, CSS, and JavaScript
- (Optional) A local web server for development

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Himanshhhyou/olevel.git
cd olevel
```

2. Open `index.html` in your web browser, or use a local development server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx http-server

# Using PHP
php -S localhost:8000
```

3. Navigate to `http://localhost:8000` in your browser

## 🌿 Branch Management & Contribution Guidelines

> 📖 **Quick Reference**: See [BRANCH_GUIDE.md](BRANCH_GUIDE.md) for a quick branch commands reference card.

### Creating a New Branch

When contributing to this project, always create a new branch for your changes:

```bash
# Create and switch to a new branch
git checkout -b feature/your-feature-name

# Or for bug fixes
git checkout -b fix/bug-description

# Or for documentation updates
git checkout -b docs/documentation-update
```

### Branch Naming Conventions

- **feature/**: New features or enhancements (e.g., `feature/add-chapter2-tests`)
- **fix/**: Bug fixes (e.g., `fix/navigation-menu`)
- **docs/**: Documentation updates (e.g., `docs/update-readme`)
- **style/**: Code style improvements (e.g., `style/format-css`)
- **refactor/**: Code refactoring (e.g., `refactor/simplify-filters`)

### Contribution Workflow

1. **Fork the repository** (if you're not a direct contributor)

2. **Create a new branch**:
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make your changes** following the coding standards

4. **Test your changes** thoroughly:
   - Open all modified HTML pages in a browser
   - Test on different screen sizes (mobile, tablet, desktop)
   - Verify all links and functionality work correctly

5. **Commit your changes**:
   ```bash
   git add .
   git commit -m "Add descriptive commit message"
   ```

6. **Push to your branch**:
   ```bash
   git push origin feature/your-feature-name
   ```

7. **Create a Pull Request** with a clear description of your changes

### Coding Standards

- Use consistent indentation (2 spaces)
- Write semantic HTML5
- Keep CSS organized and commented
- Test cross-browser compatibility
- Ensure mobile responsiveness
- Add comments for complex logic

## 📖 Available Pages

### Main Dashboard (`index.html`)
The landing page with cards for:
- Online Tests
- Study PDFs
- Class Codes
- Extra Resources (coming soon)

### Online Test Portal (`online-test.html`)
Chapter-wise tests with:
- Filter by date (Today/Upcoming/Past)
- Live test indicators
- Bilingual support (Hindi/English)
- Test topics: HTML Tags, Binary Numbers, Front-end/Back-end, etc.

### HTML Class Codes (`html-class-codes/index.html`)
40+ examples covering:
- Basic HTML structure
- Forms and inputs
- CSS styling
- Animations and effects
- Mini-projects

### Study Materials (`pdfs.html`)
PDF resources on:
- IP Address
- Port Numbers
- Web Technologies
- Binary Numbers
- Front-end and Back-end concepts

## 🎨 Mini Projects

- **Flower Animation**: CSS-based flower design
- **Newspaper Dots**: CMYK color dots
- **Fan Animation**: Rotating fan effect
- **Resume Template**: Professional resume layout
- **Orange Ice Cream**: Creative CSS design

## 🤝 Contributing

We welcome contributions! Whether it's:
- Adding new test questions
- Creating new code examples
- Improving documentation
- Fixing bugs
- Enhancing UI/UX

Please follow the branch management guidelines above and submit a pull request.

## 📝 License

This project is created for educational purposes. Feel free to use and modify for learning.

## 👨‍💻 Author

**Himanshu**
- GitHub: [@Himanshhhyou](https://github.com/Himanshhhyou)

## 🙏 Acknowledgments

- Bootstrap 5 for responsive design
- Font Awesome for icons
- All contributors who help improve this platform

---

**Happy Learning! 📚✨**
