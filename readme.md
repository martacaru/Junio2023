La solución actual para monitorizar los equipos del instituto está basada en Prometheus y Grafana. 
Durante el tiempo que ha estado en marcha desde que substituyó al anterior sistema basado en Graphite ha 
rendido muy bien  Y no es que Graphite no lo hicera. Una vez que se montó el directorio con las métricas 
en un sistema de archivos en RAM todo pasó a funcionar como la seda sin machacar a los discos con 
escrituras. Pero Prometheus es una herramienta mucho más nueva que nunca ha abusado de los discos con una carga excesiva de operaciones de escritura. Eso sí, consume más RAM.