# Clase UPE · Python en VS Code y un proceso gaussiano desde cero

Material de la clase práctica de 2 horas de la **Unidad de Planeación Energética (UNAM)**.

La pregunta que resolvemos: *una ciudad registra su demanda eléctrica diaria; ¿cuánta capacidad hay que
reservar para la próxima semana?* Se contesta con un proceso gaussiano, programado primero desde cero
con NumPy y después con scikit-learn, comprobando que las dos rutas dan el mismo resultado.

## Antes de la clase

1. Lee **[`guia/Guia_Instalacion_VSCode.docx`](guia/Guia_Instalacion_VSCode.docx)** y deja tu computadora lista
   (VS Code, extensiones Python y Jupyter, Python 3.13 y las cinco librerías). Toma 20–30 minutos.
2. Descarga **[`Clase_GP.zip`](Clase_GP.zip)** y extráelo en `Documentos`.
3. Abre `notebooks/00_verifica_entorno.ipynb` y ejecútalo: debe terminar en **ENTORNO LISTO**.

> ¿No pudiste instalar nada? Los cuatro notebooks corren sin cambios en
> [Google Colab](https://colab.research.google.com) (Archivo → Subir cuaderno).

## Qué hay aquí

| Archivo | Qué es | Duración |
|---|---|---|
| `guia/Guia_Instalacion_VSCode.docx` | Instalación desde cero en Windows, con las trampas típicas y el plan B de Colab | — |
| `Clase_GP.zip` | Lo que se descarga: los cuatro notebooks sin ejecutar y `requirements.txt` | — |
| `notebooks/00_verifica_entorno.ipynb` | Comprueba que la instalación quedó bien | 10 min |
| `notebooks/01_python_en_vscode.ipynb` | Solo el Python que usa el notebook del GP: arreglos, máscaras, funciones, `@`, gráficas | 30 min |
| `notebooks/02_proceso_gaussiano_desde_cero.ipynb` | El GP paso a paso: kernel, a priori, las seis líneas línea por línea, la respuesta, scikit-learn y la **suma de dos kernels** | 60 min |
| `notebooks/03_tarea.ipynb` | Tarea: la misma ciudad con ritmo semanal → segundo kernel periódico | — |

## Librerías

```
python -m pip install -r requirements.txt
```

`numpy`, `pandas`, `matplotlib`, `scikit-learn`, `ipykernel`. Nada más: el proceso gaussiano se programa
con NumPy y se compara contra `sklearn.gaussian_process`.

---

Abelardo Rodríguez-Pretelín · Instituto de Geología, UNAM
