# RPA_StringManipulation3
Ejercicios de RPA con UiPath

Ejercicios:
2.0) Crear un diccionario llamado “nombreDirección”. Agregar los siguientes elementos al 
mismo (Respetando mayúsculas y minúsculas):
- Clave: “Analia” – Valor: “San Nicolas - CABA”
- Clave: “Francisco” – Valor: “Bariloche - Rio Negro”
- Clave: “Viviana” – Valor: “Esquel - Chubut”
2.1) Imprimir el domicilio de Analia por pantalla.2.2) Analia nos avisa que ya no vive en caba, se mudó a “Lago Puelo - Chubut”. Reemplazar el 
valor de su clave en el diccionario con su nuevo domicilio (Tip: Utilizar comando assign)
2.3) Volver a imprimir el domicilio de Analia por pantalla verificando el correcto cambio de 
domicilio.
2.2) Verificar si existe “Gaspar” en el diccionario. Si no existe, agregarlo con la misma dirección 
que “Francisco”. (Tip: Utilizar sentencia IF y hacer referencia al valor de “Francisco” para 
obtener el domicilio) 
2.4) Imprimir por pantalla cuantos elementos tiene el diccionario. (Tip: Utilizar método Count)
2.5) Recorrer cada elemento del diccionario y en cada iteración realizar:
- Imprimir el siguiente mensaje para cada elemento “La persona $Clave$ tiene 
domicilio en $Valor$” En donde $Valor$ NO incluye la provincia, solo incluye la ciudad. (TIP: 
Utilizar String Format)
