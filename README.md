# LaTeX Note Taking Template

This is a template to take notes for University Lectures, courses or whatever
notes you want to take.

## Dependencies

Make sure to install `texlive-full` and `texlive-latex-extra`.

```shell
# Ubuntu and some Debian based distros.
sudo apt install texlive-latex-extra texlive-full -y
# Arch and some Arch based distros.
sudo pacman -S texlive-fontsextra texlive-core texlive-latexextra texlive-pictures texlive-science
```


## Build

To build manually, just use `pdflatex`:
```shell
# Run this command inside the folder of whatever version you want.
pdflatex main.tex
```

## How it looks

### General Version.

<p>
    <img src="Assets/General_Version_00.png" alt="General_Version_00" width="250"/>
    <img src="Assets/General_Version_01.png" alt="General_Version_01" width="250"/>
</p>

### EAFIT Version.

<p>
    <img src="Assets/EAFIT_Version_00.png" alt="EAFIT_Version_00" width="250"/>
    <img src="Assets/EAFIT_Version_01.png" alt="EAFIT_Version_01" width="250"/>
</p>

## Uploading to Overleaf EAFIT Latex Teamplate 

1. **Clone the Repository**  

   ```shell
   git clone https://github.com/Youngermaster/LaTex-Note-Taking-Template
   cd LaTex-Note-Taking-Template

3. **Compress the Folder**

   ```shell
    zip -r EAFIT_Version.zip EAFIT_Version/

Go to Overleaf
Click on Upload Project
Select EAFIT_Version.zip

and you will have access to the template the eafit


## Acknowledgement

I used this [LaTeX template](https://www.overleaf.com/latex/templates/report-template-v1-dot-0/xvtpxwgvmwyr) from **Kerr Beeldens** as a base for this one.
