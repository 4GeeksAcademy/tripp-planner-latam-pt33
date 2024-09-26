# tripp-planner-latam-pt33
Proyecto final 

Integrantes:
    Adriana Isea
    Carlos Alzate
    Cesar Contreras
    Kevin Villca
    Luis Rene Silva

User story:
    Como alguien que viaja con familia y amigos como turistas, quiero una app colaborativa donde enumerar las posibles actividades, evaluar costos necesarios, y de disfrute, para aprovechar al maximo mi presupuesto, y que ademas todo mi grupo de viaje pueda ver la misma informacion que yo y podamos escoger entre todos las atracciones y/o restaurantes a donde ir, los paseos que hacer, etc. Posiblemente incluso tener como una lista de mercado que incluya costos si vamos a cocinar en lugar de salir. Tambien me gustaria saber las horas de llegada de todos los viajeros.


--------------------------------------------------- Front-End -------------------------------------------------------------------
// Vista del home
    --componente de viaje por cad viaje planeado

// Componente de viaje
    --lugar
    --fecha de inicio
    --presupuesto
    --costos actuales
    --componente de actividad con opcion de seleccionar y deseleccionar // se selecciona para que su costo se sume al costo total del viaje

// Componente de actividad (ej.: restaurant, parque acuatico, tour)
    --foto
    --nombre
    --precio
    --duracion
    --fecha posible para ir
    --likes o votos

// Componente de usuario
    --nombre
    --foto
    --correo
    --numero
    --color para distinguirse por viaje
    --presupuesto personal

// Vista para la actividad
    --fotos
    --nombre
    --precio
    --duracion
    --descripcion
    --fecha posible para ir
    --likes o votos
    --comentarios

//Vista para el usuario
    --

    
--------------------------------------------------- Back-End --------------------------------------------------------------------

// db.user
    --nombre
    --foto
    --correo
    --numero
    --color para distinguirse por viaje
    --presupuesto personal
    --proximos viajes(db?)


//  db.grupo
    --persona = FK -> user.id
    --color_distincion = string

// db.viaje
    --usuario = FK -> user.id

//  db.actividad
    --fotos
    --nombre
    --precio
    --duracion
    --descripcion
    --fecha posible para ir
    --likes o votos
    --lista de comentarios(base de datos con 'FK -> actividad.id')
