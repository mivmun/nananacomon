## Paso 1: redirigete a la carpeta del proyecto

## Paso 2: cree el ambiente virtual
python -m venv myenv

## Paso 3: activar el entorno virtual 
myenv\Scripts\activate 

### Observación: si está en MacOs o Linux debe usar:
source myenv/bin/activate

## Paso 4: instalar las librerias del archivo requirements.txt
pip install -r requirements.txt

## Paso 5: luego descargar el csv mas reciente de la siguiente url: 
https://datosabiertos.mineduc.cl/titulados-en-educacion-superior/

## Paso 6: ejecutar la aplicación 
python get_excel_resumen_es.py