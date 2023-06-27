
# Reconocimiento de Lenguaje de Señas Grupo 02 Capstone

Este proyecto fue creado como un prototipo de reconocimiento de lenguaje de señas BISINDO,
contiene el reconocimiento de 3 letras del idioma, siendo estas C, E e I.

## Algunas imágenes

<div>

<div>
  <p align="center">
  <img src="https://github.com/gabrielgraunegreiros/SignLangProject/assets/50873002/53cf38cb-e69e-43e5-92e1-d17ffb655f3e" alt="screenshot" width="90%">
</p>
</div>

<div>
  <p align="center">
  <img src="https://github.com/gabrielgraunegreiros/SignLangProject/assets/50873002/20241ec9-6cc1-4f2e-af29-d706d87ab37d" alt="screenshot" width="90%">
</p>
</div>
  
</div>

Para la instalación existen 2 formas:

1. Descarga e instalación de las bibliotecas desde requirements.txt:
   Descarga el proyecto
   En la consola, escriba: conda create --name "NameOfTheEnv"
   Luego active el entorno con: conda active "NameOfTheEnv"
   Entrar al directorio del proyecto descargado con la consola
   Luego instale todas las bibliotecas de los requisitos.txt con: pip install -r "requisitos.txt"
   
2. Cree/cargue un entorno con todas las bibliotecas instaladas con SingLangProject.yaml
   Descarga el proyecto
   En la consola, escriba: conda env create -f SignLangProject.yaml
   Luego active el nuevo entorno: active NewSignLangProject

Las entradas para el prototipo son las siguientes:
- Imagen captada mediante la cámara del ordenador.
- Modelo entrenado mediante Teachable Machie by Google.
Las salidas son las siguientes:
- Imagen que muestra el reconocimiento de la seña y la refleja mediante un cuadro que rodea a la mano e indica qué seña se está haciendo.

