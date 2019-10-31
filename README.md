# Curso de Desarrollo de Apps Móviles - Activate

## Del nacimiento del teléfono móvil a las apps

### 1. Generaciones de la telefonía móvil

- **0G**: desde finales del siglo XIX.
    - Telefonía basada en radio.
    - Establecimientos específicos, navegación marítima, militares, coches, etc.
- **1G**: finales de los años 80.
    - Telefonía analógica.
    - Destinada a empresas.
    - Motorola desarrolla el primer dispositivo.
    - Aparece la itinerancia de datos.
- **2G**: años 90.
    - Telefonía digital basada en conmutación de circuitos.
    - Canal de comunicación extremo a extremo.
    - Se utiliza GSM.
        - Itinerancia internacional.
        - SMS para mensajes de texto cortos.
        - MMS para mensajes multimedia.
- **3G**: principios de los años 2000.
    - Comunitación basada en paquetes para transmitir datos.
    - Estándar UMTS: 384 kbps - 2Mbps.
- **4G**: finales de los años 2000 y 2010.
    - Solo utiliza conmutación de paquetes.
    - Desaparece la conmutación de circuitos para voz.
    - Mayor tasa de tranmisión.
    - Protocolos: WiMAX, LTE, LTEA.
- **5G**: estimada para comienzos del 2020. En desarrollo actualmente.
    - Mayores tasas de transferencia de datos: 10Mbits/segundo.
    - Soporta a un mayor número de conexiones simultáneas: 10000 usuarios.
    - Soporte a un mayor número de dispositivos registrados simultáneamente: 100000 dispositivos.
    - Eficiencia en el uso del espectro.
    - Escalabilidad.

### 2. La evolución de los smartphones

- Un dispositivo móvil es:
    - Recurso computacional.
    - Fácilmente transportable.
    - Tamaño reducido.
    - Interactivo.
    - Capacidad de comunicación.
    - Integra múltiples sensores y actuadores.
    - Caracteríticas variables entre dispositivos.
    - Tienen su propio SO.
        - Pueden ejecutar apps.

- Funcionalidad / capas
    - Terminal: implementada en el HW por el fabricante.
        - Ej. captar la señal de las antenas.
    - Sistema operativo: servicio básico
        - Convierte la señal en datos numéricos.
    - Aplicaciones: proporiona funcionalidad adicional sobre el SO.
        - Visualización de datos en un diagrama de barras.
    - Cada capa construye sobre los servicios de las anteriores.
        - Proporiona una visión uniforme.
    - La funcionalidad básica es limitada.
        - Terminal + sistema operativo.
    - Casi todos los usuarios la extienden con aplicaciones.

- Apps nativas vs multiplataformas
    - Nativas
        - Desventajas
            - Solo en un sistema operativo
        - Ventajas
            - Servicios avanzados como localización, acelerómetro, notificaciones, etc.
            - Velocidad de respuesta.
            - Sin límite de almacenamiento.
            - Dependencia reducida de la conectividad.
    - Multiplataformas
        - Desvenetajas
            - Peor experiencia de usaurio.
            - Requiere conectividad.
        - Ventajas
            - Más barato.
            - Múltiples sistemas operativos.
            - Basado frecuentemente en tecnologías webs.
            - Independiente de stores.
            - Sin instalación ni mantenimiento en el cliente.

    - Conclusiones
        - Los móviles y sus apps ya están presentes en todo el mundo.
        - El panorama no deja de evolucionar.
        - Gran fragmentación
            - Heterogeneidad de dispositivos.
            - Diferentes sistemas operativos.
            - Múltiples posibilidades de desarrollo.

![Plataformas de desarrollo](./images/t1_u2_01.png "Plataformas de desarrollo")

### 3. El mercado de las apps

- Momentos de uso  
    - Estamos dispuestos a esperar solo en situaciones donde sabemos que los retrasos son comunes.
        - Ej: navegadores solicitando una página web.
        - Siempre que haya información de progreso.
- Tiempos de uso
    - El usuario suele tener poco tiempo para usar la aplicación.
    - Existe incertidumbe sobre la interacción.
    - Requerimos reacción inmediata.
- ¿Qué buscamos?
    - Usar una app supone dedicarle parte de nuestro valioso y escaso tiempo.
    - Exigentes con lo que nos ofrecen.
- Las apps deben ser:
    - Útiles.
    - Intuitivas.
    - Divertidas.
    - De uso frecuente.
- Monetización de las apps
    - La elección del modelo de monetización y de la plataforma es importante.
    - Depende del público objetivo y de la app.
    - El usuario de iOS gasta en apps 4 veces más que el de Android.
    - Buen análisis previo.
    - Causar muy buena impresión.

## Diseño y creación de apps