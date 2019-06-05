     
 # README.md
# Brief for Poco Harum 

This is a website that has been given a complete facelift.  It has a bright, sassy appearance while capturing the "Swinging 60s" mood! 
I think I have provided a UX experience targeted at fans but also to encourage new visitors to the site.
The Audience has a clearer understanding of where they can access information in a simplified user-friendly way.

##  My sales pitch.

### UX

1) This website is for a target audience who appreciate the music and want to follow an iconic band from the 1960s. The fans both old and new
are interested to know what is happening performance wise both at local venues, national and on tour.  The band are keen to keep the audience 
informed with their activities.  

3) This website provides the means to be able to access the information needed in a user friendly fashion and also
provide access to videos and music samples from the past. 

4) I drew a couple of quick diagrams and then transferred to Balsamiq for wireframe mockups.
    I created several wireframes which include website / i-pad / i-phone and responsive.


### Credits:

My inspiration and Images come from:-

1) website frameworks / structures 
   i)   My Whiskey and CV projects in 
  ii)   Interactive front end modules-The Code Institute - so credit goes to the authors for my             inspiration from these 
        projects and I thank them. 
  iii)  All the support and encouragement from the Slack community and my Mentor, for helping me           source information and implement my website.
        They know who they are.  Much appreciated and valued.

2) Cheesecakewebsite - http://www.cheesecakeband.com

3) Hayley Shafer - https://code-institute-solutions.github.io/StudentExampleProjectGradeFive/

4) Wikipedia - https://en.wikipedia.org/wiki/Procol_Harum

3) Images and information plus links are sourced from various "Poco Harum" websites: http://www.procolharum.co.uk
http://starling.rinet.ru/music/procol.htm

    i)    Bert Sarco Express image photography
    ii)   Beyond the Pale website
    iii)  Beyond the Deep website
    iv) Audio and visual links to YouTube / Spotify / Amazon websites
    
    

    
## Features

  1) I use bootstrap which allows my website to be responsive from a mobile 
    first approach right up to a desktop.  
    To refresh my browser I used a hard command + shift + R on my Mac.to update my 
    website changes.  This is imperative in order to refresh the page fully and 
    update the changes made as I work through my project.
    
    2) As I work on my project, I make sure to push to github frequently - I note that I am able to     fix various bugs along the way for example, re-aligning social-links to display in-line instead
    of in a column and in two rows instead of one to accomodate all icons on display. This 
    seems to be the difference between my cloud9 local and github - small adjustments
    can be made to keep things in check.
    
    3) I use "font awesome icons" for my social icons increasing the size
    ensures user ability with one finger specifically on mobile first; A user-friendly approach.
    Example html. 
    <div class="display-inline col-sm-4">
                                <h5 class="uppercase general-sub">Social Media</h5>
                                <ul class="social-links">
                                    <li><a target="_blank" href="facebook"><i class="fab fa-facebook-square"></i></a></li>
                                    <li><a target="_blank" href="twitter"><i class="fab fa-twitter-square"></i></a></li>
                                    <li><a target="_blank" href="linkedin"><i class="fab fa-linkedin"></i></a></li>
                                    
CSS styles for Social links with hover effect and ease-in-out:
.social-links li a i {
    width: 30px;
    height: 30px;
    padding: 12px 0;
    border-radius: 50%;
    font-size: 14px;
    line-height: 7px;
    text-align: center;
    color: #fafafa;
    background: #8f8f8f;
    transition: all 0.35s ease-in-out;
    -moz-transition: all 0.35s ease-in-out;
    -webkit-transition: all 0.35s ease-in-out;
    -o-transition: all 0.35s ease-in-out;
}

.social-links li {
    display: inline;
}

.social-links li a i:hover {
    background: #ce5a2b;
}

#footer-details {
    margin: 25px;
}

I had an issue with my file structure.  I had my images in the css folder instead of the separate images folder in the main assets folder and my css folder was not properly represented inside my assets folder,  so in order to remedy this, I learned that File Paths are like directions. I direct the files where to look for other files within my file structure.

### So lets imagine I have this file structure - see example:
-- top directory: *root* contains html file(s) and README.md. It also contains an *assets* directory/folder.
---- *assets* directory: contains 2 more directories: *css* and *images*
------*css* directory contains a *main.css* file.
------*images* directory contains all my images. 

