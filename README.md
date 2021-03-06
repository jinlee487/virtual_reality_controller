# virtual_reality_controller

<div id="top"></div>

[![LinkedIn][linkedin-shield]][linkedin-url]
[![LinkedIn][linkedin-shield]][linkedin-url2]

<a href="https://drexel.edu/cci/partnerships/community-engagement/philly-codefest/"><img src="https://user-images.githubusercontent.com/46912607/162554633-ccb1b28f-1b1f-4875-bed6-5f0729dcbc03.png" width="630"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
    <h1 align="center">Gesture Interface and Online Experience Controller</h1>
    <h3 align="center">Philly Codefest – Best Diversity, Equity & Inclusion (DEI) Hack Winner</h3>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#inspiration">Inspiration</a></li>
      </ul>
      <ul>
        <li><a href="#what-it-does">What it does</a></li>
      </ul>
      <ul>
        <li><a href="#how-we-built-it">How we built it</a></li>
      </ul>     
      <ul>
        <li><a href="#challenges-we-ran-into">Challenges we ran into</a></li>
      </ul>
      <ul>
        <li><a href="#accomplishments-that-were-proud-of">Accomplishments that we're proud of</a></li>
      </ul>
      <ul>
        <li><a href="#what-we-learned">What we learned</a></li>
      </ul>
      <ul>
        <li><a href="#whats-next-for-test">What's next for test</a></li>
      </ul>
    </li>
    <li><a href="#installation">Installation</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
## About The Project

[![homepage-screenshot](https://user-images.githubusercontent.com/46912607/162545138-9670f89d-b212-4e1f-a6b2-b0975c0cd395.png)](https://www.youtube.com/watch?v=5R6yFyDV3-I)
- click image to play the video

[![image](https://user-images.githubusercontent.com/46912607/162871655-2e038a31-f0e8-4bb1-97f2-912debc369e8.png)](https://devpost.com/software/test-3rej76)
- click to view the hackathon


As a challenge project for Philly CodeFest 2022, We decided to make a Virtual Reality Controller.  


### Inspiration
Emerging complex new technologies and new functions increase memory loads of remembering the interactions or button locations on website. Gesture interface design based on real world experience can make the learning process easier.

### What it does
We designed a set of gesture interactions based on people’s experience from the real world. We expect the gesture interface we designed can reduce the memory loads and increase the user experience in people’s web browsing activities.

### How we built it

1. Identifying and defining the gestural language
     
    - selecting 
    
<img src="https://user-images.githubusercontent.com/46912607/162552650-0f2ae37a-6564-4f03-8903-75822a22fe24.gif" width="100" height="100">
    
    - clicking/opening
    - highlighting
    - Hovering
    - scrolling/zoom 
    
<img src="https://user-images.githubusercontent.com/46912607/162552659-f13b796b-54cd-450a-b391-7a721bc60597.gif" width="100" height="100"><img src="https://user-images.githubusercontent.com/46912607/162552655-9156e01c-55f9-408a-a44a-dc8aaef50754.gif" width="100" height="100">
    
    - call to main menu 
   
<img src="https://user-images.githubusercontent.com/46912607/162552653-2b1784df-2471-4374-8414-158fde2c15f0.gif" width="100" height="100">
    
    - Typing 
    - Back and forward pages 
   
<img src="https://user-images.githubusercontent.com/46912607/162552658-40360cbb-b5f8-4a82-8dc1-1b2a76a04ef8.gif" width="100" height="100"><img src="https://user-images.githubusercontent.com/46912607/162552657-7f50c9dc-e112-495a-bfe9-9bf7e6d7f1fa.gif" width="100" height="100">



2. Implementing the gestural language support in a web transactional experience


    [demo-video-youtube](https://youtu.be/5R6yFyDV3-I)
    
    
    Below are the major frameworks/libraries for the project.

    * [Python](https://www.python.org/)
    * [mediapipe](https://google.github.io/mediapipe/)
    * [opencv](https://opencv.org/)
    
### Challenges we ran into

    - Difficulty in differentiating finger shapes and movements
        * Some gestures look alike 
        * overlapping pre-movements after-movements

    - Difficulty in perceiving depth and distance from the camera
        * Working with single camera 
        * Absolute distance in snapshots of images 
        * Length between fingers changed as distance from camera became further 


### Accomplishments that we're proud of

Successfully implemented the following gesture feature!

    - clicking/opening
    - highlighting
    - Hovering
    - scrolling/zoom 

### What we learned

    - Requires more insight in gestural languages

    - More cameras to allow more accurate computer vision


### What's next for test

1. We want to test the gesture control we designed can be applied into AR/VR web browsing activity, which provides the flexibility of browsing the web anytime anywhere without additional control devices.
<img src="https://user-images.githubusercontent.com/46912607/162552958-b55efa75-0ee9-418c-be2e-81092f69e8d5.jpg" width="200" height="200">

2. We want to have customized function which allows people with limited finger motor abilities(e.g. Stroke patients) to tailor their own gesture controls. 
<img src="https://user-images.githubusercontent.com/46912607/162552961-e513d954-f432-4c28-8627-6f4b6f341c5a.jpg" width="200" height="200">


<p align="right">(<a href="#top">back to top</a>)</p>

## Installation

1. Download the dist zip file from the releases. 
2. unzip the folder
3. run the main.py file in the subfolders

* make sure you have the camera working and free for access

* the application will only run on windows

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement". Don't forget to give the project a star! Thanks again!

<p align="right">(<a href="#top">back to top</a>)</p>




<!-- CONTACT -->
## Contact

Jay Lee - [LinkedIn](linkedin-url) - jinwoolee@gmail.com

blog Link - [jayleecodes](https://jinlee487.github.io/)

git Link -[git](https://github.com/jinlee487)

Shirley Qian - [LinkedIn](https://www.linkedin.com/in/shirley-qiany/) - Shirley.Qiany@gmail.com

blog Link - [yijunqian](https://www.yijunqian.com/)

git Link -[git](https://github.com/yijunqian)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Below are the reference tutorials used in developing this application

* [MurtazasWorkshopRoboticsandAI](https://www.youtube.com/c/MurtazasWorkshopRoboticsandAI)

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/jinwoolee487/
[linkedin-url2]: https://www.linkedin.com/in/shirley-qiany/

[homepage-screenshot]: https://user-images.githubusercontent.com/46912607/162545138-9670f89d-b212-4e1f-a6b2-b0975c0cd395.png



