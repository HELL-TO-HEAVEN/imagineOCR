# **ImagineOCR**
<p align="center">
    <img src="Resources/Banner.png" width="890" alt="Logo"/>
</p>

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0) [![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-v1.4%20adopted-ff69b4.svg)](CODE_OF_CONDUCT.md) ![semver](https://img.shields.io/badge/semver-2.0.0-blue) [![codebeat badge](https://codebeat.co/badges/b2812d59-2a46-4ccd-b6c8-d3e909742c08)](https://codebeat.co/projects/github-com-marcoistasy-imagineocr-master)

ImagineOCR represents a fundamental restructuring of image-to-text software. Abandoning previous principles emphasising static models of orthography, imagine OCR approaches OCR as the province of object detection. Accordingly, it views each character on a page as a discrete object and allows training of a custom faster-rcnn implementation given as little as a single instance of the objects (read: characters) to be detected. 

## Using This Project
For instructions on how to get started using this project, please visit our [official wiki](https://www.notion.so/Wiki-3c27906875224f3c9509deec23a98bb0). 

## Roadmap
For our planned features and reported bugs, please visit our [official roadmap](https://www.notion.so/39742f2396ae47d9ac848f2df7112ca3?v=48efbd1371a44f42801d0ab4b3075bc3).

## Built With

* [Tensorflow](https://www.tensorflow.org)
* [Tensorflow Object Detection API](https://github.com/tensorflow/models/tree/master/research/object_detection)
* [LabelImg](https://github.com/tzutalin/labelImg)

## Contributing
Please read [CONTRIBUTING.md](https://github.com/marcoistasy/imagineOCR/blob/master/CONTRIBUTING.md) for the process for submitting pull requests to us. Also make sure to read our [CODE_OF_CONDUCT.md](https://github.com/marcoistasy/imagineOCR/blob/master/CODE_OF_CONDUCT.md).

## Versioning
We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/marcoistasy/imagineOCR/releases). 

## Authors

* **[Marco Istasy](https://github.com/marcoistasy)**

See also the list of [contributors](https://github.com/marcoistasy/imagineOCR/graphs/contributors) who participated in this project.

## License

Released under the [GLP-3.0](https://github.com/marcoistasy/imagineOCR/blob/master/LICENSE) license.

## Acknowledgments

* Sincerest thanks to Kieren Nicôlas and Stephen Lovell for their continued support and unwavering belief in the project.
