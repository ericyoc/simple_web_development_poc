# Web Development Demonstration

This repository showcases a web development that demonstrates fundamental basics with HTML, CSS, and JavaScript. The creation of a simple website includes sections for an introduction, skills, projects, and recommendations.

## Overview

The creation of a simple website consists of the following components:

1. **Navigation Bar**: The navigation bar provides links to different sections of the portfolio, including About Me, Skills, Projects, and Recommendations. It allows easy navigation throughout the page.

2. **About Me**: This section introduces the developer, Eric, and provides a brief overview of his expertise and passion for software development. It includes a profile image and a short bio.

3. **Skills**: The skills section highlights the developer's technical skills, including HTML, CSS, JavaScript, Node.js, and MongoDB. Each skill is represented by an icon and includes the years of experience.

4. **Projects**: The projects section showcases some of the notable projects the developer has worked on. Each project is presented in a card format, with a title and a list of key features or technologies used.

5. **Recommendations**: The recommendations section displays testimonials or endorsements from colleagues or clients. It includes a form where visitors can leave their own recommendations.

6. **Recommendation Form**: The recommendation form allows visitors to submit their own recommendations. It includes fields for the recommender's name (optional) and message. Upon submission, the recommendation is added to the list of existing recommendations.

7. **Popup**: A popup is displayed when a new recommendation is successfully submitted. It shows a checkmark icon and a thank you message.

8. **Scroll to Top Button**: A floating button is provided at the bottom-right corner of the page, allowing users to quickly scroll back to the top of the page.

## Functionality

The simple website includes the following JavaScript functionality:

- **Adding Recommendations**: The `addRecommendation()` function is triggered when the recommendation form is submitted. It retrieves the message entered by the user, creates a new recommendation element, and appends it to the list of existing recommendations. If the message is empty, no action is taken.

- **Popup Display**: The `showPopup(bool)` function is used to control the visibility of the popup. When called with `true`, the popup is displayed, and when called with `false`, the popup is hidden.

## Styling

The simple website is styled using CSS, which is included in the `style.css` file. The CSS provides the following visual enhancements:

- **Layout**: The layout is designed using flexbox and includes responsive styling to ensure optimal display on different screen sizes.

- **Colors**: The color scheme is based on shades of purple (#7600bc) and white, with accents of light gray.

- **Typography**: The portfolio uses the 'Trebuchet MS' font family for a clean and modern look.

- **Hover Effects**: Hover effects are applied to the navigation menu items and buttons to provide visual feedback to the user.

- **Icons**: Icons are used to represent skills and enhance the visual appeal of the portfolio.

## Conclusion

This web development demonstrates the use of HTML, CSS, and JavaScript. The webiste is both attractive and functional providing an interactive way for visitors to learn more about the developer and leave their own recommendations.

Feel free to explore the code and customize the portfolio to fit your own needs and style preferences.
