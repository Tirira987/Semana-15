Restaurante App - Semana 15
Datos del estudiante

Nombre: Richard Arturo Tirira Díaz
Carrera: Tecnologías de la Información
Asignatura: Programación Orientada a Objetos
Semana: 15

Descripción

Restaurante App es una aplicación desarrollada en Python utilizando Programación Orientada a Objetos y Tkinter.

En la Semana 15 se continúa con la evolución de la aplicación desarrollada en la Semana 14, manteniendo la arquitectura modular, la interfaz gráfica y la persistencia de información mediante archivos JSON.

En esta semana se incorpora una nueva sección de Ventas, donde se relaciona un usuario con un producto y la fecha de la operación.

Para registrar una venta se utiliza un botón mediante command= y un callback, el cual coordina la operación con RestauranteServicio y permite actualizar la información mostrada en la interfaz.

Las ventas registradas se almacenan en el archivo ventas.json, permitiendo conservar la información cuando la aplicación se cierra y vuelve a ejecutarse.

Estructura del proyecto
```
restaurante_app/
│
├── assets/
│   ├── icons/
│   │   ├── home.png
│   │   ├── users.png
│   │   ├── products.png
│   │   ├── ventas.png
│   │   ├── logout.png
│   │   ├── add.png
│   │   ├── edit.png
│   │   ├── delete.png
│   │   └── clean.png
│   │
│   └── logo/
│       ├── logo.png
│       └── icono.png
│
├── datos/
│   ├── productos.json
│   ├── usuarios.json
│   └── ventas.json
│
├── modelos/
│   ├── __init__.py
│   ├── producto.py
│   ├── usuario.py
│   └── venta.py
│
├── servicios/
│   ├── __init__.py
│   ├── archivo_servicio.py
│   └── restaurante_servicio.py
│
├── ui/
│   ├── __init__.py
│   ├── login_view.py
│   └── main_view.py
│
├── main.py
└── README.md```
Ejecución

Para ejecutar la aplicación se debe abrir una terminal dentro de la carpeta restaurante_app y ejecutar:

python main.py

También se puede utilizar:

py main.py
