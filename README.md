# Arquitectura-web

Link de swagger [Swagger](https://petstore.swagger.io/?displayOperationId=1#/)

## Primera mirada para el trabajo (Armado del CRUD) 

**El sistema va a ser una turnera médica.**

_Tendrá una clase Admin que se encargará de gestionar médicos en la base._

_Tendrá como métodos pincipales:_

* void crearMedico(Matrícula);
* void modificarMedico(Matrícula);
* void eliminarMedico(Matrícula);
* void buscarMedico(Matrícula);

_Y tendrá dos métodos aparte del C.R.U.D.:_

* void calcularSueldoMedico(Matricula);
* void asignarConsultorio(Matricula);
