# 🛡️ C++ AES-256 Smart Locker

> [!CAUTION]
> ### ⚠️ ALERTA: PROCESO IRREVERSIBLE
> Al ejecutar este programa, **todo el contenido** dentro de la carpeta objetivo será encriptado mediante AES-256-GCM y **posteriormente borrado**. 
>
> **Expansión de carpetas (Smart Scan):**
> El algoritmo es recursivo. Esto significa que si la carpeta principal contiene otras carpetas (subcarpetas), el programa entrará en cada una de ellas, encriptará los archivos internos y seguirá bajando hasta que no quede ni un solo archivo sin procesar en toda la estructura del árbol.

---

### 🚀 Pasos para la ejecución

1. **Descarga el archivo fuente**
   Descarga el archivo `Ransomware.cpp` en tu equipo.

2. **Configuración manual**
   Abre el archivo y dirígete a la **línea 53**. Modifica la ruta de la siguiente manera:
   ```cpp
   std::string carpeta_objetivo = "Aca pone el nombre de tu carpeta a encriptar";
