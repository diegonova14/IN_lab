Los programas están hechos para abrir y ejecutar.

Son dos notebooks:
- `simulacion.ipynb` que ejecuta las simulaciones en los dos modelos y exporta los datos de simulación en formato `.txt`,
- `analisis.ipynb` que normaliza los datos de simulación frente a las mediciones respecto al máximo valor del pico Compton.

Se separaron en dos documentos puesto que los tiempos de simulación son de 2 minutos por simulación. Tambien para facilidad de lectura.

Requisitos minimos:
- Libreria `Matplotlib`
- Libreria `Numpy`
- Libreria `Pandas`
- Archivo de datos experimentales `NaI_137Cs_600s.dat`
- Archivo de datos experimentales `NaI_Fondo_600s.dat`

Primero ejecutar `simulación.ipybn` y luego `analisis.ipybn`. Sin embargo, si se tienen los archivos con los resultados de simulación se pude ejecutar solo `analisis.ipybn`
