# PROYECTO 1- Criptografía y Seguridad

## Descripción

Este proyecto consiste en el desarrollo de librerías criptográficas en Python junto con interfaces gráficas para demostrar su funcionamiento.
Incluye distintos módulos relacionados con seguridad de la información y criptoanálisis.

## Objetivo

Implementar algoritmos criptográficos y herramientas de análisis, mostrando su funcionamiento mediante una interfaz interactiva.

## Estructura del Proyecto

**📁 modulos/**

Contiene la lógica principal del sistema (librerías criptográficas):

alberti.py: Cifrado polialfabético (Disco de Alberti)
frecuencias.py: Análisis de frecuencias de letras
auditoria.py: Simulación de auditoría de seguridad
debilidades.py: Clasificación de activos y vulnerabilidades
comunicaciones.py: Análisis de seguridad en comunicaciones
criptoanalisis.py: Diferencia entre fuerza bruta y criptoanálisis

**🖥️ interfaz/**

Contiene las interfaces gráficas del sistema:

menu.py: Menú principal
ventana_alberti.py: Interfaz del cifrado Alberti
ventana_frecuencias.py: Interfaz del análisis de frecuencias
ventana_auditoria.py: Interfaz de auditoría
ventana_debilidades.py: Interfaz de debilidades
ventana_comunicaciones.py: Interfaz de comunicaciones
ventana_criptoanalisis.py: Interfaz de criptoanálisis
componentes.py: Elementos reutilizables de interfaz

**🧰 utils/**

Funciones auxiliares reutilizables.

**🧪 tests/**

Pruebas del sistema.

**📄 docs/**

Documentación del proyecto:

documentacion.md: Documento técnico en desarrollo
documentacion.pdf: Versión final

**📌 Archivos principales**

main.py: Punto de entrada del programa
requirements.txt: Librerías necesarias
.gitignore: Archivos ignorados por Git

## ¿Cómo ejecutar el proyecto?

Clonar el repositorio:
```
git clone https://github.com/18283/proyecto1-criptografia.git
```

Instalar dependencias:
```
pip install -r requirements.txt
```

Ejecutar el programa:
```
python main.py
```

## Distribución del Trabajo

🔹 **1. Mapeo de Debilidades**

Responsables: Durán Marcelo, Kelly Alisson

Clasificación de activos: Hardware, Software, Datos
Asociación de vulnerabilidades y amenazas

🔹 **2. Análisis de Seguridad en Comunicaciones**

Responsable: Gonzales Alba Jose Brayan

Comparativa entre sistemas aislados e interconectados
Visualización de riesgos en el canal de comunicación

🔹 **3. Taller de Criptoanálisis Elegante**

Responsable: Mamani Peña Daniel Joaquin

Explicación interactiva de:
Fuerza bruta
Criptoanálisis
Enfoque teórico y comparativo

🔹 **4. Simulador de Auditoría Académica**

Responsable: Navarro Acosta Sara Eunice

Evaluación de seguridad mediante preguntas (P1–P4)
Determinación de estado seguro/inseguro

🔹 **5. Analizador de Frecuencias**

Responsables: (Agregar nombres)

Conteo de monogramas
Comparación con frecuencias del español
Propuesta de sustituciones automáticas

🔹 **6. Simulador del Disco de Alberti**

Responsables: (Agregar nombres)

Implementación de cifrado polialfabético
Configuración de clave y rotación del disco
Cifrado y descifrado