# Pilgrim's Pursuits

![Pilgrim's Pursuits responsive screenshot](/documentation/images/amiresponsive.PNG)

## Introduction

Pilgrim's Pursuits is a blogsite dedicated to providing comprehensive information about the Islamic pilgrimage, Hajj. It aims to address the challenges of learning about and booking Hajj packages, offering users the ability to read and write information to broaden their perspectives and simplify their decision-making process. This website is developed as part of my Individual Capstone Project for the AI Augmented Full Stack Web Developer course by Code Institute, with a focus on Django, database management, and CRUD functionality.

[View the live site here](https://pilgrims-pursuits-6f2112d13927.herokuapp.com/)

<hr>

## Table of Contents

- [User Stories](#user-stories)
- [UX Design Process](#ux-design-process)
  - [Project Board](GitHub-Projects)
  - [Wireframes](Wireframes)

## User Stories

- The user stories were created by [Microsoft Copilot](https://copilot.microsoft.com/) using the pattern of "As a ** I want to ** so that I can **", alongside further commands to Copilot to refine them, including editing some user stories entirely.

1. As a Visitor, I want to register an account so that I can access the blog site features.
2. As a Registered User, I want to log in so that I can access my account and post comments.
3. As an Admin, I want to create, edit, and delete blog posts so that I can manage content on the blog site.
4. As a Visitor, I want to view blog posts so that I can read about the Hajj pilgrimage.
5. As a Registered User, I want to comment on blog posts so that I can engage with the content and other users.
6. As an Admin, I want to moderate comments so that I can maintain the quality of discussions on the blog.
7. As a Registered User, I want to give a star rating on blog posts so that I can express my opinion on the quality of the content.
8. As a Registered User, I want to create blog posts so that I can share my experiences and knowledge.
9. As a Registered User, I want to like blog posts and comments so that I can show my appreciation for the content.
10. As a Registered User, I want to collaborate with the blog author by sending my ideas and comments, so that I can provide ideas and feedback.

## UX Design Process

- **Link to User Stories in GitHub Projects:**

  - [GitHub Projects Kanban Board](https://github.com/users/Ashrafur93/projects/6)

- **Wireframes:**

  I used Balsamiq to create the wireframes and used the Code Institute Walkthrough Project as the template for my layout. [Balsamiq](https://balsamiq.com/) was introduced to me via the Code Institute course and I have found it to be easy to learn and use. It is great for designing websites on different platforms and viewports, which helps to plan for responsive sites.

**Mobile view for:**

- Home
- About
- Register
- Login
- Article

<details open>
    <summary>Mobile Home Page Wireframe</summary>  
    <img src="">  
</details>
  
<details>
    <summary>Mobile About Page Wireframe</summary>  
    <img src="">
</details>

<details>
    <summary>Mobile Register Page Wireframe</summary>  
    <img src="">
</details>

<details>
    <summary>Mobile Login Page Wireframe</summary>  
    <img src="">
</details>

<details>
    <summary>Mobile Post Page Wireframe</summary>  
    <img src="">
</details>

**Tablet view for:**

- Home
- About
- Register
- Login
- Article

<details open>
    <summary>Tablet Home Page Wireframe</summary>  
    <img src="">  
</details>
  
<details>
    <summary>Tablet About Page Wireframe</summary>  
    <img src="">
</details>

<details>
    <summary>Tablet Register Page Wireframe</summary>  
    <img src="">
</details>

<details>
    <summary>Tablet Login Page Wireframe</summary>  
    <img src="">
</details>

<details>
    <summary>Tablet Post Page Wireframe</summary>  
    <img src="">
</details>

**Desktop view for:**

- Home
- About
- Register
- Login
- Article

<details open>
    <summary>Desktop Home Page Wireframe</summary>  
    <img src="/documentation/images/Desktop - Home.PNG">  
</details>
  
<details>
    <summary>Desktop About Page Wireframe</summary>  
    <img src="/documentation/images/Desktop - About.PNG">
</details>

<details>
    <summary>Desktop Register Page Wireframe</summary>  
    <img src="/documentation/images/Desktop - Sign up.PNG">
</details>

<details>
    <summary>Desktop Login Page Wireframe</summary>  
    <img src="/documentation/images/Desktop - Sign in.PNG">
</details>

<details>
    <summary>Desktop Post Page Wireframe</summary>  
    <img src="/documentation/images/Desktop - Post.PNG">
</details>

- I used wireframes to create the rudimentary design and layout of the blogsite, it was mainly inspired by the minimalistic and clear design of the Walkthrough project. Images provide a visual indication of the post content and alternative text supports accessibility.

- **Design Rationale:**
  - The design is a clear and simple layout with minimal distractions for the user, it is intentionally designed to have the blog posts at the user's attention.

- **Colour scheme:**

  - <details>
    <summary>Colour palette</summary>  
    <img src="/documentation/images/Coolers.png">
    </details>

  - The colour scheme was also kept minimal for a clean look with only 3 colours used for the website, which were derived from [Coolers.co](https://coolors.co/). It was inspired by the black and gold colouring of the Kaba in Makkah, as well as the official website for [Nusuk Hajj](https://hajj.nusuk.sa/).
  The typography is the default font of the Django package, which is installed during pip installation of the Django framework. The colour choices of the font also reflect minimal styling and contrast to make readability easier. 

- **Reasoning For Any Final Changes:**
  - Some changes were made from the initial concept to the current result. Due to user feedback, the navbar was given it's own colour to separate it from the rest of the page, this provides better UX as the user's eyes flow down the content easier. And due to time constraints, images were not included as thumbnails for the posts, this can be introduced in a later release.

## Key Features

- **CRUD functionality:** This is one of the defining purposes of this project and the user can successfully create, read, update and delete content. 
- **User authentication:** Users can log in and out securely, while only the original user (and admins) can edit or delete their comment.
- **Inclusivity Notes:**
  - ARIA labels have been used where required and the banner image has been given an alternate text.

## Deployment

- **Platform:** [Heroku](https://www.heroku.com)
- **High-Level Deployment Steps:**
  1. Clone the repository from Github.
  2. Set up the Heroku environment and create a PostgreSQL database. I used [Code Institute's student link](https://dbs.ci-dbs.net/)
  3. Configure the variables in Heroku for the database URL from the previous step as well as secret keys.
  4. Deploy from Heroku and click open app.
- **Verification and Validation:**
  - The deployed version was checked on each page to ensure it matches the development version in functionality and styling.
  - Additional checks were made with lighthouse and manual testing.
- **Security Measures:**
  - The environmental variables store sensitive data.
  - DEBUG mode is set to false to improve security.

## AI Implementation and Orchestration

### Use Cases and Reflections:

(Highlight how prompts, such as reverse, question-and-answer or multi-step, were used to support learners with SEND or ALN where relevant.)

- **Code Creation:**
  - Reflection: Strategic use of AI allowed for rapid prototyping, with minor adjustments for alignment with project goals.
  - Examples: Reverse prompts for alternative code solutions and question-answer prompts for resolving specific challenges.
- **Debugging:**
  - Reflection: Key interventions included resolving logic errors and enhancing maintainability, with a focus on simplifying complex logic to make it accessible.
- **Performance and UX Optimization:**
  - Reflection: Minimal manual adjustments were needed to apply AI-driven improvements, which enhanced application speed and user experience for all users.
- **Automated Unit Testing:**

  - Reflection: Adjustments were made to improve test coverage and ensure alignment with functionality. Prompts were used to generate inclusive test cases that considered edge cases for accessibility.

- **Overall Impact:**
  - AI tools streamlined repetitive tasks, enabling focus on high-level development.
  - Efficiency gains included faster debugging, comprehensive testing, and improved code quality.
  - Challenges included contextual adjustments to AI-generated outputs, which were resolved effectively, enhancing inclusivity.

## Testing Summary

- **Manual Testing:**
  - **Devices and Browsers Tested:** Windows 11 (Chrome, Edge - Samsung RF511), Android (Chrome - Samsung Galaxy Note 10+, Samsung browser - Samsung Galaxy S20 FE), iOS (Safari - iPhone 14).
  - **Features Tested:** [Summarise features tested manually, e.g., CRUD operations, navigation.]
  - **Results:** [Summarise testing results, e.g., "All critical features worked as expected, including accessibility checks."]
- **Automated Testing**
  - Tools Used: [Mention any testing frameworks or tools, e.g., Django TestCase.]
  - Features Covered: [Briefly list features covered by automated tests.]
  - Adjustments Made: [Describe any manual corrections to AI-generated test cases, particularly for accessibility.]
- **Lighthouse testing**
<details>
    <summary>Lighthouse testing screenshot</summary>  
    <img src="/documentation/images/Lighthouse.PNG">
</details>
  - Unfortunately testing shows errors on Lighthouse, despite full functionality of the blogsite. This will be addressed for future releases.

- **HTML validator**
<details>
    <summary>HTML validator - About</summary>  
    <img src="/documentation/images/HTML validator - About.PNG">
</details>
  - Unfortunately testing shows errors on W3C HTML validator, despite full functionality of the blogsite. This will be addressed for future releases.

<details>
    <summary>HTML validator - Base</summary>  
    <img src="/documentation/images/HTML validator - Base.PNG">
</details>
  - Unfortunately testing shows errors on W3C HTML validator, despite full functionality of the blogsite. This will be addressed for future releases.

  <details>
    <summary>HTML validator - Index</summary>  
    <img src="/documentation/images/HTML validator - Index 1.PNG">
    <img src="/documentation/images/HTML validator - Index 2.PNG">    
</details>
  - Unfortunately testing shows errors on W3C HTML validator, despite full functionality of the blogsite. This will be addressed for future releases.


## Future Enhancements

- [List potential improvements or additional features for future development.]
- Consider enhancements to improve accessibility further, such as voice input capabilities or additional language support.

## Credits
- **Content**
  - All the blog posts were written by Copilot with minimal intervention by me, this greatly sped up the build process.
  - [Getty Images](https://www.gettyimages.co.uk/) was used to download the banner image in each post.
  - Much of the code was derived from the Code Institute walkthrough project, with some changes made by myself as well as Copilot.
  - This README file was provided to me by Code Institute as a template, which I then edited.
  
- **Acknowledgements**
  - My deepest gratitude to the Code Institute team for this amazing course which has set me on the path to become a Web Developer.
  - A special thank you and recognition to my Facilitator Emma Lamont, Coding Coaches Ruairidh MacArthur and John Rearden and Subject Matter Expert Spencer Barriball for all their patience, knowledge and support.