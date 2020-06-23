## Conky by jodarove
Configuración del archivo conky para mostrar información en tu escritorio.
<img src='./src/images/desktop-conky-by-jdromero88.jpg' alt="conky-by-jdromero88" width="946px" />

### Configuracion para usar conky con 2 monitores
- Si tenes solo un monitor y no te funciona podes borrar la linea # 2
- que dice: xinerama_head = 2
- Si queres cambiar tu conky en otro monitor cambia el xinerama_head a 0 o 1 o 2, podes probar y unos de ellos te va a mostrar en el monitor correcto. Entonces debería quedar así:
```
  xinerama_head = 0,
```
o
```
  xinerama_head = 1,
```
