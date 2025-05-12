# Arch-Utiles
Colección de Scripts Útiles para Arch y derivadas.

# Redes Sociales
Para meterle Pluggins a Discord: [Vencord](https://vencord.dev/),

``` sh -c "$(curl -sS https://raw.githubusercontent.com/Vendicated/VencordInstaller/main/install.sh)" ``` 

# Música
para instalar Spotify premium: [Spot-X-Bash](https://github.com/SpotX-Official/SpotX-Bash), 

``` bash <(curl -sSL https://spotx-official.github.io/run.sh) ``` 

# Vídeo
Para instalar Davinci Resolve Studio 19:
(instalar normalmente y aplicar el siguiente comando)

``` sudo /usr/bin/perl -pi -e 's/\x74\x11\xe8\x21\x23\x00\x00/\xeb\x11\xe8\x21\x23\x00\x00/g' /opt/resolve/bin/resolve ```

Para arreglar el error con las librerías:
```
cd /opt/resolve/libs
sudo mkdir disabled-libraries
sudo mv libglib* disabled-libraries
sudo mv libgio* disabled-libraries
sudo mv libgmodule* disabled-libraries 
```

# Escritorios 
## Hyprland
Mis favoritos: [Illogical Impulse](https://github.com/end-4/dots-hyprland), 

``` bash <(curl -s "https://end-4.github.io/dots-hyprland-wiki/setup.sh") ```

Muy comodos de usar con teclado: [Hyde](https://github.com/Hyde-project/hyde), 

``` pacman -S --needed git base-devel
git clone --depth 1 https://github.com/HyDE-Project/HyDE ~/HyDE
cd ~/HyDE/Scripts
./install.sh
```

Muy bonitos: [Meowrch](https://github.com/meowrch/meowrch),
```
git clone https://github.com/meowrch/meowrch.git
cd meowrch
sh install.sh
```
