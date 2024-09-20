# neuvector

<img width="1485" alt="image" src="https://github.com/user-attachments/assets/a899063e-2fec-436f-8789-eaf7a5a5fa69">

```
helm repo add neuvector https://neuvector.github.io/neuvector-helm
helm repo update

helm upgrade --install nuevector neuvector/core --namespace neuvector --set tag=5.4.0 --create-namespace -f values.yaml
```

## autoscan

if you want to scan automatically go to assetss-> nodes click autoscan enable

<img width="1505" alt="image" src="https://github.com/user-attachments/assets/1cbc4a6f-3e14-410b-a724-13f44a79e221">

## registry scan

neuvector also scan registry. you can add all registry types azure, aws, nexus, jfrog vs vs

for example dockerhub below you can add and scan all images.

<img width="1099" alt="image" src="https://github.com/user-attachments/assets/3b4fcc20-338c-4528-a6a3-5067ae02d984">

