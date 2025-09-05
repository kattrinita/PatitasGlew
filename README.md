# PatitasGlew
"Sitio Web para ONG Patitas Glew - adopción y rescate de perros "
```text
[Cliente (HTTP request)]
    ⬇️
ROUTE (/api/clientes)
    ⬇️
MIDDLEWARE 
(PRE-CONTROLLER)
    ⬇️
VALIDATION (createClienteSchema)
    ⬇️
CONTROLLER (postCliente)
    ⬇️
SERVICE (registrarCliente)
    ⬇️
PRISMA / BASE DE DATOS
    ⬇️
MIDDLEWARE 
(POST-CONTROLLER)
```
