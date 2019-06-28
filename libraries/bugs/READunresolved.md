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

