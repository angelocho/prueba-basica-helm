Este repositorio es una prueba de helm con argocd. Tiene un esquema sencillo y funciones como toyaml, if else,range key value, default, quote, nindent, define (include)

Funcional y probado con minikube.

Tiene dos deployments que trabajan en un servicio (escuchando en el puerto 8080) con un pod cada uno, con containers con una imagen de nginx y otro de httpd escuchando en el 80.

Requisitos, tener minikube instalado y helm.