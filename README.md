# Введение
Самый крутой конфиг в мире на сваи (неа, его надо пилить и пилить, но с пивком потянет).
Основано на арче + sway (не удивительно в целом). Конфиг это сборная солянка из других конфигов, конфиг больше пилился под 1366x768 экран без дополнительных дисплеев, так что увы, дальше придётся самим ручками его допиливать если что-то не будет работать.   
## Что там по софту основному
Тема - `Gruvbox`   
Браузер - `Firefox`  
Терминал - `Foot`  
Конус - `vlc`  
Бар - `Waybar`  
Меню приложений - `wofi`  
Настройка wifi - `nmtui`  
Аудиосистема - `Pipewire`  
Проводник - `Команды в терминале`  
Музыка - `Выберете сами cmus или musikcube`   
__ОЧЕНЬ ВАЖНАЯ ДЕТАЛЬ: ФЕТЧ__ - `fastfetch + hyfetch`    
### Что надо допилить и мне лень
1. права доступа, типо то что в USR вылазить или когда программе надо от рута запустится где то (я не помню чесно как называется)
2. добавить GUI проводник
3. допилить GTK и libadwaita тему (но я туплю)
4. QT проги (как в 3 пункте)
5. возможно бар
6. надо убирать bluetooth с waybar при отсутствии такого модуля на материнской плате
#### Так как это поставить?  
Установить эти пакеты ниже (список что я стаивл для рача, рачка, арча. В целом можно отдельно сразу это всё ставить и должно заработать, для этого я вынесу в отдельный файл).
```
sway swaybg vlc pavucontrol blueberry pipewire-alsa alsa-utils unzip ttf-nerd-fonts-symbols ttf-jetbrains-mono waybar xorg libnotify wl-clipboard pipewire-pulse ly xdg-desktop-portal xdg-desktop-portal-gtk xdg-desktop-portal-wlr go wofi foot wayland pipewire git gnu-free-fonts noto-fonts ttf-bitstream-vera fish ttf-croscore ttf-dejavu ttf-droid ttf-ibm-plex ttf-input ttf-input-nerd ttf-liberation ttf-roboto firefox grim brightnessctl wireplumber mako gtk-engine-murrine firefox 
```
Насрано но должно работать.  
Потом скопировать конфиги или просто `git clone` и всё копирнуть в .config в папке пользователя.  

> знали бы как я себя чувствовал когда гитом пользовался через терминал...
  
##### Фоточки?
![](sway1.png)  
  
и фото 2
  
![](sway2.png)  
  
и фото wofi  
  
![](wofi.png)  
  
