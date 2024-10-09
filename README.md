html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet"
        href="https://maxst.icons8.com/vue-static/landings/line-awesome/font-awesome-line-awesome/css/all.min.css">
    <link rel="stylesheet" href="index.css">

</head>

<body>
    <div id="header">
        <div class="container">
            <nav>
                <img src="logos.png" class="logo" style="width:135px ;height: auto;">
                <ul class="list">
                    <li><a href="#">Home</a></li>
                    <li><a href="#">About Me</a></li>
                    <li><a href="#">Service</a></li>
                    <li><a href="#">Portfolio</a></li>
                    <li><a href="#">Contact</a></li>
                </ul>
                 <div class="navicons">
       <i class="fas fa-times"></i>
        <i class="fas fa-bars"></i>
     </div> 
        </nav>
        <div class="header_text">
            <p>Web Developer</p>
            <h1>Hi,I am<br> <span>Sajjad Hussain</span> <br>
                <weight>from Pakistan</weight>
            </h1>
        </div>
    </div>
    </div>

    <div id="about">
        <div class="container">
            <div class="row">
                <div class="row-1">
                    <img src="pic.sajjad.jpg">
                </div>
                <div class="row-2">
                    <h1>About Me</h1>
                    <p>I am sajjad hussain from gilgit baltistan .I am doing a Software Engineering Now in Mirpur
                        University AJK.And i also want to a highly motivated and enthusiatic student with a strong pa
                        ssion for wen development , seeking a web development internship ar a reputable software house o
                        gain hands-on experience and contribute to real-world projects.</p>
                    <div class="tab-titles">
                        <p class="tab-links link-active" onclick="opentab('skills')">Skills</p>
                        <p class="tab-links" onclick="opentab('experience')">Experience</p>
                        <p class="tab-links" onclick="opentab('education')">Education</p>
                    </div>
                    <div class="tab-contents active-tab" id="skills">
                        <ul>
                            <li> <span>Web developer</span><br>HTML,CSS,Javascript,Bootstrap,c++ </li>
                            <li>
                                <span>Communication</span><br>Communication with client
                            </li>
                            <li>
                                <span>Creativity</span><br>Thinking Level Best
                            </li>

                        </ul>
                    </div>
                    <div class="tab-contents" id="experience">
                        <ul>
                            <li>
                                <span>Project</span><br>Food website, Spotify website etc
                            </li>
                            <li>
                                <span>Volunteer work</span><br>Mobrite Company
                            </li>

                        </ul>
                    </div>
                    <div class="tab-contents" id="education">
                        <ul>
                            <li>
                                <span>Pre-Engineering</span><br>F.G Boys degree college skardu
                            </li>
                            <li>
                                <span>Software Engineering</span><br>UET Mirpur AJK
                            </li>

                        </ul>
                    </div>
                </div>

            </div>
        </div>
        <!------services-->
        <div id="services">
            <div class="container">
                <h1 class="sub-title">My Services</h1>
                <div class="services-list">
                    <div>

                        <h2>UX/Design</h2>
                        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ex esse possimus pariatur, saepe
                            deleniti magni dolorum nesciunt fuga, laudantium beatae a architecto magnam incidunt, quo
                            distinctio. Vel vitae unde optio!</p>
                        <a href="#">Learn more..</a>
                    </div>
                    <div>

                        <h2>Web developer</h2>
                        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ex esse possimus pariatur, saepe
                            deleniti magni dolorum nesciunt fuga, laudantium beatae a architecto magnam incidunt, quo
                            distinctio. Vel vitae unde optio!</p>
                        <a href="https://www.youtube.com/watch?v=">Learn more..</a>
                    </div>
                    <div>

                        <h2>Content Writer</h2>
                        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ex esse possimus pariatur, saepe
                            deleniti magni dolorum nesciunt fuga, laudantium beatae a architecto magnam incidunt, quo
                            distinctio. Vel vitae unde optio!</p>
                        <a href="#">Learn more..</a>
                    </div>

                </div>
            </div>
        </div>
        <div id="portfolio">
            <div class="container">
                <h1 class="sub-title">My Work</h1>
                <div class="work-list">
                    <div class="work">
                        <img src="card3.jpeg">
                        <div class="layer">
                            <h3>UX/DEsign</h3>
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. </p>
                            <a href="#">click me</a>
                        </div>
                    </div>
                    <div class="work">
                        <img src="card3.jpeg">
                        <div class="layer">
                            <h3>WEb developer</h3>
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. </p>
                            <a href="#">click me</a>
                        </div>
                    </div>
                    <div class="work">
                        <img src="card3.jpeg">
                        <div class="layer">
                            <h3>content writer</h3>
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. </p>
                            <a href="#">click me</a>
                        </div>
                    </div>

                </div>
                <a href="#" class="btn">See More</a>
            </div>
        </div>
        <div id="contact">
            <div class="container">
                <h1 class="sub-title">Contact Me</h1>
                <div class="row">

                    <div class="contact-left">

                        <p><i class="fas fa-paper-plane"></i> hussainsajjad1010@gmail.com</p>
                        <p>
                            <i class="fas fa-phone-square-alt "></i> 03495736218
                        </p>
                        <div class="social-icons">
                            <a href="https://facebook/"> <i class="fab fa-facebook"></i>
                            </a>
                            <a href="#"> <i class="fab fa-twitter-square"></i>
                            </a>
                            <a href="#"> <i class="fab fa-instagram"></i>
                            </a>
                            <a href="#"> <i class="fab fa-linkedin"></i>
                            </a>

                        </div>
                        <a href="sajjad cv.pdf" class="btn btn2">Download CV</a>
                    </div>
                    <div class="contact-right">
                        <form>
                            <input type="text" placeholder="name">
                            <input type="email" placeholder="email">
                            <textarea type="message" rows="6" placeholder="your message"></textarea>
                            <button class="btn3" type="submit">Submit</button>

                    </div>
                </div>
            </div>
            <div class="copyright">
                <p>copyright.Sajjad Hussain made with <i class="fas fa-heart"></i> by easy Tutorial
                </p>
            </div>
        </div>
        <script src=" index.js">

        </script>
