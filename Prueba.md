PID de los laterales.
KP:
Si pasa cualquiera de estas cosas:
El servo se mueve MUY lento → Kp muy baja
El servo vibra o tiembla cerca del equilibrio → Kp muy alta
El servo se pasa de largo y vuelve → Kp muy alta
📌 Cómo ajustar
Aumentá de a poco:
Si va lento → subí Kp: 25, 30, 40, 50…
Si tiembla → bajá Kp: 15, 10, 8…
Meta:
Que el servo se mueva rápido pero sin temblar.

KI:
Si el servo tarda en lograr equilibrio, subí Ki:
0.3
0.4
0.5
✔ Si tiembla → bajá Ki
Ki demasiado alto genera “onda senoidal” alrededor del punto.

Kd:
Si el servo se mueve muy brusco → subí Kd:
3.0
4.0
5.0
Si el servo responde lento → bajá Kd:
1.0

Configuracion recomendada para el pid de la base:
Kp: 28.0 Ki: 0,35 Kd: 3,5.

PID superior:

0.5

0.0
