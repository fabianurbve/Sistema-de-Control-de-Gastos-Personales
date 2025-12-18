SCGP v1.0
===================

💰 SCGP - Sistema de Control de Gastos Personales
Descripción del Proyecto
SCGP es una aplicación de escritorio simple y robusta diseñada para facilitar el control de tus finanzas personales. Permite registrar ingresos y gastos, visualizarlos por categorías y tipo, y calcular tu balance en tiempo real.

La aplicación fue desarrollada en Python utilizando la librería Tkinter para la interfaz gráfica y SQLite para la persistencia de los datos, garantizando portabilidad y facilidad de uso.

✨ Características Principales
Registro Intuitivo: Añade nuevos Ingresos o Gastos con facilidad, incluyendo monto, categoría y descripción.

Categorización Detallada: Movimientos clasificados por categorías predefinidas (ej. Alimentación, Sueldo, Inversión).

Balance Automático: Cálculo y visualización inmediata de tu balance total.

Filtrado de Reportes: Filtra y visualiza movimientos por tipo (Ingreso/Gasto) y categoría específica.

Visualización Gráfica: Generación de gráficos (usando Matplotlib) para entender la distribución de tus gastos.

Base de Datos Local: Utiliza SQLite (gastos_personales.db), lo que significa que todos tus datos se almacenan de forma segura y local en tu equipo.

🛠️ Tecnologías y Librerías
El proyecto está construido con:

Python 3.x

Tkinter: Para la interfaz gráfica de usuario.

SQLite3: Para la gestión de la base de datos (módulo nativo de Python).

Matplotlib: Para la generación de gráficos.

pywin32 y winshell: Utilizadas en INSTALLER.py para la creación de accesos directos en Windows.

📦 Estructura del Repositorio

main.py: Punto de entrada principal de la aplicación.

scgp_app.py: Clase principal de la interfaz de usuario (Tkinter).

logic.py: Contiene la lógica de negocio, validaciones y cálculos de balance/reporte.

database.py: Módulo para la conexión y operaciones con la base de datos SQLite.

gastos_personales.db: El archivo de la base de datos. Se crea automáticamente si no existe.

INSTALLER.py: Script para crear un acceso directo en el escritorio (enfocado en Windows).

⚠️ Advertencias Importantes
❌ No Borres ni Renombres los archivos clave (main.exe, gastos_personales.db, etc.). ❌ Ejecución del Instalador: INSTALAR.exe siempre debe ejecutarse desde la carpeta raíz de la aplicación para que pueda encontrar el archivo main.exe y el ícono correctamente.

SCGP - Sistema de Control de Gastos Personales

Versión: v1.0

Autor: Fabian


Fecha: Diciembre

