# ml5 Examples
[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors)

## Description

This repository contains a collection of  examples using [ml5.js](https://github.com/ml5js/ml5-library). The examples are meant to serve as an introduction to the library and machine learning concepts.

Examples are organized into folders according to their integration with other JavaScript libraries.

For example, the `/p5js` folder holds examples of using [ml5.js](https://github.com/ml5js/ml5-library) with [p5.js](https://p5js.org/). All examples are self-contained and can be run independently. Libraries are loaded through a Content Delivery Network (CDN) and certain examples (indicated in code comments) download a machine learning model from a "cloud" url. This means that ml5 currently relies on an internet connection in order to retrieve pre-trained models (unless they are served locally). 

Instead of using the CDN links to p5 and ml5, you can [download the p5.js libraries here](https://github.com/processing/p5.js/releases) and [ml5 library here](https://github.com/ml5js/ml5-library/releases).

## Usage

Download or clone this repository:
```
git clone https://github.com/ml5js/ml5-examples.git
```

Change directory into the new folder and start a server.
An easy way to start a server is with python. If you are have python 2:
```
cd ml5-examples
python -m SimpleHTTPServer
```
If you are have python 3:
```
cd ml5-examples
python -m http.server
```

If you don't know how to start a server, check [this](https://github.com/processing/p5.js/wiki/Local-server) guide.

## Examples Index

Below is the current `release` examples index:

### javascript

ml5.js does not require p5.js, however as ml5.js and p5.js have been designed to play nicely with eachother, most of our examples currently are developed together with p5.js. The following "vanilla" javascript examples showcase the use of ml5 without p5.js.

* [FeatureExtractor_Image_Classification](https://luckh2.github.io/a/javascript/FeatureExtractor_Image_Classification)
* [ImageClassification_Video](https://luckh2.github.io/a/javascript/ImageClassification_Video)
* [ImageClassification](https://luckh2.github.io/a/javascript/ImageClassification)
* [StyleTransfer_Image](https://luckh2.github.io/a/javascript/StyleTransfer_Image)
* [PoseNet](https://luckh2.github.io/a/javascript/PoseNet)

### p5js

* [CVAE](https://luckh2.github.io/a/p5js/CVAE)
* [BodyPix_Image](https://luckh2.github.io/a/p5js/BodyPix/BodyPix_Image/)
* [BodyPix_Webcam](https://luckh2.github.io/a/p5js/BodyPix/BodyPix_Webcam)
* [BodyPix_Webcam_Parts](https://luckh2.github.io/a/p5js/BodyPix/BodyPix_Webcam_Parts)
* [DCGAN](https://luckh2.github.io/a/p5js/DCGAN)
* [Sentiment](https://luckh2.github.io/a/p5js/Sentiment)
* [UNET](https://luckh2.github.io/a/p5js/UNET/UNET_webcam)
* [Word2Vec](https://luckh2.github.io/a/p5js/Word2Vec)
* [FeatureExtractor_Image_Classification](https://luckh2.github.io/a/p5js/FeatureExtractor/FeatureExtractor_Image_Classification)
* [FeatureExtractor_Image_Regression](https://luckh2.github.io/a/p5js/FeatureExtractor/FeatureExtractor_Image_Regression)
* [StyleTransfer_Video](https://luckh2.github.io/a/p5js/StyleTransfer/StyleTransfer_Video)
* [StyleTransfer_Image](https://luckh2.github.io/a/p5js/StyleTransfer/StyleTransfer_Image)
* [ImageClassification_Video](https://luckh2.github.io/a/p5js/ImageClassification/ImageClassification_Video)
* [ImageClassification_VideoScavengerHunt](https://luckh2.github.io/a/p5js/ImageClassification/ImageClassification_VideoScavengerHunt)
* [ImageClassification](https://luckh2.github.io/a/p5js/ImageClassification/ImageClassification)
* [ImageClassification_VideoSoundTranslate](https://luckh2.github.io/a/p5js/ImageClassification/ImageClassification_VideoSoundTranslate)
* [ImageClassification_VideoSound](https://luckh2.github.io/a/p5js/ImageClassification/ImageClassification_VideoSound)
* [ImageClassification_MultipleImages](https://luckh2.github.io/a/p5js/ImageClassification/ImageClassification_MultipleImages)
* [KNNClassification_VideoSound](https://luckh2.github.io/a/p5js/KNNClassification/KNNClassification_VideoSound)
* [KNNClassification_Video](https://luckh2.github.io/a/p5js/KNNClassification/KNNClassification_Video)
* [KNNClassification_PoseNet](https://luckh2.github.io/a/p5js/KNNClassification/KNNClassification_PoseNet)
* [KNNClassification_VideoSquare](https://luckh2.github.io/a/p5js/KNNClassification/KNNClassification_VideoSquare)
* [SketchRNN_basic](https://luckh2.github.io/a/p5js/SketchRNN/SketchRNN_basic)
* [SketchRNN_interactive](https://luckh2.github.io/a/p5js/SketchRNN/SketchRNN_interactive)
* [PitchDetection_Game](https://luckh2.github.io/a/p5js/PitchDetection/PitchDetection_Game)
* [PitchDetection](https://luckh2.github.io/a/p5js/PitchDetection/PitchDetection)
* [CharRNN_Interactive](https://luckh2.github.io/a/p5js/CharRNN/CharRNN_Interactive)
* [CharRNN_Text](https://luckh2.github.io/a/p5js/CharRNN/CharRNN_Text)
* [CharRNN_Text_Stateful](https://luckh2.github.io/a/p5js/CharRNN/CharRNN_Text_Stateful)
* [Pix2Pix_callback](https://luckh2.github.io/a/p5js/Pix2Pix/Pix2Pix_callback)
* [Pix2Pix_promise](https://luckh2.github.io/a/p5js/Pix2Pix/Pix2Pix_promise)
* [YOLO_webcam](https://luckh2.github.io/a/p5js/YOLO/YOLO_webcam)
* [YOLO_single_image](https://luckh2.github.io/a/p5js/YOLO/YOLO_single_image)
* [PoseNet_image_single](https://luckh2.github.io/a/p5js/PoseNet/PoseNet_image_single)
* [PoseNet_webcam](https://luckh2.github.io/a/p5js/PoseNet/PoseNet_webcam)
* [PoseNet_part_selection](https://luckh2.github.io/a/p5js/PoseNet/PoseNet_part_selection)

## p5.js web editor examples

The p5.js examples can also be run using the [p5.js web editor](https://alpha.editor.p5js.org). We are [in the process of porting](https://github.com/ml5js/ml5-examples/issues/6) and would welcome any contributions!

You can find all of our examples here:
* [ml5 on editor.p5js.org](https://editor.p5js.org/ml5/sketches)

NOTE: not all of the ml5.js examples are currently working on the p5.js web editor. Stay tuned for updates!

## Contributing

See CONTRIBUTING.MD

## Contributors

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
<table><tr><td align="center"><a href="https://wakatime.com/@barakplasma"><img src="https://avatars0.githubusercontent.com/u/62937?v=4" width="100px;" alt="Michael Salaverry"/><br /><sub><b>Michael Salaverry</b></sub></a><br /><a href="#content-barakplasma" title="Content">🖋</a> <a href="https://github.com/ml5js/ml5-examples/issues?q=author%3Abarakplasma" title="Bug reports">🐛</a></td></tr></table>

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
