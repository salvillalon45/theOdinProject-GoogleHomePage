# theOdinProject-GoogleHomePage
[TheOdinProject: Web Development 101] - Project: Google Home Page

# Summary
For this project, we were tasked to deconstruct an existing web page and rebuild it. 

The goal is to start thinking about how elements get placed on the page and roughly how they get styled and aligned.

For this project we were tasked to build the Google.com homepage

# Challenges
One of the challenges for this project was creating a sticky footer. I had the idea of moving the footer by using margin-top, but I felt that this is not correct solution since I felt it was too brute force. I felt that changing the display to flex was the way to go. This article helped me understand how to do it [Sticky Footer, Five Ways](https://css-tricks.com/couple-takes-sticky-footer/#article-header-id-3).

Through this project I was exposed to flex-grow, flex-shrink and flex-basis. Some properties I have not used before.

After applying this changes, I noticed that footer was not going all the way across the screen it had some extra margin that was preventing it from fully extending. I learned that we can apply 

`html, body {
  margin: 0;
}`

that will reset the pages default margin and padding for the entire html file.

You can find more on the project here: [The Odin Project - HTML/CSS](https://www.theodinproject.com/courses/web-development-101/lessons/html-css)

# Technologies:
  - HTML
  - CSS
