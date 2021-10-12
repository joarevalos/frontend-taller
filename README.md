# Taller práctico: Front-end
## LENGUAJE DE PROGRAMACIÓN III (UTIC / FTI / LASI) 2021

La siguiente es una prueba para evaluar conocimientos de **HTML, CSS, JavaScript y diseño Responsive.**

Se busca que cumpla con los requerimientos especificados.

Se evaluará habilidad en HTML y CSS, además aspectos de organización de código, buenas prácticas, prioridad y creatividad para resolver los requerimientos.

Es necesario contar con una cuenta en BitBucket para realizar este ejercicio.

Ejercicio
Clonar el repositorio.

Maquetación: Deberás traducir el diseño ubicado en design/disign.png a HTML+CSS y bootstrap (Todo lo que no este presente en el diseño, iconos, ventanas modales, etc siéntase libre en implementar).

Javascript: Se deben realizar las siguiente tareas teniendo en cuenta el usar jquery como librería principal.

Validar que el formato del campo email sea efectivamente un email y que ademas sea requerido, el campo password también es requerido. Si alguno de los campos no cumpliera con estas validaciones se debe mostrar el mensaje de error en un tooltip de bootstrap.

Al presionar el boton "SIGN IN" se debe validar que el usuario y contraseña sean validos, para ello debe "leer" con javascript el archivo remote.JSON y permitir el acceso a la aplicación solamente a esos usuarios, si el usuario y contraseña no son validos se debe informar al usuario: "Los datos ingresados son incorrectos" a través de una ventana modal de bootstrap.

Si los datos ingresados en la ventana de login son correctos se debe mostrar una ventana modal de bootstrap indicando el siguiente mensaje: "Los datos son correctos, Bienvenido".
