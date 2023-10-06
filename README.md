## Creating a Personal Website using Hugo + Netlify

### Project Summary

For Week 3 we were tasked to create our own personal portfolio website that would stand in place of our resume and our LinkedIn Profile. 

To do so we were given a very useful recording from Learn Robotic's Liz Miller. She gave a great walkthrough for setting up a portfolio using the Liftoff theme.


### Hugo Setup

I'll only be listing folders that were modified.

*assets:* \
This folder holds key assets like the javascript files and images. I added in a Northwestern image to use as the avater for the main page.

*config and config/_default:* \
This folder holders the .toml files. I primarily used _default for this assignment. In a real development scenario it would be better to leave defaults as is and then overwrite the settings manually in the dev/prod folders. 

*content:* \
This folder is important in that these markdown files power the pages themselves. I shortened and trimmed the main page to get rid of the blog posts and setup the nav structure similar to how Liz Miller did it. Note that you'll need to coordinate the changes from params.toml with changes here.

I also edited the About page to look more like my resume. 

I also did a sample post, MSDS431 Week 3 Project - Portfolio, to show what this would look like on the site.

*layouts:* \
Touched this folder briefly to play around with shortcodes and tried to add in a table of contents for the about page. A little tougher to do as the template makes everything so spread out. Could not figure out a clean way to get the floating table of contents to work. 

### Netlify Setup

Set-up was a breeze using the free plan. Netlify can connect directly to the GitHub repository and enable CI/CD based on pushes to the main branch. Free custom names are also available in the netlify.app space. Additional setup can be done to enable fully custom vanity URLs.

### References

Miller, Liz. 2023. "Portfolio Power-Up: Elevate Your Technical Brand with Hugo". 2023. https://join.learnrobotics.org/hugoconf-2023-training  \
