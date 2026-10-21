---
contenuDynamique: true
---

# Coartada de Pedro

> Pedro declara: "Estuve en el Mercado Central de 16:30 a 18:00 comprando atún".
>
> El crimen fue a las 17:00. Comprueba si su coartada se sostiene.
>
> 1. [Comenzar las llamadas](Menú)

## Menú
Elige a quién quieres llamar:

1. [Llamar al pescadero](pescadero)
2. [Llamar a la frutera](frutera)
3. [Llamar al guardia de seguridad del mercado](guardia_mercado)
4. [Llamar al barrendero de la puerta @pista_cementerio=true](barrendero)

if @pista_cementerio == true
5. [Llamar al guardia del cementerio](cementerio)
endif

## pescadero
"¿Pedro? Sí, vino sobre las 16:35. Dos lomos de atún y se fue corriendo a las 16:40. Me dijo que tenía prisa. No lo volví a ver."

1. [Colgar y volver a marcar](Menú)

## frutera
"Pedro no compra fruta aquí. Hoy no lo he visto. Ni hoy ni ayer."

1. [Colgar y volver a marcar](Menú)

## guardia_mercado
"Estoy mirando las cámaras del parking. Pedro entró a las 16:30 y salió a las 16:42. No volvió. ¿Eso es importante?"

1. [Colgar y volver a marcar](Menú)

## barrendero
"Lo vi salir del mercado a las 16:42 y coger el autobús 12. Ese va al cementerio. Me extrañó, porque iba con prisa y sin bolsas."

1. [Colgar y volver a marcar](Menú)

## cementerio
"¿Pedro? Sí, estuvo aquí de 16:50 a 18:10. En la tumba de su mujer. Hablé con él un momento, me dijo que venía a rezar. No se movió de allí en todo el rato."

1. [Anotar en la libreta](acta)

## acta
📋 ACTA 4-B — COARTADA FALSA, PERO INOCENTE

Pedro mintió: no estuvo en el mercado de 16:30 a 18:00. Salió a las 16:42 y se fue al cementerio.

Pero el guardia del cementerio lo sitúa allí de 16:50 a 18:10. A las 17:00 estaba a 20 minutos del restaurante, con testigo.

Pedro no mató a la víctima. Miente para ocultar que su mujer está muerta y que sigue cobrando la herencia.

Ahora falta el móvil: revisa la prueba de la fotografía en el pasillo.
