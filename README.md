<div id="top"></div>


<p align="center">
    <a alt="Version">
        <img src="https://img.shields.io/github/v/release/RabihND/AP2021-2022-Final?color=14adfa&logo=Semantic%20Web&logoColor=14adfa&style=for-the-badge" /></a>
    <a  alt="Downloads">
        <img src="https://img.shields.io/github/downloads/RabihND/AP2021-2022-Final/total?logo=App%20Store&logoColor=white&style=for-the-badge" /></a>
    <a href="https://github.com/RabihND/AP2021-2022-Final/graphs/contributors" alt="Contributers">
        <img src="https://img.shields.io/github/contributors/RabihND/AP2021-2022-Final?color=6fd671&logo=WhiteSource&style=for-the-badge" /></a>
    <a href="https://github.com/RabihND/AP2021-2022-Final//network/members" alt="Forks">
        <img src="https://img.shields.io/github/forks/RabihND/AP2021-2022-Final?color=cccccc&logo=Node-RED&style=for-the-badge" /></a>
    <a href=" https://github.com/RabihND/AP2021-2022-Final/stargazers">
        <img src="https://img.shields.io/github/stars/RabihND/AP2021-2022-Final?color=8e6be8&logo=Ethereum&logoColor=8e6be8&style=for-the-badge" alt="Stars"></a>
    <a href="https://github.com/RabihND/AP2021-2022-Final/master/LICENSE.txt">
        <img src="https://img.shields.io/github/license/RabihND/AP2021-2022-Final?color=%2363afdb&logo=letsencrypt&style=for-the-badge" alt="License"></a>
</p>


<!-- PROJECT LOGO -->
<br />
<div align="center">

  <h3 align="center"> Ultrasonic theremin</h3>
  <p align="center"><img src="./stuff/bot.gif" width="200"></p>
  <p align="center">
   A Kids Project using RaspberryPi (Python + SonicPi)
    <br />
    <a href="https://github.com/RabihND/AP2021-2022-Final"><strong>Explore the documents »</strong></a>
    <br />
    <br />
  </p>
</div>


---

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary> 
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#parts">Parts</a></li>
    <li><a href="#results">Results</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#refenences">Refenences</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
<p align="center"> <img  src="./stuff/playing.webp" width="500"> </p>  
<p align="justify">The <b>theremin</b> <i>(/ˈθɛrəmɪn/; originally known as the ætherphone/ether phone, thereminophone or termenvox/thereminvox)</i> is an electronic musical instrument controlled without physical contact by the thereminist (performer). It is named after its inventor, Leon Theremin, who patented the device in 1928.

<p align="justify">The instrument's controlling section usually <b>consists of two metal antennas</b> that sense the relative position of the thereminist's hands and <b>control oscillators for frequency with one hand, and amplitude (volume) with the other.</b> The electric signals from the theremin are amplified and sent to a loudspeaker.

><p align="justify"><font size="-3">The sound of the instrument is often associated with eerie situations. Thus, the theremin has been used in movie soundtracks such as Miklós Rózsa's Spellbound and The Lost Weekend, Bernard Herrmann's The Day the Earth Stood Still, and Justin Hurwitz's First Man, as well as in theme songs for television shows such as the ITV drama Midsomer Murders and the Disney+ series Loki, the latter composed by Natalie Holt. The theremin is also used in concert music (especially avant-garde and 20th- and 21st-century new music), and in popular music genres such as rock.</p></font>


<p align="right">(<a href="#top">back to top</a>)</p>


### Built With

Major frameworks/libraries used in this project:

