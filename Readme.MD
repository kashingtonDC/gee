
# Requirements: Python2, git, conda or virtualenv

## Setup

`git clone` this repository

`conda create --name ee`

`source activate ee`

`pip install google-api-python-client`

`pip install pyCrypto`

`pip install earthengine-api`

Test the install: 
`python -c "import ee; ee.Initialize()"`

Input your earth engine credentials (the ones you used to register the account). If this works everything is set up correctly

Now open a terminal and `cd` to this directory and run

`jupyter notebook`

Click on the motebook and execute the cells

# Credit
to the ee community, particularly  [Tyler Erickson](http://https://github.com/tylere) and [Ate Poortinga](http://mygeoblog.org). Some of this content is directly from tutorials they have posted