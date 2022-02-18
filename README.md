## 🎯 Objective
Build a Technical Documentation Page about any subject following the user requirements.

##📜 User Requirements
- Have a **main** element with an **id main-doc**.
- Several sections inside the **main** element with a corresponding **class main-section**. There should be a minimum of 5.
- The first element within each **.main-section** should be a **header** element which contains text that describes the topic of that section.
- Each section element with the class of **main-section** should also have an **id** that corresponds with the text of each header contained within it. Any spaces should be replaced with underscores.
- The **.main-section** elements should contain at least 10 **p** elements total (not each).
- The **.main-section** elements should contain at least 5 **code** elements total (not each).
- The **.main-section** elements should contain at least 5 **li** items total (not each).
- Use an **nav** label with an **id navbar**.
- The **navbar** element should contain one **header** element which contains text that describes the topic of the technical documentation.
- The **navbar** should contain **a** elements with the class of **nav-link**. There should be one for every element with the class **main-section**.
 - The **header** element in the navbar must come before any **a** elements in the navbar.
- Each element with the class of **nav-link** should contain text that corresponds to the header text within each section.
- Clicking on a **navbar** element, the page should navigate to the corresponding section of the **main-doc** element .
-  On regular sized devices (laptops, desktops), the element with **id navbar** should be shown on the left side of the screen and should always be visible to the user.
- The Technical Documentation page should use at least one **media query**.

## 🛠 Tools That Can Be Used
- HTML
- CSS
- JavaScript
- Bootstrap or SASS
- jQuery, React, Angular, or Vue

---

<div align="center">
  <h2 align="center">
    <strong>
      FCC-Technical-Documentation-Page
    </strong>
  </h2>
</div>

<div align="center">

[![HTML5](https://img.shields.io/badge/-HTML5-f2f2f2?style=flat&logo=html5)](https://developer.mozilla.org/en-US/docs/Glossary/HTML5)
[![CSS](https://img.shields.io/badge/-CSS3-f2f2f2?style=flat&logo=css3&logoColor=1d6eac)](https://www.w3.org/Style/CSS/specs.en.html)

</div>


## 📔 Commits Guidelines

- Using as reference [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)
- Every commit should have a sign with the contributor's GPG key
- The basic structure should be `[{ type in uppercase }] { description using imperative writing style or writing as a if it were a command }"`, for example:
  - `[UPDATE] header component with a new one more darker`
- For the types we have:
  - `[UPDATE]` : when we need to add a new feature, tests or change a property.
  - `[FIX]` : to implement the code necessary to fix a problem.
  - `[DELETE]` : when a file is going to be deleted and not replaced.
  - `[BREAKING CHANGE] or !` : to implement changes that are going to affect the integration with other services, for example:
    - `[UPDATE]! API version to v2 for new endpoints`

##  🤝 How to Contribute

1. Create a new branch using as base the `dev` branch.
2. Do the necessary improvements and make a commit: `git commit -S -am "{commit message}"` or use `git add .` and then `git commit -S -m "{commit message}"`.
3. Upload changes to the repository: `git push origin <branch name>`.
4. Create a pull request to the `dev` branch.
5. Wait for the code review and the merge.
6. Now your changes are in the dev environment.
7. After a review your changes are going to be merged to the `master` branch.
8. For certain contributors there are exeptions to these steps.
