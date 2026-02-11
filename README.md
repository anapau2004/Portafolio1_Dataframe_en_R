# Portafolio1_Dataframe_en_R
Portafolio 1: Dataframe en R
# Nombre: Ana Paula Echeverria Arellano
# Materia: Ciencias omicas Metabolomica
# Grupo 1 o 2: 1
# Número de tarea: Portafolio 1

# 1. Creación de los vectores
Pelicula <- c("Anora", "The Brutalist", "Flow", "Emilia Pérez", 
              "Wicked", "Dune: Part Two", "I’m Still Here")

Premios_Oscar_2025 <- c("Mejor Película, Mejor Director, Mejor Actriz, Mejor Guion Original, Mejor Montaje",
                        "Mejor Actor, Mejor Fotografía, Mejor Banda Sonora",
                        "Mejor Película de Animación",
                        "Mejor Actriz de Reparto, Mejor Canción Original",
                        "Mejor Diseño de Vestuario, Diseño de Producción",
                        "Mejor Sonido, Mejores Efectos Visuales",
                        "Mejor Película Internacional")

Mes_de_estreno <- c("Enero", "Diciembre", "Diciembre", "Mayo", 
                    "Noviembre", "Marzo", "Febrero")

Recaudacion_mundial_estimada <- c(41000000, 41400000, 728000000, 714000000, 
                                  20000000, 29900000, 30000000)

# 2. Creación del Dataframe
tabla_peliculas <- data.frame(
  Película = Pelicula,
  `Premios Oscar 2025` = Premios_Oscar_2025,
  `Mes de estreno` = Mes_de_estreno,
  `Recaudación mundial (estimada)` = Recaudacion_mundial_estimada
)

# 3. Visualización de la tabla
View(tabla_peliculas)
