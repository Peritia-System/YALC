# Install Recommended Services

All of the steps in this section are optional.
You can skip them and install the packages later as needed.
These are recommended for a smoother setup experience.

---

## 1. Open the Terminal

You will use the terminal frequently throughout this course.
It will become an essential tool both during and after the course.

---

## 2. Install Recommended Packages

Run the following commands to update your system and install some useful tools:

```bash
sudo dnf update

sudo dnf install \
git \
flatpak \
zip \
unzip \
nano \
python \
pip
```

If prompted for confirmation, press **Y** to continue.

---

## 3. Set Up Flatpak and Flathub

Flatpak allows you to install a wide range of Linux applications easily.

Run the following command to add the Flathub repository (if it isn’t already added):

```bash
sudo flatpak remote-add --if-not-exists flathub https://dl.flathub.org/repo/flathub.flatpakrepo
```

---

## 4. Install an IDE

To install an Integrated Development Environment ([IDE](https://en.wikipedia.org/wiki/Integrated_development_environment)), run:

```bash
sudo flatpak install flathub com.vscodium.codium
```
If prompted for confirmation, press **Y** to continue.


---
