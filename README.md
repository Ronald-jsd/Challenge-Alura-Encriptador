
# Encriptador de Texto 

Este es un proyecto de encriptador y desencriptador de texto desarrollado como parte del Challenge de Alura en colaboración con Oracle. 
La aplicación permite a los usuarios encriptar y desencriptar mensajes utilizando un algoritmo de sustitución de caracteres específico.

![encriptador-elaborado por Ronald Santiago Jaime Duran](https://github.com/user-attachments/assets/7a245beb-8cd4-4464-aa14-ec4083f2a240)

## Características

- Encriptar y desencriptar texto utilizando un sistema de sustitución de vocales.
- Opción para copiar el texto encriptado o desencriptado al portapapeles.
- Validación para asegurar que solo se utilicen letras minúsculas sin acentos o caracteres especiales.
- Interfaz gráfica sencilla y amigable con un tema claro/oscuro para la comodidad del usuario.


![modoOscuro-Ronald](https://github.com/user-attachments/assets/a8afcb1a-ec83-41ed-8c58-08694b97fb99)

## Diseño responsive
- El proyecto tiene un diseño responsive a medida de dispositivos de  `TABLET` y  `MOVIL`. 

<img src="https://github.com/user-attachments/assets/d6b53629-fce2-4658-88bc-be9c7673df05" alt="img-dispositivo-tablet" width="300"> <img src="https://github.com/user-attachments/assets/a11de150-e421-4090-b23e-bb0be6c6cbba" alt="img-dispositivo-movil" height="300">

## Tecnologias utilizadas

Este proyecto está desarrollado utilizando HTML, CSS y JavaScript. 

### Librerías utilizadas:

- [SweetAlert2](https://sweetalert2.github.io/): Usado para mostrar alertas estilizadas.


## Uso

1. **Encriptar Texto**: Ingresa un texto en el área de texto, asegurándote de que sea en minúsculas y sin acentos ni caracteres especiales.
   Luego, presiona el botón "Encriptar" para convertir el texto.
   

3. **Desencriptar Texto**: Ingresa un texto previamente encriptado y presiona "Desencriptar" para revertir el texto a su forma original.
   

5. **Copiar Texto**: Luego de encriptar o desencriptar un texto, presiona el botón "Copiar" para guardar el resultado en tu portapapeles.

   

### Restricciones

- **Solo se permiten letras minúsculas y sin acentos.**
- **No se permiten caracteres especiales ni campos vacíos.**

## Encriptación

El algoritmo de encriptación sustituye las siguientes vocales:

- `e` se convierte en `enter`
- `i` se convierte en `imes`
- `a` se convierte en `ai`
- `o` se convierte en `ober`
- `u` se convierte en `ufat`

Ejemplo:  
Texto original: `hola`  
Texto encriptado: `hoberlai`

## Desencriptación

El algoritmo de desencriptación revierte las sustituciones realizadas durante la encriptación, devolviendo el texto a su forma original.

Ejemplo:  
Texto encriptado: `hoberlai`  
Texto desencriptado: `hola`

## Funcionalidades adicionales

- **Tema Claro/Oscuro**: El usuario puede alternar entre un tema claro y oscuro presionando el botón de cambio de tema en la esquina superior izquierdo.

## Autor

- **Ronald Santiago**  
  <a href="https://github.com/Ronald-js"><img src="https://github.com/user-attachments/assets/04f25992-d106-4efa-8922-a3fe796d1289" width="40px"> </a>
    [GitHub](https://github.com/Ronald-jsd)

  <a href="https://www.linkedin.com/in/ronald-santiago-jaime-duran/"><img src="https://github.com/user-attachments/assets/9606ce90-6a6a-4466-8b9f-41500e171349" width="40px"> </a>
  [LinkedIn](https://www.linkedin.com/in/ronald-santiago-jaime-duran/)

