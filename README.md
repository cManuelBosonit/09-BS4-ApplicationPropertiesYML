# 09-BS4-ApplicationPropertiesYML

Realizar aplicación que tenga en el fichero ‘application.properties’ los siguientes valores.
VAR1=CONTENIDO DE VALOR1
My.VAR2=100
Conseguir leer las propiedades desde una un controlador y devolverlo. 
GET /valores/ -> return “valor de var1 es: “+var1+ “valor de my.var2 es: “+var2;
Intentar leer el valor ‘VAR3’, que no existe en application.properties. Deberá asignar a la variable el texto ‘var3 no tiene valor”
GET /var3/ -> return “valor de var3 es: “+var3;
Poner la variable ‘var3’ dentro del S.O.  Lanzar aplicación y ver como la presenta.
Pero cambiando el fichero application.properties por “application.yml” (adaptando el formato) Deberían obtenerse los mismos resultados que anteriormente.
