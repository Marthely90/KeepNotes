#to get the complet path of a file, this works also for a folder:
  readlink -f file.ext
  realpath file.txt

#to install ZOOM client app:
  - sudo apt -y install wget
  - wget https://zoom.us/client/latest/zoom_amd64.deb
  - sudo apt install ./zoom_amd64.deb
