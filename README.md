## Turbo Image Download

git clone https://github.com/dankliu/ibm-repo.git

## Turbo Image Script
tar zxvf ibm-turbo-install-paks-20220726.tar.gz
cd ibm/turbo-image-script

Step 1. Use shell load_docker_image.sh sync tar file to Local Docker. (Edit script imagePath to unzip image folder path). 

Step 2. Use shell push_docker_registry.sh push Local Image to Private Docker Registry (Edit Script registry to TSMC Private Registry path). 
