# Tema 1

- uno
- dos
- tres

```java
public class Persona {
    // Atributos privados
    private String nombre;
    private int edad;

    // Constructor
    public Persona(String nombre, edad) {
        this.nombre = nombre;
        this.edad = edad;
    }

    // Método
    public void saludar() {
        System.out.println("Hola, mi nombre es " + nombre + " y tengo " + edad + " años.");
    }

    public static void main(String[] args) {
        // Creación de un objeto de la clase Persona
        Persona p1 = new Persona("Ana", 25);
        p1.saludar();
    }
}
```

| Encabezado 1 | Encabezado 2 | Encabezado 3 |
|--------------|--------------|--------------|
| Dato 1       | Dato 2       | Dato 3       |
| Dato 4       | Dato 5       | Dato 6       |
