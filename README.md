# partidos-zampedri-uc

Este dataset en formato CSV contiene información de los 192 partidos jugados por Fernando Zampedri con la camiseta del Club Deportivo Universidad Cátólica de Chile hasta el 19 de Octubre de 2024, día en el cual alcanzó el récord de máximo goleador histórico del club con 119 anotaciones.

Cada fila del archivo CSV corresponde a la información de un partido.

Las columnas para cada fila son:

* cum_n_games: cantidad acumulada de partidos (o número de partido) ordenados cronológicamente
* season: temporada
* competition: torneo o competencia
* round: ronda o etapa del torneo
* date: fecha del partido
* team: equipo (siempre es Univ Católica)
* venue: localía (Home: Local / Away: Visita)
* opponent: rival
* result: resultado (W: ganado / D: empate / L: perdido)
* goals: cantidad de goles de F. Zampedri en ese partido
* cum_goals: cantidad de goles acumulados por F. Zampedri al terminar ese partido
* minutes_playerd: minutos jugados por F. Zampedri en ese partido


Los datos fueron scrapeados desde [FBref]() y [Transfermarkt]()
