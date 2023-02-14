<p align="center">
  <img src="./GVIDI_Trans.png" alt="Logo" width=100  height=100>
  <p align="center">
     <code>GVIDI</code> is a system to improve the safety of groups of hikers based on real-time monitoring and dataset generation..
    <br>
  </p>
</p>



## Description
GVIDI is a novel system for monitoring real-time group activities in natural environments and generating datasets for forensic analysis. GVIDI software and data can be used by researchers to study how environmental conditions, events, and decisions influence on the safety of expedition groups. 


## Components 📋
 - Arduino microcontroller with gyroscopes, accelerometers and Bluetooth connectivity.
 - Mobile app, developed for Android.
 - Cloud store.
 
## Prerequisites 
- GCC 12.2
- Docker 20.10.14
- Docker-compose 2.14.0
- Unity 2021 LTS
- Mapbox SDK v10
- Firebase 31.1.1
- I2C Device Library (i2cdevlib)
- DHT22 sensor library
- TinyGPS library
- KiCad 6.x.


## Execution ⚙️
- Arduino: see Arduino libraries.
- Mobile app: see Android [README file](Android/README.md).
- Cloud store (server/client): use [docker-compose.yml](WebApp/docker-compose.yml).

	

## Contributors

- Iván García
- Javier Albusac (javieralonso.albusac@uclm.es).
- José J. Castro-Schez (josejesus.castro@uclm.es).
- Vanesa Herrera (vanesa.herrera@uclm.es).
- David Vallejo (david.vallejo@uclm.es).


## Copyright and license
Code released under the MIT License.
					  
				


