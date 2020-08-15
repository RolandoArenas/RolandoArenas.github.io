¿Qué es un control de versiones?
    Un sistema de control de versiones (VCS por sus siglas en inglés) es un software que permite registrar los cambios realizados a un proyecto - compuesto de uno o varios archivos - en el momento que su(s) desarrollador(es) lo deseen de manera a poder regresar a uno de esos puntos de registro (commits) de ser necesario. Esto no solamente permite revisar versiones anteriores del proyecto para solucionar errores y/o modificarlo rápidamente, sino también nos crea un historial del mismo, donde encontramos quien o quienes intervinieron en él y que es lo que hicieron para bien... o para mal!

¿Cuáles son los problemas al no usar un control de versiones?
    Sin un VCS sería muy complicado manejar un proyecto, sobre todo si implica un desarrollo de mediana o gran envergadura. Tendríamos que compartir el proyecto reiteradas veces, crear multiples versiones con distintos nombres, y - afin de reducir el riesgo de errores - esperar a que cada uno de los miembros del equipo resuelva su parte antes de iniciar la siguiente.
    Además, si por A o B nos encontramos con un error indetectado "en su debido momento" (es decir, poco tiempo después de haberlo cometido), habrían fuertes probabilidades de que tengamos que retomar el proyecto desde muy atrás, perdiendo (mucho) tiempo... y (mucho) dinero!
    Si de por sí, la gestión de cambios y errores ya es complicada cuando se trata de un solo desarrollador en un proyecto mediano o grande, en el caso de un equipo compuesto por varios desarrolladores se torna inmanejable sin el uso de un VCS.

¿Cuáles son los beneficios?
    Los beneficios del uso de un VCS son varios:
        - Permite desarrollar varias versiones de un mismo proyecto, lo que a su vez permite corregirlo, modificarlo y/o adaptarlo, cuando así se lo requiera (para su uso en el mismo proyecto... o en otro)
        - Crea un historial del desarrollo del proyecto, brindando información de su(s) autor(es), de los cambios realizados por cada uno de ellos a lo largo del tiempo, y de sus aciertos y/o errores. También genera estadísticas.
        - Facilita el trabajo en equipo, brindando la posibilidad del desarrollo en simultáneo.

¿Qué tipos de control de versiones existen?
    Hay 3 tipos de VCS:
        - VCS locales: Las versiones se almacenan en una base de datos local (es decir en el computador de cada desarrolador), sin posibilidad de ser compartido entre varios desarrolladores.
        - VCS centralizados: Las versiones se almacenan en un servidor, pero no permiten que dos o más usuarios trabajen en el mismo archivo en simultáneo.
        - VCS distribuídos: Da a cada desarrollador de un proyecto una copia del mismo para que lo trabaje de forma local y solamente lo cargue en el servidor cuando lo considere necesario. Al mismo tiempo, hay un repositorio para cada desarrollador en el servidor, permitiendo a los administradores del proyecto decidir sobre su integración en la versión final.   
    
