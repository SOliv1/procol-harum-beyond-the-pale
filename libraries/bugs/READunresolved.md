#### unresolved alternative paralex image on home page 
The below image was supposed to appear below the first image as an *alternative* to the first image above on the home page. 
However, I have not resolved this one yet.

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

#### Overflow Home Page

Had a problem with overflow on my page at the end of my project just before submitting:
The url address is below:

* {
  background: #000 !important;
  color: #0f0 !important;
  outline: solid #f00 1px !important;
}



https://code-institute-room.slack.com/files/UF94247RB/FJXTZFPRA/-.js

Resolved:?  yes/no