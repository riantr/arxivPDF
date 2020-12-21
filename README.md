# arxivPDF
A little shell script for download ( and organize ) papers from arxiv.org.

# Install 
- [Mac] <br>
$ brew install zathura <br>
$ chmod +x arxivPDF <br>
$ cp arxivPDF ~/.local/bin
$ echo 'export PATH="$HOME/.local/bin:$PATH"' >> ~/.zshrc
$ source ~/.zshrc

- [Linux] <br>
$ sudo apt install zathura <br>
$ chmod +x arxivPDF <br>
$ cp arxivPDF ~/.local/bin
$ echo 'export PATH="$HOME/.local/bin:$PATH"' >> ~/.bashrc
$ source ~/.bashrc

# Usage
$ arxivPDF xxx.xxxxx [tag] <br>
example: arxivPDF 2004.10934 yolo