i) File names consist of names like *picture.jpg*. 
ii) File paths are like directions. I tell the files where to look for other files within the file structure.
iii) Html files are always in the root directory, (the top one). So I tell my html where to find the styles in my css file, (_assuming one has this file structure_ I have to say: `assets/css/style.css`

This means I am saying to the html file: "from the root directory (where I start from in a html file), I must first look for the *assets* folder(`assets/`), then look for the *css* folder(`assets/css`), and then look for the file named *style.css* (`assets/css/style.css`).

### But what happens if I need to add links to my images in my *main.css* file? Well then the links *to* the image files *from* the css file are different!

Just like giving directions to the supermarket, the directions (path) is different depending on where one starts from.

i)So for image links from a css folder one says something different, for example: `../images/pic1.jpg`
ii)Because the css file is inside a *css folder*, _it cannot see anything but what is in that folder_, there are no other folders inside it.

iii) So the first instruction `../` says *come up out of the current folder* or another way to put it is *move BACK one folder from this one* which in this case would move one up out of the css folder and into the assets folder. From there the file path can see the images folder so the rest of the path `../images/picture.jpg` points the way to the image.

I include a good video to explain file paths further, and to learn the difference between an absolute file path and a relative one: https://www.youtube.com/watch?v=ephId3mYu9o.  
               
                                    
    
------
## UX process
In this section I provide an insight into the UX process, focusing on who this website is for, what it is that they want to achieve and how this project is the best way to help them achieve these objectives.

### I include a list of user stories to illustrate this process, with the following general structure:

#### Some Actions to illustrate how as a user type, I want to perform an action, so that I can achieve a goal:-

i)I use a "navbar collapse" for a responsive website. example:
<div class="collapse navbar-collapse" id="navbarNavDropdown">
                    <ul class="navbar-nav mr-auto">
This provides a clean and uncluttered responsive website with the basic essential information which can be accessed via the 3-bar menu at the top right corner on mobiles and i-phones.  This is so the user can toggle easily with their right hand or both.
                       
ii) For ipads, laptops and desktops I have incorporated a traditional dropdown menu for ease of use.  I also use a nav bar dropdown menu using anchor links to navigate up and down the web-page:
                         <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                        </a>
                            <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
                                <a class="dropdown-item" href="#navbarDropdownMenulink">Home</a>
                                <a class="dropdown-item" href="#about-header">About</a>
                             </div>                                                                                                        
In order to create an nostalgic atmosphere, I build a website invoking the mood and make available  the latest "happenings".  I add brightly coloured sections and images inspired by the Procol Harum era incorporating cover albums, complete with videos and audio for enjoyable listening.

** to do** I build  a modal to create a "sign up" form to a newsletter. 
(W3 schools.com: Example )
<div class="container">
  <h2>Sign up</h2>
  <!-- Trigger the modal with a button -->
  <button type="button" class="btn btn-info btn-lg" data-toggle="modal" data-target="#myModal">Open   Modal</button>
     
2) ### I use a nav bar with dropdownmenu with anchor links to navigate the website sections.
     
3) ### To organise information from other websites - I redirect links to target websites without leaving the current one. I also create social links and "callout lead" to draw attention to their new Facebook page encouraging users to follow them on Facebook.

4) ### With the boys in the contemporary 21st century. 
They like to view the pictures and be drawn into the nostalgia of the past; another world and at the same time be brought up to date with what is happening. Catch the music from the era by listening to audios and be guided on where to find Procol Harum’s music and research info and lyrics quickly and easily via search links to other websites.

The look and feel of the website reflects the music and the era through audio / video media, and is paramount. The quick access to relevant content is also a must have.

**This section is where I share links to wireframes, mockups, diagrams etc. I created as part of the design process. These files should themselves either be included in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser.**still to add**

## Features
In this section below, I cover different aspects of my project, incorporating some of the features I mentioned above.

## User Stories
README.md continued...
## Procol Harum 1960s Band User stories:
1. John and his wife Jane, met in the heady summer of 1967 and remember well their time on that warm far off sunny day when they met for the first time at Glastonbury. They both remember that feeling of natural love and freedom to do what they want, and listen to the music that reflected their carefree mood. “Procol Harum” was a particular favourite of theirs; never failing to draw them back to that wonderful and swinging time of their early lives. This couple who of course, went on to marry each other, are major fans of ## Procol Harum ## and want to continue their love affair with the period and the band. They want to find a website that invokes the mood and be able to find out what is happening with the boys in the contemporary 21st century. They like to view the pictures and be drawn into the nostalgia of the past; another world and at the same time be brought up to date with what is happening. Catch the music from the era by listening to audios and be guided on where to find Procol Harum’s music quickly and easily via search links to other websites.
### "The look and feel of the website reflecting the music, the era via videos and other media, is paramount. The quick access to relevant content is also a must have".

