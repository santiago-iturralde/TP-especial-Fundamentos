# TP Especial - Fundamentos de Ciencia de Datos

Análisis del dataset "Horse Colic" para la materia Fundamentos de Ciencia de Datos.

### Alumnos
* Santiago Iturralde
* Laborde Joaquin

---
---

### Contenido del Repositorio
* `TPespecialFundamentos.ipynb`: Notebook de Jupyter con todo el código y análisis.
* `INFORME TRABAJO PRÁCTICO ESPECIAL.pdf`: El informe final con las conclusiones.
* `requirements.txt`: Las librerías de Python necesarias para correr el notebook.
* `horse-colic.data`: el archivo .data
* `horse-colic.names`: el archivo .names
* `horse-colic.test`: el archivo .test

---

##  Pre-requisitos

Para ejecutar este proyecto, solo necesitás **Python 3.7** o superior.

Puedes verificar tu versión de Python abriendo una terminal y escribiendo:
```bash
python --version
```

---

##  Instrucciones de Ejecución (Paso a Paso)
Estas instrucciones te guiarán para crear un entorno aislado y correr el notebook sin problemas en cualquier sistema operativo (Windows, macOS o Linux).

### 1. Clona el Repositorio
Abre tu terminal, navega hasta la carpeta donde quieras alojar el proyecto y ejecuta:
```bash
git clone [https://github.com/santiago-iturralde/TP-especial-Fundamentos.git](https://github.com/santiago-iturralde/TP-especial-Fundamentos.git)
```

### 2. Ingresa a la Carpeta
```bash
cd TP-especial-Fundamentos
```

### 3. Crea un Entorno Virtual
Esto crea una carpeta "limpia" llamada `venv` donde se instalarán las librerías, sin afectar a otros proyectos de tu computadora.
```bash
python -m venv venv
```
(En algunos sistemas puede ser `python3 -m venv venv`)

### 4. Activa el Entorno Virtual
**¡Este es el único paso que cambia según tu sistema!**

* **En Windows (CMD o PowerShell):**
    ```bash
    .\venv\Scripts\activate
    ```

* **En macOS o Linux (Bash):**
    ```bash
    source venv/bin/activate
    ```

(Sabrás que funcionó porque tu terminal ahora mostrará `(venv)` al principio de la línea).

### 5. Instala las Librerías
Con el entorno ya activado, corre el siguiente comando para instalar todas las librerías que usamos en el TP (pandas, scikit-learn, etc.):
```bash
pip install -r requirements.txt
```

### 6. Ejecuta Jupyter Notebook
Una vez instaladas las librerías, ya estás listo. Ejecuta:
```bash
jupyter notebook TPespecialFundamentos.ipynb
```
Esto abrirá automáticamente el notebook en tu navegador, ¡listo para que ejecutes las celdas!
