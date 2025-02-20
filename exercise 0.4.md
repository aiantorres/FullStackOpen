```mermaid
sequenceDiagram
 
    participant Navegador
    participant Servidor
    Note right of browser: Usuario escribe una nota en el campo de texto
    Navegador->>Servidor: Click en botón "Save"
    Note right of browser: El navegador ejecuta el event handler del formulario
```
