# Football Lovers
-----
This site is aimed primarily at employees and all sorts of professionals who want to relieve some stress after work and meet new people while playing football. User of this website will be able to find all the information about football lovers: mision statement, meeting times, pricing, social media and a sign up form.

pic responsiv

-----
## Features

-----
* Navigation

    - At the top of the page shows the group name in the right corner: FOOTBALL LOVERS.
    - The navigation links are to the left: home, gallery and sign up which links to different pages. This document consists of three pages.  
    - The navigation font contrasts with the background
    - The navigation makes the different pages of the website easy to find. 

navigation pic

-----
* The Header

    - The header shows the name of the group and the places where it be played football. It contrasts with the background.
    - The background image gives also information, which mision statements the group has.  
    - The text provides the user information about what the group is.

header pic

-------
* The be part of us section

    - This section explains the users what can they expect of the group: relax, meeting new friends, drinks and food and option to play football in summer and in winter.

be part of us pic

-----
* The meeting times section

    - give Information about places where the games take part, about pricing and meeting times. 

meeting times pic

-----
* The social media / contact section

    - By contact us section user can get in touch with the group
    - By clicking on the links facebook , tweeter, instagram or youtube the user can access to our social media information. 

pic contact us social media

--------------
* The gallery page

    - Here users can find different images of old meetings
    
pic gallery page

--------------
* The sign up page

    - Here users can sign up to Football Lovers.
    - The form collects first name, last name and email address. 
    - Users can choose by clicking on the radio buttons which district they prefer for playing.
    - The sign up form gives the user the ability to sign up to join to Football Lovers.

pic sign up page

--------------
## Testing
--------
* I tested that this page works in different browsers: chrome, firefox, safari.
* This is a responsive project, it looks nice and functions on all standard screen sizes using the devtools device toolbar.
* Navigation, Header, be part of us section, contact us gallery page and sign up page are readable and easy to understand.
* The form works, requires entries in every field, only accept corresponding values vor name and email
* The radio button works as expected.
* Let's play button works 

### Bugs
#### solved bugs
- When i was coding i realized that my css dont have any effect by styling.
- This was because i didnt pay attention at the syntax. i wrote #hero zoom instead #hero-zoom
- I add the missed "-" and solved my problem 
### Validator Testing
- HTML
    - No errors were returned when passing through the official W3C validator. 
- CSS
    - No errors were returned when passing through the official (Jigsaw) validator.
- Accessibility
    - I confirmed that the colors and fonts chose are easy to read and accesible by running it through lighthouse in devtools.

pic access

#### Unfixed Bugs
No unfixed bugs.
## Deployment
-----
- The site was deployed to Github pages as follows:
    - Choose the right reposotory in Github
    - From the source section drop down menu, select deploy from a branch.
    - By branch select main and click by save
    - A few minutes late the page provided the link to the completed website
## Credits
-----
### Content
- For the code of this project i used as template the Love Running Project provided by Code Institute
### Media
- The image in the header was taken from pexels.







**September 1 2021:** Remove `PGHOSTADDR` environment variable.

**July 19 2021:** Remove `font_fix` script now that the terminal font issue is fixed.

**June 10 2021:** Added: `font_fix` script and alias to fix the Terminal font issue

**May 10 2021:** Added `heroku_config` script to allow Heroku API key to be stored as an environment variable.

**October 08 2020:** Additional large Gitpod files (`core.mongo*` and `core.python*`) are now hidden in the Explorer, and have been added to the `.gitignore` by default.

**September 22 2020:** Gitpod occasionally creates large `core.Microsoft` files. These are now hidden in the Explorer. A `.gitignore` file has been created to make sure these files will not be committed, along with other common files.

**December 2019:** Added Eventyret's Bootstrap 4 extension. Type `!bscdn` in a HTML file to add the Bootstrap boilerplate. Check out the <a href="https://github.com/Eventyret/vscode-bcdn" target="_blank">README.md file at the official repo</a> for more options.

------

## FAQ about the uptime script

**Why have you added this script?**

It will help us to calculate how many running workspaces there are at any one time, which greatly helps us with cost and capacity planning. It will help us decide on the future direction of our cloud-based IDE strategy.

**How will this affect me?**

For everyday usage of Gitpod, it doesn’t have any effect at all. The script only captures the following data:

- An ID that is randomly generated each time the workspace is started.
- The current date and time
- The workspace status of “started” or “running”, which is sent every 5 minutes.

It is not possible for us or anyone else to trace the random ID back to an individual, and no personal data is being captured. It will not slow down the workspace or affect your work.

**So….?**

We want to tell you this so that we are being completely transparent about the data we collect and what we do with it.

**Can I opt out?**

Yes, you can. Since no personally identifiable information is being captured, we'd appreciate it if you let the script run; however if you are unhappy with the idea, simply run the following commands from the terminal window after creating the workspace, and this will remove the uptime script:

```
pkill uptime.sh
rm .vscode/uptime.sh
```

**Anything more?**

Yes! We'd strongly encourage you to look at the source code of the `uptime.sh` file so that you know what it's doing. As future software developers, it will be great practice to see how these shell scripts work.

---

Happy coding!
