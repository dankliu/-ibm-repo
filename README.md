## Turbo Image Download

```console
git clone https://github.com/dankliu/ibm-repo.git
cd ibm-repo/turbo-image
cat turbo-backup-image-20220802.zip* > ~/turbo-backup-image-20220802.zip
unzip ~/turbo-backup-image-20220802.zip
```

## Turbo Image Script
```console
tar zxvf ibm-turbo-install-paks-20220726.tar.gz
cd ibm/turbo-image-script
```

Step 1. Use shell load_docker_image.sh sync tar file to Local Docker. (Edit script imagePath to unzip image folder path). 

Step 2. Use shell push_docker_registry.sh push Local Image to Private Docker Registry (Edit Script registry to TSMC Private Registry path). 