2. Jack and his young group of 21st century band leaders are looking for modern contemporary music with a twist. Procol Harum is on their “inspiration list”. He and his peers are looking to soak up as much of the ethos of Procol Harum and find out what makes them tick and their music so evocative. They like rythmn and blues and harmonies as well as soft rock. They want to be able to navigate their way through the information on offer on the website without having to leave the site altogether. # Having the site as a base for searching all things “P H” suits them. They are busy band players and want to access information quickly and easily.

3. Another couple James and his long term partner Storm, have been together since the 1970s and own and work hard on their farm. They live an idyllic life with no children, but plenty of chickens, ducks, horses, goats, four dogs and two cats. They love to listen to the P H music and keep up with the band. They follow them religiously and like to keep track with the “happenings”. Easy access navigation Bar and clicking their way around, encourages them to explore. Neither couple are particularly computer savvy but can find their way around an easy user friendly website.
4. Andy is getting married soon and wants to find a band that incorporates the music of Procol Harum for his wedding and also wants to book his surprise honeymoon to Switzerland. He and his fiancé dream of seeing P H in concert in idyllic surroundings reflecting their soft rock and baroque music. They want to reserve their place and find out where to go and what to do. There are two concerts and they will be following their heroes to each destination. Information is available on the website via the links to find out what where and how to go about making this a reality for
them. A new facebook page regularly updated has been given pride of place on the home page to all fans to follow and keep them in the loop.

### Conclusion
Making this website as user friendly as possible is key as many of the legions of fans are of a certain age where computers were not necessarily a part of their lives. Hence also, the site should appeal to young and professionals alike. Those who have a deep appreciation of real music and musicians, should be able to feel comfortable using it, without feeling it is a stuffy place for a past generation. 
Users should be able to quickly click and find relevant content.

On the other end of the spectrum older generations daunted by technology, are made to feel as comfortable as possible and want to return time and again to a friendly atmospheric place. The objectiive of this site is to make the user feel at home. 

#### Atmosphere/Mood - a website for everyone who loves the era of music from an iconic 1960s Band
Soft furnishings, warm light, a little bit of psychedelic. This website should appeal to a wide and diverse age group without excluding anyone. Target audience 20s and 30s right up to those in their 70s.


### Existing Features

#### Feature 1 - allows users X to achieve Y, by having them fill out Z
...
For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

Features Left to Implement
Another feature idea
Technologies Used
In this section, I mention all of the languages, frameworks, libraries, and any other tools that I have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

### HTML audio tag
I used this as an audio base for listening to a sample of Procola Harum's music:- 
w3schools.com
Well organized and easy to understand Web building tutorials with lots of examples of how to use HTML, CSS, JavaScript, SQL, PHP, Python, Bootstrap, Java and XML.
-----
<audio controls>
  <source src="horse.ogg" type="audio/ogg">
  <source src="horse.mp3" type="audio/mpeg">
  Your browser does not support the audio tag.
</audio>
https://www.w3schools.com/tags/tryit.asp?filename=tryhtml5_audio
-----
### Embed Video 
https://www.w3schools.com/html/html_youtube.asp
(w3schools.com)
HTML YouTube Videos
Well organized and easy to understand Web building tutorials with lots of examples of how to use HTML, CSS, JavaScript, SQL, PHP, Python, Bootstrap, Java and XML.

  i)  Upload the video to YouTube
 ii)  Take a note of the video id
iii)  Define an <iframe> element in your web page
 iv)  Let the src attribute point to the video URL
  v)  Use the width and height attributes to specify the dimension of the player
 vi)  Add any other parameters to the URL (see below)

I use this on my website to showcase examples of videos from the era of Procol Harum such as 
"Whiter Shade of Pale"


JQuery
The project uses JQuery to simplify DOM manipulation.
Testing
In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

### Contact form:
Go to the "Contact Us" page
Try to submit the empty form and verify that an error message about the required fields appears
Try to submit the form with an invalid email address and verify that a relevant error message appears
Try to submit the form with all inputs valid and verify that a success message appears.
In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

### Deployment
This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

To deploy the website - I commited to github and started the process of pushing
to git hub.  I git add . ; git -m "commit content"; git status; git push to remote. 
Many times due to local issues with cloud9 not being compatible with my server, I had to reset to previous commits. I was unable to preview and as a result made many mistakes and unnecessary changes.
Fortunately I am able to git log then set to a previous commit on github.

**In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

Different values for environment variables (Heroku Config Vars)?
Different configuration files?
Separate git branch?
In addition, if it is not obvious, you should also describe how to run your code locally.





    
