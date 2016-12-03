# LaTeX Template
Basic project template for LaTeX created by Stephen Molyneaux.

## Using this Template for a New Project on Linux
- Create an empty repository on github
- Enter following commands in a shell to get the latest version of this template
```bash
wget https://github.com/WimbledonLabs/tex-template/archive/master.zip -O tex-template.zip
unzip tex-template.zip
rm tex-template.zip
```
The template code should be in the directory `tex-template-master`

- Copy the contents of this directory to your project folder
```bash
cp -r tex-template-master/* PATH_TO_PROJECT
```

- Navigate to your project directory, and initialize git for your project
```bash
cd PATH_TO_PROJECT
git init
git add --all
git commit -m "first commit"
git remote add origin https://github.com/YOUR_USERNAME/YOUR_PROJECT_NAME.git
git push -u origin master
```

# Using the Template

## Preparing a Debian Environment for Development
Use apt-get to install texlive
```bash
sudo apt-get install texlive
```

## Compiling Output
Yes, I made a makefile.
```bash
make
```
