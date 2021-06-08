
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/abhishekkushwaha4u/vitolx-backend">
    <img src="github-readme-resources/vit-olx-logo.png" alt="Logo" width="300" height="200">
  </a>

  <h3 align="center">VIT OLX Backend</h3>

  <p align="center">
    The Backend Code Starter to setup OLX for your own organization !
    <br />
    <a href="https://documenter.getpostman.com/view/7132402/TzY68Zax"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/abhishekkushwaha4u/vitolx-backend/issues">Report Bug</a>
    ·
    <a href="https://github.com/abhishekkushwaha4u/vitolx-backend/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
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
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project


This was an idea that me and my friend [Shounak Bhattacharya](https://www.linkedin.com/in/shounak-bhattacharya-8585ba1b4/) decided to work on for our IWP J component under the able guidance of our IWP mam, [Professor Malathy E](https://research.vit.ac.in/researcher/malathy-e), Assistant Professor, in F2 slot.

Here's why some reasons we wanted to work on something like this:
* With COVID almost getting over, we are expecting everyone back on campus, hence freshers and all new people to populate soon.
* The scene is vastly different for people in final year and freshers, final years are mostly about to pass out and mostly with no intention of retaining items like pillows, mattrices, books etc
* On the other hand, frehers are in dire need of these resources as a lot of them need them all that once, but the shops at Vellore are unable to supply and meet the demand quickly, mostly students end up suffering because of lack of these basic amenities at college.

Our idea was to build a small web application to enable people to allow exchange of these items in a community friendly way, hence solving this simple problem.

### Built With

* [Django](https://www.djangoproject.com/)
* [Python](https://www.python.org/)


### Setting Up VirtualEnvironment(Follow this in case you are new)

* virtualenv - Setting up the virtual environment
  ```sh
  virtualenv env
  ```
* virtualenv activation - Activating of the virtual environment
  ```sh
  source env/bin/activate # Linux and Mac OS
  ```
  ```powershell
  .\env\Scripts\activate # Windows
  ```

<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

You need to have Python 3.6+ installed on your system and added to path. In case you do not have python installed, you can follow [this](https://medium.com/analytics-vidhya/step-by-step-guide-to-install-python-environment-on-ubuntu-337d8dbdd05d) to set python up for your system.



### Installation

1. Download the frontend repo from [here](https://github.com/Shounak-bhattacharya/VIT-OLX
)
2. Clone this repo
   ```sh
   git clone https://github.com/abhishekkushwaha4u/vitolx-backend
   ```
3. Setup and activate a virtualenvironment(Described Above)
4. Install pip packages
   ```sh
   pip install -r requirements.txt
   ```
5. To setup migrations(Do this after changing your database creds or use sqlite by default)
   ```sh
   python manage.py makemigrations
   python manage.py migrate
   ```
6. To run the server, type 
   ```sh
   python manage.py runserver
   ```

Your can serve the frontend code on any localserver and use it easily integrated with your backend on localhost.
<!-- USAGE EXAMPLES -->
## Usage

_For more examples, please refer to the [Documentation](https://documenter.getpostman.com/view/7132402/TzY68Zax)_


<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/abhishekkushwaha4u/vitolx-backend/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Abhishek Kushwaha- [@itsAbhi1706](https://twitter.com/itsAbhi1706) - abh1234@mail.com

Backend Repo Link: [Backend Repo](https://github.com/abhishekkushwaha4u/vitolx-backend)

FrontEnd Repo Link: [Fronted Repo](https://github.com/Shounak-bhattacharya/VIT-OLX
)




<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/abhishekkushwaha4u/vitolx-backend?style=for-the-badge
[contributors-url]: https://github.com/abhishekkushwaha4u/vitolx-backend/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/abhishekkushwaha4u/vitolx-backend.svg?style=for-the-badge
[forks-url]: https://github.com/abhishekkushwaha4u/vitolx-backend/network/members
[stars-shield]: https://img.shields.io/github/stars/abhishekkushwaha4u/vitolx-backend.svg?style=for-the-badge
[stars-url]: https://github.com/abhishekkushwaha4u/vitolx-backend/stargazers
[issues-shield]: https://img.shields.io/github/issues/abhishekkushwaha4u/vitolx-backend.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/abhishekkushwaha4u/vitolx-backend.svg?style=for-the-badge
[license-url]: https://github.com/abhishekkushwaha4u/vitolx-backend/blob/master/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/abhishek-kushwaha-b04341194/
[product-screenshot]: ss
