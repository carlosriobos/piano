# Empaquetadores web

- Tengo ofuscacion
- Tengo minificacion
- Tengo compresion de imagenes
- Tengo shaking
- Tengo procesadores de css
- Tengo frameworks css
- Tengo frameworks web
- Uso de lenguajes que no sean js (typescript, jsx)
- Tengo mecanismos de optimizacion del codigo
- etc etc

# Empaquetadores famosos

- webpack
- rollup
- wmr
- esbuild
- parcel
- snowpack
- **vite**

# Pasos

## Crear un proyecto npm
npm init

## Añadir la dependencia con tonejs (dependencia de produccion)
npm install tone

# Añadir el empaquetador parcel (dependencia de desarrollo)
npm install --save-dev parcel

# Construimos y arrancamos la aplicacion\
npx parcel src/index.html
npx parcel build src/index.html

# Añadimos la libreria react
npm install react react-dom