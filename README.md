# Buscaminas

Buscaminas de 10x10 con 10 minas, hecho en Java Swing.

## Controles
- Clic izquierdo: descubrir celda
- Clic derecho: marcar / desmarcar con "B"

## Requisitos
- JDK 17 o superior

## Compilar y ejecutar
Desde la raíz del proyecto (Windows):

```
mkdir out
javac -encoding UTF-8 -cp "src\main\resources\logminas.jar" -d out src\main\java\buscaminas\*.java
java -cp "out;src\main\resources\logminas.jar" buscaminas.Tablero
```

En Linux/macOS, cambia `\` por `/` y `;` por `:`.

Con Maven hay que instalar antes `logminas.jar` como dependencia `logminas:1.0-SNAPSHOT`.
