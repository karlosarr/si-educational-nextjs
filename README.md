# si-educational-nextjs

## Despliegue a Firebase

Sigue estos pasos para desplegar el proyecto en Firebase Hosting:

### Requisitos previos

- Tener instalado [Node.js](https://nodejs.org/)
- Tener instalado [Firebase CLI](https://firebase.google.com/docs/cli)

```bash
npm install -g firebase-tools
```

### Autenticación en Firebase

```bash
firebase login
```

### Inicializar Firebase en el proyecto

```bash
firebase init
```
Selecciona **Hosting** y configura el directorio de salida (por ejemplo, `out` si usas `next export`).

### Construir el proyecto

```bash
npm run build
```
Si usas `next export` para sitios estáticos:
```bash
npm run export
```

### Desplegar a Firebase

```bash
firebase deploy
```

Consulta la [documentación oficial de Firebase Hosting](https://firebase.google.com/docs/hosting) para más detalles.
