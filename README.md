# i3-plasma
Mi configuracion de I3 y plasma

## Requisitos
Instalar los siguientes paquetes
-i3status-rust (https://raw.githubusercontent.com/greshake/i3status-rust)
-i3-gaps
-i3blocks
-i3status

# Como usar I3WM junto con plasma
1. Crear el fichero i3-plasma.desktop en /usr/share/xsessions/

2. Copiar en i3-plasma.desktop el contenido:
```
[Desktop Entry]
Type=XSession
Exec=env KDEWM=/usr/bin/i3 /usr/bin/startplasma-x11
DesktopNames=KDE
Name=Plasma with i3
Comment=Plasma with i3
```

3. git clone https://github.com/damianS7/i3-plasma
4. cd i3-plasmas && mv * ~/.config/i3
5. Seleccionar la session "Plasma with i3" en la pantalla de login (ej: SDDM)

