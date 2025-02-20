```mermaid
sequenceDiagram
 
    participant Navegador
    participant Servidor
    Note right of Navegador: Usuario escribe una nota en el campo de texto
    Navegador->>Servidor: Click en botón "Save"
    Note right of Navegador: El navegador ejecuta el event handler del formulario
```
