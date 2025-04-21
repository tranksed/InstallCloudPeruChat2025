DESCARGANDO EL INSTALADOR E INICIANDO LA PRIMERA INSTALACIÓN (USAR SOLO PARA LA PRIMERA INSTALACIÓN):

```bash
sudo apt install -y git && git clone https://github.com/tranksed/InstallCloudPeruChat2025.git install && sudo chmod -R 777 ./install && cd ./install && sudo ./install_primaria
```

ACCEDIENDO AL DIRECTORIO DEL INSTALADOR E INICIANDO INSTALACIONES ADICIONALES (USAR ESTE COMANDO PARA LA SEGUNDA O MÁS INSTALACIONES):
```bash
cd && cd ./install && sudo ./install_instancia
```

EN CASO DA ERROR DE USUARIO CREALO DE ESTA MANERA

sudo useradd -m -s /bin/bash deploy
sudo passwd deploy
