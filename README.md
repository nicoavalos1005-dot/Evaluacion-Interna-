# Evaluacion-Interna-
El obejtivo de este programa es crear una solucion eficaz para el monitoreo del precio de skins de counterstrike 2, el programa va a cumplir o seguir los siguientes requisitos:

-Usuario y contraseña, pregunta de autoidentificacion(todo se guarda en sql), se revisara si el usuario ya a usado antes el programa para evadir el proceso de inicio

-link de webhook de su servidor de discord 

-Arma a seguir el precio y valor a conseguir, el valor a conseguir se evaluara con el precio dado por el api para no seguir precios imposibles

-La decoracion de los mensajes van a poder ser personalizables, siguiendo el tutorial colocado en el mismo programa

-Se revisara constantemente la coneccion a internet mediante la confirmacion de un mensaje mandado a discord el cual devuelve el codigo 204 si el mensaje llego y si no significa que no hay internet, esta opcion se podra desabilitar ya que puede ser molestoso las notificaciones constantes

-Aunque el bot no consiga el precio deseado exactamente mandara mensajes cada 15 minutos reportando el precio acutal, ademas si se encuentra un precio similar pero no el exacto se le avisara al usuario

-Se apagaran las notificaciones de cada 15 minutos durante la noche, las demas no de 10h00pm hasta 6h00am

-Despues de 3 dias de uso se reportara en un exel mandado al discord  en un grafico los precios que hubieron en el dia

(se intentara conseguir una rasperry para poder ejecutar el programa 24/7)
