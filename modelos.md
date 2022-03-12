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
            "birth_date":"",  # asignar
            
            "email":"correo externo del usuario gmail, hotmail",
            
            "email_empresarial":"gonzalo@virtuallawyer.com",
           
            "ciudad":"Santiago", # asignar
            "region":"",
            "RUN":" nro de identificacion",

            "universidad":" datos academicos",
            "anho de titulacion":"",
            "especialidades":["derecho civil", "derecho penal"],
            "titulos":["licenciatura cone especi" ],
            "telefono":"",

            "calificacion":"1-5  estrellas con promedio " ,
            "calificadores" :["usuario 1", "usuario2"],

            "Image_profile"
        },

    "lawyer_data":{
        "carnet":"17816384",
        "image_carnet":"https://micarnet.com/micarnet.jpeg",
        "matricula":"",
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

type_user : { "lawyer", "customer","admin"}

```

- Formulario de registro para el abogado
- Formulario de registro para el cliente

- Actualizacion de datos para usuario
- Actualizacion de datos para abogado

- Perfil del usuario (como mostrar la informacion al cliente)
- login



### Parametros de registro (Abogado)


Que el abogado se registre 
y el administrador puede aprobar o rechazar

- Foto del titulo y post titulos y especializaciones
- Foto carnet de identidad ambos lados
- Revision de antecedentes ?


### Parametros de registro (Cliente)
El cliente se registra por un formulario
- Activacion de cuenta obligatoria  con verificacion del correo


### 
- Solicitar medio de pago
mas la tarjeta de debito o credito 
( investigar ) ( externo )   ??????????????? 
(como pedidos ya ) (pasarela de pago) 

datos de la tarjeta de debito
mercado pago
paypal 
pasarela y forma de pago
https://www.mercadopago.cl/developers/es/guides/online-payments/checkout-api/testing
https://www.khipu.com/api/


## Módulo de correos corporativos
(como se va gestionar los correos corporativos )
preguntas acerca de los correos
1. ¿Comó gestionar los correos corporativos?
2. ¿Existe la posibilidad de migrar correos?
3. ¿Otorgamos nosotros el buzon de correo?
4. ¿Como lo pagamos?  ???  

server fisico host web 
instalar un programa server de correos,





### Módulo de publicación de los servicios profesionales

Los abogados tendran un perfil para responder a los trabajos que realizan, el perfil mostrara areas de especialidad de trabajo

Navegacion del cliente en la busqueda de resolver un servicio será
```
-> servicios por region
    ->  Areas de servicio 
        ->  Vista de todos los abogados 
            -> contactar al abogado
```

campo de texto de busqueda

filtro -> region, area de servicio
divorcio - > lista abogados que se especializan en esos temas,  -> servicios relacionados con la busqueda -> lista de abogados


chat > whatsapp 
        - tienes chat
        desventaja
        - no controlas la informacion


o por formulario genérico

categorizar servicios[]
servicios empresariales
servicios interempresas
servicios para personas
servicios especializados




## Módulo de pagos
pasarela de pagos > mercadolibre, tarjeta de debito

Si el cliente paga a un abogado , el pago lo retenemos hasta que el abogado concluya con su trabajo, el pago lo libera el cliente.

Arbitraje, 
que el abogado no a cumplido, y solicita el pago.

Pasarela de pagos paga al abogado.


## Módulo de rating
Calificacion al abogado
cuando califica un cliente,  despues de recibir un servicio,
el cliente puede comentar acerca del abogado


### gestion de documentos ?
¿ Como el cliente recibe documentos ?  en funcion a los servicios del abogado
envio de documentos por correo al abogado mediante formulario
envio de documentos directamente por correo
chat interno?  firebase, websockets 




### que es lo que no se va a desarrollar
sistema de monitoreo o metricas (clicks de los usuarios)
sistema de monitoreo de arquitectura  ( cpu, ram , rom)
formularios dinamicos por cada tipo de servicio
sistema de formulario
