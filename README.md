<head> <meta http-equiv="Content-type" content="text/html;charset=UTF-8"></head>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MVMT Physical Therapy</title>
</head>
<style>
    @import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@100;200;300;400;500;600;700;800;900&display=swap");

/* Global Styles */

* {
  font-family: "Montserrat", sans-serif;
  margin: 0;
  padding: 5;
  box-sizing: border-box;
}

body { 
  padding: px 0%;
  background: #f5f5f54d;
}

a{
  text-decoration: none;
}

/* Container Styles */
.container {
  display: flex;
  height: 89vh;
}
.main-wrapper{

  flex: 2;  overflow-y: scroll;
}
.side-bar{
  background: #faf9f9;
  flex: .3;
  padding: 40px;
  /* background-color: white; */
}

.side-bar ul{
  padding: 0 40px;
  list-style: none;
}

.side-bar{
  background: rgb(230, 230, 231);
}


@media only screen and (max-width: 900px) {
  .container {
    flex-direction: column;
  }
  .side-bar{
    background: #114;
    color: white !important;
  }
  .side-bar a{
    color: white !important;
  }
}

/* Navigation Menu Styles */

nav.nav-menu {
  width: 100%;
  background-color:#f1473e;
  padding: 10px;
}

nav.nav-menu ul {
  width: 100%;
  display: flex;
  align-items: center;
  list-style: none;
  font-size: clamp(.8rem, 1.2vw, 2rem); 
}

.nav-menu .nav-item {
  padding: 10px;
  transition: background-color 500ms ease-in-out;
}

.nav-menu .nav-item:hover {
  cursor: pointer;
  background-color: #f5f5f54d;
}

.nav-menu .nav-item a{
  text-decoration: none;
  color: white;
}


/* Main Content Wrapper Styles */
.main-wrapper {
  background: white;
}

section {
  margin-bottom: 50px;
}

section.head,
section.youtube-embed {
  text-align: left;
}

.button-link {
  display: block;
  margin: 20px 0 0 0;
  padding: 10px 25px;
  width: fit-content;
  background: #f1473e;
  border-radius: 0px;
  text-decoration: none;
  color: white;
  transition: 0.3s transform ease-in-out;
  text-align: center;
}

.button-link-red {
  display: block;
  margin: 20px 0 0 0;
  padding: 10px 25px;
  width: fit-content;
  background: #f1473e;
  border-radius: 0px;
  text-decoration: none;
  color: white;
  transition: 0.3s transform ease-in-out;
  text-align: center;
}

.button-link-blue {
  display: block;
  margin: 20px 0 0 0;
  padding: 10px 25px;
  width: fit-content;
  background: #003299;
  border-radius: 0px;
  text-decoration: none;
  color: white;
  transition: 0.3s transform ease-in-out;
  text-align: center;
}

.button-link-green {
  display: block;
  margin: 20px 0 0 0;
  padding: 10px 25px;
  width: fit-content;
  background: #326600;
  border-radius: 0px;
  text-decoration: none;
  color: white;
  transition: 0.3s transform ease-in-out;
  text-align: center;
}

h1 {
  font-size: 30px;
  color:white;
  text-align: center;
}

h2 {
  margin-bottom: 10px;
  margin-top: 10px;
  text-align: left;
  font-size: 30px;
}
h4 {
  font-size: 25px;
  font-weight: bold;
  color: #ffffff;
}

ul{
  padding-left: 30px;
  }
  
  .side ul{
    text-align: justify;
    margin-bottom: 10px;
    line-height: 1.5rem;
    font-family: "Cormorant SC", sans-serif;
    font-size:30px;

  }

  ol{
    padding-left: 40px;
    }
    
    .side ol{
      text-align: justify;
      margin-bottom: 10px;
      line-height: 1.5rem;
      font-family: "Cormorant SC", sans-serif;
      font-size:30px;
  
    }

p {
  text-align: justify;
  margin-bottom: 10px;
  line-height: 1.5rem;
}

img {
  max-width: 100%;
  float: left;
  border-radius: 10px;
  margin: 15px;
}

.two-col {
  display: flex;
  justify-content: space-between;
  gap: 20px;
  background: white;
}

