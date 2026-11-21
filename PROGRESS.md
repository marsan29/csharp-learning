# PROGRESS --- Formación Backend C# y .NET

**Objetivo:** Desarrollar aplicaciones backend de forma autónoma con C#,
.NET, ASP.NET Core y PostgreSQL.

**Estado general:** Fase 0 completada. Diagnóstico práctico de C# en
progreso.

**Fase actual:** Fase 1 --- C# Reboot.

**Subfase actual:** Diagnóstico práctico de conocimientos de C#.

**Última actualización:** 21 de noviembre de 2026.

------------------------------------------------------------------------

## 1. Conocimientos previos declarados

  -----------------------------------------------------------------------
  Tema                                Situación
  ----------------------------------- -----------------------------------
  Fundamentos de C#                   Curso realizado; diagnóstico
                                      práctico en progreso

  POO con C#                          Curso realizado; pendiente de
                                      diagnóstico práctico

  Fundamentos de .NET                 Conocimientos iniciales
                                      comprobados; falta profundizar

  SQL y PostgreSQL                    Estudios anteriores; pendiente de
                                      diagnóstico práctico

  Git y GitHub                        Flujo básico practicado
                                      correctamente
  -----------------------------------------------------------------------

## 2. Entorno de desarrollo

  Herramienta               Estado / Versión
  ------------------------- ---------------------------------------
  Sistema operativo         Windows 10
  Visual Studio Community   2026 --- 18.10.3
  SDK de .NET               10.0.401
  Runtime de .NET           10.0.12
  ASP.NET Core Runtime      10.0.12
  Git                       2.53.0.windows.2
  Git Credential Manager    2.7.3
  GitHub                    Cuenta configurada
  .NET CLI                  Verificado desde Git Bash
  ASP.NET Core Web API      Plantilla disponible en Visual Studio
  GitHub CLI (`gh`)         No instalado; no necesario por ahora

**Cargas de trabajo de Visual Studio:** - Desarrollo de escritorio de
.NET. - Desarrollo de ASP.NET y web.

## 3. Conceptos practicados y observados

  -----------------------------------------------------------------------
  Concepto                Nivel actual            Evidencia / observación
  ----------------------- ----------------------- -----------------------
  Uso básico de Visual    En desarrollo           Creación y ejecución de
  Studio                                          proyectos

  Crear una solución y un Practicado              Se reutiliza la
  proyecto de consola                             solución principal

  Diferencia entre        Comprendido             Se explicó la relación
  solución y proyecto     inicialmente            entre `.slnx` y
                                                  `.csproj`

  Ejecutar proyectos con  Practicado              Ejercicios de consola
  Visual Studio                                   

  Ejecutar proyectos      Practicado              Ejecución del proyecto
  mediante `dotnet run`                           `VariablesAndTypes`

  Estructura básica de un Comprendido             Revisado durante la
  `.csproj`               inicialmente            preparación

  Variables y tipos       Dominado inicialmente   Declaración y uso de
  básicos                                         `string`, `int`,
                                                  `double`, `char` y
                                                  `bool`

  Declaración, asignación Dominado inicialmente   Explicó la diferencia y
  e inicialización                                escribió un ejemplo

  Interpolación de        Dominado inicialmente   Utilizada en salidas de
  cadenas                                         consola

  Operaciones aritméticas Dominado inicialmente   Cálculo de promedios,
  básicas                                         descuentos y precios

  Formato numérico (`F1`, Dominado inicialmente   Aplicado en ejercicios
  `C2`, `P0`)                                     

  `double` frente a       En desarrollo           Eligió `decimal` para
  `decimal`                                       precios y aplicó el
                                                  sufijo `m`; falta
                                                  profundizar en sus
                                                  diferencias

  Operadores de           Dominado inicialmente   Uso de `>=`, `<` y `<=`
  comparación                                     en condiciones

  Operadores lógicos      En desarrollo           Comprensión y uso
                                                  correcto de `&&`; `||`
                                                  y `!` todavía no
                                                  evaluados

  Precedencia y           Dominado inicialmente   Uso de paréntesis en el
  agrupación de                                   cálculo del promedio
  expresiones                                     

  Condicionales `if`,     Dominado inicialmente   Construyó decisiones a
  `else if` y `else`                              partir de promedio y
                                                  asistencia

  Operador ternario       Dominado inicialmente   Lo utilizó para mostrar
                                                  aprobado/reprobado

  Refactorización de      Necesita refuerzo       Comprendió el ejemplo
  lógica condicional                              después de orientación,
                                                  pero todavía le cuesta
                                                  identificar cuándo
                                                  separar condiciones y
                                                  cómo contemplar varios
                                                  resultados posibles

  Análisis de casos y     Necesita refuerzo       Requiere práctica para
  reglas de negocio                               detectar condiciones
                                                  simultáneas, límites,
                                                  datos inválidos y
                                                  distintos motivos de
                                                  rechazo
  -----------------------------------------------------------------------

