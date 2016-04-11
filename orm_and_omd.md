# ORM (Mapeo Objeto-Relacional)

El **mapeo objeto-relacional** (más conocido por su nombre en inglés, Object-Relational mapping, o sus siglas O/RM, ORM, y O/R mapping) es una técnica de programación para convertir datos entre el sistema de tipos utilizado en un lenguaje de programación orientado a objetos y la utilización de una base de datos relacional como motor de persistencia. En la práctica esto crea una base de datos orientada a objetos virtual, sobre la base de datos relacional. Esto posibilita el uso de las características propias de la orientación a objetos (básicamente herencia y polimorfismo). Hay paquetes comerciales y de uso libre disponibles que desarrollan el mapeo relacional de objetos, aunque algunos programadores prefieren crear sus propias herramientas ORM.

# ODM (Mapeo Objeto-Documento)

Un ODM nos aporta las ventajas de un ORM pudiendo almacenar los objetos de nuestro modelo de la aplicación en almacenamiento NoSQL (Documentos) con la misma facilidad que existía para persistir el modelo relacional. Doctrine se ha expandido con el objetivo de dar soporte a bases de datos como MongoDB y CouchDB. La unidad básica de persistencia en estos sistemas es el Documento y será fácil transformarlo en objetos de programación.

**¿Qué características nos aporta Doctrine2 como ODM?**

Ciertas características que nos aporta este framework y que deberíamos conocer son:

* Almacenamiento de nuevos documentos, actualización y eliminación.
* Capacidad seguimiento de las acciones en las entidades para posteriormente persistirlos con el método flush() transparentemente.
* Soporte para Colecciones y asociaciones del tipo OneToMany y ManyToOne.
* Soporte para documentos embebidos; tanto para uno como varios campos de documentos. Esto es una diferencia respecto a los ORM ya que no permiten soporte para mapear.
* Operaciones de cascada de la persistencia y la eliminación de los objetos.
* Especificación de metadatos de mapeo en distintos formatos (XML,YAML,PHP,Annotations).

La documentación no es demasiado extensa y completa pero ayuda a entender los conceptos e implementación básicos de Colecciones y Documentos.
