# Tamiz · releases

Aquí viven el APK de [Tamiz](https://github.com/CapReed/tamiz) y el manifest que la app
consulta para saber si hay versión nueva. El código fuente está en un repo privado; este
existe porque la descarga tiene que funcionar sin credenciales.

- `version.json` — lo que lee la app para detectar actualizaciones.
- Releases — cada APK firmado. La última siempre está en
  `https://github.com/CapReed/tamiz-releases/releases/latest/download/app-release.apk`,
  una URL que no cambia nunca.

No hay nada que instalar desde aquí a mano: la propia app avisa cuando hay versión nueva
y la instala.
