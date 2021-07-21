# i3-plasma
Mi configuracion de I3 y plasma

# Como usar I3WM junto con plasma
1. Crear el fichero i3-plasma.desktop en /usr/share/xsessions/

2. Pegar el contenido:
```
[Desktop Entry]
Type=XSession
Exec=env KDEWM=/usr/bin/i3 /usr/bin/startplasma-x11
DesktopNames=KDE
Name=Plasma with i3
Comment=Plasma with i3
```
3. Seleccionar la session en la pantalla de login (SDDM ...)

4. cd ~/.config/
5. git clone https://github.com/damianS7/i3-plasma
6. rm -R ./i3 && mv i3-plasma i3

## Requisitos
i3status-rust (https://raw.githubusercontent.com/greshake/i3status-rust)


