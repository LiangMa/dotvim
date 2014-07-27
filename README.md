
#How to use the dovim from aonther box without all settings
cd ~

git clone http://github.com/username/dotvim.git ~/.vim

ln -s ~/.vim/vimrc ~/.vimrc


cd ~/.vim

git submodule init
git submodule update

git submodule foreach git pull origin master

