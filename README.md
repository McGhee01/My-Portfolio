# My-Portfolio

Strategies Used:

<!-- Used In CSS -->
In the Body section of my CSS work, I made my backfround using the background-color and selected gray as my desired color.

body {
    background-color:gray;
   
  }

 First, chose images from the Internet and from my Google Photos. Next, I acquired a image adress from each picture I wanted to use for my Portfolio. To make all pictures the same size, I changed the width by using the img {width} method and chose 800px as my desired size. Finally, to make one single picture bigger than the rest, I added a code where by using the # and the name of the class desired to enlarge only one singular picture. Therefore, one picture was 800px and the remaining pictures were 700px.

 img{
    width: 700px;
}
#Myself{
    width:800px;
}

 For my navigation to be created and spread across the page, I used the display: inline code via listed items. As seen in my style.css:

 li {
    display: inline;
}

 To make all pictures align to the center of the page, I simply used .CenterLinks from my class in my index.html and wrote teh code for the margin to auto and text-align to center as seen:

 .CenterLinks{
    margin:auto;
    text-align: center;
}

Padding was used to ensure that the pictures will not stay along the left side of the portfolio. The padding calculatoins is so the pictures will be shown in the middle of the page.

.Padding {
    padding-top: 50px;
    padding-right: 30px;
    padding-bottom: 50px;
    padding-left: 80px;
  }

  Link to Page To Update Navbar via Commented Code On index.html and style.css files:
  https://www.w3schools.com/howto/howto_css_topnav_equal_width.asp