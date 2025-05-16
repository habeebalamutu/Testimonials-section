Frontend Mentor - Testimonials grid section solution
This is a solution to the Testimonials grid section challenge on Frontend Mentor. Frontend Mentor challenges help you improve your coding skills by building realistic projects.

Table of contents
Overview
The challenge
Built with
What I learned
Useful resources
Author
Acknowledgments



Overview
The challenge
Users should be able to:

View the optimal layout for the site depending on their device's screen size

Built with
Semantic HTML5 markup
CSS custom properties
Flexbox
CSS Grid
Mobile-first workflow
What I learned
During this project, I learned how to use CSS Grid to create complex, responsive layouts that adapt to both mobile and desktop designs. I also improved my skills with CSS custom properties for consistent theming and practiced a mobile-first approach for better responsiveness.

Example code snippet:

@media (min-width: 900px) {
  .testimonials-grid {
    grid-template-columns: repeat(4, 1fr);
    grid-template-rows: repeat(2, auto);
    gap: 2rem;
  }
}

Useful resources
CSS Grid Layout Guide (MDN) - Helped me understand and implement grid layouts.
Frontend Mentor Community - Great for feedback and tips on best practices.


Author
Frontend Mentor - @habeebalamutu
Acknowledgments
Thanks to the Frontend Mentor community for feedback and inspiration.