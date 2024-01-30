---
title: 'Evaluar docentes UNAH'
description: 'Evalua dodentes mas facil'
pubDate: 'Jul 08 2024'
heroImage: '/logo-unah.png'
---

Contiene un código para evaluar los docentes de forma más rápida en registro.  

Instrucciones:
1. Entrar a "Evaluar Docentes".
2. Inspeccionar (click derecho; inspeccionar) sobre el choice box "seleccionar".
3. Seleccionar "console".
4. Copiar el código que aparece en el archivo "código" de este repositorio.
5. Pegarlo en "console"
6. Presione enter

Ojo:
Se estableció por determinado el "select.value = 4" que califica al docente por "excelente", si desea calificarlo de una forma diferente puede cambiar el "4" por un numero del "1-4". 
```
for (const select of document.getElementsByTagName('select')) {
    select.value = 4;
    select.onchange();
}
```