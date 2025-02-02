# Project overview
I designed, coded, and deployed this single page application (SPA) that uses vertical scrolling for navigation, instead of the horizontal navigation seen in my other project. This SPA improves the way coding is taught and learned and supports various types of engaging media, including 2D and 3D images, audio recordings, and iframes. Animation is used sparingly to highlight important UI elements. Since the platform is built on top of the RevealJS presentation framework, there is documentation that makes it possible to make changes to the content with only a basic understanding of HTML.

This project is a near clone of the Horizontal-GO-SDK-Elearning-Module except that in this version, I have made the navigation vertical (i.e. scrolling up and down). Going from left and right button navigation to scrolling navigation was incredibly simple and illustrates the power of the Reveal.js platform.
The following code was all I needed to change to make the presentation scrollable:
```
<script>
  Reveal.initialize({
    plugins: [RevealHighlight],
    progress: true,
    // Activate the scroll view
    view: 'scroll',
    // Force the scrollbar to remain visible
    scrollProgress: true,
  });
</script>
```

# Unique ability to explore text line-by-line
When I created this SPA, I wanted to take a unique approach to exploring and explaining code. I decided to walk the audience through each line of code, highlighting the exact part being explained. It was a challenge to keep the voice recording and code highlighting in sync, but once I got the program logic right, updating and adding to the content became a cinch.

# Focus on education and user experience standards
The SPA is purposefully designed for both mobile and desktop screens. The UI and UX were vetted by a formally educated UI/UX professional (Mariana Pulgarin). Furthermore, as an instructional designer by trade, I paid close attention to the educational merit and organization of the content to ensure it was pedagogically sound and effective.

# Technical simplicity for easy hosting, maintainability, and modifications
From a technical standpoint, this SPA consists of HTML, CSS, and JavaScript contained in a single folder that can be hosted almost anywhere and opened in any modern browser. Updating the content or styles is as simple as using a text editor to modify a single “index.html” file and some logically organized CSS.

# Development lifecycle and best practices
Being that I have kept this SPA as simple as possible, there is a standard and modern workflow for application development that provides the following benefits:
- Faster onboarding for developers
- Consistency across any hosting environment, including local, cloud, or on-premise
- Version-control with Git
- Issues reproduced and tracked easily
- Detailed audit trail for all changes.
- Reduced risk of unwanted changes and the ability to correct them before they go into production.
- Changes can require code peer-review, approval, and tests before being deployed into the production environment.
- Continuous integration and continuous deployment (CI/CD) is possible.

# Conclusion
This SPA shows that I can design and code complex web applications for clients who want a modern UX and UI that can educate and delight their audience. It also represents a significant effort on my part to advance the way coding and other subjects can be taught and learned. It has high UX and instructional design standards built-in, is based on well-documented and simple technology, and offers a development lifecycle that adheres to best practices.

Hakim El Hattab is the creator of the open source reveal.js project from which my elearning platform is built. It would be remiss of me not to give him proper credit for his work. You can get more information about reveal.js, including documentation from here: <https://revealjs.com/markup/>. You can also create a reveal.js presentation using a graphical editor here: <https://slides.com>.

