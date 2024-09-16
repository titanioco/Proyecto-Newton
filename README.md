# Proyecto-Newton
Descripción y uso del método de Newton-Rhapson para encontrar raices de una función 
[Método o Iteración de Newton y sus Aplicaciones](https://app.guidde.com/playbooks/dXYNXYHeonhQEojp4zgr9f)
==========================================================================================================

[Click here to watch](https://app.guidde.com/share/playbooks/dXYNXYHeonhQEojp4zgr9f)

### ![Quick guidde](https://static.guidde.com/v0/qg%2Fs36dhGZMZGU1SDhyBhR27hjkFNk2%2FdXYNXYHeonhQEojp4zgr9f%2FfJFgHxzzVGeiCDkCvQDo2T_cover.png?alt=media&token=858143b3-2bc0-412e-aca9-acba76eb142b)

### 1\. Alejandra a Daniela  Cálculo Diferencial

Hoy conoceremos más respecto a la Iteración de Newton, ó Método de Newton-Rhapson Este algoritmo, o método para calcular las raíces de una función, es decir los puntos en los que dicha función tiene un valor de cero, fue diseñado por Isaac Newton aunque fue Joseph Rhapson quien continuó con el trabajo. Rhapson expandió el conpecto que es usado en múltiples áreas, desde el cálculo hasta la química. Este algoritmo hace uso del concepto de aproximaciones y es un caso ejemplar de derivación términos funcionales. Hoy exploraremos el concepto y algunas utilidades.

![Alejandra a
Daniela 
Cálculo Diferencial](https://static.guidde.com/v0/qg%2Fs36dhGZMZGU1SDhyBhR27hjkFNk2%2FdXYNXYHeonhQEojp4zgr9f%2FfJFgHxzzVGeiCDkCvQDo2T_doc.png?alt=media&token=36a9315f-fcc1-419a-ac7a-a7ff198cfda6)

### 2\. View "4.9 Método de Newton - Cálculo volumen 1 | OpenStax"

Gráficamente podemos entender el razonamiento detrás del método de Newton-Rhapson, en base a líneas tangentes que se aproximan al punto en que nuestra función se cruza con el eje x

![View '4.9 Método de Newton - Cálculo volumen 1 | OpenStax'](https://static.guidde.com/v0/qg%2Fs36dhGZMZGU1SDhyBhR27hjkFNk2%2FdXYNXYHeonhQEojp4zgr9f%2FmoA9h3fwUNCvo5TDR3mHCX_doc.png?alt=media&token=10967cce-6db9-4205-a396-c4d85ae790df)

### 3\. Raices poco claras

Surge debido a las limitaciones que puede tener la fórmula cuadrática y otros métodos algebráicos para calcular raices de forma precisa y veloz Es por esto que la fortaleza de este algoritmo está en generar aproximaciones muy cercanas a las raíces que queremos conocer hasta que la variación con el valor real sea despreciable, sin embargo es necesario conocer las limitaciones de este método como lo es los puntos máximos y mínimos de una función donde la pendiente de su recta tangente sea cero pues al ser un cociente, nos dejaría con una indeterminación.

![Raices poco claras](https://static.guidde.com/v0/qg%2Fs36dhGZMZGU1SDhyBhR27hjkFNk2%2FdXYNXYHeonhQEojp4zgr9f%2FosjzVHSPwpqraXxcuhKTwa_doc.png?alt=media&token=701ae927-95f9-4794-b782-b66c08c1f735)

### 4\. Aprox. 1

Tomamos una aproximación inicial, esta primer recta tangente a la función, nos acerca pero no es de mucha ayuda aún

![Aprox. 1](https://static.guidde.com/v0/qg%2Fs36dhGZMZGU1SDhyBhR27hjkFNk2%2FdXYNXYHeonhQEojp4zgr9f%2F1SBJcbAyLMXjxj4vMse8br_doc.png?alt=media&token=a6448630-bf39-4125-920c-b0f9725d409c)

### 5\. (x(i),x´(i))

en su punto más cercano aún hay poca precisión.

![(x(i),x´(i))](https://static.guidde.com/v0/qg%2Fs36dhGZMZGU1SDhyBhR27hjkFNk2%2FdXYNXYHeonhQEojp4zgr9f%2FngwWMYFD7BVABH2xnFqprN_doc.png?alt=media&token=502450a4-f197-4841-bfb8-b4a5eafd33c8)

### 6\. Aprox. 2

con la segunda iteración del algoritmo, utilizamos los datos que obtuvimos en el paso anterior, de esta forma nos acercamos un poco más a la raíz que queremos conocer la exactitud del resultado se incrementa conforme realizamos los pasos de este bucle nuevamente.

![Aprox. 2](https://static.guidde.com/v0/qg%2Fs36dhGZMZGU1SDhyBhR27hjkFNk2%2FdXYNXYHeonhQEojp4zgr9f%2Foqz2gWyHFv5imw4wtSfvAD_doc.png?alt=media&token=f78df225-3427-4172-b72c-84460999b946)

### 7\. (x(ii),x¨(ii))

aunque nos acercamos bastante aún podríamos utilizar el método para aproximarnos incluso más a la raíz real esto puede repetirse cuantas veces sea necesario hasta encontrar el nivel de precisión que podemos tolerar en algunas de las distintas aplicaciones de este algoritmo. como lo son, la creación de fractales, ecuaciones no-lineales, e incluso para simulaciones de procesos químicos.

![(x(ii),x¨(ii))](https://static.guidde.com/v0/qg%2Fs36dhGZMZGU1SDhyBhR27hjkFNk2%2FdXYNXYHeonhQEojp4zgr9f%2Fw82GW6xD6UbqNaEr3moBX8_doc.png?alt=media&token=518fe9d5-1215-4e80-b47b-97b1df877790)

### 8\. Segunda ejecución

a medida que nos ejecutamos los pasos del bucle, contínuamente encontramos puntos por los que nuestra nueva recta es tangente, tanto su pendiente como su acercamiento cambian hasta que ambas funciones cruzan el eje x, en puntos muy cercanos.

![Segunda ejecución](https://static.guidde.com/v0/qg%2Fs36dhGZMZGU1SDhyBhR27hjkFNk2%2FdXYNXYHeonhQEojp4zgr9f%2F1ogXejbkZeqSrpsaXtn448_doc.png?alt=media&token=ef50c067-0187-4fbd-bb45-fb31c01612c5)

### 9\. Click here

con frecuencia observaremos limitaciones con la aplicación de la fórmula cuadrática que no facilitan el cálculo de las raíces de una función, en este momento podremos utilizar el método de newton para realizar aproximaciones a estas raíces. sin embargo debemos notar los puntos máximos y mínimos donde nuestro algoritmo tiene una fuerte limitación

![Click here](https://static.guidde.com/v0/qg%2Fs36dhGZMZGU1SDhyBhR27hjkFNk2%2FdXYNXYHeonhQEojp4zgr9f%2FbqKYD1bFbAm9Hk1v14hBsR_doc.png?alt=media&token=2ff02b3a-d376-4042-876e-6a8d1e5314ac)

### 10\. Click here

es en estos puntos donde la pendiente es cero y al encontrarse en el denominador, puede dar como resultado situaciones con indeterminantes como 0/0

![Click here](https://static.guidde.com/v0/qg%2Fs36dhGZMZGU1SDhyBhR27hjkFNk2%2FdXYNXYHeonhQEojp4zgr9f%2Fh1JUfRDK5o2FAqdxPu1VTD_doc.png?alt=media&token=669bdbeb-735b-4f27-8643-89b8b08e9ab8)

### 11\. View "Método de Newton-Raphson para simulación de procesos químicos"

View the page at "Método de Newton-Raphson para simulación de procesos químicos"

![View 'Método de Newton-Raphson para simulación de procesos químicos'](https://static.guidde.com/v0/qg%2Fs36dhGZMZGU1SDhyBhR27hjkFNk2%2FdXYNXYHeonhQEojp4zgr9f%2F6nqLYLjgsHWszmGAvWYrCT_doc.png?alt=media&token=b2d91fc1-93a6-44cc-bef2-3ca18e57ff33)

### 12\. View "Método de Newton-Raphson para simulación de procesos químicos"

Go to the "Método de Newton-Raphson para simulación de procesos químicos" page

![View 'Método de Newton-Raphson para simulación de procesos químicos'](https://static.guidde.com/v0/qg%2Fs36dhGZMZGU1SDhyBhR27hjkFNk2%2FdXYNXYHeonhQEojp4zgr9f%2F1j2mLPGJ1h2szYbboZBmVP_doc.png?alt=media&token=7139c39e-395d-4d6f-9fa9-9d0a12b7e2ea)

### 13\. View "Método de Newton-Raphson para simulación de procesos químicos"

Refer to the specified content.

![View 'Método de Newton-Raphson para simulación de procesos químicos'](https://static.guidde.com/v0/qg%2Fs36dhGZMZGU1SDhyBhR27hjkFNk2%2FdXYNXYHeonhQEojp4zgr9f%2FhZ2fjN1xEpELcZJLvA5dHZ_doc.png?alt=media&token=32fe7f0a-106b-45b0-96c8-33ddf4212b91)

### 14\. View "Método de Newton-Raphson para simulación de procesos químicos"

Access the specified content.

![View 'Método de Newton-Raphson para simulación de procesos químicos'](https://static.guidde.com/v0/qg%2Fs36dhGZMZGU1SDhyBhR27hjkFNk2%2FdXYNXYHeonhQEojp4zgr9f%2FvNRErVrv2QVKsEYQr7vnGg_doc.png?alt=media&token=c4081216-70ac-4323-ad59-81cdf6c7b33e)

### 15\. View "Método de Newton-Raphson para simulación de procesos químicos"

View the content provided.

![View 'Método de Newton-Raphson para simulación de procesos químicos'](https://static.guidde.com/v0/qg%2Fs36dhGZMZGU1SDhyBhR27hjkFNk2%2FdXYNXYHeonhQEojp4zgr9f%2F6svPXSeZsUshJZA9fAadjD_doc.png?alt=media&token=22aa63d7-28af-4029-9cb8-00432ffcb87e)

### 16\. View "Método de Newton-Raphson para simulación de procesos químicos"

Refer to the content provided.

![View 'Método de Newton-Raphson para simulación de procesos químicos'](https://static.guidde.com/v0/qg%2Fs36dhGZMZGU1SDhyBhR27hjkFNk2%2FdXYNXYHeonhQEojp4zgr9f%2FfeBCgNy3ASXTp8DDCkGRi4_doc.png?alt=media&token=7d0e064a-7144-492a-a9fc-29b032968db3)

### 17\. View "Método de Newton-Raphson para simulación de procesos químicos"

Access the content provided.

![View 'Método de Newton-Raphson para simulación de procesos químicos'](https://static.guidde.com/v0/qg%2Fs36dhGZMZGU1SDhyBhR27hjkFNk2%2FdXYNXYHeonhQEojp4zgr9f%2FwdghhRWAQJU3jMwFWJN6xM_doc.png?alt=media&token=dce560f4-84bd-4e5f-b11c-cbfb40cdd0f8)

The guide covered a range of actions across different applications, simplifying tasks such as clicking on buttons in Geogebra and accessing specific content in Openstax and Ingenieriaquimicareviews. These clear instructions aim to facilitate user interaction and navigation within the applications.

[Powered by **guidde**](https://www.guidde.com)
