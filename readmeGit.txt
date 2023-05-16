sudo apt update
sudo apt install docker.io
git clone copyPath/..
ls
cd fileName/
sudo docker build -t imgName .
sudo docker images (check imgName status)
sudo docker run -d -p 7667:7667 imgName
		(port no : port no) check from dockerfile	
sudo docker ps (check running image)
open chrome copy ipv4:7667 