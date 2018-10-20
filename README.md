# Artierra

![logo](resources/logo.png)

## About

...

## Setup

### Install pip

Run the following commands to download and install pip, using python:

```
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
sudo python get-pip.py
```

Then you can remove the downloaded file:

```
rm -f get-pip.py
```

### Upgrading pip

On Linux or MacOS:

```
pip install -U pip
```

On Windows:

```
python -m pip install -U pip
```

### Install Dependencies

Make sure you are at the root of the project.
Run the following to install all the dependencies.

```
pip install --ignore-installed --user -r requirements.txt

```

If any error comes up, feel free to open an issue :)

#### Dependencies List

The following packages are needed to run the python project.

- nose
- tornado
- numpy
- scipy
- pandas
- keras
- pillow
- tensorflow

## Resources

- [Making AI Art with Style Transfer using Keras](https://medium.com/mlreview/making-ai-art-with-style-transfer-using-keras-8bb5fa44b216)
- [Logo - Earth Icon](http://www.endlessicons.com/free-icons/earth-icon/)
