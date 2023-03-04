# Screened Host 
## Funcionamiento
El Screened host es un firewall tipo hardware que se usa para proteger nuestra red.
Este consta con dos tarjetas de red una conectada a la red interna y otra a la red externa.

El tráfico que viene desde una red pasa por el Screened host antes de pasar por la otra tarjeta.

Si los paquetes cumplen las reglas los deja pasar, y si no lo hacen los filtra.

## Estructura 
- **El firewall:** Elemento principal del Screened Host. Es el encargado de proteger la red interna.
- **El Bastión:** Servidor de seguridad situado en una zona entre la red externa y red interna (zona DMZ). Actúa como “puerta de entrada” y garantiza que la red interna esté segura. 
- **El Switch:** Necesario para conectar el firewall y el bastión con otros dispositivos de las redes interna y externa.

| Ventajas | Desventajas |
| -------- | ----------- |
| Proporciona más seguridad que usar un simplemente usar un router |Puede ser vulnerable a ataques DoS |
| Permite controlar el acceso a la red interna |Si un atacante logra controlar cualquier dispositivo que compone el Screened host, puede tener acceso a toda la red protegida |
| Se pueden personalizar ciertas reglas | Si el firewall falla, toda la red protegida puede quedar expuesta a posibles amenazas |






