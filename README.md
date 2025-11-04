Portfolio Website :
  A modern, responsive portfolio template to showcase my work, experience, education, and skills. Built with Bootstrap 4, SCSS, and enhanced with animations using ScrollReveal.js and Tilt.js.

Features:
      One-page, smooth scrolling layout
      Fully responsive design
      Customizable with detailed instructions
      Built with Bootstrap 4, SCSS, and Parcel
      Scroll and parallax animations using ScrollReveal.js and Tilt.js

Sections:

      Hero: Portfolio title & CTA

      About: Bio and CV link

      Projects: Showcase of my work

      Experience: Professional background

      Education: Academic credentials

      Skills: Technical skills

      Contact: Email link

      Footer: Social media links

Getting Started:

Clone the repo

Install dependencies with npm or Yarn

Customize sections with my info


## How To Use 🔧

$ npm audit fix
$ npm i @parcel/transformer-sass

# Install dependencies
$ npm install

# Start the development server
$ npm start
```

Using Yarn: Be aware of that you'll need to delete the `package-lock.json` file before executing the below commands.

```bash
# Install dependencies
$ yarn

# Start the development server
$ yarn start
```

**NOTE**:
If your run into issues installing the dependencies with NPM, use this below command:

```bash
# Install dependencies with all permissions
$ sudo npm install --unsafe-perm=true --allow-root
```

Once your server has started, go to this url `http://localhost:1234/` to see the portfolio locally. It should look like the below screenshot.


---

## Template Instructions:

### Step 1 - STRUCTURE

Go to `/src/index.html` and put your information, there are 5 sections:

### (1) Hero Section

- On `.hero-title`, put your custom portfolio title.
- On `.hero-cta`, put your custom button label.

```html


### (2) About Section

- On `<img>` tag, fill the `src` property with your profile picture path, your picture must be located inside `/src/assets/` folder.
- On `<p>` tag with class name `.about-wrapper__info-text`, include information about you, I recommend to put 2 paragraphs in order to work well and a maximum of 3 paragraphs.
- On last `<a>` tag, include your CV (.pdf) path on `href` property, your resume CV must be located inside `/src/assets/` folder.

### (3) Projects Section

- Each project lives inside a `row`.
- On `<h3>` tag with class name `.project-wrapper__text-title`, include your project title.
- On `<p>` tag with `loremp ipsum` text, include your project description.
- On first `<a>` tag, put your project url on `href` property.
- On second `<a>` tag, put your project repository url on `href` property.

---

- Inside `<div>` tag with class name `.project-wrapper__image`, put your project image url on the `src` of the `<img>` and put again your project url in the `href` property of the `<a>` tag.
- Recommended size for project image (1366 x 767), your project image must be located inside `/src/assets/` folder.

### (4) Contact Section

- On `<p>` tag with class name `.contact-wrapper__text`, include some custom call-to-action message.
- On `<a>` tag, put your email address on `href` property.

### (5) Footer Section

- Put your Social Media URL on each `href` attribute of the `<a>` tags.
- If you an additional Social Media account different than Twitter, Linkedin or GitHub, then go to [Font Awesome Icons](https://fontawesome.com/v4.7.0/icons/) and search for the icon's class name you are looking.
- You can delete or add as many `<a>` tags your want.

### Step 2 - STYLES

Change the color theme of the website - (choose 2 colors to create a gradient)

Go to `/src/sass/abstracts/_variables.scss` and only change the values for this variables `$main-color` and `$secondary-color` with your prefered HEX color.
If you want to get some gradients inspiration I highly recommend you to check this website [UI Gradient](https://uigradients.com/#BrightVault)

```scss
// Default values
$main-color: #02aab0;
$secondary-color: #00cdac;
```

---

## Deployment 📦

Once you finish your setup. You need to put your website online!

I highly recommend to use [Netlify](https://netlify.com) because it is super easy.

## Technologies used 🛠️

- [Parcel](https://parceljs.org/) - Bundler
- [Bootstrap 4](https://getbootstrap.com/docs/4.3/getting-started/introduction/) - Frontend component library
- [Sass](https://sass-lang.com/documentation) - CSS extension language
- [ScrollReveal.js](https://scrollrevealjs.org/) - JavaScript library
- [Tilt.js](https://gijsroge.github.io/tilt.js/) - JavaScript tiny parallax library


