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
**1. What you will learn?**

By building an ultrasonic theremin, you will learn:
- How to **detect distances** with an ultrasonic distance sensor.
- How to **communicate** variables between Sonic Pi and Python.

 
**2. What you will need?** 

- **2.1. Hardware:** 
    - 330Ω Resistor
    - 470Ω Resistor
    - Solderless Breadboard
    - Ultrasonic Distance Sensor
    - 3 x Male to Male Jumper Leads
    - 4 x Male to Female Jumper Leads
- **2.2. Software:**

    This project relies on the latest version of Sonic Pi and python-osc. To install the software you need, run the following commands in a terminal window:
    ```zsh
    sudo apt update && sudo apt upgrade -y
    sudo pip3 install python-osc
    ```

**3. Setting up the circuitry**

<p align="justify">An <b>ultrasonic distance sensor</b> is a device that sends out pulses of ultrasonic sound, and measures the time they take to bounce off nearby objects and be reflected back. They can measure distances fairly accurately, up to about a meter.</p>

An ultrasonic distance sensor has four pins. They are called <b><i>Ground (Gnd), Trigger (Trig), Echo (Echo) and Power (Vcc)</i></b>.

To use an ultrasonic distance sensor you need to connect the <b>Gnd pin</b> to the ground pin on the Raspberry Pi, the <b>Trig pin</b> to a GPIO pin on the Raspberry Pi and the <b>Vcc pin</b> to the 5V pin on the Raspberry Pi.

The <b>Echo pin</b> is a little more complicated. It needs to be connected through a <i>330 ohm resistor</i> to a GPIO pin on the Raspberry Pi, and that pin needs to be grounded through a <i>470 ohm resistor</i>.

The diagram below shows one suggested arrangement for setting this up.

<p align="center"> <img  src="./stuff/circuit.png" width="400"> </p>  




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


**Project Link:** [https://github.com/RabihND/UltrasonicTheremin](https://github.com/RabihND/UltrasonicTheremin)

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- ROADMAP -->
## Roadmap

- [x] 
<p align="right">(<a href="#top">back to top</a>)</p>


---



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
