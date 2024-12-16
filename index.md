## Portfolio
Welcome to my portfolio! On this website, I have a variety of projects that I have been working on over the past few years at Northwestern University. These range from software development and embedded systems in C, C++, Python, ROS, and MATLAB to machining and mechanical design. I hope you enjoy browsing! 

If you wish to reach out, [click here](mailto:carolineterryn2025@u.northwestern.edu).

To view my resume, [click here](https://github.com/user-attachments/files/18142018/Resume.pdf).

### The Poolinator
As a team, we programmed the Franka Emika Robot (FER) to play a game of pool on a tabletop pool set. The FER will continue to attempt to knock the blue balls into a pocket until the red ball gets knocked into a pocket or when all of the balls have been cleared off the table. 

<img width="500" alt="Poolinator in Action" src="https://github.com/user-attachments/assets/ab40a052-6dd3-48f3-a214-d8fd682553aa" />

<video width="500" controls>
  <source src="https://github.com/user-attachments/assets/71ba657b-6114-4a4d-85ac-b4600d58953f" type="video/mp4">
</video>

[Click here to view the full Poolinator Demo](https://drive.google.com/file/d/1psu3DP3Hr34mRSthxlqQxPMicgn3MlMN/view?usp=sharing)

### Teleoperated Turtle
Using the `turtlesim` package on ROS, I developed code to command a turtle to traverse waypoints that are generated via service calls. Once the turtle finishes traversing a cycle of waypoints, a custom message is published on the `/loop_metrics` topic that contains the number of loops completed by the turtle, the actual distance traveled, and the error between the actual distance traveled and the straight-line distance of the path.

A video of the turtle following the waypoints can be seen below.

<video width="500" controls>
  <source src="https://github.com/user-attachments/assets/2dac45da-11d4-454e-9fd4-bd8c3972bc1d" type="video/webm">
</video>


### Machining a 2-DOF Pantograph
<div class="slideshow-container">
  <!-- Slide 1 -->
  <div class="mySlides fade">
    <img src="https://github.com/user-attachments/assets/bee45706-c4c6-4257-946b-b14474d65a8e" style="height:400px" alt="Image 1">
    <div class="caption">Initial SolidWorks Design</div>
  </div>

  <!-- Slide 2 -->
  <div class="mySlides fade">
    <img src="https://github.com/user-attachments/assets/b1ede566-a9c4-440a-85ef-67a83f3582ed" style="height:400px" alt="Lathe">
    <div class="caption">First, we lathe!</div>
  </div>

  <!-- Slide 3 -->
  <div class="mySlides fade">
    <img src="https://github.com/user-attachments/assets/aedf17ed-7727-41d9-904c-a57ef46cddd6" style="height:400px" alt="Selfie Number 1">
    <div class="caption">Selfie Break #1</div>
  </div>

  <!-- Slide 4 -->
  <div class="mySlides fade">
    <img src="https://github.com/user-attachments/assets/2a2116d8-aaa4-47e2-a15a-92988f9dce0d" style="height:400px" alt="Milling Op 1">
    <div class="caption">Now, we mill!</div>
  </div>

   <!-- Slide 5 -->
  <div class="mySlides fade">
    <img src="https://github.com/user-attachments/assets/2ab62598-13d8-47bf-b10e-7f393a17d6a4" style="height:400px" alt="Milling Op 2">
    <div class="caption">and more milling...</div>
  </div>

   <!-- Slide 6 -->
  <div class="mySlides fade">
    <img src="https://github.com/user-attachments/assets/839e99a7-d59c-4269-8624-bd1d6d0eea59" style="height:400px" alt="Milling Op 3">
    <div class="caption">and more milling...</div>
  </div>
  
  <!-- Slide 7 -->
  <div class="mySlides fade">
    <img src="https://github.com/user-attachments/assets/ec5c6ddc-29de-48e4-9e34-1dff9010363c" style="height:400px" alt="Selfie Number 2">
    <div class="caption">Quick milling selfie break!</div>
  </div>

  <!-- Slide 8 -->
  <div class="mySlides fade">
    <img src="https://github.com/user-attachments/assets/45fe18d0-ed26-4112-99b1-460d62a502d2" style="height:400px" alt="Milling Op 4">
    <div class="caption">and more milling...</div>
  </div>

  <!-- Slide 9 -->
  <div class="mySlides fade">
    <img src="https://github.com/user-attachments/assets/1edfa0ae-d8ad-4bb2-945f-28ff59b1d7c1" style="height:400px" alt="Assembly">
    <div class="caption">Final assembly post-machining!</div>
  </div>

  <!-- Slide 10 -->
  <div class="mySlides fade">
    <img src="https://github.com/user-attachments/assets/84cbc043-f570-4228-9d59-492303ed297d" style="height:400px" alt="Final Product">
    <div class="caption">Final Product</div>
  </div>

  <!-- Next/Prev Buttons -->
  <a class="prev" onclick="plusSlides(-1)">❮</a>
  <a class="next" onclick="plusSlides(1)">❯</a>
</div>

<script>
// Just manually navigate between slides with arrows
let slideIndex = 0;

function showSlides() {
  let slides = document.getElementsByClassName("mySlides");
  for (let i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  // Hide all slides
  }
  slides[slideIndex].style.display = "block"; // Show current slide
}

function plusSlides(n) {
  slideIndex += n;
  if (slideIndex >= document.getElementsByClassName("mySlides").length) { slideIndex = 0; }
  if (slideIndex < 0) { slideIndex = document.getElementsByClassName("mySlides").length - 1; }
  showSlides();
}

// Initialize the first image to be visible
showSlides();
</script>

### Tetris

