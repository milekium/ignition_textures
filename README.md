[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

# Ignition Textures
Collection of simple ignition models with textures, intended to be use as a simple place to get textures already in ignition way.


<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## About The Project
ATT: PROJECT IS IN EARLY STATE, PLEASE EXPECT CONSTANT UPDATES AND CHANGES.

[![Product Name Screen Shot][product-screenshot]](https://example.com)


There are many great README templates available on GitHub, however, I didn't find one that really suit my needs so I created this enhanced one. I want to create a README template so amazing that it'll be the last one you ever need.

Here's why:
* Your time should be focused on creating something amazing. A project that solves a problem and helps others
* You shouldn't be doing the same tasks over and over like creating a README from scratch
* You should element DRY principles to the rest of your life :smile:

Of course, no one template will serve all projects since your needs may be different. So I'll be adding more in the near future. You may also suggest changes by forking this repo and creating a pull request or opening an issue.

A list of commonly used resources that I find helpful are listed in the acknowledgments.

### Built With
Main tools used for building this project:
* [Ubuntu 18.04](https://ubuntu.com)
* [Ignition Citadel Binary installation](https://ignitionrobotics.org/docs/citadel)
* [Blender](https://www.blender.org)

<!-- GETTING STARTED -->
## Getting Started

This is an simple example if you are familiar with the ignition or gazebo work flow, for those with no previous experience, it is 
recommended to read documentation in the official [page](https://ignitionrobotics.org/docs/citadel):
To get a local copy up and running follow these simple example steps.

### Prerequisites

To use this textures you need a working space with ignition ready.
to install ignition-citadel, please visit the official documentation [page](https://ignitionrobotics.org/docs/citadel):


### Installation

1. Create a working space and Clone the repo:
```sh
cd ~
mkdir ign_ws & cd ign_ws
git clone https://github.com/milekium/ignition_textures.git
```
2. Run the World with the models inside:
```sh
ign gazebo ~/ign_ws/ignition_textures/textures_world.sdf
```
  -Optional
Enter your log errors into the console with:
```sh
ign gazebo ~/ign_ws/ignition_textures/textures_world.sdf
```
3. Load another model:
For load different models, you need to edit the textures_world.sdf file to change the uri as:
```xml
109      <uri>file:///~/ign_ws/ignition_textures/mossy_bark/</uri>
```
to 
```xml
109      <uri>file:///~/ign_ws/ignition_textures/ground_forest/</uri>
```

<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_



<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/milekium/ignition_textures/issues) for a list of proposed features (and known issues).



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

Milekium - milekium@protonmail.com

Project Link: [https://github.com/milekium/ignition_textures](https://github.com/milekium/ignition_textures)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
3er Party Textures from:
* [Freepbr.com](https://freepbr.com)
* [poliigon.com](https://help.poliigon.com/en/)
* [Choose an Open Source License](https://choosealicense.com)
* [blendswap.com](https://www.blendswap.com/search?keyword=brush)
* [cc0textures.com](https://cc0textures.com/list?q=&method=&type=&sort=Downloads)



<!-- MARKDOWN LINKS & IMAGES -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/milekium
[product-screenshot]: images/screenshot.png