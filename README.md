# Italian Course (Definitive Edition)

An interactive Italian language course built with reveal.js, designed to teach Italian through engaging presentation-style lessons.

## 📚 Overview

This project provides a comprehensive Italian language learning experience through interactive web-based presentations. Each lesson covers different aspects of the Italian language, from phonetics to grammar and common phrases.

## ✨ Features

- **Interactive Presentations**: Powered by reveal.js for smooth, engaging slide transitions
- **Structured Learning**: Progressive lessons building from fundamentals to advanced topics
- **Phonetics Focus**: Detailed coverage of Italian pronunciation and phonetic rules
- **Web-Based**: Access lessons from any device with a web browser
- **Responsive Design**: Works seamlessly on desktop and mobile devices

## 🚀 Getting Started

### Prerequisites

- Node.js >= 18.0.0
- npm (Node Package Manager)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Alessandro-Rocchi/Italian-Course-Def.git
   cd Italian-Course-Def
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Build the project:
   ```bash
   npm run build
   ```

### Running the Course

Start the development server:
```bash
npm start
```

Then open your browser and navigate to `http://localhost:8000` to view the course index.

## 📖 Course Structure

The course is organized into lessons, each focusing on specific topics:

- **Lesson 1: Phonetics** - Italian alphabet, vowels, consonants, and pronunciation rules
- **Lesson 2: Basic Grammar** - Fundamental grammar concepts (coming soon)
- **Lesson 3: Common Phrases** - Essential everyday expressions (coming soon)

### Accessing Lessons

- Visit `index.html` for the main course index
- Individual lessons are located in the `slides/` directory
- Navigate directly to specific lessons (e.g., `slides/Lesson01.html`)

## 🛠️ Development

### Project Scripts

- `npm start` - Start the development server
- `npm run build` - Build the project for production
- `npm test` - Run tests

### Adding New Lessons

1. Create a new HTML file in the `slides/` directory (e.g., `Lesson04.html`)
2. Use the existing lesson files as templates
3. Update `index.html` to include a link to your new lesson
4. Follow the reveal.js documentation for advanced features

### Project Structure

```
Italian-Course-Def/
├── slides/           # Individual lesson presentations
├── dist/            # Compiled reveal.js distribution
├── plugin/          # reveal.js plugins
├── css/             # Custom stylesheets
├── js/              # JavaScript files
├── index.html       # Course index page
└── package.json     # Project dependencies
```

## 🎯 Technologies Used

- **reveal.js** (v5.2.1) - The HTML presentation framework
- **Gulp** - Build automation
- **highlight.js** - Code syntax highlighting
- **marked** - Markdown parsing

## 📝 License

This project uses the reveal.js framework, which is licensed under the MIT License.

Copyright (C) 2011-2024 Hakim El Hattab, http://hakim.se, and reveal.js contributors

See the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Whether it's:
- Adding new lessons
- Improving existing content
- Fixing bugs
- Enhancing documentation

Please feel free to submit pull requests or open issues.

## 📞 Contact & Feedback

This is an interactive course - **PLEASE GIVE US FEEDBACK!** Your input helps improve the learning experience for everyone.

## 🌟 Acknowledgments

- Built with [reveal.js](https://revealjs.com/) by Hakim El Hattab
- Italian language content and instruction by Alessandro Rocchi and contributors

---

*Buono studio! (Happy learning!)*
