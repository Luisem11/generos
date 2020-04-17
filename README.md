# Géneros Músicales Web
![Logo Parque Explora](https://reservas.parqueexplora.org/v2_base/temas/movil/images/logo2.png "Logo Parque Explora")
### Descripción 
Implementación Web de experiencia de sala música, consite en la historia de los géneros músicales a través de videos.
### Versiones disponibles
- **Version 1 :** uso de librería de `FullPage JS ` para la navegación.
- **Videos Locales** : carga los videos desde la carpeta `src/videos` .
- **Videos Youtube** : carga los videos desde Youtube.  Canal [Luis Ernesto Monsalve ](http://https://www.youtube.com/playlist?list=PLPR_CTsWB6uOuzTpo1LLulwahTNG4AyUU "Luis Ernesto Monsalve ").
### Observaciones
- **Links de Youtube**: para cambiar el acceso a los videos de Youtube se debe ir al script del archivo html donde hay una variable llamada links_videos donde se debe poner el id del video de Youtube.
```javascript
var links_videos= {
            "popular": "K0gZUHJV2hg",
            "electronica": "Kyzr-aTGGPc",
            "bolero": "251txEYuSh4",
            "rock": "pmmgWm3k_8Y",
            "salsa": "28wz63eJk90",
            "hiphop": "U0viQhq8rlQ",
            "champeta": "SzDK7PGTdgw",
            "tropical": "B8VweiN0DxY",
            "tango": "dxnt3ws5J2A",
            "ranchera": "B-Ot_WAd4IM"
```
### Librerías
- jQuery
- Popper.js
- Bootstrap JS 
