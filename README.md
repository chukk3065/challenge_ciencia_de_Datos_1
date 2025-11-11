1. Sobre el proyecto.
    Hola, este es el resultado de un Challenge de Alura Latam. 
    tiene el proposito de emitir una recomendación al Sr. Juan para que pueda tomar la mejor desicion sobre cual de sus tiendas cerrar, todo esto basado en datos reales obtenidos de las bases de datos de 
    cada una de sus tiendas, los datos analizados fueron:
        - Monto total de ingresos.
        - Costo promedio de envio por cada tienda.
        - Productos mas vendidos por categoria.
        - Calificación promedio de cada tienda (opinión de los clientes sobre la tienda).
        - Productos mas y menos vendidos de cada tienda.

        con base en esto se emitió una recomendación sobre que tienda debería ser vendida, basandose en las fortalezas y debilidades de cada tienda.
       Adicional a esto agregúe una columna en donde se aprecian los valores de las ventas y envios expresadas en dolares para una visualizacion mas comoda
       y un apartado de la relacion entre los ingresos y los envios para reflejar el efectivo que cada envío genera.

2. Estructura del proyecto.
   Dentro del apartado de Google Collab el proyecto está organizado por cada tienda, siguiendo la estructura que se aprecia en el punto anterior y por ultimo una seccion en donde se concentran tres tablas
   sus respectivos graficos en los cuales se observan las comparativas de los resultados obtenidos, las conclusiones obtenidas de este analisis se encuentran en el documento PDF que acompaña al
   archivo para importar el entorno de Google Collab.

3. Graficos obtenidos. 
3.1. Reporte de ingresos por cada tienda (en dolares).
   <img width="921" height="539" alt="image" src="https://github.com/user-attachments/assets/ebfca202-cb51-4d6e-89e5-8a134a76dda1" />
3.2. Costo promedio de envío en cada tienda.
   <img width="921" height="570" alt="image" src="https://github.com/user-attachments/assets/e344fb6b-dbe1-4992-88b5-b2d9b7f16153" />
3.3. Relación Ingresos/envíos.
   <img width="921" height="548" alt="image" src="https://github.com/user-attachments/assets/c53c8121-a991-408c-939e-dab4ad0aac8d" />
3.4. Calificación promedio de cada tienda. 
   <img width="921" height="630" alt="image" src="https://github.com/user-attachments/assets/5a3af82a-49ad-406a-9a40-b56a4ea60eba" />
3.5. Productos mas vendidos por sucursal.
   <img width="921" height="382" alt="image" src="https://github.com/user-attachments/assets/86c5c496-6e4f-4dcb-882a-1a725d8b14b3" />
3.6.
   <img width="921" height="382" alt="image" src="https://github.com/user-attachments/assets/723b6415-49d8-4f2d-8963-7fdc20052eac" />

4. Guia para importar el archivo.
   1. Importar archivos desde tu computadora (almacenamiento de sesión)
      Este método carga los archivos directamente al entorno de ejecución temporal de Colab. Los archivos se eliminarán cuando finalice la sesión. 
      Usando la interfaz de usuario:
      En el menú lateral izquierdo, haz clic en el icono de "Archivos" (la carpeta).
   2. Haz clic en el botón "Subir al almacenamiento de sesión" (el icono de flecha hacia arriba).
   3. Selecciona el archivo deseado en tu computadora local y haz clic en "Abrir"

Usando código Python:
from google.colab import files

uploaded = files.upload()

for filename in uploaded.keys():
  print(f'Uploaded file "{filename}"')

English. 
1. About the project
Hello, this is the result of a Challenge from Alura Latam.
Its purpose is to provide a recommendation to Mr. Juan so that he can make the best decision regarding which of his stores should be closed. All of this is based on real data obtained from each store’s database. The analyzed data includes:

- Total revenue amount
- Average shipping cost per store
- Best-selling products by category
- Average rating of each store (customer reviews)
- Best- and worst-selling products of each store

Based on this information, a recommendation was made regarding which store should be sold, considering the strengths and weaknesses of each one.
In addition, I added a column in which the values of sales and shipping costs are expressed in dollars for a more convenient visualization,
as well as a section showing the relationship between revenue and shipping to reflect the profit generated per shipment.

2. Project structure
In the Google Colab notebook, the project is organized by store, following the structure shown in the previous section, and finally a section where three tables and their corresponding charts are compiled. These allow us to compare the results obtained.
The conclusions from this analysis can be found in the PDF document that accompanies the file used to import the Google Colab environment.

3. Charts obtained
3.1. Revenue report per store (in dollars).
<img width="921" height="539" alt="image" src="https://github.com/user-attachments/assets/ebfca202-cb51-4d6e-89e5-8a134a76dda1" />
3.2. Average shipping cost per store.
<img width="921" height="570" alt="image" src="https://github.com/user-attachments/assets/e344fb6b-dbe1-4992-88b5-b2d9b7f16153" />
3.3. Revenue/Shipping relationship.
<img width="921" height="548" alt="image" src="https://github.com/user-attachments/assets/c53c8121-a991-408c-939e-dab4ad0aac8d" />
3.4. Average rating of each store.
<img width="921" height="630" alt="image" src="https://github.com/user-attachments/assets/5a3af82a-49ad-406a-9a40-b56a4ea60eba" />
3.5. Best-selling products per store.
<img width="921" height="382" alt="image" src="https://github.com/user-attachments/assets/86c5c496-6e4f-4dcb-882a-1a725d8b14b3" />
3.6.
<img width="921" height="382" alt="image" src="https://github.com/user-attachments/assets/b8ca5883-f900-4895-8e4e-263352a3eac3" />

4. Guide for importing the file

Import files from your computer (session storage)
This method uploads files directly into Colab’s temporary runtime environment. Files will be deleted once the session ends.
Using the user interface:
In the left sidebar, click on the "Files" icon (the folder).

Click the “Upload to session storage” button (the upward arrow icon).

Select the desired file from your local computer and click “Open”.

Using Python code:

from google.colab import files

uploaded = files.upload()

for filename in uploaded.keys():
  print(f'Uploaded file "{filename}"')




