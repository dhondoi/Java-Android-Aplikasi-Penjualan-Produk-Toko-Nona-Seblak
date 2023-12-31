<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
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

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
-->


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/dhondoi/Aplikasi-Nona-Seblak-Berbasis-Android">
    <img src="images/title.jpg" alt="Logo" width="400" >
  </a>

  <h3 align="center">Aplikasi Nona Seblak Berbasis Android</h3>

  <p align="center">
    Aplikasi berbasis Android yang (saat ini) tertuju pembuatan laporan pemasukan di Toko Nona Seblak
    <!--
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template">View Demo</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Report Bug</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Request Feature</a>
    -->
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
      <ul>
          <li><a href="#about-the-project">About The Project</a></li>
          <li><a href="#built-with">Built With</a></li>
          <li><a href="#features">Features</a></li>
          <li><a href="#roadmap">Roadmap</a></li>
      </ul>
  <!--
  <ol>
    <li>
      
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
  -->
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

<!-- ![Product Name Screen Shot][product-screenshot] -->

Seblak merupakan salah satu kuliner yang diminati oleh kalangan para remaja karena kebanyakan kuliner tersebut memiliki cita rasa pedas. Dengan banyaknya minat yang ingin menikmati seblak, menjadikan salah satu plihan untuk para pembisnis untuk memulai usaha, salah satunya adalah Toko Nona Seblak. Toko Nona Seblak menyediakan kategori dalam bentuk paketan maupun prasmanan. Mereka juga menyediakan berbagai macam topping sebagai tambahan, jika para konsumen merasa isi dalam seblak tersebut masih kurang. Setiap hari sebelum toko ditutup, pegawai mengumpulkan semua data penjualan kedalam buku besar. Setelah semua data terkumpul, dikalkulasikan sehingga menghasilkan total penjualan yang didapat. Dengan hal tersebut saya berinisiatif untuk menawarkan aplikasi untuk mengelola data secara komputerisasi.

Alasan Membuat Aplikasi Nona Seblak:
* Laporan pemasukan masih dalam bentuk buku besar, kemungkinan sulit untuk mengkalkulasi atau mendata hal yang diperlukan nantinya sebagai laporan.
* Mengurangi pendataan bisnis menggunakan media kertas.
* Pengkalkulasian secara terkomputerisasi

Dengan alasan tersebut, diperlukan aplikasi yang nantinya diharapkan laporan yang dihasilkan lebih efisien dan terorganisir.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Built With

Untuk membuat Aplikasi ini ada beberapa teknologi yang dibutuhkan.

* [![Android Studio][android-studio]][android-studio-url]
* [![Java][java]][java-url]
* [![SQLite][sqlite]][sqlite-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Features

### Mengelola Data Kategori

![Kategori Menu][category-menu]

Sebelum masuk ke tahap pengelolaan data produk, diperlukan data kategori yang berfungsi untuk mengelompokan produk dengan semestinya.

### Mengelola Data Produk

![Produk Menu][product-menu]

Merupakan tahap pengelolaan data produk, yang nantinya digunakan untuk keperluan dalam tahap pemesanan produk.

### Mengelola Data Varian

![Varian Menu][variant-menu]

Merupakan tahap pengelolaan data varian yang digunakan sebagai opsi setiap adanya pemesanan (misal dalam seblak terdapat varian pedas, sedang, dan tidak pedas)

### Penjualan

Terdapat menu penjualan yang nantinya jika ada pesanan. Terdapat fitur untuk konek ke bluetooth printer (saat ini pengaturannya masih mutlak).

### Laporan Pemasukan

Setelah pesanan selesai dilakukan, data pesanan tersebut masuk ke dalam laporan pemasukan.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Roadmap

- [ ] Buat menjadi support pada semua layar.
- [ ] Buat pengaturan koneksi bluetooth.
- [ ] Buat fitur pengelolaan dan laporan pengeluaran.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED 
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

-->

<!-- USAGE EXAMPLES 
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>

-->

<!-- ROADMAP 
## Roadmap

- [x] Add Changelog
- [x] Add back to top links
- [ ] Add Additional Templates w/ Examples
- [ ] Add "components" document to easily copy & paste sections of the readme
- [ ] Multi-language Support
    - [ ] Chinese
    - [ ] Spanish

See the [open issues](https://github.com/othneildrew/Best-README-Template/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

-->

<!-- CONTRIBUTING 
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

-->

<!-- LICENSE 
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

-->

<!-- CONTACT 
## Contact

Your Name - [@your_twitter](https://twitter.com/your_username) - email@example.com

Project Link: [https://github.com/your_username/repo_name](https://github.com/your_username/repo_name)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

-->

<!-- ACKNOWLEDGMENTS 
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Malven's Flexbox Cheatsheet](https://flexbox.malven.co/)
* [Malven's Grid Cheatsheet](https://grid.malven.co/)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)
* [React Icons](https://react-icons.github.io/react-icons/search)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

-->

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
<!--
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
-->


[product-screenshot]: images/splash_screen.jpg

[android-studio]: https://img.shields.io/badge/Android%20Studio-3DDC84.svg?style=for-the-badge&logo=android-studio&logoColor=white
[android-studio-url]: https://developer.android.com/studio
[java]: https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white
[java-url]: https://openjdk.org/
[sqlite]: https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white
[sqlite-url]: https://www.sqlite.org/index.html

[splash-screen]: images/splash_screen.jpg
[category-menu]: images/category_menu.jpg
[product-menu]: images/product_menu.jpg
[variant-menu]: images/variant_menu.jpg
