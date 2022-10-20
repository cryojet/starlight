<a name="readme-top"></a>
![ProgLang](https://img.shields.io/badge/Language-C%2B%2B-9cf?style=for-the-badge)
![IntToolkit](https://img.shields.io/badge/Interface-Qt5-green?style=for-the-badge)
![Issues](https://img.shields.io/github/issues/nevfuxon/starlight?color=yellow&style=for-the-badge)
![License](https://img.shields.io/github/license/nevfuxon/starlight?color=red&style=for-the-badge)
<br />
<div align="center">
  <a href="https://github.com/nevfuxon/starlight">
    <img src="https://raw.githubusercontent.com/nevfuxon/starlight/extras/resc/logo.png" alt="Starlight Logo" width="80" height="80">
  </a>

  <h3 align="center">Starlight: Qt5 Music Player</h3>

  <p align="center">
    A simple Qt5 music player reworked from <a href="https://github.com/andreisergiu98/music-player-qt5">MPQt5</a>
    <br />
    <a href="https://github.com/nevfuxon/starlight/wiki"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://raw.githubusercontent.com/nevfuxon/starlight/extras/resc/logo.png">View Demo</a>
    ·
    <a href="https://github.com/nevfuxon/starlight/issues">Report Bug</a>
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

![SQt5 Preview](https://raw.githubusercontent.com/nevfuxon/starlight/extras/resc/screenshot.png)

This is `starlight`; a supposed-to-be revival of [MPQt5](https://github.com/andreisergiu98/music-player-qt5) and is also my starting point on Qt5/C++ programming.

Alongside my small projects, this is probably the most promising one out of all of them. While being terrible at first, I'll try to improve it over time :)

But why? We already have better music players; like [`rhythmbox`](https://gitlab.gnome.org/GNOME/rhythmbox), or [`audacious`](https://github.com/audacious-media-player/audacious), or [`juk`](https://github.com/KDE/juk)???

Here's why:
* **All of them are __bloated__**. Without any X components (if you're a psychopath who loves smacking your keyboard in the TTY interface), they all cost around 150+ MBs (which is not a big deal ~~for you~~) What's worse is, the dependencies for a local or a different architecture build is twice the size than dependencies for prebuilt ones.(i disapprove `qemu-user`)
* **Crumpled source files that even you can't make your own out of them**. For professionals, this is not a problem for them at all since there's a guide(that only they can understand, too), but for simpletons... oh well.

Of course, i do not also claim that mine is better. Their music players are a generation ahead of mine and is also the same time, their interface is also as twice as better than a blunt-looking player like mine.


<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [Termux](https://termux.dev/en/)
* [Ubuntu](https://ubuntu.com/)
* [QMake](https://doc.qt.io/qt-6/qmake-manual.html)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

Since I did not have setup the workflow for this repository for an automated build, you'll have to build the package yourself for now.

### Prerequisites

Get dependencies
* GCC, Make, and Git
  ```sh
  sudo apt-get install gcc g++ gdb cmake make build-essential git
  ```
* Qt5 (including dependencies for `multimedia5`)
  ```
  sudo apt-get install qtbase5-dev qtdeclarative5-dev qt5-doc qt5-doc-html qtbase5-doc-html qtbase5-examples qtmultimedia5-dev libqt5multimediawidgets5 libqt5multimedia5-plugins libqt5multimedia5
  ```

### Installation
1. Clone the repository
   ```sh
   git clone https://github.com/nevfuxon/starlight
   ```
2. Change to source directory
   ```sh
   cd starlight/src
   ```
3. Generate makefile and build the binary
   ```sh
   qmake;make
   ```
4. Test run if it works:
   ```sh
   ./QtMusicPlayer
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

No additional arguments are needed when running from the Terminal, but I'll add some. Someday.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [x] redo README
- [x] Refactor source files
- [ ] Add optional arguments for running in terminal
- [ ] Revamp user interface 
- [ ] Multi-language Support
    - [ ] Chinese
    - [ ] Spanish
- [ ] MPD integration
- [ ] ...and more

See this [issue](https://github.com/nevfuxon/starlight/issue/1) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what makes this project better. Any contributions you make are **greatly appreciated**.


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Twitter - [@veuxTW](https://twitter.com/veuxTW)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Acknowledging the following for this project:

* [andreisergiu98/music-player-qt5](https://github.com/andreisergiu98/music-player-qt5)
* [Cantata Music Player: for MPD integration investigation](https://github.com/CDrummond/cantata)
* [Qt5 Toolkit](https://www.qt.io/)
* [GitHub Pages](https://pages.github.com)
* [the entirety of the MIT license](https://opensource.org/licenses/MIT)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
