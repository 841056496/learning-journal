# Week 9 - Study Diary

Learning activities and resources
- This week, I focused on practicing 9 scss. My goal was to build a more visually appealing multi-page website, using the environment as the theme for a green future, showing:
1. Variables I used consistent colors, fonts
2. Nesting I used a structured SCSS selector
3. Blending I used reusable styles like transitions, box shadows
4. Extension/inheritance uses the shared button style
The main resources I used in this exercise refer to csss official documents. I mainly used VS Code +Live Sass Compiler plug-in for real-time SCSS→CSS compilation.
Unsplash/ pixel free environment images are also used (to enhance the visual effects of the site).

## Estimated working hours
A total of 3 hours, roughly divided into:
Half an hour planning the website structure (HTML pages, images, parts)
1 hour to write and test SCSS files (variables, mixins, etc.).
1 hour to debug layout issues and fine-tune design (e.g. Hero section, card layout)
Half an hour to record the process in my study journal.

## Content insight
Sass variable
- It is very convenient to define "$primary-color", "$secondary-color", "$dark-bg". Instead of repeating color hexadecimal codes, I can quickly adjust the color palette of the entire site in one place.
nest
- Nested 'navul' and 'or'. cards.card img makes SCSS more readable, but I have to be careful not to nest too deeply.
mixin
- Created a "mixin Transition ($time)" to standardize hover effects, and a "mixin card-Shadow" to maintain a consistent box shadow style across multiple card layouts.
Extension/inheritance
- Use '. Btn-warning {extend.btn} 'lets me share 90% of the button style and only change the background color. This approach saves code duplication and keeps button styles consistent.
Multi-file Sass
- Divide the code into _variables. "scss", "_mixins. scss, _global. Scss ', plus' main '. Scss is a new approach. It keeps SCSS organized and maintainable, especially as the site gets larger.

Career/employability/learning insights
Sass is widely used in professional front-end workflows. Knowing how to construct parts, import them, and use compiler plug-ins is an essential skill for many web development roles.
Separating logic (variables, mixins) from layout rules can facilitate scalable design practices. It fits well with the DRY (don't repeat yourself) principle, which is highly valued by employers.
Using **VS Code** + **Live Sass Compiler** is a quick setup to emulate a modern development environment (although for larger projects, I might switch to Gulp or Webpack).
The green environment theme helped me practice building a more visually appealing "cause driven" website, which is a great portfolio that showcases style and purpose driven design.


A deep dive into Sass this week gave me a better understanding of how front-end developers manage complex styles in real projects. The combination of partial imports, variables, blends, and extensions allowed me to build a visually coherent, multi-page "Green Future" website. I noticed how easy it was to keep track of brand colors and consistent spacing once I put them in variables.
In terms of workflow, Live Sass Compiler facilitates instant feedback. If I make a syntax error in SCSS, the compiler immediately warns me, which speeds up debugging. Next time, I might try using Gulp for more powerful tasks like automatic prefixes or image optimization. Overall, I gained confidence in designing a website that was not only richer in topic, but also easier to maintain. I look forward to further refining the site, perhaps adding response breakpoints with nested media queries or advanced blends.
