# MapsApp
No usar directamente en AngularCLI (a menos que estén creadas las variables de entorno), ya que las variables de entorno se crean basados en el .env

## Pasos:
1. Ir a https://www.mapbox.com/ para crear una cuenta y conseguir la key. (Se necesita tarjeta como metdo de pago)
*OPCIONAL:* Si no cuenta con tarjeta de credito, este generador de numeros puede ayudar en dicho proceso https://herramientas-online.com/generador-tarjeta-credito-cvv.php
2. Clonar el .env.template y renombrarlo a .env
3. Llenar las variables de entorno acorde
4. Crear Angular Envs (opcional)
```
npm run envs
```

4. Para development ejecutar:
```
npm run start
```

5. Para producción ejecutar:
```
npm run build
```