.two-col div {
  width: 100%;
}

@media only screen and (max-width: 900px) {
  body {
    padding: 20%;
  }

  .two-col {
    flex-direction: column;
  }

  .two-col div {
    width: 100%;
  }

  .main-wrapper {
    padding: 5%;
  }
}
.hero-image {
  /* Use "linear-gradient" to add a darken background effect to the image (photographer.jpg). This will make the text easier to read */
  background-image: linear-gradient(rgba(0, 0, 0, 0.822), rgba(0, 0, 0, 0.719)), url("https://static.wixstatic.com/media/1ab4bb_d7c7dd03e9124fdcbc06f2fef0fd9654~mv2.jpg/v1/fill/w_1349,h_810,fp_0.49_0.63,q_85,usm_0.66_1.00_0.01,enc_auto/pexels-anna-ilina-11900639_edited_edited.jpg");
  /* Set a specific height */
  height: 450px;
  /* Position and center the image to scale nicely on all screens */
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;
}
/* Place text in the middle of the image */
.hero-text {
  text-align: left;
  position: absolute;
  top: 40%;
  left: 35%;
  transform: translate(-30%, -30%);
  color: #ffffff(255, 255, 255);
  font-weight:500;
  font-size: 16px;
  width: 100%;
  padding: 20px;
}

.boxsolid {
    border: solid 2px;
    margin: 50px;
}

.em {
    text-align: left;
    padding: 0px 0px 0px 40px;
}

.em2 {
    text-align: left;
    padding: 0px 30px 0px 30px;
}


</style>
<div class="two-col">
        <div style="display: flex ; justify-content: center;padding-left: 50px;"> <a href="https://www.mvmtphysicaltherapync.com/"><img style="height: 60px;width: 150px;" src="https://static.wixstatic.com/media/358882_c2562da6db2245c0977a0353cd395e0b~mv2.png/v1/fill/w_177,h_88,al_c,q_85,usm_0.66_1.00_0.01,enc_auto/MVMT%20PT%20Logo_RO3_Mvmt%20Logo%20-%20Red.png" alt="Houston evictions"></a></div>
        <div style="display: flex; justify-content: center; text-align: center;font-size: 20px;font-weight: bolder;padding-top: 50px;"><a href="Tel:(919) 627-8256"><span style="color: black;"> (919) 627-8256</span></a></div>
