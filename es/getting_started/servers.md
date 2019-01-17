# Servidores de prueba y producción

## Requisitos de Sistema mínimos recomendados:

### 1. Production Server:
  - Distrubution: Ubuntu 16.04.3
  - RAM: 32GB
  - Processor: Quad core
  - Hard Drive: 20 GB
  - Database: Postgres

### 2. Staging Server:
  - Distrubution: Ubuntu 16.04.3
  - RAM: 16GB
  - Processor: Dual core
  - Hard Drive: 20 GB
  - Database: Postgres

Si tu ciudad tiene una población superior a 1.000.000, considera añadir un balanceador de carga y usar 2-3 servidores de producción, además de un servidor de base de datos dedicado.

## Instrucciones de instalación
Se encuentran en el [repositorio del instalador](https://github.com/consul/installer)
