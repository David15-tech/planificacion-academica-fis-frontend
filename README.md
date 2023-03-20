# Instalación para desarrollo

### Prerequisitos

- Tener instalado nodejs versión >= 16.X.X
- Tener levantado el componente SPA_BACKEND en el puerto 3000

### Instalación

1. Clone el repositorio del componente en GitHub:

```bash
git clone git@github.com:Trabajo-de-Titulacion/planificacion-academica-fis-frontend.git
```

2. Dentro del directorio del proyecto, cambie su rama actual a la rama de un integrante, en este caso a:

```bash
git checkout development-alejandro-llanganate
```

3. Acceda al directorio donde se encuentra el proyecto en Angular con el comando:

```bash
cd SPA-Frontend/
```

4. Instale las dependencias del proyecto con el comando:

```
npm install -f
```

5. Para levantar la aplicación SPA ejecute el siguiente comando:

```bash
ng serve
```

<aside>
📖 Nota: El aplicativo se levantará en http://localhost:4200 en caso de no disponer otra aplicación Angular ejecutándose.

</aside>

6. Ingrese a la dirección  [http://localhost:4200/login](http://localhost:4200/login) para iniciar sesión.