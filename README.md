# GastApp-proyecto-NuevasTecnologias
Descripción

GastApp es una aplicación diseñada para gestionar gastos personales.
Permite registrar ingresos, gastos y visualizar la información para llevar un mejor control financiero.

Este proyecto fue desarrollado como parte de la asignatura Nuevas Tecnologías.

------------------------------------------------------------------------------------------------------------------------

# Configuración del Proyecto

Para trabajar con el proyecto se debe seguir el siguiente proceso.

# Clonar el repositorio

git clone https://github.com/Anavalencia17/GastApp-proyecto-NuevasTecnologias.git

# Entrar al proyecto

cd GastApp-proyecto-NuevasTecnologias

# Abrir el proyecto

Abrir el archivo index.html en el navegador.
------------------------------------------------------------------------------------------------------------------------
#	Reglas de Colaboración:

1.	Prohibido hacer commits directos a main o develop.
2.	Cada tarea debe tener su propia rama feature/nombre-tarea.
3.	Toda fusión debe pasar por un Pull Request y ser aprobada por al menos un compañero.
4.	Mensajes de commit claros (ej: feat: agregar validación de formulario).

------------------------------------------------------------------------------------------------------------------------
# Modelo de Trabajo (GitFlow)

El proyecto utiliza un modelo de trabajo basado en GitFlow para organizar el desarrollo.

# Ramas principales

Rama	           Descripción
main	           Contiene el código final estable del proyecto
develop	         Rama donde se integran nuevas funcionalidades

------------------------------------------------------------------------------------------------------------------------
# Flujo de trabajo
1 Crear una rama

git checkout -b feature/nombre-tarea

2 Guardar cambios

git add .
git commit -m "Descripción del cambio"

3 Subir cambios

git push origin feature/nombre-tarea

4 Crear Pull Request

En GitHub se debe crear un Pull Request para que el código sea revisado antes de fusionarlo con la rama develop.
