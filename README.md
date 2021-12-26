# FC-Frontend-Fase01-ModeloBD

- Un usuario está asociado a varios candidatos
- Un candidato está asociado a solo un usuario

- un candidato está asociado a varias etiquetas
- una etiqueta está asociada a varios candidatos.
- Se resuelve esta relación de muchos a muchos con la tabla candidato_etiqueta 
  el mismo que hereda las KEY de las tablas 'candidato' y 'etiqueta'
  y tiene un campo más que me permite conocer el nivel de ese candidato en dicha etiqueta.
