# pulse
Monitoring PVE, PBS, PMS 


Install:
apt update && apt upgrade -y 
apt install docker.io docker-compose curl -y  
systemctl enable docker --now

mkdir /opt/pulse
chown 100000:100000 /opt/pulse
cd /opt/pulse
nano docker-compose.yml  
...
docker-compose up -d

