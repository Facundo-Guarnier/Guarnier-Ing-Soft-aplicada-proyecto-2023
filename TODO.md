https://virtual.um.edu.ar/pluginfile.php/372313/mod_resource/content/1/Trabajo%20final%20-%20Ing%20de%20Software%20Aplicada.pdf

https://github.com/jhipster/jdl-samples

- JHipster con JDL
  jhipster import-jdl jhipster-jdl.jdl

- Usar docker

- Test de unidad (selenium?)

- Testeo con cypress
  \src\test\javascript\cypress\e2e

- Gestion de logs con ELK (Logstash, Elasticsearch, Kibana)
  \src\main\resources\config\application-xxx.yml -> logging>logstash>enabled:True,
  logging>logstash>port:50000

- PWA con el proyecto JHipster.
  \src\main\webapp\manifest.webapp
  \src\main\webapp\index.html
  $ npm run prod

- Crear una aplicación progresiva en ionic que consuma una API del proyecto
  JHipster

- Convertir la aplicación Ionic en PWA permitiendo que pueda funcionar sin
  conexión.

- Implementar un servidor de integración continua (Jenkins) que lea el
  repositorio y genere una imagen docker de la aplicación (Dockerhub)
