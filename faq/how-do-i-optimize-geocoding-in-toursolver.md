# 12. ¿Cómo optimizo la geocodificación en TourSolver?

* **Proporcione direcciones completas y precisas** Asegúrese de que cada dirección incluya el nombre de la calle, el número, el código postal, la ciudad y el país. Datos limpios y consistentes mejoran los resultados de geocodificación.
*   **Use campos separados para cada componente de la dirección** TourSolver admite dos formatos para ingresar la información de direcciones:

    1. **Columnas estructuradas** – Calle, Código Postal, Ciudad y País ingresados por separado.
    2. **Campo combinado único** – Dirección completa ingresada en una sola columna.

    👉 Para asegurar una geocodificación precisa, **elija un formato y úselo de manera consistente**. No mezcle columnas estructuradas con un campo combinado en el mismo conjunto de datos, ya que esto puede causar errores o inconsistencias en el reconocimiento de direcciones.
* **Verifique la información del distrito** Para mejorar la precisión de la geocodificación, siempre **especifique el distrito correcto** al ingresar los datos de direcciones. TourSolver ahora incluye una **columna de Distrito**, que ayuda al sistema a delimitar la búsqueda y localizar la zona correcta de manera más efectiva.👉 Usar el campo de distrito de forma constante garantiza que las direcciones se asignen a la zona geográfica correcta y reduce errores en la planificación de rutas.

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

* **Prefiera las coordenadas GPS cuando estén disponibles** Si dispone de valores de latitud y longitud, inclúyalos. TourSolver los utilizará directamente y omitirá la geocodificación de direcciones, lo que resulta en mayor precisión.
* **Revise la calidad de la geocodificación después de la importación** Utilice los indicadores de calidad de geocodificación para identificar puntos incorrectos o de baja calidad y corregirlos en los datos.
* **Opción de reposicionamiento en la aplicación móvil** Para mejorar la calidad de la geocodificación, TourSolver ofrece una **opción de Reposicionamiento** en la aplicación móvil. Esta función permite a los usuarios **actualizar o ajustar la ubicación directamente desde su dispositivo móvil**, garantizando que la posición registrada sea precisa y esté alineada con el sitio real.👉 Usar la opción de reposicionamiento ayuda a corregir discrepancias menores y mejora la precisión de las direcciones geocodificadas en la planificación de rutas.
