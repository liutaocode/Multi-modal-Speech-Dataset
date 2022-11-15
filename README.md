# Multi-modal Speech Dataset

``SD``: Speaker Diarization, ``LR``: Lip reading, ``SV``: Speaker Verfication, ``ASR``, Automatic Speech Recognition, ``ASD``: Active Speaker Detection, ``SS``: Speech Separation

|   Dataset  |  Hours   |  Scenario   |  Demos   |  URL   | Fees|Purpose|
|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
|   AMI  |   100  |   Meeting  |   -  | [URL](https://groups.inf.ed.ac.uk/ami/corpus/)   | Free | ``SD`` |
|LRW|173|BBC|[demo](https://www.robots.ox.ac.uk/~vgg/data/lip_reading/visualisation.htm)|[URL](https://www.robots.ox.ac.uk/~vgg/data/lip_reading/lrw1.html)|Free| ``LR``|
|LRS2|225|BBC|-|[URL](https://www.robots.ox.ac.uk/~vgg/data/lip_reading/lrs2.html)|Free|``ASR``,``LR``|
|LRS3|438|TED|-|[URL](https://www.robots.ox.ac.uk/~vgg/data/lip_reading/lrs3.html)|Free|``ASR``,``LR``|
|VoxCeleb1|352|YouTube Celebrities|-|[URL](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/vox1.html)|Free|``ASR``, ``SV``, ``SS``|
|VoxCeleb2|2441|YouTube Celebrities|-|[URL](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/vox2.html)|Free|``ASR``, ``SV``, ``SS``|
|AVSpeech|4700|YouTube|[demo](https://looking-to-listen.github.io/avspeech/explore.html)|[URL](https://looking-to-listen.github.io/avspeech/)|Free| ``SS``|
|AVA-ActiveSpeaker|38.5|YouTube Movie|-|[URL](https://github.com/cvdfoundation/ava-dataset)|Free|``ASD``|
|AVA-AVD|29|YouTube Movie|-|[URL](https://github.com/cvdfoundation/ava-dataset)|Free| ``SD``|
|MSDWild|80|YouTube Conversation|[demo](https://x-lance.github.io/MSDWILD/)|[URL](https://github.com/X-LANCE/MSDWILD)|Free|``ASD``, ``SD``|
|MISP|127|Home Chat|[demo](https://mispchallenge.github.io/mispchallenge2022/overview.html)|[URL](https://mispchallenge.github.io/mispchallenge2022)|Free|``ASR``, ``SD``|


* ``AMI``, ``AVA-ActiveSpeaker``, ``MSDWild`` and ``MISP`` provide the original video (not cropped faces).
* ``LRS2``, ``LRS3`` and ``VoxCeleb2`` provide cropped face videos.
* ``VoxCeleb1`` does not provide cropped face, but [this repo](https://github.com/AliaksandrSiarohin/video-preprocessing) provides the processed result([URL](https://drive.google.com/u/0/uc?id=1VLhAbzbrexqg-nHq8l1AV8oc-Sq-x0kZ)) by downloading and processing the original videos .
* ``AVSpeech`` only provides download ids of YouTube, lots of videos are missing.
