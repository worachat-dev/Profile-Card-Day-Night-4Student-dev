## Profile Card with Day/Night Theme

Welcome to the **Profile Card with Day/Night Theme** project! This repository showcases a responsive and modern profile card with an integrated theme switcher between a "Black" and "White" theme. The design offers a sleek and elegant look, enhanced by a tooltip for social media links.

![Profile Card Screenshot - Dark Theme](https://raw.githubusercontent.com/worachat-dev/profile-card-day-night-4student/main/screenshot01.png)
![Profile Card Screenshot - Light Theme](https://raw.githubusercontent.com/worachat-dev/profile-card-day-night-4student/main/screenshot02.png)

### Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

### Demo

You can view the live demo of the project [here](https://github.com/worachat-dev/profile-card-day-night-4student).

### Features

- **Responsive Design:** Adapts seamlessly to various screen sizes.
- **Dual Themes:** Toggle between "Black" and "White" themes.
- **Social Media Tooltip:** Hover over social icons to reveal tooltips.
- **Modern UI:** Utilizes contemporary CSS styles and gradients.

### Getting Started

To get a local copy up and running follow these simple steps.

#### Prerequisites

Make sure you have the following installed:
- A modern web browser
- Basic knowledge of HTML and CSS

#### Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/worachat-dev/profile-card-day-night-4student.git
   ```
2. Open the `index.html` file in your browser to view the profile card.

### Usage

The profile card is designed to be easily customizable. You can edit the `index.html` and `style.css` files to change content, images, and styles to suit your preferences.

#### HTML Structure

The main structure is simple and modular. Here is a snippet:
```html
<body class="black-theme">
    <div id="switch">
        <i class="fas fa-sun"></i>
    </div>
    <div class="container">
        <div class="card">
            <div class="card__top">
                <img src="./about.png" alt="Background Image" class="card__background">
                <div class="profile__photo">
                    <img src="./profile.png" alt="Profile Photo" class="profile__img">
                </div>
            </div>
            <div class="card__content">
                <h2>Worachat Wannawong</h2>
                <h3>Web Developer</h3>
                <p><span><i class="fas fa-map-marker-alt"></i></span> Gifted NK, Thailand</p>
                <p><span><i class="far fa-building"></i></span> STEAM platform</p>
                <p><span><i class="far fa-envelope"></i></span> <a href="mailto:xxxx@gmail.com">XXXX@gmail.com</a></p>
                <a href="https://github.com/worachat-dev" class="button">Github Projects</a>
            </div>
        </div>
    </div>
    <script src="./script.js"></script>
</body>
```

#### CSS Styles

The CSS is designed with simplicity and modularity in mind. It includes styles for both themes and transitions:
```css
body {
    font-family: "Lato", sans-serif;
    letter-spacing: 0.5px;
    font-weight: 400;
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    overflow: hidden;
    position: relative;
}

/* Themes, card, and other styles */
```

### Contributing

Contributions are what make the open-source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Authors

- **Worachat W, Dev.** - *Game Design & Dev. 2024*

## License

Distributed under the MIT License. See `LICENSE` for more information.

### Acknowledgments

This project was inspired by the [Profile Card with Tooltip](https://github.com/RedEdge967/Profile-Card) created by Chandula Janith (RedEdge967). The original design provided a foundational idea which was further adapted and enhanced in this project.

---

Feel free to customize and enhance this profile card according to your needs. If you have any suggestions or improvements, please contribute!

---

### Screenshot Links

- **[Screenshot - Dark Theme](https://raw.githubusercontent.com/worachat-dev/profile-card-day-night-4student/main/screenshot01.png)**
- **[Screenshot - Light Theme](https://raw.githubusercontent.com/worachat-dev/profile-card-day-night-4student/main/screenshot02.png)**

---

You can include additional information, screenshots, or even GIFs to make the README more engaging and informative. The file references (`screenshot01.png`, `screenshot02.png`, `index.html`, `style.css`, `script.js`) should be updated to match the actual files in your repository.