</div>
<body>
    <!--Navigation Menu-->
    <nav class="nav-menu">
        <ul style="display: flex;justify-content: center;">
            <li class="nav-item"><a href="https://www.mvmtphysicaltherapync.com/">Main</a></li>
            <li class="nav-item"><a href="https://goo.gl/maps/ihWqwuA67BKebvfR7">Maps</a></li>
            <li class="nav-item"><a href="#">Physical Therapist Near Me & Durham, NC</a></li>
        </ul>
    </nav>

    <!---Main Container-->
    <div class="container">

        <!--Main Wrapper-->
        <div class="main-wrapper">
            <section class="head">
                <div class="hero-image">
                 <div class="hero-text">
                        <h1>PERFORM  PAIN-FREE.</h1>
                 </div>
                </div>         
        </section>
            <!--Content-->
            <section class="head">
                <h2>The Shoulder Joint</h2>
                <br>
                <p>The shoulder is a highly complex and mobile joint that allows us to perform a wide range of functional everyday movements. The shoulder joint is a highly complex joint that works in tandem with several other joints and muscles to allow us to perform a wide range of movements.  These movements are essential for completing daily tasks, such as reaching for objects, carrying bags, and performing household chores. Understanding these movements can help us appreciate the importance of shoulder health and the impact of shoulder injuries.</p>
                <img class="size-medium alignright" src="https://static.wixstatic.com/media/9533e9_046844bdf7c34915975d580fe1eafa71~mv2.jpg/v1/fill/w_740,h_745,al_c,q_85,usm_0.66_1.00_0.01,enc_auto/9533e9_046844bdf7c34915975d580fe1eafa71~mv2.jpg" width="500"/>
                <p>The shoulder joint is a ball-and-socket joint that connects the upper arm bone (humerus) to the shoulder blade (scapula). The joint is surrounded by several muscles and tendons, including the rotator cuff muscles, which help to stabilize the joint and facilitate movement.</p>
                <p>In addition to the shoulder joint, several other joints and muscles work in tandem to allow for shoulder movement. The sternoclavicular joint, which connects the collarbone (clavicle) to the breastbone (sternum), is essential for shoulder movement and stability. The acromioclavicular (AC) joint, which connects the clavicle to the shoulder blade, also plays a crucial role in shoulder movement.</p>
                <p>The scapulothoracic joint, which connects the shoulder blade to the ribcage, is also essential for shoulder movement. This joint allows for scapular movement, which is necessary for raising the arm overhead and for reaching behind the back. The movements of the scapula are coordinated with the movements of the shoulder joint and the other joints involved in shoulder movement.</p>
                <p>One of the most common functional everyday movements of the shoulder is shoulder flexion. This movement involves raising the arm forward and upward, such as reaching for a shelf or putting on a shirt. Shoulder flexion requires the coordinated action of the deltoid muscle, the rotator cuff muscles, and the biceps and triceps.</p>
                <p>Another functional everyday movement of the shoulder is shoulder abduction. This movement involves raising the arm out to the side, such as when carrying a bag or reaching for an object on a high shelf to your side. Shoulder abduction requires the coordinated action of the deltoid muscle and the rotator cuff muscles.</p>
                <p>Internal and external rotation of the shoulder are also essential for performing everyday tasks. Internal rotation involves rotating the arm inward, such as when reaching behind the back. External rotation involves rotating the arm outward, such as when reaching behind the head or when throwing a ball. These movements require the coordinated action of the rotator cuff muscles and the muscles of the chest and upper back.</p>
                <p>The scapula, or shoulder blade, plays a crucial role in shoulder movements and overall shoulder health. Scapular retraction, which involves squeezing the shoulder blades together, is necessary for maintaining proper posture and for performing everyday movements such as carrying a bag. Scapular protraction, which involves pushing the shoulder blades apart, is necessary for reaching forward and for performing movements such as pushing or pulling.</p>
                <p>In conclusion, the shoulder joint is essential for performing a wide range of functional everyday movements. Shoulder flexion, abduction, internal and external rotation, and scapular movements are all important for completing daily tasks. Understanding these movements and their requirements can help us appreciate the importance of shoulder health and the impact of shoulder injuries. Maintaining good shoulder health through proper exercise, posture, and lifestyle habits can help us maintain our ability to perform everyday activities.</p>
            </section>
            <!--Embeds-->
            <section>

                <!--Maps--><iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d6463.946321806524!2d-78.894581!3d35.898673!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x89acef9ae2185dc1%3A0x685159f145cac609!2sMVMT%20Physical%20Therapy!5e0!3m2!1sen!2sus!4v1684979672046!5m2!1sen!2sus" width="100%" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
                <!--Things to do--><iframe src="https://www.tripadvisor.com/Attractions-g49092-Activities-Durham_North_Carolina.html" style="border:0px #ffffff none;" name="myiFrame" scrolling="no" frameborder="1" marginheight="0px" marginwidth="0px" height="400px" width="100%" allowfullscreen></iframe>
                <!--News--><iframe src="https://www.newsobserver.com/news/local/counties/durham-county/" style="border:0px #ffffff none;" name="myiFrame" scrolling="no" frameborder="1" marginheight="0px" marginwidth="0px" height="400px" width="100%" allowfullscreen></iframe>      
            </section>

            <!--Links-->
            <section>
                <a target="_bLank" href="#"></a><br>
                <a target="_bLank" href="#"></a><br>
                <a target="_bLank" href="#"></a><br>
            </section>

        </div>

        <!---Sidebar-->
        <div class="side-bar">
            <section>
                <h2>Useful Links</h2>
                <ul>
                    <li><a href="https://www.mvmtphysicaltherapync.com/">Main</a></li>
                    <li><a href="https://goo.gl/maps/ihWqwuA67BKebvfR7">Maps</a></li>
                    <li><a href="#">Physical Therapist Near Me & Durham, NC</a></li>
                </ul>
            </section>
        </div>
    </div>
</body>
</html>
