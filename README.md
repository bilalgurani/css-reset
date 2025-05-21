# 🎨 Modern CSS Reset

A modern, comprehensive CSS reset that provides a solid foundation for your web projects. This reset ensures consistent styling across different browsers while maintaining accessibility and usability.

## ✨ Features

- Maintains accessibility features
- Prevents unwanted scrollbars
- Improves default typography
- Better box-sizing defaults
- Responsive media elements
- Proper form element resets
- Improved touch behavior
- Better default line-heights

### Direct download:
Download the style.css file from this repository and include it in your project.

## 🚀 Usage

### Using in HTML:
html
<link rel="stylesheet" href="style.css">


Make sure to include the reset CSS before your custom styles.

## 🔍 What's Included

css
*,
*::after,
*::before {
  margin: 0;
  padding: 0;
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
  list-style: none;
  list-style-type: none;
  text-decoration: none;
}

html {
  /* font-size: 10px; */
  /* 10px / 16px = 0.625 = 62.5% */
  font-size: 62.5%;
  -webkit-box-sizing: inherit;
          box-sizing: inherit;
  scroll-behavior: smooth;
  overflow-x: hidden;
  height: -webkit-fill-available;
}

body {
  line-height: 1;
  font-weight: 400;
  overflow-x: hidden;
}

a, button {
  cursor: pointer;
  border: none;
  outline: none;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  text-decoration: none;
}
img, video, svg {
  display: block;
  max-width: 100%;
  height: auto;
  -o-object-fit: cover;
     object-fit: cover;
}

h1, h2, h3, h4, h5, h6 {
  text-wrap: balance;
}

p {
  /* It prevents from too big because its hard to read for users */
  max-width: 65ch;
  text-wrap: pretty;
}


## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)
- iOS Safari (latest)
- Android Chrome (latest)

## 💡 Why Use This Reset?

1. **Consistency**: Ensures consistent styling across different browsers
2. **Modern**: Built for modern web development needs
3. **Lightweight**: Minimal size, maximum impact
4. **Maintainable**: Well-documented and easy to customize
5. **Accessible**: Preserves important accessibility features

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (git checkout -b feature/AmazingFeature)
3. Commit your changes (git commit -m 'Add some AmazingFeature')
4. Push to the branch (git push origin feature/AmazingFeature)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📬 Contact

Your Name - [@callmeAlc](https://x.com/callmeAlc)

---

Made with ❤️ by Bilal Gurani
