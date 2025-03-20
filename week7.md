# Week 7 - Learning Journal

## Learning Activities & Resources
This week I continued my previous PHP learning and started a small website called "Green Planet" ** to show the PHP skills I need to master in Prac 7. The main concern is:
1. **echo Output ** : Print out HTML tags and variables dynamically to bring some changes to the page.
2. **if/else judgment ** : Made a small function to display different greetings according to the current time, feel very fun;
3. **for/while/foreach loop ** : A list of environmental problems (for) is listed on the page, a reciprocal loop (while) is given, and environmental tips are randomly displayed with the foreach loop;
4. ** Custom function ** : wrote a 'calcCarbonEmission()' function to simulate the calculation of how much carbon dioxide will be produced by a car driving a distance, and a 'getRandomEcoTip()' for random environmental protection suggestions;
5. **include** : Draw the head and tail pages into 'header.php' and 'footer.php', and modify the website structure more convenient later.

In the process, I mainly read the official PHP documentation and some short examples to understand the parameter passing of functions, how to get the time through date(), array_rand(), and so on. Also deployed on the **Google Cloud**, learned basic Apache configuration, open ports, and upload files.

## Estimated Hours
- ** It took about ** 3.5 hours in total:
- **1.5 hours ** local code writing and test loop/judgment;
- **0.5 hours ** Google Cloud VM (install LAMP, set firewall), during which the port was not open;
- **0.5 hours ** Upload and deploy my "Green Planet" website;
- **1 hour ** Further debug CSS, try different colors, make the head and tail green background, feel very environmentally friendly atmosphere.

## Content Insights
- **echo + if/else** : These basic syntax is the core operation of PHP, most dynamic websites are inseparable from the condition and output;
- **for/while/foreach** : Different loops have their own uses. I found the foreach operation array to be the most intuitive and suitable for counting scenarios.
- ** Function ** : Pass parameters to the function, which can call the same logic in different pages, which is conducive to maintenance and reuse. For example, my function for calculating carbon emissions only needs to be written once, even if I want to add the type of electric vehicle in the future, that is, change a switch branch;
- **include** : Especially useful, do not have to repeat the header or footer in every page, the website structure is much clearer.

## Career/Employability/Learning Insights
- **PHP** is still a very common backend language in the industry, for example, PHP is often written in **WordPress** customization.
- Hands-on configuration of Apache** * on the cloud server, opening port 80, uploading files using SSH, also made me feel the importance of connecting with the actual online environment, rather than just staying in the state of local XAMPP;
- Using an interesting topic (such as "environmental protection") as an example helps me get more involved in the situation, more motivated to learn, and more ideas about how technology can be applied to the real world than just looking at random examples.

---

**Reflection**
To be honest, this "Green Planet" project let me have a more intuitive understanding of PHP, but also let me realize that writing a multi-page website is not difficult, the key is to master the file structure and include skills. What bothers me most is the color conflict of CSS - white text and white background. Fortunately, the final debugging was successful, and I also practiced the 'nano' editor and the basic command line of Linux. These practices have given me a clearer idea of the complete process of deploying a small dynamic website.
I plan to improve the project next week, such as adding a simple "comment" or "register" page, using more PHP features to make the site more complete, and also laying the foundation for more complex assignments or projects in the future.