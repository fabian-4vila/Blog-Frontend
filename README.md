# Ecommerce de Práctica con Angular 18
Este proyecto es un ecommerce de práctica desarrollado con Angular 18. El objetivo es construir una plataforma dinámica donde los usuarios puedan explorar productos, agregarlos al carrito, gestionar sus compras y simular una experiencia real de comercio electrónico. Esta aplicación está pensada como ejercicio práctico para mejorar las habilidades en desarrollo frontend con Angular.

## Tecnologías

- **Angular 18 (LTS):** Framework principal para el frontend.
    
- **TypeScript:** Lenguaje utilizado para escribir código en Angular.
    
- **CSS/SASS:** Para el diseño y estilo del blog.
    
- **HTML5:** Estructura del contenido.
    

## Características

- Publicación de notas diarias.
    
- Sistema de visualización de las entradas.
    
- Diseño responsivo para diferentes dispositivos.
    
- Uso de Signals para la gestión de reactividad.
    

## Requisitos del sistema

Asegúrate de tener instalados los siguientes elementos en tu entorno de desarrollo:

- **Node.js** (versión 18 o superior)
    
- **Angular CLI** (versión más reciente compatible con Angular 18)
    
- **NPM** o **Yarn** como gestor de paquetes

## Estructura del proyecto
```zsh
B-F-E-Commerce/
├── .vscode/                 
│     ├── extensions.json
│     ├── launch.json
│     └── tasks.json
├── public/                   
│    └── favicon.ico       
├── src/  
│    ├── app/
│    │    ├── products/
│    │    │    ├── data-access/
│    │    │    │    ├── products-state.service.ts
│    │    │    │    └── products.service.ts
│    │    │    ├── features/
│    │    │    └── ui/product-card/
│    │    ├── shared/
│    │    │    ├── UI/header/
│    │    │    ├── data-access/
│    │    │    └── interfaces/
│    │    ├── app.component.html
│    │    ├── app.component.scss
│    │    ├── app.component.spec.ts
│    │    ├── app.component.ts
│    │    ├── app.config.ts
│    │    └── app.routes.ts
│    ├── environments/
│    │    ├──environment.development.ts
│    │    └── environment.ts
│    ├── index.html
│    ├── main.ts
│    └── styles.scss    
├── .editorconfig            
├── .gitignore              
├── README.md              
├── angular.json              
├── eslint.config.js       
├── package-lock.json       
├── package.json              
├── tailwind.config.js       
├── tsconfig.app.json        
├── tsconfig.json          
└── tsconfig.spec.json       

```

