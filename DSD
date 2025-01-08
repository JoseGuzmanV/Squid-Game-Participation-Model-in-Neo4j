```cypher
// Paso 1: Crear los nodos de los jugadores
CREATE (p1:Jugador {id: 1, nombre: 'Jugador 1'})
CREATE (p2:Jugador {id: 2, nombre: 'Jugador 2'})
CREATE (p3:Jugador {id: 3, nombre: 'Jugador 3'})
CREATE (p4:Jugador {id: 4, nombre: 'Jugador 4'})
CREATE (p5:Jugador {id: 5, nombre: 'Jugador 5'})

// Paso 2: Crear los nodos de los juegos
CREATE (j1:Juego {nombre_del_juego: 'Luz roja, luz verde'})
CREATE (j2:Juego {nombre_del_juego: 'El juego de la cuerda'})
CREATE (j3:Juego {nombre_del_juego: 'La pelotita'})

// Paso 3: Crear las relaciones entre los jugadores y los juegos
// Relacionamos Jugadores con el juego "Luz roja, luz verde"
MATCH (p1:Jugador {id: 1}), (j1:Juego {nombre_del_juego: 'Luz roja, luz verde'})
WITH p1, j1
CREATE (p1)-[:PARTICIPA_EN]->(j1)

// Relacionamos Jugadores con el juego "Luz roja, luz verde"
MATCH (p2:Jugador {id: 2}), (j1:Juego {nombre_del_juego: 'Luz roja, luz verde'})
WITH p2, j1
CREATE (p2)-[:PARTICIPA_EN]->(j1)

// Relacionamos Jugadores con el juego "El juego de la cuerda"
MATCH (p3:Jugador {id: 3}), (j2:Juego {nombre_del_juego: 'El juego de la cuerda'})
WITH p3, j2
CREATE (p3)-[:PARTICIPA_EN]->(j2)

// Relacionamos Jugadores con el juego "El juego de la cuerda"
MATCH (p4:Jugador {id: 4}), (j2:Juego {nombre_del_juego: 'El juego de la cuerda'})
WITH p4, j2
CREATE (p4)-[:PARTICIPA_EN]->(j2)

// Relacionamos Jugador con el juego "La pelotita"
MATCH (p5:Jugador {id: 5}), (j3:Juego {nombre_del_juego: 'La pelotita'})
WITH p5, j3
CREATE (p5)-[:PARTICIPA_EN]->(j3)
```
