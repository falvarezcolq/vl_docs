# VirtualLawyer v 0.1 (Borrador)

## Brainstorm

```
contenido de reglas, 
comportamiento,
normas,
Estandares minimos de calificacion
quejas hacia los abogados
mas adelante
formatos tipo para biblioteca  para disponibilidad de los abogados

```


## Módulo de usuarios
los modelos se refieren a una abstraccion de la informacion de los objetos representados en el sistemas



### Modelo
```json
{
    "users" :
        {
            "name":"",
            "last_name":"",
            "birth_date":"",
            "email":"correo externo del usuario gmail, hotmail",
            "email_empresarial":"gonzalo@virtuallawyer.com",
            "ubicacion":" privado",
            "ciudad":"Santiago",
            "region":"",
            "RUT":" nro de identificacion",

            "universidad":" datos academicos",
            "anho de titulacion":"",
            "especialidades":["derecho civil", "derecho penal"],
            "titulos":["licenciatura cone especi" ],
            "telefono":"",

            "calificacion":"1-5  estrellas con promedio " ,
            "calificadores" :["usuario 1", "usuario2"],
        },

    "lawyer_data":{
        "carnet":"17816384",
        "image_carnet":"https://micarnet.com/micarnet.jpeg"
        "profesional_titles":[
            {
                "name":"Licenciatura en Derecho",
                "year":"2010",
                "institution":"Universidad Catolica de Chile"
            },
            {
                "name":"Maestria en Derecho Penal",
                "year":"2015",
                "institution":"Universidad de Valparaiso",
            },
        ],
    }
}

type_user : { "abogado", "cliente"}

```

### Parametros de registro (Abogado)

El abogado es registrado por el administrador

- Foto del titulo y post titulos y especializaciones
- Foto carnet de identidad ambos lados




### Parametros de registro (Cliente)
El cliente se registra por un formulario
- Activacion de cuenta obligatoria
- Solicitar medio de pago
mas la tarjeta de debito o credito 
( investigar ) ( externo 



## Módulo de correos corporativos
(como se va gestionar los correos corporativos )
preguntas acerca de los correos
1. ¿Comó gestionar los correos corporativos?
2. ¿Existe la posibilidad de migrar correos?
3. ¿Otorgamos nosotros el buzon de correo?
4. ¿Como lo pagamos?




### Módulo de publicación de los servicios profesionales

Los abogados tendran un perfil para responder a los trabajos que realizan, el perfil mostrara areas de especialidad de trabajo

Navegacion del cliente en la busqueda de resolver un servicio será
```
-> servicios por region
    ->  Areas de servicio 
        ->  Vista de todos los abogados 
            -> contactar al abogado
```

chat interno?

o por formulario?


Módulo de pagos
Módulo de rating
