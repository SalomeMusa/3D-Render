##COMO SE CREA UNA IMAGEN?
Como se ve en la imagen el renderizado de figuras 3D es como una proyeccion. Se toma la figura y se proyecta sobre un plano el cual forma una piramide con lo que seria el ojo del espectador. El ojo del espectador seria esta punta de la piramide que hace que el resto parezca como un lienzo. 
De esta forma se sustenta la creacion de imagenes en diversos medios. Osea que, este concepto tiene una aplicacion universal en la representacion visual.

![alt text](image.png)
##COMO SE HACE LA PROYECCION?
Esta proyeccion lo que hace es transformar objetos tridimencionales(x,y,z) a un plano bidimensional (x,y). Esto genera una ilusion de profundidad sobre el espectador en una superficie que en realidad es plana.
Por ejemplo. Si un vertice del cubo se conecta con el ojo del espectador (aclaro que es el vertice de la esquina mas a la derecha de la piramide) El punto que pasa por el plano vendria siendo la proyeccion del mismo.Los vértices c0, c1, c2 y c3, su proyección sobre el lienzo da lugar a los puntos c0', c1', c2' y c3'. Entonces en nuestro plano se van representar estos objetos en 3D como puntos proyectados.

![alt text](image-1.png)

##TEMA PROXIMO: LUCES Y COLORES

Referencias: https://www.scratchapixel.com/lessons/3d-basic-rendering/introduction-to-ray-tracing/how-does-it-work.html 
Basicamente explico lo que dice ahi con mis palabras para entenderlo mejor e internalizar los conceptos que componen este proceso de renderizacion.