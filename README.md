# Simulación del Sistema Solar

Este código tiene como objetivo simular el sistema solar, incluyendo los cuatro gigantes gaseosos y el Sol, mediante el método numérico de Runge-Kutta de cuarto orden. En el proceso de formulación, se han adoptado aproximaciones basadas en condiciones iniciales específicas.

## Configuración inicial

En el instante inicial (t=0), se ha configurado el sistema solar en una disposición alineada, lo que resulta en una velocidad inicial con una componente casi nula. Para corregir este aspecto y obtener una aproximación más precisa a las órbitas reales, se ha ajustado esta velocidad inicial a un valor cercano a cero.

Adicionalmente, se ha considerado al Sol en un estado estático. Esto implica que, debido a la proximidad del sistema de referencia al Sol y la infinitesimal distancia entre ellos, el movimiento del Sol se considera insignificante.

## Ecuaciones y Método Numérico

El código utiliza el método de Runge-Kutta de cuarto orden para resolver las ecuaciones diferenciales que describen el movimiento de los planetas. La función `planetary_system` define el sistema de ecuaciones diferenciales, y se considera la masa y la dirección de la fuerza entre los planetas.

## Parámetros de la Simulación

- Duración total de la simulación: 500 años
- Paso de tiempo: (6 horas)

## Dependencias

- NumPy
- Matplotlib

## Ejecución del Código

El código puede ejecutarse en un entorno de Python con las dependencias instaladas. Se recomienda utilizar un entorno virtual para gestionar las dependencias.

```bash
pip install numpy matplotlib
python nombre_del_archivo.py
