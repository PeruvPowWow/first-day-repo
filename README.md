# first-day-repo

Google FU Homework

Why cant i push or pull from github repo after I updated macOS?
1. If you cant push or pull to your github repos then it may have something to do with the ssh. You can install openssh from Homebrew to update the default ssh. You can also use a freshly sourced terminal as well

What syntax do i use for switching cases
2. The syntax would be git switch

How do I make cool hover effects in CSS?
3. This would be done in the CSS file and this is one of the ways you can write it:
#nav a:hover{ 
    transition: ease-in-out all .4s; 
    -moz-transition: ease-in-out all .4s;
    -webkit-transition: ease-in-out all .4s;
    background-color:#000000;
    color:#FFFE41;
    text-decoration:none;
    font-weight:bold;
}

What does this error code mean? (Put in code)
4. It looks like we are running into a CORS issue and have to set up the correct option which is mainly origin or credentail
https://stackoverflow.com/questions/20035101/why-does-my-javascript-code-receive-a-no-access-control-allow-origin-header-i


The function for creating new buttons is not working with on.click listener?
5. We can change the onclick event of an element with jQuery withouit running the new function with:
$("#id").attr("onclick","new_function_name()");

Why is my data no being appended when I have made an AJAX call to an API endpoint?
6. It looks like you dont have to use JSON.stringify() to convert object to string. the data passed to $.ajax must be an object and not JSON. 

Go to Mozilla and type in what is the preferred syntax for .forEach
7. Looks like it is forEach()

How can I change the array of numbers from this to this?
8. I can sort this by  for arr.sort()

Why are my animations made in Chrome not working in Firefox?
9. Make sure to either use Firefox in Safe Mode or Firefox Developer Edition

I created a function that is used for a loop and when set an amount of time the console logs it "undefined"
10. One solution would be to using let instead of var and if we want to move the members to HTML we need to use += to contenate with the previous string not =