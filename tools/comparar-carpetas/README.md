# Comparar carpetas

Recorre dos carpetas y compara la huella SHA-256 de cada archivo. El CSV distingue `SOLO_ORIGEN`, `SOLO_DESTINO` y `CAMBIADO`.

La utilidad no copia, mueve ni elimina. Calcular huellas completas puede tardar con archivos muy grandes.

```powershell
python comparar_carpetas.py C:/origen C:/destino comparacion_carpetas.csv
```

Al abrir `comparar_carpetas.exe` sin argumentos aparece un asistente para las carpetas y el informe.