### Observaciones del diagnóstico

-   El usuario puede escribir programas pequeños de consola con
    variables, cálculos y condiciones.
-   Comprende las condiciones que implementa cuando se explican de forma
    concreta.
-   En ejercicios con varias reglas, puede centrarse inicialmente en el
    primer caso que detecta y no contemplar todos los escenarios
    posibles.
-   Necesita fortalecer el hábito de traducir un enunciado a reglas,
    identificar límites y casos posibles antes de escribir el código.
-   La refactorización debe enseñarse progresivamente mediante ejemplos
    y ejercicios intermedios: primero reconocer duplicación o
    responsabilidades mezcladas, luego reorganizar condiciones y
    finalmente mejorar estructuras más complejas.
-   No asumir que el usuario debe descubrir por sí solo todos los
    requisitos de un programa real: practicar cómo aclarar requisitos
    con quien solicita el software y cómo derivar casos de prueba a
    partir de las reglas acordadas.

## 4. Git y GitHub

**Repositorio principal:**

https://github.com/marsan29/csharp-learning

**Ubicación local:**

`C:\Users\marce\source\repos\csharp-learning`

**Configuración realizada:** - Identidad de Git configurada. - Git
Credential Manager configurado. - Autenticación con GitHub mediante
navegador. - Repositorio remoto conectado mediante HTTPS. - Rama
principal: `main`. - `.gitignore` de Visual Studio.

**Flujo practicado:** - `git status` - `git add` - `git commit` -
`git push` - `git remote -v` - `git clone`

**Comprensión demostrada:** - Working Directory. - Staging Area. -
Repositorio local. - Repositorio remoto. - Archivos untracked. -
Archivos modificados y staged. - Commits y sincronización con GitHub. -
Diferencia entre `git init` y `git clone`.

**Último commit registrado:**

`6877fb5 — feat: add name and surname output`

**Estado final comprobado en la sesión de preparación:** rama `main`
sincronizada con `origin/main`, working tree limpio. No se ha confirmado
un nuevo commit durante las sesiones de diagnóstico.

## 5. Ejercicios y proyectos

### Proyecto: FirstConsoleApp

**Repositorio:** `csharp-learning`\
**Tecnología:** C# / .NET 10

**Archivos principales:** - `Program.cs` - `FirstConsoleApp.csproj` -
`csharp-learning.slnx`

**Ejercicio realizado:** - Mostrar mensajes en consola. - Declarar
variables para nombre y apellido. - Utilizar interpolación de cadenas. -
Ejecutar el programa desde Visual Studio. - Ejecutar el programa
mediante .NET CLI. - Versionar los cambios con Git. - Publicar los
cambios en GitHub.

**Estado:** completado como primer ejercicio de preparación.

### Proyecto: VariablesAndTypes

**Ubicación dentro del repositorio:**

`Exercises/Phase1-CSharpReboot/01-VariablesAndTypes/VariablesAndTypes/`

**Ejercicios realizados:** - Crear variables de distintos tipos. -
Mostrar un perfil en consola. - Diferenciar declaración, asignación e
inicialización. - Calcular un descuento y el precio final usando
`decimal`. - Aplicar formatos monetarios y porcentuales.

**Estado:** ejercicio completado; fundamentos evaluados como dominados
inicialmente.

### Proyecto: Operators

**Ubicación prevista dentro del repositorio:**

`Exercises/Phase1-CSharpReboot/02-Operators/Operators/`

**Ejercicios realizados:** - Calcular el promedio de tres
calificaciones. - Comparar el promedio con una nota mínima. - Mostrar el
resultado con operador ternario. - Evaluar aprobación con promedio y
porcentaje de asistencia. - Separar condiciones para poder informar más
de un motivo de reprobación. - Considerar la validación de un promedio
fuera del rango permitido.

**Estado:** bloque de operadores y condicionales trabajado. El
razonamiento básico está demostrado; el análisis sistemático de casos y
la refactorización necesitan más práctica. No se ha confirmado un commit
de este proyecto.

## 6. Conceptos por reforzar y pendientes de diagnóstico

### Refuerzo prioritario

-   Descomponer enunciados en reglas de negocio antes de programar.
-   Identificar casos normales, límites, entradas inválidas y
    combinaciones de condiciones.
