#!/bin/bash

/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

brew install git

sudo easy_install pip
sudo pip install pycurl

brew install ansible

sudo pip install boto msrest msrestazure azure==2.0.0rc5 dopy==0.3.5 "apache-libcloud>=1.5.0" linode-python pyrax
mkdir -p ~/Library/Python/2.7/lib/python/site-packages
echo '/usr/local/lib/python2.7/site-packages' > ~/Library/Python/2.7/lib/python/site-packages/homebrew.pth

cd

rm -rf streisand

git clone https://github.com/jlund/streisand.git && cd streisand

./streisand
