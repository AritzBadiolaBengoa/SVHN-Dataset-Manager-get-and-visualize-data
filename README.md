# Getting and visualizing data from SVHN

The Street View House Numbers ([SVHN](http://ufldl.stanford.edu/housenumbers/)) Dataset, as expressed in the link, "is a real-world image dataset for developing machine learning and object recognition algorithms with minimal requirement on data preprocessing and formatting". It is a dataset created using images of house numbers got from Google Street View and labeled.

Main Functions of the program:

- **Downloading the dataset.**

- **Loading the dataset.**

- **Visualizing the images from the dataset and their labels.**
  - The label '0' has been replaced by '10'.

The project has been developed using *Jupyter Notebook* and has been tested in [Python 3.8](https://www.python.org/downloads/release/python-380/). 

## Installation
First of all it is necessary to install [Jupyter Notebook](https://jupyter.org/install). Follow the instructions included in the link depending on the preferences of each one.

Use the requirements.txt file and [pip](https://pip.pypa.io/en/stable/) to install all the required libraries automatically.

```bash
pip install -r .\requirements.txt
```
## Data
*All the necessary data is downloaded using the code*, anyway if it is prefered to download the data from Google Drive (it can take a lot of time from the original sources) or there is any problem when downloading the data using the code, it is provided in the following [Google Drive link](https://drive.google.com/drive/folders/115BxS5N7y7Oi6dZfKyTMzMpXuqfxxTln?usp=sharing). Include the files in the root path of the project.

**Basics about the SVHN dataset**:
- There are 10 classes: from '1' to '10' ('0' by default but changed to 10 in the code)
- In this case only the cropped digits have been included.
- Each sample contains the RGB data and the image index.

## Usage

The code is self-explanatory, and additional comments are included to clarify what tasks are performed and/or why are perfomed.

The output of the application is the image of the house number in 32x32 pixels and the label, so, the digit that the image contains.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
Details included in the LICENCE.txt file.