-   Diseñar y comprobar casos de prueba para cada regla.
-   Refactorizar condicionales sin cambiar el comportamiento del
    programa.
-   Reconocer cuándo conviene separar validación de datos, decisión del
    resultado y explicación de los motivos.
-   Practicar progresivamente lógica condicional de dificultad
    intermedia.

### Pendientes de evaluación

-   Operadores lógicos `||` y `!`.
-   Ciclos: `for`, `while` y `do while`.
-   Arrays y matrices.
-   Strings y sus operaciones.
-   Colecciones, incluida `List<T>`.
-   Métodos, parámetros y valores de retorno.
-   Conversiones de tipos.
-   Excepciones y validaciones.
-   Clases, objetos, propiedades, métodos y encapsulamiento.
-   SQL: consultas, filtros, JOIN y operaciones CRUD.
-   PostgreSQL.

## 7. Errores recurrentes y decisiones de aprendizaje

-   No se han identificado errores sintácticos recurrentes.
-   La principal dificultad observada hasta ahora es de análisis:
    anticipar todos los escenarios que se desprenden de varias reglas y
    organizar el código para cubrirlos.
-   El aprendizaje de refactorización debe ser gradual y práctico, sin
    introducir abstracciones avanzadas prematuramente.
-   Cuando un requisito no esté claro, practicar cómo formular preguntas
    para aclararlo antes de implementar.
-   Se aprenderá .NET CLI mediante prácticas.
-   Git y GitHub se integrarán durante todo el recorrido.
-   Platzi será un recurso complementario.
-   No se introducirán arquitecturas ni patrones antes de necesitarlos.

## 8. Registro de sesiones

### 19 de noviembre de 2026 --- Preparación del entorno

**Actividades completadas:** - Verificación de Visual Studio Community
2026. - Verificación de .NET SDK y runtimes. - Instalación y
configuración de Git. - Configuración de identidad y autenticación de
GitHub. - Creación y clonación del repositorio `csharp-learning`. -
Creación de solución y proyecto de consola. - Ejecución del primer
programa. - Comprobación de .NET CLI desde Git Bash. - Instalación de la
carga de trabajo ASP.NET y desarrollo web. - Verificación de la
plantilla ASP.NET Core Web API. - Práctica del ciclo completo de Git:
add, commit y push.

**Resultado:** Fase 0 completada.

### 21 de noviembre de 2026 --- Diagnóstico práctico: variables, tipos, operadores y condicionales

**Actividades completadas:** - Ejercicios de declaración y uso de
variables con tipos básicos. - Diferenciación entre declaración,
asignación e inicialización. - Cálculos con `double` y `decimal`. -
Aplicación de formatos numéricos. - Cálculo de promedios. - Uso de
operadores aritméticos y de comparación. - Uso de `&&` en condiciones
compuestas. - Construcción de decisiones con `if`, `else if` y `else`. -
Uso del operador ternario. - Ejercicio de aprobación/reprobación según
promedio y asistencia. - Refactorización inicial para informar más de un
motivo de reprobación. - Consideración de validaciones para valores
fuera del rango permitido.

**Resultado y evaluación:** - Variables y tipos básicos: dominado
inicialmente. - Operaciones aritméticas, comparación y formato: dominado
inicialmente. - Condicionales y operador ternario: dominado
inicialmente. - `&&`: uso correcto demostrado. - Refactorización y
análisis de casos: necesitan refuerzo mediante ejercicios guiados de
dificultad gradual.

**Observación del usuario:** siente que todavía le cuesta visualizar
cómo refactorizar y cómo anticipar todos los casos posibles. Se acuerda
trabajar explícitamente estas habilidades en próximas sesiones,
explicando que los requisitos deben aclararse con quien solicita el
programa y que, a partir de ellos, el desarrollador debe derivar
escenarios y pruebas.

## 9. Próximo paso exacto

Continuar el diagnóstico práctico de C# con **estructuras de
repetición**.

La sesión siguiente comienza retomando la pregunta conceptual pendiente:

> Si se quieren mostrar los números del 1 al 10 en consola sin escribir
> diez llamadas a `Console.WriteLine()`, ¿qué estructura de repetición
> elegirías y por qué?

Después, realizar un ejercicio a la vez para practicar ciclos, empezando
por `for` y avanzando según la comprensión demostrada.

En paralelo, incorporar pequeños ejercicios de análisis de requisitos y
casos de prueba para fortalecer la lógica y la refactorización. No
avanzar de tema únicamente por completar ejercicios: comprobar primero
el razonamiento y la capacidad de explicar el código.
