<a name="readme-top"></a>
[![LinkedIn][linkedin-shield]][linkedin-url]

=

<!-- ABOUT THE PROJECT -->

## About The Project

<div align="center"> 
<img width="685" alt="project-image" src="https://github.com/p-gatsby/p-gatsby/assets/106583795/ae172f95-8654-44ef-871c-c6ed0de92e53">
</div>

This application, built with Electron, Flask, and Selenium, is designed to streamline clinical processes by automating redundant tasks like filling in patient information using previously submitted data.
<!-- GETTING STARTED -->

## Getting Started

Welcome to Clinic-Source-Automation-App! This guide provides detailed steps to set up the environment and install this project on your local computer.

### Prerequisites

Before you begin, ensure you have the following installed:

- Node.js
- Python3

### Installation

Clone the repository > Clinic-Source-Automation-App

  ```bash
  git clone https://github.com/p-gatsby/Clinic-Source-Automation-App.git
  ```

Electron app installation ~ > Clinic-Source-Automation-App > Client

- Install node dependencies
  ```sh
  npm install
  ```

Flask server installation ~ > Clinic-Source-Automation-App > Server

- Install virtual environment:

  ```sh
  python3 -m venv env
  ```

- Install server dependencies:

  ```sh
  pip install -r requirements.txt
  ```

### Server Environmental Variables

  ```
  WAIT_TIMEOUT = 10
  CHROMEDRIVER_PATH = /app/.chromedriver/bin/chromedriver
  GOOGLE_CHROME_BIN = /app/.apt/usr/bin/google-chrome
  ```

### Running the app

- Run Electron App
  ```sh
  npm start
  ```
- Run Flask Server
  ```sh
  flask --app app run
  ```

<!-- LICENSE -->

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/petergatsby
[product-screenshot]: images/screenshot.png