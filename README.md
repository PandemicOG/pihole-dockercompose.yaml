everything you need to get pihole running in one simple file

install docker and docker compose

sudo apt update && sudo apt upgrade -y

curl -sSL https://get.docker.com | sh

sudo usermod -aG docker $USER

docker run hello-world


install docker compose

sudo apt-get install libffi-dev libssl-dev

sudo apt install python3-dev

sudo apt-get install -y python3 python3-pip

sudo pip3 install docker-compose

sudo systemctl to enable Docker



git clone https://github.com/PandemicOG/pihole-dockercompose.yaml.git

cd pihole-dockercompose.yaml

docker compose up -d