</body>

</html>
css
body {
    background-color: black;
    color: #fff;
}

* {
    margin: 0%;
    padding: 0%;
    box-sizing: border-box;
    font-family: sans-serif;
}

#header {
    width: 100%;
    height: 100vh;
    background-size: cover;
    background-position: center;
    background-image: url(nayma.jpg);
}

.container {
    padding: 15px 15px;
}

nav {
    display: flex;
    text-decoration: none;
    text-align: center;
    justify-content: space-between;
}

nav ul li {
    list-style: none;
    display: inline-block;
    margin: 13px 20px;
    color: #fff;
}

nav ul li a {
    text-decoration: none;
    color: #fff;
    font-size: 18px;
    position: relative;
    letter-spacing: 0.5;
}

nav ul li a::after {
    content: '';
    height: 3px;
    width: 0px;
    background-color: red;
    position: absolute;
    left: 0;
    bottom: -6px;
    transition: 0.3s;

}

nav ul li a:hover::after {
    width: 100%;
}

.header_text {
    font-size: 20px;
    margin-top: 30px;
    margin-left: 30px;
    line-height: 60px;
}


.header_text h1 {
    margin-top: 21px;

}

.header_text h1 span {
    color: rgb(154, 0, 0);
    margin-left: 12px;

}

.header_text h1 weight {
    margin-left: 70px;
}

.header_text p {
    font-style: oblique;
    font-display: 5px;
    color: chocolate;
}

/*.........about me!!!*/
.row {
    display: flex;
    padding: 34px 20px;
    gap: 55px;
}

.row-1 img {
    width: 335px;
    height: auto;
    border-radius: 18px;

}

.row-2 p {
    opacity: 0.7;
}

.tab-titles {
    display: flex;
    gap: 15px;
    margin-top: 8px;


}

.tab-links {
    font-size: 1.2rem;
    font-weight: 400;
    position: relative;
    margin-right: 50px;
    cursor: pointer;
}

.tab-links::after {
    content: '';
    width: 0px;
    height: 3px;
    background: red;
    left: 0;
    transition: 0.4s;
    bottom: -3px;
    position: absolute;
}

.tab-links.link-active::after {
    width: 50%;
}

.tab-contents {
    margin-top: 15px;
    display: none;

}

.tab-contents.active-tab {
    display: block;
}

.tab-contents ul li span {
    color: red;
    font-size: 19px;
    line-gap-override: 2px;
    padding: 10px;
    opacity: 0.9;
}

ul li {
    list-style: none;
    margin: 8px 0px;
    opacity: 0.8;
}

/*--------services*/
.sub-title {
    padding-left: 415px;
}

.services-list {
    display: grid;
    grid: 175px / auto auto auto;
    grid-gap: 30px;
    padding: 40px;

}

.services-list div {
    background-color: #262626;
    padding: 27px;
    font-size: 13px;
    font-weight: 300;
    border-radius: 15px;
    text-align: center;
    transition: background 0.5s, tranform 0.5s;
}

