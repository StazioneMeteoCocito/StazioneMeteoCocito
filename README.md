# Cocito Weather Station / Stazione Meteo del Liceo Cocito
<p align="center">
<img src="https://avatars.githubusercontent.com/u/94685891?v=4">
</p>


Source Code for the weather station situated at [Liceo Cocito](https://liceococito.edu.it) : station, server and display is hosted in the following repositories

<p align="center">
<a href="https://t.me/StazioneMeteoCocitoBot"><img src="https://img.shields.io/badge/@StazioneMeteoCocitoBot-Telegram-blue.svg" alt="@matmasak on telegram"></a>
<a href="https://twitter.com/Meteococito"><img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/MeteoCocito"></a>
<a href="https://www.instagram.com/meteococito/"><img src ="https://img.shields.io/badge/Instagram-meteococito-orange" alt="Instagram"></a>
</p>

<p align="center">
<img src="https://github-readme-stats.vercel.app/api?username=StazioneMeteoCocito&show_icons=true&theme=dark" height="165">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=StazioneMeteoCocito&layout=compact&theme=dark">
</p>  
  
## Overview

|Component|Repository|Description|Languages|Further developments|
|---|---|---|---|---|
|Dataset<br />![GitHub](https://img.shields.io/github/license/StazioneMeteoCocito/dati)|[`dati`](https://github.com/StazioneMeteoCocito/dati)|Holds all the data collected so far|CSV, JSON||
|Arduino<br />![GitHub](https://img.shields.io/github/license/StazioneMeteoCocito/arduino)<br />[![made-with-c++](https://img.shields.io/badge/Made%20with-C%2B%2B-f34b7d.svg)](https://isocpp.prg)|[`arduino`](https://github.com/StazioneMeteoCocito/arduino)|Handles the acquisition of air quality data from the PM10-2,5 and smoke sensors, sending it to the raspberry over a serial connection|C++||
|Station<br />![GitHub](https://img.shields.io/github/license/StazioneMeteoCocito/station)<br />![GitHub](https://img.shields.io/github/license/StazioneMeteoCocito/instagramGrapher)<br />![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)|[`station`](https://github.com/StazioneMeteoCocito/station)|The software which runs on the raspberry pi and receives temperature, humidity and pressure data from the sense hat, along with serial data from the arduino is tasked with acquisition storage of the weather data.|python|Better memory management, reboot cycle|
|Server<br />![GitHub](https://img.shields.io/github/license/StazioneMeteoCocito/server)<br />[![made-with-php](https://img.shields.io/badge/Made%20with-PHP-4F5D95.svg)](https://www.php.net/)|[`server`](https://github.com/StazioneMeteoCocito/server)|This Web App pulls git weather data, stores it and allows for retrieval and plotting of archival and current data, along with excel exports.<br />Includes the telegram bot.|PHP|REST API|
|Neon display![GitHub](https://img.shields.io/github/license/StazioneMeteoCocito/retroDisplay)<br />[![made-with-javascript](https://img.shields.io/badge/Made%20with-JavaScript-f1e05a.svg)](https://www.javascript.com)|[`retroDisplay`](https://github.com/StazioneMeteoCocito/retroDisplay)|A simple neon display that shows current data. Ideal for small screens|Javascript|
|Documentation<br />![GitHub](https://img.shields.io/github/license/StazioneMeteoCocito/documents)<br />[![made-with-LaTeX](https://img.shields.io/badge/Made%20with-LaTeX-3D6117.svg)](https://isocpp.prg)|[`documents`](https://github.com/StazioneMeteoCocito/documents)|The presetation papers of the project|LaTeX||
|Terminal Client<br />![GitHub](https://img.shields.io/github/license/StazioneMeteoCocito/clicitow)<br />[![made-with-c++](https://img.shields.io/badge/Made%20with-C%2B%2B-f34b7d.svg)](https://isocpp.prg)|[`clicitow`](https://github.com/StazioneMeteoCocito/clicitow)|A TUI client which allows browsing of latest and historical data and hardware reports in a terminal or teletype.|C||
|Twitter Bot<br />![GitHub](https://img.shields.io/github/license/StazioneMeteoCocito/twitterBot)<br />[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)|[`twitterBot`](https://github.com/StazioneMeteoCocito/twitterBot)|Twitter bot of the station, providing regular updates at [@MeteoCocito](https://twitter.com/MeteoCocito). Recent bullettins are also stored.|Python3||
|Python3 library<br />![GitHub](https://img.shields.io/github/license/StazioneMeteoCocito/arduino)<br />[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)|[`meteoCocitoPy`](https://github.com/StazioneMeteoCocito/meteoCocitoPy)|Python library for accessing and manipulating data from the station.|Python3||
|Instagram Grapher Bot<br />![GitHub](https://img.shields.io/github/license/StazioneMeteoCocito/instagramGrapher)<br />[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)|[`instagramGrapher`](https://github.com/StazioneMeteoCocito/instagramGrapher)|Bot graphing daily data and posting it to Instagram with averages|Python3||

![](https://raw.githubusercontent.com/StazioneMeteoCocito/instagramGrapher/main/day.jpg)

> 2021, Mattia Mascarello, Lorenzo Dellapiana, Luca Biello, The MIT License

