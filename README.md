#Задача 1  
![Снимок экрана от 2024-01-13 14-11-34](https://github.com/JustAleksy/05-virt-04-docker-in-practice/assets/143338652/19b30259-f9a8-4659-be96-612da2cf278a)
![Снимок экрана от 2024-01-13 14-10-24](https://github.com/JustAleksy/05-virt-04-docker-in-practice/assets/143338652/214d04cd-cc6e-4a25-9989-145403b38188)

#Задача 2  
[vulnerabilities.csv](https://github.com/JustAleksy/05-virt-04-docker-in-practice/files/13931923/vulnerabilities.csv)

#Задача 3  
![Снимок экрана от 2024-01-14 12-40-37](https://github.com/JustAleksy/05-virt-04-docker-in-practice/assets/143338652/ad6f3dfa-479a-4b83-b63f-a2d34311f368)

#Задача 4  
![Снимок экрана от 2024-01-14 16-48-01](https://github.com/JustAleksy/05-virt-04-docker-in-practice/assets/143338652/05806941-19c3-4d2b-ab4f-f48106cfb083)

#Скрипт:  
#!/bin/bash  

CLONE_DIR="/opt/shvirtd-example-python"  
sudo git clone https://github.com/JustAleksy/shvirtd-example-python.git "$CLONE_DIR"  
cd "$CLONE_DIR" || exit  
sudo docker compose -f proxy.yaml up -d  
sudo docker compose up -d  

Ссылка на форк:  
https://github.com/JustAleksy/shvirtd-example-python.git

Задача 6  
![Снимок экрана от 2024-01-14 17-51-43](https://github.com/JustAleksy/05-virt-04-docker-in-practice/assets/143338652/17c57c9e-8fb6-43cc-9bb7-9ba584cdbda3)
![Снимок экрана от 2024-01-14 17-42-32](https://github.com/JustAleksy/05-virt-04-docker-in-practice/assets/143338652/08793625-ef74-4f4a-aae5-4ada796d0cbb)



