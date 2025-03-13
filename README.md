<a id="readme-top"></a>

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![project_license][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/frapiocov/xrpaestumgate">
    <img src="images/xpg.png" alt="Logo" width="200" height="100">
  </a>

<h3 align="center">XR-PaestumGate</h3>

  <p align="center">
    XR-PaestumGate explores the potential of immersive technologies such as
    Virtual Reality (VR) in the field of cultural heritage valorization. The open source project extends the virtual reconstruction of the
    archaeological site of Paestum through the design and implementation of
    a serious game (SG) in VR integrating game mechanics designed to increase user involvement and interest.The experience consists of various activities, from exploring the environment to discover its key places to the possibility of driving a Roman chariot.
    <br />
    <a href="https://github.com/github_username/repo_name"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/github_username/repo_name">View Demo</a>
    &middot;
    <a href="https://github.com/github_username/repo_name/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    &middot;
    <a href="https://github.com/github_username/repo_name/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

* Unity version 2022.3.53f1 LTS
* C#
* Meta All in One SDK
* 3DS Max Studio

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started
To get a local copy up and running follow these simple steps:

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
Before starting, ensure you have the following installed:
- **Unity Hub** (latest version recommended)
- **Unity Editor**
- **Git** (for cloning the repository)
- **Visual Studio** (or another compatible IDE for script editing)
- **Meta Quest Link** and **Meta Quest Developer Hub** (if you have a Meta standalone VR device). Alternatively, download the software from the producer of your vr device
- **3DS Studio Max** (latest version recommended) for import all the scene's prefab. The software is available on a pay-per-use licence, but a 7-day trial is sufficient to import the necessary project requirements


### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/frapiocov/xrpaestumgate.git
   ```
2. Change git remote url to avoid accidental pushes to base project
   ```sh
   git remote set-url origin github_username/repo_name
   git remote -v # confirm the changes
   ```
3. Open Unity Hub
4. Click **Open** and select the cloned project folder
5. Ensure you have the correct Unity version (2022.3.53f1) installed.
6. Wait for Unity to load the project and compile assets. (ensure you have 3DS Max installed and with active license)
7. Install Dependencies
  - Open the **Package Manager** (`Window` > `Package Manager`)
  - Install any missing dependencies or packages
  - If required, configure **Oculus Plugin Management** for VR support
8. Build
  - Go to File > Build Settings
  - Select the platform: Android
  - Click Switch Platform if needed
  - Setup the *Scenes in Build* with the project Scenes (it is recommended to use the menu scene as first in the list). an example of what it should look like in the image below
  <p align="center">
    <img src="images/project/build.jpg" alt="Logo" width="380">
  </p>

9. Run the project
  - Click Play in the Unity Editor to test the game
  - For a standalone build, click **Build and Run** in the Build Settings window. The result is an **apk** file for your VR device

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- USAGE EXAMPLES -->
## Usage
The versions (VR and desktop) of the game are divided in two different directories, both have the same game modes:
- Exploration: freely explore the ancient site of Paestum on foot or using the chariot
- Chariot Run: timed chariot race along a predefined route
- Key Places: explore the map and locate the points of interest on the map within a time limit

The following is the Scenes directories:
  <p align="center">
    <img src="images/project/scenes.jpg" alt="Scenes" width="400">
  </p>
The subdirectories contains all the Scenes for Desktop and VR version of XR-PaestumGate as visible from the images below
<p align="center">
    <img src="images/project/dtscenes.jpg" alt="Desktop" width="220">
    <img src="images/project/vrscenes.jpg" alt="Desktop" width="280">
</p>


<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Troubleshooting
- If errors occur, check the **Console** for logs
- Ensure all **Unity packages** are installed and up to date
- Restart Unity or delete the `Library` folder if necessary
- Verify that **Oculus software** is running (for VR projects)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
<!-- ROADMAP -->
## Roadmap

- [ ] Add hint for keyplaces modality 
- [ ] Minimap for VR mode

See the [open issues](https://github.com/github_username/repo_name/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Top contributors:

<a href="https://github.com/frapiocov/xrpaestumgate/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=frapiocov/xrpaestumgate" alt="contrib.rocks image" />
</a>



<!-- LICENSE -->
## License

Distributed under the project_license. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Francesco Pio Covino - francescop.covino@gmail.com

Project Link: [https://github.com/frapiocov/xrpaestumgate](https://github.com/frapiocov/xrpaestumgate)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* []() Unity
* []() C#

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/frapiocov/xrpaestumgate.svg?style=for-the-badge
[contributors-url]: https://github.com/frapiocov/xrpaestumgate/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/frapiocov/xrpaestumgate.svg?style=for-the-badge
[forks-url]: https://github.com/frapiocov/xrpaestumgate/network/members
[stars-shield]: https://img.shields.io/github/stars/frapiocov/xrpaestumgate.svg?style=for-the-badge
[stars-url]: https://github.com/frapiocov/xrpaestumgate/stargazers
[issues-shield]: https://img.shields.io/github/issues/frapiocov/xrpaestumgate.svg?style=for-the-badge
[issues-url]: https://github.com/frapiocov/xrpaestumgate/issues
[license-shield]: https://img.shields.io/github/license/frapiocov/xrpaestumgate.svg?style=for-the-badge
[license-url]: https://github.com/frapiocov/xrpaestumgate/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
[product-screenshot]: images/pg_explore.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com
[Unity]: https://img.shields.io/badge/-Unity-%23444444?style=for-the-badge&logo=unity&logoColor=black
[Unity-url]: https://unity.com/