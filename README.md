#Homework #2

The purpose of this homework assignment is to get familiar with writing json objects and working with git and GitHub

https://classroom.github.com/assignment-invitations/407b7322e70319536d92ae2b6f45909e

##Create a json Object of Yourself
You will create a json object that will be used to pass information to an about me page.

Your json object must include:
- First Name
- Last Name
- Some image of your choosing
- One array

It is up to you what you include in your json beyond these requirements. An example is shown below that incorporates each of the above requirements.

example.json
```json
{
    "firstName":"James",
    "lastName":"Getrost",
    "age":20,
    "picture": "https://pbs.twimg.com/profile_images/634798028277190656/dJtsX-0E.jpg",
    "nickNames": [
        {"nick": "Jim"},
        {"nick": "Ogre"}
    ]
}
```

##Get Your JSON Object
Get the url for your JSON file after committing it to GitHub. View your JSON file on GitHub and click on the raw button that will show you the plain json. Copy the url for this raw JSON and insert it into your javascript file.

```javascript
$.getJSON("your_url_here", function(data) {
    //your json object will be stored in data
}
```

##HTML and CSS
Customize your page with extra html and css. Make it unique to you.
