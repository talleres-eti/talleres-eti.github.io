---
layout: page
title:  "Conservation"
date:   2024-07-21 18:43:20 -0400
categories: s1
permalink: /:year/:categories/:title
---

# Conservación
![Revolución Francesa](/assets/images/s1/revolution.jpg)

## Problema a Resolver
En 1789, en el contexto de la [Revolución Francesa](https://es.wikipedia.org/wiki/Revoluci%C3%B3n_francesa), la Asamblea Nacional Constituyente Francesa proclamó la [Declaración de los Derechos del Hombre y del Ciudadano](https://es.wikipedia.org/wiki/Declaraci%C3%B3n_de_los_Derechos_del_Hombre_y_del_Ciudadano), la cual sentó las bases de derechos humanos en sociedad; sin embargo, esta declaración dejó notablemente fuera a las mujeres, pues esta declaración indicaba que los derechos solo son para ciudadanos, y los ciudadanos solo podían ser hombres. En respuesta a esto, [Olympe de Gouges](https://es.wikipedia.org/wiki/Olympe_de_Gouges), una activista y feminista francesa, proclamó la [Declaración de los Derechos de la Mujer y de la Ciudadana](https://es.wikipedia.org/wiki/Declaraci%C3%B3n_de_los_Derechos_de_la_Mujer_y_de_la_Ciudadana), siendo uno de los primeros documentos históricos que proponen la equidad de género.

Tú perteneces a un equipo de conservación histórica que buscará conservar este documento de manera digital para que así futuras generaciones puedan acceder a este. Una investigadora ya ha anotado la traducción del documento, ahora el trabajo de tu equipo será transcribir los primeros 4 artículos de la Declaración de los Derechos de la Mujer y de la Ciudadana a un archivo llamado `transcript.txt`.

## Distribución de Código

Para este problema y todos los problemas del Git Commit, utilizaremos GitHub Codespaces, una manera sencilla de trabajar como si tuviéramos una computadora en la nube. No necesitas instalar nada, ya que todo estará listo para que lo uses. Para ejecutar esto, sigue los siguientes pasos:

+ Descarga la distribución del código

   * **Accede a tu GitHub Codespaces de Git Commit:** Haz clic en el siguiente botón para crear un nuevo repositorio en tu cuenta personal. Ponle el nombre que quieras; te recomendamos "Conservation". Guarda el repositorio en tu cuenta.
     [![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://github.com/new?template_name=codespace&template_owner=gitcommituyu)

   * Una vez que hayas guardado el repositorio, verás un botón que dice "Code" y una opción que dice "Codespaces".

   * Haz clic en "Codespaces" y luego en "Crear nuevo Codespace". Espera unos minutos mientras se inicia todo el entorno. Una vez que el Codespace haya iniciado, estarás listo para trabajar con el entorno configurado.

   * Deberías encontrar que tu ventana de terminal se asemeja a la siguiente:
     ```
     $
     ```

   * Ahora, ejecuta el siguiente comando para descargar el archivo ZIP llamado `1.zip` en tu GitHub Codespaces:
     ```
     wget http://157.245.132.153/gitcommit/1.zip
     ```

   * Descomprime el archivo ZIP ejecutando:
     ```
     unzip 1.zip
     ```
     
   * Elimina el archivo ZIP ya que no lo necesitas más, ejecutando:
     ```
     rm 1.zip
     ```

    **Agregar y verificar archivos:**
   * Verifica el estado de los archivos que acabas de descomprimir ejecutando:
     ```
     git status
     ```
   * Agrega los archivos a tu repositorio. Tienes tres opciones:
     1. Agregar los archivos de manera individual:
        ```
        git add conservation/images/001.png
        ```
     2. Agregar todo el folder:
        ```
        git add conservation/*
        ```
     3. Agregar todos los archivos:
        ```
        git add *
        ```
   * Envía los cambios a tu cuenta de GitHub con el siguiente comando:
     ```
     git push
     ```

   **Acceder al directorio de trabajo:**
   * Dirígete a la carpeta `conservation` ejecutando:
     ```
     cd conservation
     ```
   * Deberías encontrar que tu ventana de terminal se asemeja a la siguiente:
     ```
     conservation/ $
     ```

    **Verificar contenido del directorio:**
   * Si todo ha salido bien, al ejecutar:
     ```
     ls
     ```
     deberías encontrar una carpeta llamada `images` y un archivo llamado `transcript.txt` en tu carpeta `conservation`.

## Especificación

En grupos de 2 a 4 personas, una vez que cada uno haya completado de forma individual este reto, sigan estos pasos para trabajar de manera colaborativa:

* Una persona del grupo debe crear un nuevo repositorio en GitHub llamado `conservation-gitcommit`.
* Si son equipos de dos, se dividen entre dos personas. Si son equipos de cuatro, se dividen entre cuatro personas, y cada uno se encargará de transcribir una parte del archivo `transcript.txt` de manera individual.
* Cada persona debe enviar su transcripción al repositorio mediante *pull requests* hacia el repositorio creado por la primera persona.
* Asegúrense de revisar y aprobar las *pull requests* para que todas las transcripciones se integren en la rama `main`.
* Deben documentar al menos un problema encontrado durante el proceso de transcripción en la sección de Issues de GitHub.

Para llevar un registro detallado de tu progreso, te recomendamos que realices un commit cada vez que completes la transcripción de un artículo. Esto te ayudará a mantener un historial claro de tus cambios y facilitará la colaboración con otros miembros del equipo.

+ Ejemplo de archivo `transcript.txt`
  * Primer Art: Soy el texto del primer artículo, debo estar en una sola línea.
  * Segundo Art: Soy el texto del segundo artículo, debo estar en una sola línea.
  * Tercer Art: Soy el texto del tercer artículo, debo estar en una sola línea.
  * Cuarto Art: Soy el texto del cuarto artículo, debo estar en una sola línea.

## Cómo testear tu implementación
Para testear la correctitud de tu implementación, puedes ejecutar el siguiente comando en tu terminal:
```
check50 gitcommituyu/problems/2024/conservation --local
```

## Envíanos tu Solución
Puedes enviar tu implementación a este desafío a nuestra [GitHub Discussions](https://github.com/orgs/gitcommituyu/discussions/4) dedicada. Si es correcta, estarás participando de un sorteo de premios de GitHub.

## Reconocimientos
* Ilustración principal del enunciado de la obra [La Libertad guiando al pueblo](https://es.wikipedia.org/wiki/La_Libertad_guiando_al_pueblo) obtenida de Wikipedia. 
* Imágenes de la [Declaración de los Derechos de la Mujer y de la Ciudadana](https://es.wikipedia.org/wiki/Declaraci%C3%B3n_de_los_Derechos_de_la_Mujer_y_de_la_Ciudadana) obtenidas de [Gallica](https://gallica.bnf.fr/ark:/12148/bpt6k64848397/f1.item), la librería digital de la Biblioteca Nacional de Francia.
