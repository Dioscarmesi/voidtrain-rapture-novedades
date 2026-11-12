# Novedades de VoidTrain Rapture

Este repositorio alimenta el **panel de novedades** del mundo de VRChat *VoidTrain Rapture*.
El mundo descarga `novedades.txt` desde GitHub Pages cada 10 minutos, así que para cambiar lo que
ven los jugadores **basta con editar ese archivo aquí** (botón del lápiz en GitHub) y guardar:
no hay que volver a subir el mundo. Los cambios tardan unos minutos en verse.

## Formato de `novedades.txt`

- Una sección por idioma. El código va entre corchetes, solo en su línea:
  `[es]` `[en]` `[ja]` `[ko]` `[zh-Hans]` `[zh-Hant]` `[ru]` `[de]` `[fr]` `[pt]` `[it]` `[pl]` `[th]` `[id]` `[tr]`
- Cada jugador ve la sección de su idioma. Si falta, ve `[en]`; si también falta, `[es]`.
- Se puede dar formato con etiquetas de TextMeshPro: `<b>negrita</b>`, `<color=#FFB85A>color</color>`, `<size=120%>grande</size>`.
- No empieces ninguna línea de texto con `[`: el panel lo tomaría por el inicio de otra sección.
- Máximo unos 6000 caracteres en total; cabe aproximadamente una pantalla de 20 líneas por idioma.

Dirección que lee el mundo: `https://dioscarmesi.github.io/voidtrain-rapture-novedades/novedades.txt`
