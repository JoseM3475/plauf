# Especificación de Requisitos de Software (ERS)

## 1. Introducción

### 1.1 Propósito

El objetivo de este documento es definir los requisitos de la primera versión de la página web PlaUF.

### 1.2 Alcance

La aplicación consistirá en una página web estática que mostrará:

- El nombre de la web: PlaUF.
- Una dirección de correo electrónico de contacto: info@plauf.com.

Esta versión no incluirá formularios, autenticación ni almacenamiento de datos.

### 1.3 Definiciones

| Término | Descripción |
|----------|-------------|
| ERS | Especificación de Requisitos Software |
| Usuario | Persona que accede a la página web |
| PlaUF | Nombre de la aplicación web |

## 2. Descripción General

### 2.1 Perspectiva del Producto

PlaUF será una página web accesible desde cualquier navegador moderno.

### 2.2 Usuarios Objetivo

- Visitantes que necesiten información de contacto de PlaUF.

### 2.3 Suposiciones y Dependencias

- El usuario dispone de acceso a Internet.
- El sitio web estará disponible mediante HTTPS.

## 3. Requisitos Funcionales

### RF-01 Mostrar nombre del sitio

El sistema deberá mostrar el nombre de la web:

```text
PlaUF
```

### RF-02 Mostrar correo electrónico de contacto

El sistema deberá mostrar la dirección de correo electrónico:

```text
info@plauf.com
```

### RF-03 Acceso público

La información deberá estar disponible sin necesidad de autenticación.

## 4. Requisitos No Funcionales

### RNF-01 Disponibilidad

La página deberá estar disponible las 24 horas del día, salvo interrupciones programadas por mantenimiento.

### RNF-02 Rendimiento

La página deberá cargarse en menos de 3 segundos en condiciones normales de red.

### RNF-03 Compatibilidad

La página deberá visualizarse correctamente en:

- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Safari

### RNF-04 Diseño Responsive

La página deberá adaptarse correctamente a dispositivos:

- Escritorio
- Tablet
- Teléfono móvil

### RNF-05 Seguridad

La página deberá servirse mediante HTTPS.

## 5. Interfaz de Usuario

### 5.1 Página Principal

La página principal mostrará:

```text
PlaUF

Email de contacto:
info@plauf.com
```

## 6. Criterios de Aceptación

### CA-01

Dado que un usuario accede a la página principal, cuando esta se carga correctamente, entonces se deberá visualizar el texto "PlaUF".

### CA-02

Dado que un usuario accede a la página principal, cuando esta se carga correctamente, entonces se deberá visualizar el correo electrónico "info@plauf.com".

### CA-03

Dado que un usuario accede desde un dispositivo móvil o de escritorio, cuando visualiza la página, entonces el contenido deberá mostrarse correctamente.

## 7. Requisitos Futuros

Las siguientes funcionalidades quedan fuera del alcance de la versión actual y podrán incorporarse en futuras versiones:

- Formulario de contacto.
- Registro de usuarios.
- Inicio de sesión.
- Gestión de contenidos.
- Integración con bases de datos.
- API REST.
- Panel de administración.

## 8. Control de Versiones

| Versión | Fecha | Descripción |
|----------|----------|-------------|
| 1.0 | 23/09/2026 | Versión inicial del documento |
