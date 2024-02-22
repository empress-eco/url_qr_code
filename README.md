<div align="center">
  <img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="Project Logo"/>
  <h1 align="center">Empress PibiCut: Your URL Shortening & QR Code Generation Solution</h1>
  <p align="center">
    A swift, efficient, and user-friendly tool for URL shortening and QR code generation.
    <br />
    <a href="https://grow.empress.eco/">Explore the Docs</a>
    ·
    <a href="https://github.com/empress-eco/url_qr_code/issues">Report Bug</a>
    ·
    <a href="https://github.com/empress-eco/url_qr_code/issues/new">Request Feature</a>
  </p>
</div>

## About The Project

### 📖 Overview
Empress PibiCut is a powerful tool designed to swiftly produce shortened URLs and generate QR codes on your server. It is ideal for developers, marketers, or anyone seeking a streamlined, user-friendly approach to URL shortening and QR code generation. 

### 🌟 Key Features
- Quick generation of shortened URLs
- Instantaneous QR code production for shortened URLs
- Option to add a centered picture on the QR code

### 🛠 Built With
This project utilizes the following major frameworks/libraries:
- Empress Server Instance
- QR Code

## Getting Started

### Prerequisites
- Empress Server Instance. Refer to <a href="https://github.com/Empress/Empress">here</a> for more details.
- QR Code. Refer to <a href="https://github.com/lincolnloop/python-qrcode">here</a> for more details.

### Installation
To install Empress PibiCut, clone the repository using this [link](https://github.com/empress-eco/url_qr_code.git) and then execute the following commands from the Empress-bench folder:

```sh
$ bench get-app pibicut https://github.com/empress-eco/url_qr_code.git
$ bench install-app pibicut
```
For a multi-tenant environment, use the following command
```sh
$ bench --site site_name install-app pibicut
```
## Usage
Upon installation, a new doctype 'Shortener' is generated. Search for the 'Shortener' Doctype to view and create shortened URLs. When accessed, the resulting shortened URL redirects to the long URL, as does scanning the generated QR Code.

## Contributing
We welcome contributions! Here's how you can contribute:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License and Acknowledgements

### License
This project is under the MIT License. Your contributions are also licensed under the MIT License.

### Acknowledgments
We express our deep gratitude to the Empress Community for providing the server instance and the Lincoln Loop for the QR Code library. Their pioneering work and dedication have been instrumental in bringing this project to life.