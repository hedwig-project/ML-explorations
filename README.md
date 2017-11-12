To set a virtualenv, to run this app locally:

sudo apt-get update  
sudo apt-get install xmlsec1  
sudo apt-get install python-dev libxml2-dev libxslt1-dev zlib1g-dev  
sudo apt-get install libxslt-dev libxml2-dev  
sudo pip install virtualenv  
sudo pip install virtualenvwrapper  
mkdir $HOME/envs  
export WORKON_HOME=$HOME/envs  
source /usr/local/bin/virtualenvwrapper.sh -p $WORKON_HOME  
mkvirtualenv --py python3 ML  
setvirtualenvproject  
source $HOME/envs/cte/ML/activate  
pip install -r pip-requirements.txt  