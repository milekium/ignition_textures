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

[![Protoros][product-screenshot]](https://protoros.com)


Ignition is part of the great [Ros](https://index.ros.org/doc/ros2/) (Robot Operation System) ecosystem. New releases of Ros as Ros2, come with new features and exiting capabilities for the robot development. Ignition is to be consider the new implementation of Gazebo for the world and robot simulation, this project is intended to explore the new features of ignition.  

Motivation:
* Robot simulation makes robot development more fast and reliaveble. 
* World simulation with high detials and non predictable interactions, makes the simulation more valuable.
* World simulations and robot deployment can be fun :smile:

Of course, the goal of this project is to facilitate robot developers working with ros to test theirs robots in more complex and complete worlds, while reducing the time to develop this worlds.

Some resources that I use for this project and may be helpful are listed in the acknowledgments.

### Built With
Main tools used for building this project:
* [Ubuntu 18.04](https://ubuntu.com)
* [Ignition Citadel Binary installation](https://ignitionrobotics.org/docs/citadel)
* [Blender](https://www.blender.org)

<!-- GETTING STARTED -->
## Getting Started

This is an simple example if you are familiar with the ignition or gazebo work flow, for those with no previous experience, it is recommended to read documentation in the official [page](https://ignitionrobotics.org/docs/citadel):
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
ign gazebo ~/ign_ws/ignition_textures/textures_world.sdf  --verbose
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

Here are some examples included in the project to show different textures applied to different objects:
|Model Name| ""  | ""  | "" |  
|:---:|:---:|:---:|:---:|
| Ground Forest Texture | ![ ][texture1-screenshot] | ![ ][texture1-screenshot1] | ![ ][texture1-screenshot2] |
| Ground Rock Texture | ![][texture2-screenshot] | ![][texture2-screenshot1] | ![][texture2-screenshot2] |
| Another Groun Rock | ![][texture3-screenshot] | ![][texture3-screenshot1] | ![][texture3-screenshot2] |
| Mossy Bark | ![][texture4-screenshot] | ![][texture4-screenshot1] | ![][texture4-screenshot2] |
| Wood Case | ![][texture5-screenshot] | ![][texture5-screenshot1] | ![][texture5-screenshot2] |

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
[product-screenshot]: thumbnails/1.png

[texture1-screenshot]: ground_forest/thumbnails/1.png
[texture1-screenshot1]: ground_forest/thumbnails/2.png
[texture1-screenshot2]: ground_forest/thumbnails/3.png

[texture2-screenshot]: ground_rock/thumbnails/1.png
[texture2-screenshot1]: ground_rock/thumbnails/2.png
[texture2-screenshot2]: ground_rock/thumbnails/3.png

[texture3-screenshot]: ground_rock22/thumbnails/1.png
[texture3-screenshot1]: ground_rock22/thumbnails/2.png
[texture3-screenshot2]: ground_rock22/thumbnails/3.png


[texture4-screenshot]: mossy_bark/thumbnails/1.png
[texture4-screenshot1]: mossy_bark/thumbnails/2.png
[texture4-screenshot2]: mossy_bark/thumbnails/3.png

[texture5-screenshot]: wood_case/thumbnails/1.png
[texture5-screenshot1]: wood_case/thumbnails/2.png
[texture5-screenshot2]: wood_case/thumbnails/3.png