.services-list h2 {
    font-size: 20px;
    font-weight: 700;
    margin-bottom: 10px;
}

.services-list a {
    text-decoration: none;
    color: white;
    font-size: 1.2rem;
}

.services-list div:hover {
    background-color: #ff004f;
    transform: translatey(-10px)
}


.work-list {
    display: flex;
    justify-content: space-evenly;
    margin-top: 18px;

}

.work {

    position: relative;
    margin-top: 12px;

}

.work img {

    border-radius: 10px;

    width: 240px;
    height: 245px;

    transition: background 0.5s transform 0.5s;


}

.layer {
    border-radius: 10px;
    width: 100%;

    background: linear-gradient(rgba(0, 0, 0, 0.6), #ff004f);
    left: 0px;
    bottom: 0px;
    overflow: hidden;
    position: absolute;
    text-align: center;
    justify-content: center;
    padding: 0px 40px;
    flex-direction: column;
    display: flex;
    transition: transform 0.5s;
}

.layer h3 {

    font-weight: 500;
    margin-bottom: 18px;
}

.layer a {
    text-decoration: none;
    color: black;
    font-family: sans-serif;
    font-weight: 700;
}

.work:hover img {
    transform: scale(1.1);
}

.work:hover .layer {
    height: 100%;

}

.btn {
    text-decoration: none;
    color: #fff;
    font-weight: 500;
    margin-top: 35px;
    margin-left: 489px;
    display: block;
    width: fit-content;
    border: 2px solid rgba(91, 10, 10, 0.373);
    border-radius: 6px;
    transition: background 0.5s, transform 0.5s;

}

.btn:hover {
    background: #ff004f;
    transform: scale(1.1);

}

.contact-left {
    flex-basis: 35%;
}

.contact-right {
    flex-basis: 60%;
}

.contact-left p {
    margin-top: 48px;
    margin-left: 23px;
}

.contact-left p i {
    margin-left: 23px;
    color: #ff004f;
    font-size: 25px;
}

.social-icons {
    margin-top: 25px;
}

.social-icons a {
    text-decoration: none;
    color: #abaaba;
    margin-left: 34px;
    font-size: 25px;
    display: inline block;
    transition: transform 0.5s;
}

.social-icons a:hover {
    color: #ff004f;
    transform: scale(1.1);
}

.btn.btn2 {
    background: #ff004f;
    width: 105px;
    text-align: center;
    justify-content: left;
    margin-left: 48px;
    font-size: 14px;

}

.contact-right form {
    width: 100%;
}

form input,
form textarea {
    width: 100%;
    padding: 10px;
    background: #262626;
    color: white;
    margin: 8px 0px;
    margin-top: 15px;
    border: none;
    outline: none;
    font-size: 18px;
}

.btn3 {
    width: 70px;
    height: 23px;
    background-color: #ff004f;
    border: 1px solid #ff0000;
    border-radius: 6px;
    font-weight: 600;
    transition: transform 0.5s;
    cursor: pointer;
}

.btn3:hover {
    transform: scale(1.1);
}

.copyright {
    width: 100%;
    background-color: #262626;
    text-align: center;
    padding: 18px 0;
    margin-top: 10px;
    font-weight: 500;
    font-family: sans-serif;
}

.copyright i {
    color: #ff004f;
}

.navicons {
    display: none;
}

@media only screen and (max-width:600px) {
    #header {
        position: center;
    }

    .header_text {

        font-size: 16px;

    }

    .header_text h1 {
        font-size: 25px;
    }

    .navicons {
        display: block;
        font-size: 25px;
    }

    nav ul {
        top: 0;
        right: 0;
        background: #ff004f;
        position: fixed;
        width: 100px;
        height: 100vh;
        padding-top: 50px;
        font-size: 12px;
        z-index: 2;

    }

    nav ul li {
        display: block;
        margin: 25px;
        font-size: 12px;
    }

    .navicons {
        position: absolute;
        margin-left: 45px;
        top: 25px;
    }


}
js
var tablinks = document.getElementsByClassName("tab-links");
var tabcontents = document.getElementsByClassName("tab-contents");
function opentab(tabname) {
    for (tablink of tablinks) {
        tablink.classList.remove("link-active");
    }
    for (tabcontent of tabcontents) {
        tabcontent.classList.remove("active-tab");
    }
    event.currentTarget.classList.add("link-active");
    document.getElementById(tabname).classList.add("active-tab");
}


