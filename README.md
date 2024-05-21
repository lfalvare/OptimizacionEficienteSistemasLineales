# Optimización Eficiente de Sistemas de Ecuaciones Lineales a Gran Escala

## Descripción

Este repositorio contiene los programas creados para el proyecto de doctorado titulado **"Optimización eficiente de sistemas de ecuaciones lineales a gran escala mediante precondicionamiento y procesamiento paralelo basados en métodos de Krylov"**. El objetivo del proyecto es desarrollar y optimizar algoritmos para resolver sistemas de ecuaciones lineales a gran escala de manera eficiente utilizando técnicas avanzadas de precondicionamiento y procesamiento paralelo.

## Contenido

- **Clases y funciones para el manejo de matrices dispersas**: Incluye métodos para descargar, cargar y visualizar matrices dispersas desde el repositorio SuiteSparse Matrix Collection.
- **Implementaciones de métodos de Krylov**: Contiene implementaciones optimizadas de métodos de Krylov para la resolución de sistemas de ecuaciones lineales.
- **Precondicionadores**: Algoritmos y técnicas de precondicionamiento diseñadas para mejorar la convergencia de los métodos iterativos.
- **Implementación de métodos de Krylov en paralelo**: Utiliza técnicas de procesamiento paralelo para mejorar la eficiencia y escalabilidad de los métodos de Krylov en sistemas de ecuaciones lineales a gran escala.
- **Ejemplos y pruebas**: Scripts y notebooks que demuestran el uso de las clases y funciones desarrolladas, así como pruebas de rendimiento y escalabilidad.

## Requisitos

- Python 3.x
- Bibliotecas Python:
  - `ssgetpy`
  - `numpy`
  - `scipy`
  - `matplotlib`
  - `multiprocessing`
  - `mpi4py`
  - `psutil`
  - `joblib`

## Instalación

1. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/tuusuario/optimizacion-ecuaciones-lineales.git
   cd optimizacion-ecuaciones-lineales

## Uso
### Descargar y cargar matrices dispersas
  from utilidad_matrices_dispersa import UtilidadMatricesDispersas

  # Definir el nombre del grupo, el nombre de la matriz y el directorio de descarga
  nombre_grupo = 'HB'
  nombre_matriz = 'ash331'
  path_descarga = '/ruta/a/tu/directorio/matrices'

  # Crear una instancia de la utilidad de matrices dispersas
  utilidad = UtilidadMatricesDispersas(nombre_grupo, nombre_matriz, path_descarga)

  # Descargar y cargar la matriz
  utilidad.descargar_matriz()
  matriz = utilidad.cargar_matriz()

  # Visualizar la estructura de la matriz
  if matriz is not None:
      utilidad.visualizar_estructura_matriz()

## Contribuciones

## Licencia
