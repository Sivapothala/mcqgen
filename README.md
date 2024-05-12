> to Create a Virtual env 
    python -m venv <env-name>
setup.py -> to install local package in our virtual environment

to install local package into virtual env just add "-e ." to requirements.txt (or)
python setup.py install

pip install -r requirements.txt to install all the packages

# for hosting the project in AWS 

first login to the AWS: https://aws.amazon.com/console/

search about the EC2

you need to config the UBUNTU Machine

launch the instance

update the machine:

sudo apt update

sudo apt-get update

sudo apt upgrade -y

sudo apt install git curl unzip tar make sudo vim wget -y

git clone "Your-repository"

sudo apt install python3-pip

pip3 install -r requirements.txt

python3 -m streamlit run StreamlitAPP.py

if you want to add openai api key
create .env file in your server touch .env
vi .env #press insert #copy your api key and paste it there #press and then :wq and hit enter

go with security and add the inbound rule add the port 8501
