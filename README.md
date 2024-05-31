El Código de la API Backend trabaja junto al FrontEnd: https://github.com/ClaudioCGG/ScreeenMatchFrasesFrontEnd

Tener en consideración que la BBDD apunta spring.datasource.url=jdbc:postgresql://${DB_HOST}/scm_frases

Se adjunta al proyecto le sumo una base de 30 peliculas para sumar a la base para insertar por medio de Query Tool PostgreSQL:

INSERT INTO frases (id, frase, pelicula, personaje, poster) VALUES
(1,'Voy a hacerle una oferta que no podrá rechazar.','El Padrino','Marlon Brando','https://m.media-amazon.com/images/M/MV5BM2MyNjYxNmUtYTAwNi00MTYxLWJmNWYtYzZlODY3ZTk3OTFlXkEyXkFqcGdeQXVyNzkwMjQ5NzM@._V1_SX300.jpg'),
(2,La vida es como una caja de bombones, nunca sabes lo que te va a tocar.','Forrest Gump','Tom Hanks','https://m.media-amazon.com/images/M/MV5BM2M1MmVhNDgtNmI0YS00ZDNmLTkyNjctNTJiYTQ2N2NmYzc2XkEyXkFqcGdeQXVyNzkwMjQ5NzM@._V1_SX300.jpg'),
(3,Yo soy tu padre.','El Imperio Contraataca','James Earl Jones (voz de Darth Vader)','https://m.media-amazon.com/images/M/MV5BYmU1NDRjNDgtMzhiMi00NjZmLTg5NGItZDNiZjU5NTU4OTE0XkEyXkFqcGdeQXVyNzkwMjQ5NzM@._V1_SX300.jpg'),
(4,Siempre nos quedará París.','Casablanca','Humphrey Bogart','https://m.media-amazon.com/images/M/MV5BY2IzZGY2YmEtYzljNS00NTM5LTgwMzUtMzM1NjQ4NGI0OTk0XkEyXkFqcGdeQXVyNDYyMDk5MTU@._V1_SX300.jpg'),
(5,Francamente, querida, me importa un bledo.','Lo que el viento se llevó','Clark Gable','https://m.media-amazon.com/images/M/MV5BY2IzZGY2YmEtYzljNS00NTM5LTgwMzUtMzM1NjQ4NGI0OTk0XkEyXkFqcGdeQXVyNDYyMDk5MTU@._V1_SX300.jpg'),
(6,No hay lugar como el hogar.','El Mago de Oz','Judy Garland','https://m.media-amazon.com/images/M/MV5BY2NjNDU1ZjctN2VhZi00Nzc5LTljNmItMTZiOTg1ODkwYjgwXkEyXkFqcGdeQXVyNTkxMzEwMzU@._V1_SX300.jpg'),
(7,¿Me estás hablando a mí?','Taxi Driver','Robert De Niro','https://m.media-amazon.com/images/M/MV5BM2M1MmVhNDgtNmI0YS00ZDNmLTkyNjctNTJiYTQ2N2NmYzc2XkEyXkFqcGdeQXVyNzkwMjQ5NzM@._V1_SX300.jpg'),
(8,¡Muéstrame el dinero!','Jerry Maguire','Cuba Gooding Jr.','https://m.media-amazon.com/images/M/MV5BYTM0ZWNmZTUtOTVkZS00MTZiLTg3M2QtZjA0Y2RmOWM1NWEyXkEyXkFqcGdeQXVyNjU0OTQ0OTY@._V1_SX300.jpg'),
(9,Soy el rey del mundo.','Titanic','Leonardo DiCaprio','https://m.media-amazon.com/images/M/MV5BMDdmZGU3NDQtY2E5My00ZTliLWIzOTUtMTY4ZGI1YjdiNjk3XkEyXkFqcGdeQXVyNTA4NzY1MzY@._V1_SX300.jpg'),
(10,Un Anillo para gobernarlos a todos.','El Señor de los Anillos: La Comunidad del Anillo','Cate Blanchett (voz en off)','https://m.media-amazon.com/images/M/MV5BZTQ4YTA1YmEtNWY1Yy00ODA2LWI2MGYtZGY2ZTgzYjEzMDZjXkEyXkFqcGdeQXVyNTE1MDE2MzY@._V1_SX300.jpg'),
(11,Hasta la vista, baby.','Terminator 2: El juicio final','Arnold Schwarzenegger','https://m.media-amazon.com/images/M/MV5BMjE2Mzg4MDY1M15BMl5BanBnXkFtZTcwNjE4NDMyMQ@@._V1_SX300.jpg'),
(12,Me encanta el olor a napalm por la mañana.','Apocalypse Now','Robert Duvall','https://m.media-amazon.com/images/M/MV5BYmQyNTA1ZGItNjZjMi00NzFlLWEzMWEtNWMwN2Q2MjJhYzEyXkEyXkFqcGdeQXVyMjUzOTY1NTc@._V1_SX300.jpg'),
(13,Ponte el conejito de vuelta en la caja.','Con Air','Nicolas Cage','https://m.media-amazon.com/images/M/MV5BMGZmNGIxMTYtMmVjMy00YzhkLWIyOTktNTExZGFiYjNiNzdlXkEyXkFqcGdeQXVyMTQxNzMzNDI@._V1_SX300.jpg'),
(14,Vamos, alégrame el día.','Dirty Harry','Clint Eastwood','https://m.media-amazon.com/images/M/MV5BMzdhMTM2YTItOWU2YS00MTM0LTgyNDYtMDM1OWM3NzkzNTM2XkEyXkFqcGdeQXVyNjc1NTYyMjg@._V1_SX300.jpg'),
(15,Veo gente muerta.','El Sexto Sentido','Haley Joel Osment','https://m.media-amazon.com/images/M/MV5BMWM4NTFhYjctNzUyNi00NGMwLTk3NTYtMDIyNTZmMzRlYmQyXkEyXkFqcGdeQXVyMTAwMzUyOTc@._V1_SX300.jpg'),
(16,¿No estáis entretenidos?','Gladiador','Russell Crowe','https://m.media-amazon.com/images/M/MV5BMDliMmNhNDEtODUyOS00MjNlLTgxODEtN2U3NzIxMGVkZTA1L2ltYWdlXkEyXkFqcGdeQXVyNjU0OTQ0OTY@._V1_SX300.jpg'),
(17,La primera regla del Club de la Lucha es: no hables del Club de la Lucha.','El Club de la Lucha','Brad Pitt','https://m.media-amazon.com/images/M/MV5BMmEzNTkxYjQtZTc0MC00YTVjLTg5ZTEtZWMwOWVlYzY0NWIwXkEyXkFqcGdeQXVyNzkwMjQ5NzM@._V1_SX300.jpg'),
(18,¿Qué miras, gallina?','Volver al Futuro','Michael J. Fox','https://m.media-amazon.com/images/M/MV5BZmU0M2Y1OGUtZjIxNi00ZjBkLTg1MjgtOWIyNThiZWIwYjRiXkEyXkFqcGdeQXVyMTQxNzMzNDI@._V1_SX300.jpg'),
(19,No hay cuchara.','Matrix','Keanu Reeves','https://m.media-amazon.com/images/M/MV5BYzUzOTA5ZTMtMTdlZS00MmQ5LWFmNjEtMjE5MTczN2RjNjE3XkEyXkFqcGdeQXVyNTc2ODIyMzY@._V1_SX300.jpg'),
(20,¡Aquí está Johnny!','El Resplandor','Jack Nicholson','https://m.media-amazon.com/images/M/MV5BZmU0M2Y1OGUtZjIxNi00ZjBkLTg1MjgtOWIyNThiZWIwYjRiXkEyXkFqcGdeQXVyMTQxNzMzNDI@._V1_SX300.jpg'),
(21,¡Pueden quitarnos la vida, pero jamás nos quitarán... la libertad!','Braveheart','Mel Gibson','https://m.media-amazon.com/images/M/MV5BMzkzMmU0YTYtOWM3My00YzBmLWI0YzctOGYyNTkwMWE5MTJkXkEyXkFqcGdeQXVyNzkwMjQ5NzM@._V1_SX300.jpg'),
(22,Hakuna Matata.','El Rey León','Nathan Lane y Ernie Sabella (Timon y Pumbaa)','https://m.media-amazon.com/images/M/MV5BYTYxNGMyZTYtMjE3MS00MzNjLWFjNmYtMDk3N2FmM2JiM2M1XkEyXkFqcGdeQXVyNjY5NDU4NzI@._V1_SX300.jpg'),
(23,Que la Fuerza te acompañe.','La Guerra de las Galaxias','Harrison Ford','https://m.media-amazon.com/images/M/MV5BOTA5NjhiOTAtZWM0ZC00MWNhLThiMzEtZDFkOTk2OTU1ZDJkXkEyXkFqcGdeQXVyMTA4NDI1NTQx._V1_SX300.jpg'),
(24,E.T. teléfono casa.','E.T. el extraterrestre','Pat Welsh (voz de E.T.)','https://m.media-amazon.com/images/M/MV5BMTQ2ODFlMDAtNzdhOC00ZDYzLWE3YTMtNDU4ZGFmZmJmYTczXkEyXkFqcGdeQXVyMTQxNzMzNDI@._V1_SX300.jpg'),
(25,Este significa algo. Esto es importante.','Encuentros Cercanos del Tercer Tipo','Richard Dreyfuss','https://m.media-amazon.com/images/M/MV5BMjM1NjE5NjQxN15BMl5BanBnXkFtZTgwMjYzMzQxMDE@._V1_SX300.jpg'),
(26,Si lo construyes, él vendrá.','Campo de Sueños','Kevin Costner','https://m.media-amazon.com/images/M/MV5BNzk5OWY0YjAtYWU3ZS00Y2Q4LWFlNjItMzgwMTQ2MjIyMDFmL2ltYWdlL2ltYWdlXkEyXkFqcGdeQXVyMTQxNzMzNDI@._V1_SX300.jpg'),
(27,La vida se abre camino.','Jurassic Park','Jeff Goldblum','https://m.media-amazon.com/images/M/MV5BMjM2MDgxMDg0Nl5BMl5BanBnXkFtZTgwNTM2OTM5NDE@._V1_SX300.jpg'),
(28,Clarice, ¿los corderos siguen gritando?','El silencio de los corderos','Anthony Hopkins','https://m.media-amazon.com/images/M/MV5BNjNhZTk0ZmEtNjJhMi00YzFlLWE1MmEtYzM1M2ZmMGMwMTU4XkEyXkFqcGdeQXVyNjU0OTQ0OTY@._V1_SX300.jpg'),
(29,Di hola a mi pequeño amigo.','Scarface','Al Pacino','https://m.media-amazon.com/images/M/MV5BNjdjNGQ4NDEtNTEwYS00MTgxLTliYzQtYzE2ZDRiZjFhZmNlXkEyXkFqcGdeQXVyNjU0OTQ0OTY@._V1_SX300.jpg'),
(30,Bienvenidos a la Roca.','La Roca','Sean Connery','https://m.media-amazon.com/images/M/MV5BZDJjOTE0N2EtMmRlZS00NzU0LWE0ZWQtM2Q3MWMxNjcwZjBhXkEyXkFqcGdeQXVyNDk3NzU2MTQ@._V1_SX300.jpg');
