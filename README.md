# Actores

## Jugador:

Descripcion:Usuario con permisos de usar la aplicacion

## Jugador2:

Descripcion:Usuario secundario de la aplicacion

## Sistema:

Descripcion:Sistema programado para sustentar al bot y al jugador

# Operaciones por Actor

## Jugador

i.Iniciar sesion

ii.Mejorar su personaje

iii.Movilidad de su personaje durante la partida

iv.Editar su personaje

v.Jugar contra bot o otros jugadores

## Jugador 2

i.Iniciar sesion

ii.Mejorar su personaje

iii.Movilidad de su personaje durante la partida

iv.Editar su personaje

v.Jugar contra bot o otros jugadores


## Sistema

i.Evita que el nivel del bot supere al del jugador

ii.Crear mapas con obstaculos al azar

iii.Sumar velocidad cuando el jugador suba de nivel

iv.Recuperar al jugador a la ultima posicion antes de morir

v.Posibilidad de crear diversos pisos igual a la cantidad de jugadores

vi.Controlar al bot
### Actores
#### Jugador
|  Actor |  Jugador |
|---|---|
| Descripción  | _Usuario normal de la aplicación_  |
| Características  |_Usa la aplicación de forma gratuita_ |
| Relaciones | __  |
| Referencias | _Iniciar sesion,Mejorar su personaje,Movilidad de su personaje durante la partida,Editar su personaje,Jugar contra bot o otros jugadores_ |   
|  Notas |  __ |
| Autor  | _Emanuel santamaria_ |
|Fecha | _12/11/2024_ |

|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |
#### Jugador2
|  Actor | Jugador2 |
|---|---|
| Descripción  | _Usuario que depende del jugador_  |
| Características  |_Usa la aplicacion junto con el jugador_ |
| Relaciones | __  |
| Referencias | _Iniciar sesion,Mejorar su personaje,Movilidad de su personaje durante la partida,Editar su personaje,Jugar contra bot o otros jugadores_ |   
|  Notas |  __ |
| Autor  | _Emanuel Santamaria_ |
|Fecha | _12/11/2024_ |

|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |

#### Sistema
|  Actor | Sistema |
|---|---|
| Descripción  | _Sistema que rige la aplicacion_  |
| Características  |_Crea obstaculos en el mapa, al igual de crear el mapa_ |
| Relaciones | __  |
| Referencias | _Evita que el nivel del bot supere al del jugador,Crear mapas con obstaculos al azar,Sumar velocidad cuando el jugador suba de nivel,Recuperar al jugador a la ultima posicion antes de morir,Posibilidad de crear diversos pisos igual a la cantidad de jugadores, Controlar al bot_ |   
|  Notas |  __ |
| Autor  | _Emanuel Santamaria_ |
|Fecha | _12/11/2024_ |

|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |
### Casos de uso
#### Iniciar sesion
|  Caso de Uso	CU |Iniciar sesion  |
  |---|---|
  | Fuentes  | _[Documento]()_  |
  | Actor  |  _Jugador,Jugador2_ |
  | Descripción | _Permite iniciar sesion en la aplicacion_  |
  | Flujo básico | __ |
  | Pre-condiciones | _Estar dentro de la aplicación_  |  
  | Post-condiciones  | _El usuario debe jugar_  |  
  |  Requerimientos | _El usuario debe de tener una cuenta_  |
  |  Notas |  __ |
  | Autor  | _Emanuel Santamaria_ |
  |Fecha | _12/11/2024_ |

|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |
  
#### Mejorar a su personaje
|  Caso de Uso	CU | Mejorar a su personaje  |
  |---|---|
  | Fuentes  | _[Documento]()_  |
  | Actor  |  _Jugador,Jugador2_ |
  | Descripción | _Tienen posibilidad de mejorar a su personaje a cambio de experiencia_  |
  | Flujo básico | __ |
  | Pre-condiciones | _Estar dentro de la aplicación, tener experiencia_  |  
  | Post-condiciones  | __  |  
  |  Requerimientos | _El usuario debe de tener una cuenta_  |
  |  Notas |  __ |
  | Autor  | _Emanuel Santamaria_ |
  |Fecha | _12/11/2024_ |

|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |
  
#### Movilidad de su personaje durante la partida
|  Caso de Uso	CU | Movilidad  |
  |---|---|
  | Fuentes  | _[Documento]()_  |
  | Actor  |  _Jugador,Jugador2_ |
  | Descripción | _El jugador puede moverse durante la partida, izquierda, derecha, saltar y agacharse_  |
  | Flujo básico | _Entra a la aplicion, inicia una partida _ |
  | Pre-condiciones | _Estar dentro de la aplicación, estar en una partida_  |  
  | Post-condiciones  | __  |  
  |  Requerimientos | _El usuario debe de tener una cuenta_  |
  |  Notas |  __ |
  | Autor  | Emanuel Santamaria_ |
  |Fecha | _15/11/2024_ |

|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |
  
#### Editar a su personaje
|  Caso de Uso	CU | Editar personaje  |
  |---|---|
  | Fuentes  | _[Documento]()_  |
  | Actor  |  _Jugador, Jugador2_ |
  | Descripción | _Puede costumizar a su personaje mediante intercambio de experiencia_  |
  | Flujo básico | _Entra aplicacion, Elige que quiere modificar, Lo cambia por experiencia_ |
  | Pre-condiciones | _Estar dentro de la aplicación, tener experiencia_  |  
  | Post-condiciones  | __  |  
  |  Requerimientos | _El usuario debe de tener una cuenta_  |
  |  Notas |  __ |
  | Autor  | _Emanuel Santamaria_ |
  |Fecha | _15/11/2024_ |

