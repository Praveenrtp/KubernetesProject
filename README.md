# KubernetesProject
Deployed MongoDB pod and Mongo-Express pod where a browser request goes to the mongo express external service which then forwards it to the mongo-express pod which then connects to the internal service of MongoDB and forwards it to the MongoDB pod where it authenticates the request using the credentials.

