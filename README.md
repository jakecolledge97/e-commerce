<div id="top"></div>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



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
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/jakecolledge97/e-commerce">
    <img src="https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/240/apple/285/card-index-dividers_1f5c2-fe0f.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">E-Commerce Backend</h3>

  <p align="center">
    An E-Commerce backend data organiser.
    <br />
    <a href="https://github.com/jakecolledge97/e-commerce"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://drive.google.com/file/d/1RiG-2HF2WRy1mC-_A0-KTlb-0rIss_s9/view">View Demo</a>
    ·
    <a href="https://github.com/jakecolledge97/e-commerce/issues">Report Bug</a>
    ·
    <a href="https://github.com/jakecolledge97/e-commerce/issues">Request Feature</a>
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
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

![![Insomnia Screen Shot][product-screenshot]](./Assets/e-commerce-insomnia.png)

This Project was a homework assignment given by Adelaide Uni's Coding Bootcamp. We had to use the information we were taught in the Object-Relational Mapping activities in the course. In this program you can create a database and fill it with seeds that are pre provided; You can use your chosen program (I used Insomnia) to explore the HTTP routes and interact with them using GET, POST, PUT, and DELETE. This project helped me to understand http routes more and creating database information. 


<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

* [Node.js](https://nodejs.org/en/)
* [DotEnv - Npm](https://www.npmjs.com/package/dotenv)
* [Express - Npm](https://www.npmjs.com/package/express)
* [Mysql2 - Npm](https://www.npmjs.com/package/mysql2)
* [Sequelize](https://sequelize.org/)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

To set this application up locally follow the steps bellow

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/jakecolledge97/e-commerce.git
   ```
2. Install NPM packages
   ```sh
   npm install
   ```

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Once installed you will have to set up the database and seeds. In the '.env.EXAMPLE' file you will need to fill out the information.

1. Run the database
    ```sh
    mysql -u <your username> -p

    password: <your password>

    source ./db/schema.sql

    quit
    ```

2. Run the seeds file
    ```sh
    run npm seed
    ```

3. Now you can start the local server
    ```sh
    npm start
    ```

<p align="right">(<a href="#top">back to top</a>)</p>

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

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

My Email - jakecolledgework@gmail.com

Project Link: [https://github.com/jakecolledge97/e-commerce](https://github.com/jakecolledge97/e-commerce)

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/jakecolledge97/e-commerce.svg?style=for-the-badge
[contributors-url]: https://github.com/jakecolledge97/e-commerce/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/jakecolledge97/e-commerce.svg?style=for-the-badge
[forks-url]: https://github.com/jakecolledge97/e-commerce/network/members
[stars-shield]: https://img.shields.io/github/stars/jakecolledge97/e-commerce.svg?style=for-the-badge
[stars-url]: https://github.com/jakecolledge97/e-commerce/stargazers
[issues-shield]: https://img.shields.io/github/issues/jakecolledge97/e-commerce.svg?style=for-the-badge
[issues-url]: https://github.com/jakecolledge97/e-commerce/issues
[license-shield]: https://img.shields.io/github/license/jakecolledge97/e-commerce.svg?style=for-the-badge
[license-url]: https://github.com/jakecolledge97/e-commerce/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/jake-colledge-462986223
[product-screenshot]: images/screenshot.png
