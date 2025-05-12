
## Browser Support

| Chrome | Firefox | Edge | Safari | Opera |
|:---:|:---:|:---:|:---:|:---:|
| <img src="https://github.com/creativetimofficial/public-assets/blob/master/logos/chrome-logo.png?raw=true" width="64" height="64"> | <img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/firefox-logo.png" width="64" height="64"> | <img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/edge-logo.png" width="64" height="64"> | <img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/safari-logo.png" width="64" height="64"> | <img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/opera-logo.png" width="64" height="64"> |

## Contribution
---

## Angular - Guía de Desarrollo

### Servidor de desarrollo
```bash
ng serve
```
Navega a `http://localhost:4200/`. La app se recargará automáticamente si cambias archivos fuente.

### Instalación con nodemon
```bash
npm install --save-dev nodemon
```
Agrega a `package.json`:
```json
"ng-serve-nodemon": "nodemon --watch src --exec \"ng serve\""
```
Corre con:
```bash
npm run ng-serve-nodemon
```

### Generación de código
```bash
ng generate component nombre-del-componente
```
También puedes generar directivas, pipes, servicios, clases, guards, interfaces, enums y módulos.

### Compilación
```bash
ng build
```

### Pruebas unitarias
```bash
ng test
```
Ejecuta pruebas usando [Karma](https://karma-runner.github.io).

### Pruebas End-to-End
```bash
ng e2e
```
Instala un paquete compatible para poder ejecutar estas pruebas.

### Ayuda adicional
```bash
ng help
```
[Documentación oficial de Angular CLI](https://angular.io/cli)