|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |
  
#### Jugar contra bot u otro jugador
| Caso de Uso CU | Jugar  |
  |---|---|
  | Fuentes | _[Documento]()_|
  | Actor | _Jugador,Jugador2_|
  | Descripcion | _Tiene la opcion de jugar una partida contra un bot o contra otro jugador_ |
  | Flujo Basico | _Entrar en la aplicacion, Iniciar partida_ |
  | Pre-condiciones | _Estar dentro de la aplicacion_ |
  | Post Condiciones | __ |
  | Requerimientos | _El usuario debe tener una cuenta_ |
  | Notas | __ |
  | Autor | _Emanuel Santamaria_ |
  | Fecha | _15/11/2024_ |

|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |
  
#### Evitar que el nivel del bot supere al del jugador
| Caso de Uso CU | Controlar el nivel del bot  |
  |---|---|
  | Fuentes | _[Documento]()_|
  | Actor | _Sistema_|
  | Descripcion | _Controla el nivel del bot de manera tal que nunca sobrepase el nivel del jugador_ |
  | Flujo Basico | _Entrar en la aplicacion |
  | Pre-condiciones | _Estar dentro de la aplicacion_ |
  | Post Condiciones | __ |
  | Requerimientos | __ |
  | Notas | __ |
  | Autor | _Emanuel Santamaria_ |
  | Fecha | _15/11/2024_ |

|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |
  
#### Crear mapas con obstaculos al azar
| Caso de Uso CU | Crear mapas  |
  |---|---|
  | Fuentes | _[Documento]()_|
  | Actor | _Sistema_|
  | Descripcion | _El sistema crea mapas diversos con obstaculos los cuales el jugador debera evadir_ |
  | Flujo Basico | _Entrar en la aplicacion, Iniciar partida_ |
  | Pre-condiciones | _Estar dentro de la aplicacion_ |
  | Post Condiciones | __ |
  | Requerimientos | __ |
  | Notas | __ |
  | Autor | _Emanuel Santamaria_ |
  | Fecha | _15/11/2024_ |

  |  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |

#### Sumar velocidad cuando el jugador suba de nivel
| Caso de Uso CU | Sumar velocidad  |
  |---|---|
  | Fuentes | _[Documento]()_|
  | Actor | _Sistema_ |
  | Descripcion | _Al el jugador subir de nivel el sistema suma velocidad al jugador_ |
  | Flujo Basico | _Entrar en la aplicacion, Iniciar partida_ |
  | Pre-condiciones | _Estar dentro de la aplicacion_ |
  | Post Condiciones | __ |
  | Requerimientos | __ |
  | Notas | __ |
  | Autor | _Emanuel Santamaria_ |
  | Fecha | _15/11/2024_ |

|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |
  
  #### Recuperar al jugador a la ultima posicion antes de morir
| Caso de Uso CU | Recuperar al jugador  |
  |---|---|
  | Fuentes | _[Documento]()_|
  | Actor | _Sistema_|
  | Descripcion | _Cuando el jugador es destruido por un obstculo al pasdo un segundo el sistema recupera al jugador a unos instantes antes de morir_ |
  | Flujo Basico | _Entrar en la aplicacion, Iniciar partida_ |
  | Pre-condiciones | _Estar dentro de la aplicacion_ |
  | Post Condiciones | __ |
  | Requerimientos | __ |
  | Notas | __ |
  | Autor | _Emanuel Santamaria_ |
  | Fecha | _15/11/2024_ |

|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |
  
  #### Posibilidad de crear diversos pisos igual a la cantidad de jugadores
| Caso de Uso CU | Crear pisos  |
  |---|---|
  | Fuentes | _[Documento]()_|
  | Actor | _Sistema_|
  | Descripcion | _Crea pisos diferentes con obstaculos diferentes igual a la cantidad de jugadores(minimo2 jugador/jugador2 o jugador/bot, maximo 3 jugador/jugador2/bot)_ |
  | Flujo Basico | _Entrar en la aplicacion, Iniciar partida_ |
  | Pre-condiciones | _Estar dentro de la aplicacion_ |
  | Post Condiciones | __ |
  | Requerimientos | _El usuario debe tener una cuenta_ |
  | Notas | __ |
  | Autor | _Emanuel Santamaria_ |
  | Fecha | _15/11/2024_ |

  |  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |

 #### Controlar al bot
| Caso de Uso CU | Controlar al bot  |
  |---|---|
  | Fuentes | _[Documento]()_|
  | Actor | _Sistema_|
  | Descripcion | _Crontola al bot durante la partida, pareciendo un jugador mas_ |
  | Flujo Basico | _Entrar en la aplicacion, Iniciar partida_ |
  | Pre-condiciones | _Estar dentro de la aplicacion_ |
  | Post Condiciones | __ |
  | Requerimientos | _El usuario debe tener una cuenta_ |
  | Notas | __ |
  | Autor | _Emanuel Santamaria_ |
  | Fecha | _15/11/2024_ |
