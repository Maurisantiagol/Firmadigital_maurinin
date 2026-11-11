# Firmadigital_maurinin

App web en Node.js y Express para subir archivos, como parte de un proyecto escolar de firma digital (2021). Proyecto viejo e incompleto: su único endpoint recibe el archivo y lo guarda en `uploads/`.

> El README anterior decía "Algoritmo AES con archivos.txt": era texto copiado de AESMAURININ y no corresponde a este repositorio. El `package.json` también es una copia del de DESMAURININ.

Creado por: Montes de Oca Arellano Edgar y Santiago De Luis Mauricio. Grupo 5IV7. Alias: Marinin y Santiagol.

## Qué hace

- `POST /api/subir-archivo`: recibe un archivo y lo guarda en `uploads/`, y responde con su ruta.
- La lógica de firma digital no está implementada en el controlador actual.

## Stack

- Node.js + Express (`express`, `express-fileupload`)
- `crypto` y `crypto-js` en las dependencias
- Despliegue en Azure App Service mediante el workflow de `.github/workflows`

## Cómo correrlo

```bash
npm install
npm start
```
