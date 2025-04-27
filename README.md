# 🌿 Green IT Project

Welcome to the **GreenIT-Project** – an academic initiative developed as part of the Green IT program at **EFREI**.  
Let's build a more sustainable web, one commit at a time. 💚

> 📍 GitHub Repo: [chealeanpenhchakrith/Green-IT-Project](https://github.com/chealeanpenhchakrith/Green-IT-Project)

---

## 🎯 Project Objective

🚀 **Goal**: Design, implement, and analyze the **carbon footprint** of a website.  
🌎 **Mission**: Build an environmentally friendly site with minimal impact on the planet.  
🌱 **Focus**: Energy efficiency, clean design, and sustainable development.

---

## 📦 About the Project

This project is part of the **Green IT coursework** at EFREI.  
We aim to apply sustainable web development practices and evaluate the environmental impact of common design and coding choices.

---

## 🔧 Getting Started

If you’re contributing to this project, follow these steps to get started locally.

---

### 🪝 Step 1 – Fork the Repository

Head over to the original repo and click **"Fork"** (top right):

👉 [https://github.com/chealeanpenhchakrith/Green-IT-Project](https://github.com/chealeanpenhchakrith/Green-IT-Project)

---

### 💻 Step 2 – Clone Your Fork

Open your terminal and run:

```bash
git clone https://github.com/YOUR_USERNAME/Green-IT-Project.git
cd Green-IT-Project
```

## ⚠️ Replace YOUR_USERNAME with your actual GitHub username ⚠️

---

### 🔌 Step 3 – Set Upstream to Sync with the Original Repo

Your fork won’t automatically receive updates from the original project. To keep your fork up to date:

Add the original repo as an upstream remote (only once):

```bash
git remote add upstream https://github.com/chealeanpenhchakrith/Green-IT-Project.git
```

🔍 Verify your remotes (optional):

```bash
git remote -v
```

You should see something like :

```bash
origin    https://github.com/YOUR_USERNAME/Green-IT-Project.git (fetch)
upstream  https://github.com/chealeanpenhchakrith/Green-IT-Project.git (fetch)
```

📥 Sync your fork with the latest changes from upstream :

```bash
git fetch upstream
git checkout main
git merge upstream/main
```

✅ Now your local fork is up to date with the original repository!

---

## 🏫 Project Info

🎓 Institution: EFREI

🌱 Theme: Green IT / Sustainable Web Development

👤 Maintainer: @chealeanpenhchakrith

---

## 📄 License
This project is created for academic and educational purposes.

---

## Description of different parts of the website and the functionalities 

Home Page:

Description of the goal of the website, and its purpose
A link at the bottom of the page towards the Login/Signup page

Catalogue Page:

Contains all the available products with its name, description, price and who is selling it
Need to be logged in in order to interact with the products
Once logged in user has the possibility to create sell order through button "Add sell order"
Admin user can remove users' sell order 

Profile Page:

User can create a new account or can log in if he already has an account
Once logged in user can view its information as well as the products he added to sell and can remove it 
User can also disconnect from his account

To run the database, you need to type in the terminal "npm run dev" in order to access to all the functionalities 

View Cart Page:

User can view its own cart and can interact by removing items from its cart or checkout all of his items

Add Sell Order Page:

User can create new sell order by adding the product's name, description, category, price and the quantity available
Once it is added or canceled, the page returns the user to the Catalogue Page
