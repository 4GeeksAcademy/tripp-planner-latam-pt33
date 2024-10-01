# tripp-planner-latam-pt33
Proyecto final 

Integrantes:
    Adriana Isea
    Carlos Alzate
    Cesar Contreras
    Kevin Villca
    Luis Rene Silva

User story:
    Como alguien que le gusta viajar, quiero una app colaborativa donde enumerar las posibles actividades, evaluar costos para aprovechar al maximo mi viaje solo o en grupo. 

features:
 --reaccionar a las experiencias/actividades
 --Dividir las experiencias en categorias ?

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
