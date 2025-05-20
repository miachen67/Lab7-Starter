### Name(s): Mia Chen
**1) Where would you fit your automated tests in your Recipe project development pipeline?**
Within a Github action that runs whenever the code is pushed. Automation testing are where scripts are written to automatically test software based on certain events, such as code getting pushed to a remote repository. Here, Github action is a tool that can ensure any new code that is pushed to the repo must pass the automated tests before it can be merged with main. 

**2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)**
No, unit testing would be more suitable for this.

**3) What is the difference between navigation and snapshot mode?**
Navigation mode loads the page and analyzes the overall performance upon the load; it can't analyze interaction or changes in the content. Snapshot mode analyzes the page in its current state and can analyze accessibility issues that or more complex but cannot provide overall performance metrics or analyze changes to the DOM tree. 

**4) Name 3 things we could do to improve the CSE 110 shop site based on the Lighthouse results.**
(1) We could include a meta description in the HTML code to improve search engine optimization. 
(2) Include a lang attribute to specify the primary language for this website, improving accessibility.
(3) Include a viewport meta tag to improve the user experience on smaller-screen devices and also preventing a 300ms delay upon a tap. 

