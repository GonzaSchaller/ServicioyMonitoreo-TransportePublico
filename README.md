# Monitoreo-de-Estado-de-Servicios-de-Transporte-Publico-y-de-Establecimientos

Integrantes:
- Lucas Deferrari
- Gonzalo Schaller
- Agustin Neustadt
- Alessandro Caragiulo
- Juan Aguirre

Enunciado : https://docs.google.com/document/d/11rQXhiO0EiZEqh_RzlydB1GPJFIsSqRCcuQn3e2JdtE/edit

# Consideraciones
- Se utiliza una base de datos para persistir los datos (Postgress), se puede cambiar la bd en el archivo de persistance.xml
- También utilizamos DJango para probar funcionalidad en otro stack tecnológico -> Se encuentra en DDSPython
- Se utiliza un cliente liviano
- Se utiliza una API rest para obtener las provincias y municipios
- Se puede crear cuentas, la contraseña solo requiere una mayuscula (esto se puede cambiar agregando estrategias al validadorDeContraseñas)
- Está deployeado en Render pero puede probarse en local -> link: https://mobhub.onrender.com/
  
  Para entrar como administrador (cuenta con más funcionalidades)-> Usuario: admin Contraseña: Admin
  
  Para entrar como usuario común se puede crear una cuenta
- La primera vez tarda mucho en iniciar sesion si se entra desde Render (2 o 3 minutos), debido a que Render es un servicio gratuito


# Fotos de algunas de las funcionalidades:
![image](https://github.com/GonzaSchaller/Monitoreo-de-Estado-de-Servicios-de-Transporte-P-blico-y-de-Establecimientos/assets/102746916/c023eb1a-c04d-42b0-8a7c-715df2033ca2)
![image](https://github.com/GonzaSchaller/Monitoreo-de-Estado-de-Servicios-de-Transporte-P-blico-y-de-Establecimientos/assets/102746916/b6bd34ee-9a0f-47e7-8a33-f0957aebd270)
![image](https://github.com/GonzaSchaller/Monitoreo-de-Estado-de-Servicios-de-Transporte-P-blico-y-de-Establecimientos/assets/102746916/f9809b19-6115-4f92-a860-26786ca195f7)
![image](https://github.com/GonzaSchaller/Monitoreo-de-Estado-de-Servicios-de-Transporte-P-blico-y-de-Establecimientos/assets/102746916/6186d2f9-0908-4c0a-96b7-824c9a867607)
![image](https://github.com/GonzaSchaller/Monitoreo-de-Estado-de-Servicios-de-Transporte-P-blico-y-de-Establecimientos/assets/102746916/82e9029e-dfea-4e93-ac5a-c3a7faf19baa)
![image](https://github.com/GonzaSchaller/Monitoreo-de-Estado-de-Servicios-de-Transporte-P-blico-y-de-Establecimientos/assets/102746916/da8ebe2f-c65f-4c5d-989f-a737ca9a575f)






