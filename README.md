<p align="center" width="100%">
    <img height="100" src="https://github.com/said7388/developer-portfolio/assets/77630868/c0064908-cd5f-4751-a77c-eba90a62b55c">
</p>

---
# [Built Portfolio With GitHub ](https://github.com/said7388/github-portfolio)

---

# Developer Portfolio

### Hello I am Atalib Ag, are you struggling to create a professional website or business website? Look no further! You can use the Developer Portfolio template and create your very own personalized website today! My website is designed to be user-friendly and easily customizable, making it perfect for both developers and freelancers.

---

# Demo :movie_camera:

![image](https://github.com/AtalibAgAlmousleck/developer-portfolio/assets/87047616/49e10506-5acd-45c8-9315-cccade0c0a96)

---

## Table of Contents :scroll:

- [Sections](#sections-bookmark)
- [Demo](#demo-movie_camera)
- [Installation](#installation-arrow_down)
- [Getting Started](#getting-started-dart)
- [Usage](#usage-joystick)
- [Packages Used](#packages-used-package)

---

# Sections :bookmark:

- HERO SECTION
- ABOUT US
- EXPERIENCE
- SKILLS
- PROJECTS
- CONTACT US
- Team section todo: coming soon
- Testimonial section todo: coming soon
- Blog section todo: coming soon

---

# Installation :arrow_down:

### You will need to download Git and Node to run this project

- [Git](https://git-scm.com/downloads)
- [Node](https://nodejs.org/en/download/)

#### Make sure you have the latest version of both Git and Node on your computer.

```
node --version
git --version
```

## <br />

# Getting Started :dart:

### Fork and Clone the repo

To Fork the repo click on the fork button at the top right of the page. Once the repo is forked open your terminal and perform the following commands

```
git clone https://github.com/<YOUR GITHUB USERNAME>/developer-portfolio.git

cd developer-portfolio
```

### Install packages from the root directory

```bash
npm install
# or
yarn install
```

Then, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

---

# Usage :joystick:

Goto [emailjs.com](https://www.emailjs.com/) and create a new account for the mail sending. In free trial you will get 200 mail per month. After setup `emailjs` account, Please create a new `.env` file from `.env.example` file.

Eg:

```env
NEXT_PUBLIC_EMAILJS_SERVICE_ID =
NEXT_PUBLIC_EMAILJS_TEMPLATE_ID =
NEXT_PUBLIC_EMAILJS_PUBLIC_KEY =
NEXT_PUBLIC_GTM = # For site analytics
NEXT_PUBLIC_APP_URL = "http://127.0.0.1:3000"
NEXT_PUBLIC_RECAPTCHA_SECRET_KEY = # For captcha verification on contact form
NEXT_PUBLIC_RECAPTCHA_SITE_KEY =
```

### Then, Customize data in the `utils/data` [folder](https://github.com/said7388/developer-portfolio/tree/main/utils/data).

Eg:

```javascript
export const personalData = {
  name: "Almousleck Atalib Ag",
  profile: "/profile.png",
  designation: "Full-Stack Software Developer",
  description: "My name is Atalib Ag....",
  email: "microservices97@gmail.com",
  phone: "+86 130 2720 7507",
  address: "Sichuan, China",
  github: "https://github.com/AtalibAgAlmousleck",
  facebook: "",
  linkedIn: "",
  twitter: "",
  stackOverflow: "https://stackoverflow.com/users/almousleck",
  leetcode: "https://leetcode.com/almousleck/",
  devUsername: "almousleck",
  resume: "",
};
```

`devUsername` Used for fetching blog from `dev.to`.

---

---

# Packages Used :package:

| Used Package List  |
| :----------------: |
|        next        |
|  @emailjs/browser  |
|    lottie-react    |
| react-fast-marquee |
|    react-icons     |
|   react-toastify   |
|        sass        |
|    tailwindcss     |

---
