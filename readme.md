# Sweet Lift Taxi: Predicción de Pedidos de Taxis en Aeropuertos

## Descripción del proyecto

Sweet Lift Taxi ha recopilado datos históricos de pedidos de taxis en aeropuertos para anticipar la demanda horaria y atraer a más conductores durante las horas pico. En este proyecto se desarrolla un modelo de series temporales que predice el número de pedidos para la próxima hora.

## Estructura del repositorio

```
├── data/
│   └── historia_pedidos.csv    # Datos crudos de pedidos por hora
├── notebooks/
│   └── SweetLiftTaxi.ipynb      # Notebook con EDA y modelado
├── requirements.txt            # Dependencias del proyecto
└── README.md                   # Este archivo
```

## Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/sweet-lift-taxi.git
   cd sweet-lift-taxi
   ```
2. Crea un entorno virtual e instala dependencias:
   ```bash
   python -m venv venv
   source venv/bin/activate     # Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```

## Uso

Abre y ejecuta el Jupyter Notebook:

```bash
jupyter notebook notebooks/SweetLiftTaxi.ipynb
```

Dentro del notebook encontrarás:

- **EDA**: Análisis exploratorio y limpieza de datos.
- **Modelado**: Entrenamiento y evaluación de un modelo de series temporales.
- **Resultados**: Cálculo de RMSE en conjunto de prueba, con objetivo ≤ 48.

## Métrica de Evaluación

- **RMSE** (Error Cuadrático Medio): debe ser ≤ 48.

## Contribuciones

¡Bienvenidas! Si quieres mejorar el proyecto, abre un issue o envía un pull request.

## Licencia

Este proyecto está bajo la Licencia MIT.

