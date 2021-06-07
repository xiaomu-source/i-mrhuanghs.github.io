Project
=======
Hugo-blog

Hugo
=======
Hugo Static Site Generator v0.80.0/extended darwin/amd64

Deployment
----------
# How to set up the backend system on Ubuntu

The backend system is deployed on Ubuntu. Below are dependencies required.
1. Build dependency
    - Install libs
        sudo apt-get install hugo
# How to set up the backend system on OS X

## Preparation

1. Install [Homebrew](http://brew.sh/index.html "Homebrew/brew")

	Homebrew is a free and open-source software package management system
	that simplifies the installation of software on OS X.

	~~~~
   ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
   ~~~~
   
2. Install Hugo

    brew install hugo
    
   **Notice** that the Hugo version for Hugo-blog is v0.80.0
   
   

## Installation

1. Download source of the backend system

   ~~~~
   # configure git if not configured
   git config --global user.name "<your full name>"
   git config --global user.email <your email>
   git config --global core.editor vim
   # choose whatever name you like
   mkdir github
   cd github
   git clone git@github.com:i-mrhuanghs/hugo-blog.git hugo-blog
   cd hugo-blog
   git clone git@github.com:i-mrhuanghs/i-mrhuanghs.github.io.git public
   ~~~~

2. Run the backend system

    ~~~~
    #Start the backend system
    hugo server -D
    ~~~~