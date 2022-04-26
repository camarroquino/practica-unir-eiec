# practica-unir-eiec

## Realizar una copia del repositorio

- Visitar Url del repositorio -> [Repositorio de la practica](https://github.com/camarroquino/practica-unir-eiec).

  ![Repositorio](1.png "Repositorio")

- Dar clic en el botón "Fork"
  
  ![Fork](2.png "Fork")

- Iniciar sesión con las credeciales de la cuenta personal

  ![Login](3.png "Login")

- Crear el fork.

  ![Link](4.png "Link")

## Clonar el repositorio personal

En caso del repositorio principal

En el directorio deseado ejecutar:

```
  git clone https://github.com/camarroquino/practica-unir-eiec.git
```

## Ejecución de la aplicación

- Instalar [NodeJs](https://nodejs.org/en/).
- Ejecutar en la carpeta del proyecto "angular-example".

```
npm install
```

```
ng serve -o
```

## Modificar el codigo fuente

Modificar el archivo de la ruta *angular-example\src\app\app-routing.module.ts*

Duplicar linea 353

  ![Code](5.png "Code")

## Trtabajo con la rama

Generar la rama
```
git branch camilo_modification
```

Realizar checkout de la rama
```
git checkout camilos_modification
```

Verificar la creación de la rama y que este activa
```
git branch -l
```

Agregar todos los cambios al commit
```
git add -A
```

Ejecutar el commit
```
git commit -m "Commit for Camilo's branch"
```

Verificar el estado
```
git status
```

Resultado de verificación del estado

  ![Status](6.png "Status")

Realizar el push
```
git push --set-upstream origin camilos_modification
```

Resultado al generar el Push

![Status](7.png "Status")

## Solicitar el Pull request

![Status](8.png "Status")

![Status](9.png "Status")

![Status](10.png "Status")

![Status](11.png "Status")
