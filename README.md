# LaTeX Template
Basic project template for LaTeX created by Stephen Molyneaux.

## Using this Template for a New Project on Linux
- [Create a repository on github](https://github.com/new)
- Set the following variables in your shell
```bash
export USERNAME=WimbledonLabs # Replace with YOUR github username
export PROJECT=name-of-repo # Replace the name of the repository you just created
```
- Navigate to your desired project directory (must be empty)
- Enter following commands in a shell to get the latest version of this template
```bash
git clone https://github.com/$USERNAME/$PROJECT.git .

wget https://github.com/WimbledonLabs/tex-template/archive/master.zip
unzip master.zip

mv -n tex-template-master/* .
rm master.zip
rm tex-template-master/ -r

git add --all
git commit -m "Imported WimbledonLabs/tex-template"
git push
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
