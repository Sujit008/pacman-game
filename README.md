**************************

Steps to Install PACMAN Game 

1. Create NamesSpace --  kubectl create namespace pacman  
Run kubectl apply -f ns-pacman.yaml

2. Create PV and PVC -- size 2 GB -- Type - - FileSystem
Run kubectl apply -f pv-mogo.yaml -n pacman
Run Kubectl apply -f mongo-pvc.yaml -n pacman

3. Create 