* [Python 3.10](https://www.python.org/)
* [Sonic Pi](https://sonic-pi.net/)

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- PARTS -->
## Parts
**1. Master Mind Class**

The main MasterMind game Process; it contains:
- **get_random_solution()**:  Returns a random "solution" to be the hidden code.
- **check_guess()**: Returns the nb of "correct" and nb of "misplaced" guess.
- **get_correct_colors()**: Returns the "correct" colors.
- **get_misplaced_colors()**: Returns the "misplaced" colors.
- **is_won()**: Verify that the guess is correct according to the solution.
 
**2. MainWindowUi  Class** (GUI_Window)

The main window of the game designed by Qt; it contains:
- **setupUi()**: The QT codes that generate the main window.
- **resetButtonClicked()**:  That delete the selected colors.
- **set_thisguesstable()**: connect the colors.
- **clicked_color()**: Send the selected colors to the Guess table.
- **clicked_submit()**:  After clicking the submit button; its check the guess and return the score to the Scores Table.
- **show_game_over()**: Show the Game Over Dialog.
-**print_score()**: print score in the terminal (NOT GUI).

**3. GameOverWindow Class** (GUI_Window)

The resulting window, which shows the player's loss(+) or victory(-).
- **display_text()**: Return a text with include the result of the game.(Win/Loss)

**4. Splash Screen Class** (GUI_Windows)
>{⌛} 



<p align="right">(<a href="#top">back to top</a>)</p>

<!-- RESULTS -->
## Results

**GUI OUTPUT:**
<details>
<summary>ScreenShoot Preview 🖼️</summary>
  <body>
    <p align="center"> <img src="./stuff/GUI_output.jpg" width="200"> </p>
  </body>
</details>

---

**TERMINAL OUTPUT:**
<details>
<summary>ScreenShoot Preview 🖼️</summary>
  <body>
    <p align="center"> <img src="./stuff/terminal_output.jpg" width="300"> </p>
  </body>
</details>

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- REFERENCES -->
## Refenences

🔎

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contacts


Rabih ND - [@RabihND](https://github.com/RabihND) 

Hasan Sanei - [@hasansanei](https://github.com/hasansanei)

**Project Link:** [https://github.com/RabihND/AP2021-2022-Final](https://github.com/RabihND/AP2021-2022-Final)

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- ROADMAP -->
## Roadmap

- [x] Write the main code-map.
- [x] Design the GUI window. 
- [x] Write the MasterMain Core Functions.
- [x] Design the GameOver window.
- [x] <a href="https://github.com/RabihND/AP2021-2022-Final/releases/latest"><strong>Build the .EXE Release</strong></a>
- [ ] Splash screen
- [ ] Build APK release.

<p align="right">(<a href="#top">back to top</a>)</p>


---
<div align="center">
<p>
<img src="./stuff/logo.png" width="110">
<p align="center"><b>
Amirkabir University  of Technology</b>

(Tehran Polytechnic)
</p>
</p>
</div>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[version-sheild]: https://img.shields.io/github/v/release/RabihND/AP2021-2022-Final?color=14adfa&logo=Semantic%20Web&logoColor=14adfa&style=for-the-badge
[download-sheild]: https://img.shields.io/github/downloads/RabihND/AP2021-2022-Final/total?logo=App%20Store&logoColor=white&style=for-the-badge
[line-sheild]: https://img.shields.io/tokei/lines/github/RabihND/AP2021-2022-Final?color=green&logo=visualstudiocode&style=for-the-badge
[contributors-shield]: https://img.shields.io/github/contributors/RabihND/AP2021-2022-Final?color=6fd671&logo=WhiteSource&style=for-the-badge
[contributors-url]: https://github.com/RabihND/AP2021-2022-Final/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/RabihND/AP2021-2022-Final?color=cccccc&logo=Node-RED&style=for-the-badge
[forks-url]: https://github.com/RabihND/AP2021-2022-Final//network/members
[stars-shield]: https://img.shields.io/github/stars/RabihND/AP2021-2022-Final?color=8e6be8&logo=Ethereum&logoColor=8e6be8&style=for-the-badge
[stars-url]: https://github.com/RabihND/AP2021-2022-Final/stargazers
[license-shield]: https://img.shields.io/github/license/RabihND/AP2021-2022-Final?color=%2363afdb&logo=letsencrypt&style=for-the-badge
[license-url]: https://github.com/RabihND/AP2021-2022-Final/master/LICENSE.txt
