# dnsmasq docker container


### systemd

```
git clone https://github.com/turing-machines/dnsmasq-docker
cd dnsmasq-docker

docker build -t turing-machines/dnsmasq .

cp dnsmask.docker.service /etc/systemd/system

sudo systemctl enable dnsmasq.service
sudo sustemctl start dnsmasq.service

```

