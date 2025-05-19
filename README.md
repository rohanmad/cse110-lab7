1) I would put the automated tests within a Github action that runs whenever code is pushed, as it is the best for code development, allowing us to quickly identify bugs and maintain code quality across team members. It's easiest to review pull requests that have the tests automatically run on them, rather than manually running tests locally, and running them after development is finished. <br/>

2) No, I would not use an end to end test to check if a function is returning the correct output.<br/>

3) Snapshot takes a quick snapshot of the page without reloading it or doing a full navigation. It checks if the HTML to see if it is valid and semantic, which is helpful to determine accessibility of the website. The navigation mode simulates a complete page reload, and provides a overview of the general performance of the website, including speed and load times, and also provides general diagnostics as to how the website can be improved further. <br/>

4) Based on the Lighthouse results, there are a few things we can do to improve the CSE 110 shop site. First, we can include a `<meta name = "viewport">` tag, which will not only optimize the app for mobile screen devices, but will also prevent a 300 millisecond delay to user input. 
   
   The website can also be improved by adding a meta description. A meta description will make sure our website is optimized to basic search engine optimization standards. This will allow users to find our website easier. 

   Lastly, we can optimize the size of the images on our website to save some storage. Since the image we have stored is larger than the actual image displayed, we can resize them to save storage and make the website more optimized.


