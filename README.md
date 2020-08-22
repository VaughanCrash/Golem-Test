# Golem-Test

Testing Alpha on Ubuntu 20.4.1 ...

Ran straight off a usb key live installer as I don't usually run Ubuntu.

Ran into trouble with python3-venv (Ubuntu had python3.8 installed) requiring the following:

After a bit of googleing and not much luck, had to install 3.6

sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt update
sudo apt install python3.6
sudo apt install python3.6-venv

after then everything went peachy.

[See here for screencast](https://drive.google.com/file/d/1BTLa04instVchr0ce1H6G30eJhzM7u2k/view?usp=sharing)
