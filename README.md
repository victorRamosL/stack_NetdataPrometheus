# 🌟 Stack NetdataPrometheus

Un proyecto increíble que para la monitorización completa del sistema. 🚀✨

## 📖 Tabla de Contenidos
1. [Descripción](#descripción)
2. [Características](#características)
3. [Instalación](#instalación)
4. [Uso](#uso)

---

## 📋 Descripción
Este proyecto despliega un stack con Docker Compose, que contiene un contenedor de Netdata, y otro de Prometheus. 
Además, contiene un contenedor de AlertManager, para configurar las alertas, y Grafana para visualizar los datos
de la monitorización 💡

---

## ✨ Características
- ✅ Interfaz intuitiva y moderna.
- 🌍 Monitorización completa.

---

## ⚙️ Instalación
1. Clona el repositorio:
   ```bash
   git clone https://github.com/victoropss/stack_NetdataPrometheus.git

## Uso
1. Configura los archivos de configuración a tu gusto:

2. Inicializa los contenedores:
   ```bash
   docker compose up -d

3. Accede a los servicios a través del navegador
   
   Netdata: tuip:19999

   Prometheus: tuip:9090

   AlertManager: tuip:9093

   Grafana: tuip:3000

4. En Grafana, configura a Prometheus, y a NetData como fuentes de datos
