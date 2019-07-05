
 #### Migration to AWS - Cloud 9 - My UX experience
 
 I migrated to AWS Cloud 9 just over a week ago.  I did not find the process as smooth going as expected.
 The platform does not appear to be a good UX experience so far. Apart from logging out every 30 minutes, it also appears to be a bit hard to navigate around once you are logged out and having to log in again.
 I think there should be a lot more work for it to be a more user friendly experience for developers and students alike. 
 Unfortunately is frought with difficulties in my opinion at present.
 Resolved: YES - Successfully migrated.

#### alternative paralex image on home page 
The below image was supposed to appear below the first image as an *alternative* to the first image above on the home page. 
However, I have not resolved this one yet. 

Resolved: YES

.container-fluid .callout-container .media img {
    content: "";
    display: block;
    position: fixed;
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    z-index: -10;
    background: url("../images/backstageband.png") no-repeat center center;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
    background-attachment: scroll;
}

#### Overflow Home Page - Bootstrap positioning

Had a problem with overflow on my page at the end of my project just before submitting:
The url address is below:

* {
  background: #000 !important;
  color: #0f0 !important;
  outline: solid #f00 1px !important;
}

https://getbootstrap.com/docs/4.3/utilities/display/#hiding-elements

https://code-institute-room.slack.com/files/UF94247RB/FJXTZFPRA/-.js

Resolved: NO.

#### Audio Sound Cloud - Upon review I try to fix some of the following directly before submitting my project.  The results are below:

I did try to improve the below embed code by adding the CSS properties to Main CSS.
*Some of the embads have now disappeared.

html-
<iframe="audio" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/168407406&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>

main css-
.audio {
	width: 100%;
	height: 166px;
}
Resolved: NO

#### Website  and Search Buttons:

I have not resolved all the buttons - Most are disabled as I am not sure where to direct them except to "target_blank"

Resolved: NO 

#### Emailers
I did not resolve this one as I did not know how to write the error message or the thank you message.
Resolved - NO

#### Forms
I did not know how to set up the following:
<form action="/action_page.php">
Therefore I was unable to send a thank you message.

#### Socia Links
My social links are disabled
I am also aware of the square that shows up when hoverig over - am not sure what is causing this.  But it was pointed out to me during review.

#### Layout issues - UNRESOLVED

I admit that I do have unresovled layout issues and that my audio section has not worked the way I have wanted it too.  I have left everything in place in this audio section on the first page but since I am still learning I expect to be able to resolve these with time, experience and practise as I progress through the course.
I am also aware of my responsive issues and some unwanted white spaces due to overflow.  I have tried to fix these but have caused other probelems else where. I am now submitting this now. 
I am therefore aware of some of these issues.  Examples: Centering, hidden columns  and overflow issues on home page.
container / row / column Grid issues - I am aware that I have not yet completely mastered this yet.

    --the End --

