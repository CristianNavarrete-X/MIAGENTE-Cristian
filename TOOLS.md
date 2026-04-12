## get_weather
Servicio Meteorológico Externo.
- **Endpoint:** https://api.open-meteo.com/v1/forecast
- **Parámetros Requeridos:** latitude (float), longitude (float), current_weather (true).
- **Instrucción:** Cuando el usuario pregunte por el clima o necesite sugerencias basadas en el ambiente, realiza una petición GET a este endpoint.
- **Interpretación:** Extrae la clave 'temperature' y 'windspeed' del JSON devuelto para responder.
