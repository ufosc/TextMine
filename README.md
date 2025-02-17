# DocuMiner

A production-ready pipeline for text mining and subject indexing

## Installation

In order to run this project, it will require many dependencies. \
Since it is written mostly in Python, you will need to install python. \
Dependency packages should then be able to be installed using ``pip``. \
To find the dependencies, go to ``requirements.txt`` and ensure all are installed on your system.

To install dependencies, you can download the latest version of each one quickly: \
``pip install -r requirements.txt``

However, if this fails, you can download the latest version of individual packages manually. \
``pip install DEPENDENCY`` \
If this fails, you can also run \
``pip install DEPENDENCY --user``

Should en_core_web_sm fail to install, then run these commands:
1. ``python -m spacy download en``
2. ``python -m spacy download en_core_web_sm``

From here, all required libraries should be installed on your system. \
This will allow you to do tokenizers, configuration, and file/data utilities.

Optionally, you can also install a few extra utilities if you wish to use the modeling features.
- PyTorch, ``torch``
- TensorFlow, ``tensorflow``
- Flax, ``flax``
The install process is the same as using the previous ``pip install`` commands.

## Run

From the working directory, run \
``python preprocessing/driver.py`` \
This will launch the main function, which will prompt you for text location. \
If you wish to use the included sample texts, ensure that you input \
``preprocessing/sampleTxt`` \
for the directory, and from there input any ``sample[X].txt`` of the files.

## Want to Contribute?

To contribute, there are no special requirements, just fork and submit a pull request for the maintainers to review. \
More code and documentation coming soon.

## Authors

Open Source Club
