## TEST N° 1 -------------------------------------------------------------------------------------------------
**P1. ¿Qué código de respuesta devuelve un servicio Global que no devuelve datos?**
- 400
- 500
- 200
- 204 ← CORRECTA

**P2. Para realizar un commit:**
- Hay que poner un asunto y una breve descripción del cambio ← CORRECTA
- Tiene que ser de un cambio importante sobre el código
- Hay que describir siempre el cambio realizado en inglés
- No es necesario describir el cambio

**P3. ¿Quién prueba un servicio la noche de implantación?**
- Las pruebas las realiza Integración y Desarrollo
- Los responsables de las líneas
- El responsable del desarrollo ← CORRECTA
- El desarrollador, al día siguiente de la implantación

**P4. ¿En qué estado del JIRA debe dar el consumidor el VºBº?**
- En Designing Service
- En Under Construction
- En Ready To Integrate 
- En Pending Release Candidate Validation ← CORRECTA

**P5. ¿Cómo se solicita una variable de Arquitectura?**
- Mediante un Jira ← CORRECTA
- Mediante un Remedy a Gobierno
- Mediante un Remedy a Arquitectura ← CORRECTA
- Con un correo a Gobierno

**P6. ¿De cuál de los siguientes estados del ticket JIRA es responsable el equipo de Gobierno?**
- En Under Construction
- En Designing Metadata
- En Validating Metadata
- En Deployed ← CORRECTA

**P7. ¿Cuál es el nombre del jar que se genera en un servicio de negocio cuando se compila?**
- uuaa-logicalId-version.jar
- uuaa_logicalId-facade.jar
- uuaa_logicalId.jar ← CORRECTA
- Ninguna de las anteriores

**P8. Imagina que tienes que implementar un servicio con filtros. ¿Qué componentes situarías en el DAO?**
- Clases backend ← CORRECTA
- Clases backend y llamadas al backend
- Clases backend, llamadas al backend y mapper backend
- Clases backend, llamadas al backend, mapper backend y entidades internas

**P9. Si en una iniciativa se nos pide que dependiendo de la AAP el servicio se comporte de una u otra forma, ¿cómo debemos actuar?**
- Incluir la lógica en el servicio llamando a ServiceInvocationContext
- Incluir la lógica en el servicio llamando a ServiceUtilities
- No debemos incluir esa lógica en el servicio, la debe incluir la transacción ← CORRECTA
- Solo podemos comprobar si el canal que llama es asistido o desasistido

**P10. ¿Qué código corresponde cuando un servicio no devuelve datos?**
- 200
- 400
- 204 ← CORRECTA
- 403

**P11. ¿Cuándo se hace el control de canal?**
- Siempre ← CORRECTA
- Si el servicio usa tarjetas
- Solo cuando se hace en oficinas
- Solo desde las AAP atendidas

**P12. Si realizamos una modificación sobre la rama Release Candidate, el nombre de nuestra rama tendrá el formato:**
- Hotfix/[ticket JIRA]-[breve descripción]
- Feature/[ticket JIRA]-[breve descripción]
- Custom/[ticket JIRA]-[breve descripción]
- Bugfix/[ticket JIRA]-[breve descripción] ← CORRECTA

**P13. ¿Cuándo se desbloquean los servicios en Integrado (bloqueados por una implantación)?**
- El día de la subida a PRO ← CORRECTA
- El día de la subida a Piloto
- Ya nunca se bloquean
- Cuando se revisa la Calidad

**P14. ¿En cuál de estos estados del JIRA el responsable no es el equipo de desarrollo?**
- En Designing Metadata
- En Designing Security ← CORRECTA
- En Under Construction
- En Designing Service

**P15. ¿Qué código de error devuelve un servicio cuando está corrupto?**
- 400
- 409
- 500
- 404 ← CORRECTA

**P16. ¿Cuándo un ticket JIRA pasa a ser un ticket inactivo?**
- Han pasado 15 días desde su modificación ← CORRECTA
- He subido el servicio y no he avanzado el ticket
- El ticket es sobre un servicio que ya se está modificando
- No he contestado a los comentarios de esa semana

**P17. Si quiero añadir una rutina nueva para usarla dentro de un servicio, ¿dónde la añado?**
- En el business-service.xml ← CORRECTA
- En el facade con la anotación @SN(routines=[rutina])
- En el pom.xml
- Ninguna de las anteriores

**P18. ¿Dónde está disponible la nueva documentación de Arquitectura?**
- En Google Drive
- En el site de Gobierno
- En el site de Arquitectura
- En el Platform ← CORRECTA

**P19. ¿Qué código de respuesta devuelve un servicio de creación cuando ha funcionado correctamente?**
- 400
- 201 ← CORRECTA
- 409
- 204

**P20. ¿Quién decide las fechas de las subidas de las calendadas?**
- Los usuarios integradores
- Los líderes de las líneas
- Gobierno de Arquitectura
- Gestión de Cambios ← CORRECTA

**P21. ¿Qué código corresponde a un error funcional en implementación Global?**
- 400 ← CORRECTA
- 500
- 409
- 204

**P22. ¿Quién se encarga de mergear nuestros cambios a la rama Master?**
- El Release Manager ← CORRECTA
- Nosotros mediante Remedy
- Gobierno ASO
- Nosotros a través de SourceTree

**P23. ¿Qué nombre tiene una rama del fork?**
- GRAP-4742 o ASOGP-4742 ← CORRECTA
- SOPVII-21009
- feature/FixDescripciones
- xe51715

**P24. ¿Cómo se implementa un enumerado?**
- Como tipo Enum
- Como String ← CORRECTA
- Nunca se define un Enum en un servicio
- Como un array de enum

**P25. ¿Cuál sería un nombre correcto de un fork?**
- El ticket JIRA asociado
- [username]-repositorio ← CORRECTA
- El ticket GRAP asociado
- Cualquier nombre

**P26. ¿Cuál de las siguientes reglas de Sonar para implantar no es exigida para subir nuestro código?**
- Que la cobertura sea superior a la que había en master
- Que al menos funcionen el 65% de los tests ← CORRECTA
- Que no haya incidencias críticas
- Que no haya incidencias bloqueantes

**P27. Cuando se versiona un servicio, ¿qué se hace realmente?**
- Se versiona el SMC (facade, business, dao)
- Se versiona solo la facade ← CORRECTA
- Se versiona el SN entero con todos los SMC
- Se versiona la facade de todo el SN (no hace falta versionar todo el SN entero)

**P28. ¿Qué código corresponde a un error funcional en implementación Local?**
- 400 ← CORRECTA
- 500
- 409
- 403

**P29. ¿Cuál de los siguientes formatos para validar el WADL en PRO es correcto?**
- https://bbva.es/ASO/cryptographicServices/v01/?_wadl
- curl –x GET /requestsStoresPayments/V01/?_wadl
- curl –x GET http://lprsm302:7560/redsys/v0/redsys/?_wadl ← CORRECTA
- curl –x GET http://lprsm302:7560/redsys/v0/?_wadl

**P30. ¿Se debe acceder al contexto del servicio para tomar decisiones en función de la APP?**
- Sí, siempre
- No, salvo que sea estrictamente necesario
- No ← CORRECTA
- Sí, en el caso de que el consumidor lo requiera

**P31. ¿Cuándo hay que hacer control de canal en un servicio?**
- Siempre ← CORRECTA
- Solo cuando son servicios de particulares
- Solo en las AAPs atendidas
- Solo en las AAPs desatendidas

**P32. ¿Se puede llamar a un SMC desde otro SMC?**
- Sí, incluyendo la llamada con un RestConnector
- Sí, incluyendo el SMC en el business-service.xml
- Sí, incluyendo el SMC en el pom.xml
- No ← CORRECTA

**P33. ¿Qué código corresponde cuando un servicio no devuelve datos?**
- 200
- 400
- 204 ← CORRECTA
- 403

**P34. ¿En qué ruta debo incluir el Cucumber nuevo?**
- Com.bbva.arch.qe.test
- Acceptane ← CORRECTA
- Com.bbva.enax.stores.bdd
- Cucumber/src/main/java/com/bbva/arch/qe/test






## TEST N° 2 -------------------------------------------------------------------------------------------------
**P1. ¿En cuál de estos estados del JIRA el responsable no es el equipo de desarrollo?**
- En Edición de Datos
- En Comprobación Inicial ← CORRECTA
- En Construcción
- En Edición de Datos Global

**P2. ¿Cuándo hay que realizar el control de canal a un servicio?**
- Sólo en AAPs atendidas
- Sólo en AAPs desatendidas
- Siempre ← CORRECTA
- Sólo en los servicios críticos

**P3. ¿Cuándo puedo mergear mi rama en la rama master?**
- Cuando vaya a subir a producción y tenga el ticket en “Pendiente de Producción”
- Cuando ya se haya subido a producción y tenga el ticket en "Verificación de Repositorio"
- Nunca debo mergear mi rama en la de master ← CORRECTA
- Una vez haya mergeado en la rama de desarrollo y se haya comprobado que todo funciona

**P4. ¿Cuántos features tiene que tener nuestro cucumber si el servicio es un POST?**
- 6
- 7 
- 8 ← CORRECTA
- 9

**P5. ¿Cuál es la cobertura mínima para pasar Sonar?**
- 55%
- 65% ← CORRECTA
- 75%
- 85%

**P6. ¿Cuándo puedo crear un ticket de modificación express?**
- Cuando la modificación no impacta al diseño ← CORRECTA
- Cuando necesito modificar un servicio rápidamente
- Cuando la modificación es muy pequeña, aunque impacte al diseño
- Cuando no sea necesario volver a catalogar el servicio

**P7. Para solicitar la inclusión de nuestro código en master hay que:**
- Rellenar un formulario a integración y despliegue indicando nuestra rama ← CORRECTA
- Rellenar un formulario a integración y despliegue indicando el SN para que suba la rama “desarrollo”
- Solicitar mediante un correo a integración y despliegue indicando la fecha calendada de la subida
- Pasar el ticket JIRA a pendiente de producción

**P8. ¿Cuántos features tiene que tener nuestro cucumber si el servicio es un GET de tipo list?**
- 6
- 7
- 8 ← CORRECTA
- 9

**P9. ¿Sobre qué rama destino tiene que ir el Pull Request del RAML?**
- Master
- La rama del ticket GRAP
- Develop ← CORRECTA
- Ninguna de las anteriores

**P10. ¿A qué nivel del servicio se encuentra la carpeta “acceptance”?**
- A nivel de las capas
- A nivel del mapper de la facade
- A nivel del mapper a la transacción
- A nivel de la carpeta raíz ← CORRECTA

**P11. ¿Cuántos features tiene que tener nuestro cucumber si el servicio es un GET de tipo detalle?**
- 6 ← CORRECTA
- 7
- 8
- 9

**P12. ¿En cuál de estos estados del JIRA el responsable no es el equipo de desarrollo?**
- A. En edición de Datos
- B. En comprobación inicial ← CORRECTA
- C. En construcción
- D. En edición de Datos Global

**P13. ¿En qué situación puedo no sacar mi rama del último tag de PRO?**
- Nunca, siempre ha de ser el último tag de producción ← CORRECTA
- Siempre que haya un tag DEV más nuevo
- Siempre que hayan pasado 2 meses desde el último
- Nunca hay que sacar la rama del último tag de PRO

**P14. ¿Cómo se implementan los test unitarios?**
- Con Cucumber
- Con Sonar
- Con Junit ← CORRECTA
- Con Postman

**P15. ¿En cuál de estos estados del JIRA el responsable es el equipo de Global?**
- Pendiente de validación Global ← CORRECTA
- En edición de datos
- En construcción
- En edición de Datos Global

**P16. ¿Cuántos features tiene que tener nuestro cucumber si el servicio es un DELETE?**
- 4
- 5 ← CORRECTA
- 6
- 7

**P17. Para desarrollar un API hay que:**
- Abrir un Ticket JIRA GRAP
- Ir al workshop y hablar con el equipo de GLOBAL para que ellos abran un ticket JIRA
- Enviar un correo al equipo de GLOBAL con un breve resumen de la iniciativa
- Cuando enviamos el DFT, el equipo de GLOBAL abrirá un ticket JIRA ← CORRECTA

**P18. ¿Qué medio no me va a resolver las dudas sobre la construcción de un Servicio?**
- A. La comunidad Google+
- B. Mis compañeros de equipo
- C. Askbot
- D. Buzón de Gobierno ← CORRECTA

**P19. ¿Con cuáles de las incidencias en Sonar no está permitido solicitar la implantación?**
- A. Crítica e invalidadora
- B. Crítica y bloqueante ← CORRECTA
- C. Mayor y bloqueante
- D. Ninguna de las anteriores

**P20. ¿Cuántos features tiene que tener nuestro cucumber si el servicio es un PATCH?**
- 4
- 5 ← CORRECTA
- 6
- 7

**P21. ¿Cómo se prueban los servicios la noche de la implantación?**
- A. Solo se debe probar que levanta el Wadl
- B. Prueba funcional, a poder ser invocando desde el front. ← CORRECTA
- C. No se pueden probar los servicios en PRO
- D. Solo se deben probar desde postman

**P22. Para desplegar en Integrado**
- Hay que mergear a Master nuestros cambios y desplegar esta rama
- Se despliega esta rama
- Hay que mergear nuestros cambios en desarrollo y desplegar esta rama ← CORRECTA
- No es necesario probar en Integrado, con probar en Gremio es suficiente

**P23. ¿Cuándo un ticket JIRA pasa a estar inactivo?**
- Han pasado 15 días desde su última modificación ← CORRECTA
- Ha subido el servicio y no he avanzado el ticket
- El ticket es sobre un servicio que ya se está modificando
- No he contestado a los comentarios de esa semana

**P24. ¿Cuál de estas afirmaciones no es correcta?**
- El ticket Jira lo abre la persona que vaya a desarrollar la iniciativa
- EL ticket Jira lo abre la persona que va a diseñar la iniciativa
- El ticket Jira lo abre el responsable de la iniciativa
- El ticket Jira lo abre el responsable de la Línea ← CORRECTA

**P25. ¿Cómo se implementan los test funcionales?**
- Con Cucumber ← CORRECTA
- Con Sonar
- Con Junit
- Con Postman

**P26. ¿Cuál es el número mínimo de ramas que ha de tener un repositorio?**
- 2 ← CORRECTA
- 0
- 1
- 3

**P27. ¿Cómo se solicita la modificación del valor de una variable de arquitectura?**
- Mediante un ticket JIRA
- Mediante un Remedy a Gobierno
- Mediante un correo a Arquitectura
- Mediante un Remedy a Arquitectura de Servicios ← CORRECTA

**P28. ¿Qué contiene la carpeta “acceptance”?**
- Cucumber ← CORRECTA
- Junits
- Business-service.xml
- Contextos de las Transacciones

**P29. ¿Por cuál de estos motivos puede Integración y Despliegue rechazar la subida del servicio?**
- La cobertura sea igual o superior a la que había en Producción
- Funcionen el 80% de los test ← CORRECTA
- Funcionen todos los test del cucumber
- Cuando se solicita la subida, el ticket se encuentre en el estado “En Construcción” 

**P30. ¿Cuál es el flujo de despliegue por entornos correcto?**
- Desarrollo -> Gremio -> Integrado -> Piloto -> Producción
- Desarrollo -> Gremio -> Integrado -> AUS -> Piloto -> Producción ← CORRECTA
- Desarrollo -> Integrado -> Producción
- Desarrolo -> Integrado -> Gremio -> Piloto -> Producción

**P31. ¿Qué Gobiernos hay en España?**
- A. Gobierno de Servicios y APX
- B. Gobierno de Servicios, APX y Global
- C. Gobierno de Arquitectura y Gobierno de Datos ← CORRECTA
- D. Gobierno de Servicios, APX y Batch.

**P32. Si quiero añadir una rutina nueva para usarla dentro de un servicio, ¿dónde la añado?**
- A) En el business-service.xml ← CORRECTA
- B) En el facade con la anotación @SN(routines=[rutina])
- C) En el pom.xml
- D) Ninguna de las anteriores

**P33. ¿Se puede comportar un servicio de forma diferente según la AAP?**
- A. Sí, incluyendo la llamada con un RestConnector
- B. Sí, incluyendo el SMC en el business-service.xml
- C. Sí, incluyendo el SMC en el pom.xml
- D. No ← CORRECTA

**P34. ¿Qué código HTTP de respuesta se utilizará cuando un servicio con funcionamiento ASO devuelva un error funcional?**
- A. 200
- B. 409
- C. 400 ← CORRECTA
- D. Ninguno de los anteriores









## TEST N° 3 -------------------------------------------------------------------------------------------------
**P1. Si se versiona una transacción APX pero NO incluye nuevas transacciones Host en su árbol de llamadas. ¿Es necesario catalogar y perfilar de nuevo el servicio?**
- Sí
- No ← CORRECTA

**P2. Señala la frase correcta.**
- Los desarrollos nuevos no deben bajar la cobertura de lo que ya hay en producción.
- La cobertura mínima para un despliegue es el 65%.
- Todas las anteriores son correctas. ← CORRECTA
- Ninguna es correcta

**P3. Como developer ¿cómo puedo desplegar mi rama feature en Integrado?**
- No puede con el Rol de developer
- Puedo desplegar mi rama sin ningún problema
- Mediante un mergeo en la rama Integration, y desplegando esta ← CORRECTA
- Solo puede desplegar en Integrado con el rol de release manager

**P4. ¿Por qué se considera un ticket en estado “En Construcción”, inactivo?**
- Han pasado 15 días desde su modificación
- Han pasado 20 días desde su modificación
- Han pasado 10 días desde su modificación
- Han pasado 40 días desde su modificación ← CORRECTA

**P5. ¿Cuántas transacciones hay que indicar en los metadatos?**
- Las transacciones a las que se llaman en el servicio
- El árbol de transacciones de las transacciones del servicio
- Todas las anteriores ← CORRECTA
- Ninguna de las anteriores

**P6. La rama hotfix sale de la rama de...**
- Develop
- Master ← CORRECTA
- Integration
- Ninguna de las anteriores

**P7. En un servicio NUEVO, ¿dónde incluirías los valuable codes?**
- Los servicios nuevos no incluyen valuable codes, lo debe realizar la APX. ← CORRECTA
- pom.xml
- En la facade.
- A nivel raíz.

**P8. Como Release Manager puedo desplegar la rama feature en ...**
- Gremio > Octa > Aus ← CORRECTA
- Desarrollo > Integrado > Gremio >
- Desarrollo > Gremio
- Ninguna de las anteriores

**P9. ¿En cuál de estos estados es el desarrollador responsable del ticket Jira?**
- Under Construction ← CORRECTA
- Validating Design
- Reviewing Design
- Ready to Production Deployment

**P10. ¿Quién se encarga de realizar actualmente los mergeos a la rama desarrollo?**
- Integración y despliegue
- Se realiza mediante Pull Request
- El desarrollador ← CORRECTA
- Los integradores de la UUAA

**P11. ¿De qué rama saldrá nuestra feature en el nuevo modelo?**
- Master
- producción
- Develop ← CORRECTA
- Rc

**P12. ¿Cuál de estas afirmaciones no es correcta?**
- La app de net cash es desatendida
- La app de Contact Center es atendida
- La app de oficinas es desatendida ← CORRECTA
- La app de la net es desandida

**P13. En el nuevo pipeline nuestra bugfix sale de la rama...**
- Master
- develop
- RC ← CORRECTA
- Production

**P14. ¿Qué rol puede desplegar en entorno de producción?**
- Developer
- Master
- Release Manager ← CORRECTA
- Integrador de UUAA

**P15. ¿Cuál sería un nombre correcto como rama del fork?**
- El ticket GRAP asociado
- El ticket jira asociado ← CORRECTA
- feature/fix Descripciones
- Mi usuario

**P16. ¿Cuál es la principal diferencia entre un ticket de Modificación de SMC y un ticket de Modificación Exprés de servicio?**
- El ticket express se usa para correcciones urgentes y justificadas mientras que el de modificación es para cualquier otro caso. ← CORRECTA
- En el ticket de modificación se solicita el consumo de un servicio y el ticket de Modificación Exprés no
- En el ticket de Modificación Exprés se solicita el consumo de un servicio y en el ticket de Modificación de SMC no
- En el ticket de Modificación Exprés hay que modificar el diseño y en el ticket de Modificación de SMC no

**P17. Como developer puedo desplegar mi rama feature en...**
- Gremio > Integrado
- Gremio
- Desarrollo > gremio > Integrado ← CORRECTA
- Ninguna de las anteriores

**P18. ¿Qué código de error se corresponde con un error técnico?**
- 500 ← CORRECTA
- 409
- 400
- 404

**P19. Cuando se versiona un servicio, se versiona:**
- La facade ← CORRECTA
- La facade, business.
- La facade, business, dao.
- Ninguna.

**P20. ¿Si se quiere que un servicio pase de mono-operativo a multi-operativo qué tendremos que tener en cuenta?**
- Deberá subir primero el servicio y después la catalogación ya que si no fallará el servicio. ← CORRECTA
- Deberá subir primero la catalogación y después el servicio ya que si no fallará el servicio.
- No se puede realizar el cambio
- Se tendrá que versionar el servicio

**P21. ¿Quién se encarga de solicitar los consumos de los servicios mediante el ticket JIRA correspondiente?**
- El desarrollador del servicio.
- El propietario del servicio.
- El consumidor. ← CORRECTA
- Gobierno.

**P22. ¿Cómo se dan de alta las variables de Arquitectura?**
- Indicándolo en el jira de Gobierno
- Vía remedy a Gobierno
- Vía remedy a Arquitectura ← CORRECTA
- Por correo a Arquitectura con copia a Gobierno

**P23. Si tengo que hacer una corrección de una incidencia que no es bloqueante ¿qué tipo de rama se creará...?**
- Bugfix ← CORRECTA
- Hotfix
- Feature
- Ninguna de las anteriores

**P24. ¿Cuándo se desbloquean los Servicios en Integrado (bloqueados por una implantación)?**
- El día de la subida a Piloto
- El día de la subida a PRO
- Cuando se revisa la Calidad
- Ya nunca se bloquean ← CORRECTA

**P25. ¿Quién es el encargado de realizar la subida de un componente a master?**
- El equipo de Integración y Despliegue
- Release Manager ← CORRECTA
- El desarrollador mediante un mergeo a master
- El desarrollador mediante una pull request a master

**P26. ¿Qué significa CRUD?**
- Conjunto de reglas que hay detrás de los test Cucumber
- Nuevo procedimiento Jira para dar de alta un MSA para un Q determinado
- Funciones básicas en bases de datos o la capa de persistencia en un SW ← CORRECTA
- La nueva uuaa que ha creado Global para los servicios que van a ser implementados en AWS

**P27. ¿Con cuánta antelación debo pedir la integración si no desarrollo ENAX/ERGO?**
- 14 días antes de la implantación
- 7 días antes de la implantación
- Los días que establezca el calendario de I&D de la UUAA en cuestión ← CORRECTA
- Los días que establece el integrador de mi UUAA

**P28. ¿Quién tiene que solicitar el consumo de un servicio?**
- La persona de Gobierno que lleve el ticket
- El responsable de la línea
- El consumidor ← CORRECTA
- El desarrollador

**P29. ¿Cuál de estos datos son sensibles y se deben ofuscar en trazas?**
- PAN, CVV, teléfonos, direcciones de e-mail, contraseñas, PIN y OTP. ← CORRECTA
- PAN, CVV, Fecha de Caducidad de la tarjeta
- DNI, PAN, CVV
- IBAN, contractID, DNI

**P30. Puedo desplegar mi rama hotfix/bugfix en los entornos...**
- gremio
- desarrollo > gremio
- desarrollo > gremio > integrado ← CORRECTA
- No puedo desplegar mi rama

**P31. ¿Cuánta cobertura debe tener mínimo un servicio para poder subir a producción?**
- 80%
- 70%
- 100%
- 65% ← CORRECTA

**P32. ¿Qué código devuelve un servicio que falla por no estar perfilado correctamente?**
- 401 ← CORRECTA
- 409
- 403
- 400

**P33. ¿A partir de qué estado del ticket Jira se puede solicitar el consumo de un servicio?**
- Construcción. ← CORRECTA
- Cerrado.
- Comprobación inicial.
- Pendiente de catalogación.

**P34. ¿Quién se encarga de realizar actualmente los mergeos a la rama master de las diferentes ramas?**
- Integración y despliegue
- Se realiza mediante Pull Request
- El desarrollador
- Release Manager ← CORRECTA













## TEST N° 4 -------------------------------------------------------------------------------------------------
**P1. ¿Qué código HTTP devuelve un servicio si la respuesta es correcta?**
- 204
- 200 ← CORRECTA
- 400
- 409

**P2. ¿Qué significa CRUD?**
- Conjunto de reglas que hay detrás de los test Cucumber
- Nuevo procedimiento Jira para dar de alta un MSA para un Q determinado
- Funciones básicas en bases de datos o la capa de persistencia en un SW ← CORRECTA
- La nueva uuaa que ha creado Global para los servicios que van a ser implementados en AWS

**P3. ¿Qué hace la anotación @Produces?**
- Aporta información sobre el servicio y además se utiliza para servicios antiguos para documentarlos y visualizarlos a través de swagger.
- Indica las posibles respuestas que puede tener un servicio.
- Indica en qué formato entran o salen los datos del servicio ← CORRECTA
- Indica la ruta relativa del SMC en cuestión.

**P4. ¿Con cuánta antelación debo pedir la integración si no desarrollo ENAX/ERGO?**
- 14 días antes de la implantación
- 7 días antes de la implantación
- Los días que establezca el calendario de I&D de la UUAA en cuestión ← CORRECTA
- Los días que establece el integrador de mi UUAA

**P5. ¿Qué hace la anotación @Consumes?**
- Aporta información sobre el servicio y además se utiliza para servicios antiguos para documentarlos y visualizarlos a través de swagger.
- Indica las posibles respuestas que puede tener un servicio.
- Indica en qué formato entran o salen los datos del servicio ← CORRECTA
- Indica la ruta relativa del SMC en cuestión.

**P6. ¿Cuál es la anotación de control de canal para un contrato?**
- @User
- @Contract ← CORRECTA
- @ValidateContractId
- @Amount

**P7. ¿Cuánta cobertura debe tener mínimo un servicio para poder subir a producción?**
- 80%
- 70%
- 100%
- 65% ← CORRECTA

**P8. ¿Cuándo se desbloquean los Servicios en Integrado (bloqueados por una implantación)?**
- Ya nunca se bloquean ← CORRECTA
- El día de la subida a PRO
- El día de la subida a Piloto
- Cuando se revisa la Calidad

**P9. ¿Cuáles son los datos sensibles?**
- PAN, CVV, teléfonos, direcciones de e-mail, contraseñas, PIN y OTP. ← CORRECTA
- PAN, CVV, Fecha de nacimiento, teléfonos, direcciones de e-mail, contraseñas, PIN y OTP
- PAN, CVV, ID del usuario, contraseñas y PIN
- PAN, CVV, Fecha de expiración de tarjeta, teléfonos y OTP

**P10. ¿Cuál de las siguientes reglas de SONAR para implantar no es de las exigidas para implantar nuestro código?**
- Que la cobertura sea superior a la que había en master
- Que al menos funcionen el 65% de los tests ← CORRECTA
- Que no haya incidencias críticas
- Que no haya incidencias bloqueantes

**P11. ¿Cómo se solicita una variable de Arquitectura?**
- Mediante un Jira
- Mediante un Remedy a Gobierno
- Mediante un remedy a Arquitectura ← CORRECTA
- Con un correo a Gobierno


**P13. ¿Qué hay que hacer para solicitar OCTA?**
- Solicitarlo al integrador de la UUAA
- Mandar un correo a Integración y Despliegue solicitándolo
- Solicitud a Arquitectura vía remedy ← CORRECTA
- Solicitar las pruebas de rendimiento a través de la consola

**P14. ¿Cuál es el estado previo a perfilado y catalogación en un proceso global de consumo de servicio ASO (nuevo flujo)?**
- Solicitud de consumo en Jira
- Validación Local de la Petición ← CORRECTA
- Pruebas EEPP
- Validación final

**P15. ¿Quién tiene que solicitar el consumo de un servicio?**
- La persona de Gobierno que lleve el ticket
- El responsable de la línea
- El consumidor ← CORRECTA
- El desarrollador

**P16. ¿Quién es el encargado de realizar la subida de un componente a master?**
- El equipo de Integración y Despliegue
- El integrador de la UUAA ← CORRECTA
- El desarrollador mediante un mergeo a master
- El desarrollador mediante una pull request a master

**P17. ¿Cómo se prueban los servicios la noche de la implantación?**
- Solo se debe probar que levanta el Wadl
- Prueba funcional, a poder ser invocando desde el front. ← CORRECTA
- No se pueden probar los servicios en PRO
- Solo se deben probar desde postman

**P18. ¿Qué nombre tiene una rama del fork en Global?**
- GRAP-4742 o ASOGP-4742 ← CORRECTA
- SOPVII-21009
- feature/FixDescripciones
- MiUsuario

**P19. ¿Cuál es el timeout censado de un servicio ASO?**
- 12000 ms ← CORRECTA
- 20000 ms
- 3000 ms
- 1000 ms

**P20. ¿Qué hace la anotación @Path?**
- Aporta información sobre el servicio y además se utiliza para servicios antiguos para documentarlos y visualizarlos a través de swagger.
- Indica las posibles respuestas que puede tener un servicio.
- Indica en qué formato entran o salen los datos del servicio
- Indica la ruta relativa del SMC en cuestión. ← CORRECTA

**P21. ¿Por qué se considera un ticket en estado “En Construcción”, inactivo?**
- Han pasado 15 días desde su modificación
- Han pasado 20 días desde su modificación
- Han pasado 10 días desde su modificación
- Han pasado 40 días desde su modificación ← CORRECTA

**P22. ¿Qué hace la anotación @ApiOperation?**
- Aporta información sobre el servicio y además se utiliza para servicios antiguos para documentarlos y visualizarlos a través de swagger. ← CORRECTA
- Indica las posibles respuestas que puede tener un servicio.
- Indica en qué formato entran o salen los datos del servicio
- Ninguna de las anteriores.

**P23. ¿Cuál es el timeout censado de un servicio APX Zona Crítica?**
- 12000 ms
- 20000 ms
- 3000 ms ← CORRECTA
- 1000 ms






## TEST N° 5 -------------------------------------------------------------------------------------------------
**P1. ¿Quién es el encargado de realizar la subida de un componente a master?**
- El equipo de Integración y Despliegue
- El integrador de la UUAA ← CORRECTA
- El desarrollador mediante un mergeo a master
- El desarrollador mediante una pull request a master

**P2. ¿En qué estado se deben realizar las pruebas del servicio?**
- En construcción ← CORRECTA
- Edición de datos
- Ciberseguridad
- Test

**P3. Tengo un servicio de negocio con una entidad cuyo identificador debe estar cifrado tanto en la entrada como en la salida de los servicios multicanal que operan sobre dicha entidad. Dicho identificador está formado por varios campos entre los que está el identificador de contrato necesario para realizar las operaciones. ¿Qué anotación de arquitectura ASO debo usar si además quiero asegurar el control del canal sobre dicho contrato?**
- @SecurityFunction
- @GenerateldOP ← CORRECTA
- @Format
- @DatoAuditable

**P4. ¿Cuál es la anotación que se utiliza para indicar la versión del servicio de negocio?**
- VS
- VE
- V
- VN ← CORRECTA

**P5. En el caso de que un servicio pase de mono a multioperación ¿cuáles son los pasos a seguir?**
- Deberá subir primero el servicio y después la catalogación ya que si no fallará el servicio ← CORRECTA
- Deberá subir primero la catalogación y después el servicio ya que si no fallará el servicio
- Habría que hacer un versionado del Servicio
- Es independiente qué sube primero ya que no tiene impacto en el Servicio

**P6. ¿Cuándo hay que hacer un control del canal en un servicio?**
- Cuando se estén tratando en el servicio clientes o contratos ← CORRECTA
- Sólo cuando son servicio de particulares
- Cuando se estén tratando en el servicio clientes o contratos en las AAPs atendidas
- Cuando se estén tratando en el servicio clientes o contratos en las AAPs desatendidas

**P7. ¿Cuál de las siguientes afirmaciones es una de las no exigidas para pasar Sonar?**
- Se supere el 65% de la cobertura
- La cobertura sea igual o mayor que la que había en master antes de nuestros cambios
- Funcionen el 65% de los test ← CORRECTA
- Que no haya incidencias críticas ni bloqueantes

**P9. ¿Se debe acceder al contexto del servicio para tomar decisiones en función de la APP?**
- No ← CORRECTA
- Si, siempre
- Si, en el caso de que el consumidor lo requiera
- No, salvo que sea estrictamente necesario

**P10. ¿Qué tipo de pruebas se deben realizar la noche de la implantación?**
- Con levantar el WADL vale
- Pruebas técnicas
- Pruebas funcionales ← CORRECTA
- Pruebas de los servicios críticos

**P11. ¿Por qué se considera un ticket en estado “En Construcción”, inactivo?**
- Han pasado 15 días desde su modificación
- Han pasado 20 días desde su modificación
- Han pasado 10 días desde su modificación
- Han pasado 40 días desde su modificación ← CORRECTA

**P12. ¿Quién decide las fechas de las subidas de las calendadas?**
- Los usuarios integradores
- Los líderes de las líneas
- Gobierno de Arquitectura
- Gestión de cambios ← CORRECTA

**P13. ¿Cuánta cobertura debe tener mínimo un servicio para poder subir a producción?**
- 80%
- 70%
- 100%
- 65% ← CORRECTA

**P14. ¿Qué código de HTTP de respuesta se debe utilizar cuando un servicio devuelve un error funcional en servicios de API Catalog?**
- 400 ← CORRECTA
- 204
- 409
- 500

**P15. ¿Cuál de las siguientes afirmaciones es de las exigidas por Sonar?**
- No haya incidencias críticas ni bloqueantes ← CORRECTA
- No haya incidencias críticas, bloqueantes ni mayor
- No haya incidencias críticas ni mayor
- No haya incidencias bloqueantes ni mayor

**P16. ¿Cuál es la anotación para recuperar información del contexto?**
- ServiceInvocationContext ← CORRECTA
- ContextProvider
- ServiceUtilities
- ArqSpringContext

**P17. ¿Cuál sería un nombre correcto como rama del fork?**
- El ticket del grap asociado
- El ticket del jira asociado ← CORRECTA
- Feature/FixDescripciones
- Mi usuario

**P18. Completa la frase. El control de canal valida que…**
- El cliente tiene poder sobre el contrato
- El contrato pertenece al cliente
- El cliente es el titular del contrato
- El cliente puede operar/consultar con ese contrato ← CORRECTA

**P19. ¿En cuál de estos estados es el desarrollador responsable del ticket Jira?**
- En construcción ← CORRECTA
- Validación de Datos
- Validación de Datos Global
- Pendiente de Implantación

**P20. ¿Qué código de Error se corresponde con un error técnico?**
- 500 ← CORRECTA
- 409
- 400
- 404

**P21. ¿Cuándo se desbloquean los Servicios en Integrado (bloqueados por una implantación)?**
- El día de la subida a PRO
- Ya nunca se bloquean ← CORRECTA
- El día de la subida a Piloto
- Cuando se revisa la Calidad

**P22. ¿Qué es el restconnector?**
- Es un conector para conectar con un backend del tipo WebService tipo SOAP
- Es un conector para obtener el recaptcha de Google
- Es un conector para realizar llamadas a KSZB o solicitar cualquier tipo de operativa de cifrado
- Es un conector para la comunicación con cualquier servicio REST desde servicios ASO ← CORRECTA

**P23. ¿En qué ruta debo incluir el cucumber nuevo?**
- Com.bbva.arch.qe.test
- Acceptane ← CORRECTA
- Com.bbva.enax.stores.bdd
- Cucumber/src/main/java/com/bbva/arch/qe/test

**P24. En caso de tener que versionar un servicio, ¿en qué fichero se debe incluir el bean de la nueva versión?**
- Dentro de la anotación @SN(routines=…)
- Se define un xml nuevo que se importa en el business.service xml
- En el business-service.xml ← CORRECTA
- Ninguna de las anteriores

**P25. ¿Cuál es la diferencia entre un ticket de Modificación de SMC y un ticket de Modificación Exprés de servicio?**
- En el ticket de Modificación de SMC hay que modificar el diseño y en el ticket de Modificación Exprés no ← CORRECTA
- En el ticket de Modificación de SMC se solicita el consumo de un servicio y en el ticket de Modificación Exprés no
- En el ticket de Modificación Exprés se solicita el consumo de un servicio y en el ticket de Modificación de SMC no
- En el ticket de Modificación Exprés hay que modificar el diseño y en el ticket de Modificación de SMC no

**P26. ¿Cuál de estas afirmaciones no es correcta?**
- La app de net cash es desatendida
- La app de Contac center es atendida
- La app de oficinas es desatendida ← CORRECTA
- La app de la net es desandida

**P27. ¿Cómo se dan de alta las variables de Arquitectura?**
- indicándolo en el Jira de Gobierno
- Vía Remedy a Gobierno
- Vía Remedy a Arquitectura ← CORRECTA
- Por correo a Arquitectura con copia a Gobierno

**P28. ¿Qué significa CRUD?**
- Conjunto de reglas que hay detrás de los test Cucumber
- Nuevo procedimiento Jira para dar de alta un MSA para un Q determinado
- Funciones básicas en bases de datos o la capa de persistencia en un SW ← CORRECTA
- La nueva uuaa que ha creado Global para los servicios que van a ser implementados en AWS

**P29. ¿Quién tiene que solicitar el consumo de un Servicio?**
- La persona de Gobierno que lleva el ticket
- El responsable de la línea
- El consumidor ← CORRECTA
- El desarrollador

**P30. ¿Qué hay que hacer cuando retrocedo un ticket ASO a “Pendiente Validación Global” por modificación?**
- Añadir las modificaciones en un comentario en el ASO
- Comunicar al API Designer las modificaciones
- Hacer un DFT solo con las modificaciones que aplican
- Indicar las modificaciones con comentarios en DFT original ← CORRECTA

**P31. ¿Cuál es el estado previo al perfilado del servicio?**
- Validación de datos
- Ciberseguridad
- Pendiente de perfilado
- Pendiente de Catalogación ← CORRECTA

**P32. ¿Qué reglas de calidad Sonar deben pasar los servicios para poder implantarse en producción?**
- Que no haya incidencias críticas y se cumpla un mínimo de cobertura ← CORRECTA
- Que no haya incidencias críticas y se cumpla un mínimo de cobertura y se ejecuten todos los test correctamente
- Que se cumpla un mínimo de cobertura
- Que no haya incidencias críticas y se ejecuten todos los test correctamente.

**P33. ¿Para qué sirve el ticket ASO Service Modification de tipo "code"?**
- Para modificar solamente código. Es decir, no afecta al diseño del componente ← CORRECTA
- Modificaciones que afectan al código y al diseño pero no al API
- Modificaciones que afectan al API, al diseño y al código
- Modificaciones que vienen motivadas por una incidencia que ha subido vía ticket express (el de abajo), y que afectan al diseño

**P34. ¿Qué es el conector WSDL?**
- Es un conector para conectar con un backend del tipo WebService tipo SOAP ← CORRECTA
- Es un conector para obtener el recaptcha de Google
- Es un conector para realizar llamadas a KSZB o solicitar cualquier tipo de operativa de cifrado
- Es un conector para la comunicación con cualquier servicio REST desde servicios ASO

**P35. ¿En la consola Ether qué rama se puede desplegar en Integrado?**
- Develop
- Feature
- Bugfix/Hotfix
- Integration ← CORRECTA








## TEST N° 6 -------------------------------------------------------------------------------------------------
**P1. ¿Qué código de HTTP de respuesta se debe utilizar cuando un servicio devuelve un error funcional en servicios de API Catalog?**
- 400 ← CORRECTA
- 204
- 409
- 500

**P2. ¿Para qué sirve el ticket ASO Service Modification de tipo API?**
- Para modificar solamente código. Es decir, no afecta al diseño del componente
- Modificaciones que afectan al código y al diseño, pero no al API
- Modificaciones que afectan al API, al diseño y al código  ← CORRECTA
- Modificaciones que vienen motivadas por una incidencia que se ha subido vía ticket exprés (el de abajo), y afectan al diseño

**P3. ¿Para qué sirve el ticket ASO Service Modification de tipo "Regularization"?**
- Para modificar solamente código. Es decir, no afecta al diseño del componente
- Modificaciones que afectan al código y al diseño, pero no al API
- Modificaciones que afectan al API, al diseño y al código
- Modificaciones que vienen motivadas por una incidencia que se ha subido vía ticket exprés (el de abajo), y que afectan al diseño ← CORRECTA

**P4. ¿Quién tiene que solicitar el consumo de un servicio?**
- La persona de Gobierno que lleva el ticket
- El responsable de la línea
- El consumidor ← CORRECTA
- El desarrollador

**P5. ¿Cuántos escenarios de cucumber como mínimo debe tener un servicio get-detalle?**
- 7
- 6 ← CORRECTA
- 5
- 8

**P6. ¿Sobre qué tipo de datos se realiza el control de canal?**
- Clientes y contratos ← CORRECTA
- Clientes, contratos y datos personales (teléfono, correo electrónico, etc.)
- Cliente y datos personales (teléfono, correo electrónico, etc.)
- Contratos y datos personales (teléfono, correo electrónico etc.)

**P7. ¿Cuáles son los datos sensibles?**
- PAN, CVV, teléfonos, direcciones de e-mail, contraseñas, PIN y OTP ← CORRECTA
- PIN, CVV, Fecha Expiración Tarjeta
- teléfono y mail
- Usuario y contraseña

**P8. ¿Cuándo se desbloquean los Servicios en Integrado (bloqueados por una implantación)?**
- Ya nunca se bloquean ← CORRECTA
- El día de la subida a PRO
- El día de la subida a Piloto
- Cuando se revisa la Calidad

**P9. ¿Cuál de estos es el orden correcto de despliegue de un servicio por entornos?**
- Desarrollo -> Gremio -> Integrado -> AUS -> Piloto -> Producción ← CORRECTA
- Desarrollo -> Integrado -> AUS -> Piloto -> Producción
- Desarrollo -> Integrado -> AUS -> Producción
- Gremio -> Desarrollo -> Integrado -> AUS -> Piloto -> Producción

**P10. (Completa la frase) El control de canal valida que ...**
- el cliente está autorizado para realizar esa consulta u operación ← CORRECTA
- el cliente ya ha realizado alguna vez esa consulta u operación
- el cliente tiene un contrato de consulta u operación
- el cliente es quien dice ser mediante la cámara del teléfono/ordenador

**P11. ¿Qué devuelve un servicio multipaso en el primer paso y se tiene que mandar informado de vuelta en el paso 2?**
- El cuf asociado a la firma del documento ← CORRECTA
- Id de la petición para que el paso uno y dos estén relacionados
- Un body de respuesta
- El código http de error

**P12. ¿Cómo se solicita una variable de Arquitectura?**
- Mediante un Jira
- Mediante un Remedy a Gobierno
- Mediante un remedy a Arquitectura ← CORRECTA
- Con un correo a Gobierno

**P13. ¿Qué indica la anotación @Produces?**
- Indica el formato de salida de los datos ← CORRECTA
- En caso de que el servicio devuelva un documento, indica la ruta donde se ubicará dicho documento
- Indica la salida del servicio
- Informa del swagger de salida del servicio

**P14. ¿Con cuánta antelación debo pedir la integración si no desarrollo ENAX/ERGO?**
- Los días que establezca el calendario de I&D de la UUAA en cuestión ← CORRECTA
- 14 días antes de la implantación
- 7 días antes de la implantación
- Los días que establece el integrador de mi UUAA

**P15. ¿Qué significa CRUD?**
- Funciones básicas en bases de datos o la capa de persistencia en un SW ← CORRECTA
- Conjunto de reglas que hay detrás de los test Cucumber
- Nuevo procedimiento Jira para dar de alta un MSA para un Q determinado
- La nueva uuaa que ha creado Global para los servicios que van a ser implementados en AWS

**P16. ¿Cuál de las siguientes reglas de SONAR para implantar no es de las exigidas para implantar nuestro código?**
- Que al menos funcionen el 65% de los tests ← CORRECTA
- Que la cobertura sea superior a la que había en master
- Que no haya incidencias críticas
- Que no haya incidencias bloqueantes

**P17. Imagina que tienes que implementar un servicio con filtros. ¿Qué componentes situarías en el dao?**
- Clases backend ← CORRECTA
- Clases backend y llamadas al backend
- Clases backend, llamadas al backend y mapper backend
- Clases backend, llamadas al backend, mapper backend y entidades internas

**P18. ¿Cuántos escenarios de cucumber son necesarios en un servicio de tipo post?**
- 7
- 6
- 5
- 8 ← CORRECTA

**P19. ¿Qué código corresponde a un error funcional en implementación local?**
- 400 ← CORRECTA
- 500
- 409
- 204

**P20. En el desarrollo de un servicio multicanal que se comunicará con host, se necesitan dos archivos .java para petición y respuesta de la trx. Dichos ficheros ...**
- Se crean en la capa dao/model se autogenera con la consola de Arquitectura, importando el contexto de la transacción. ← CORRECTA
- En realidad no es necesario que se generen esos ficheros, con importar la transacción es suficiente
- Esos ficheros nunca se deben generar en la capa dao/model, lo prohíbe Arquitectura
- Se crean en la capa dao/model, se deben generar manualmente

**P21. ¿En la consola Ether qué rama se puede desplegar en Integrado?**
- Integration ← CORRECTA
- Develop
- Feature
- Bugfix/Hotfix

**P22. ¿Para qué sirve el ticket ASO Service Modification de tipo "code"?**
- Para modificar solamente código. Es decir, no afecta al diseño del componente ← CORRECTA
- Modificaciones que afectan al código y al diseño pero no al API
- Modificaciones que afectan al API, al diseño y al código
- Modificaciones que vienen motivadas por una incidencia que ha subido vía ticket express (el de abajo), y que afectan al diseño

**P23. ¿Qué es el conector de recaptcha?**
- Es un conector para obtener el recaptcha de Google ← CORRECTA
- Es un conector para conectar con un backend del tipo WebService tipo SOAP
- Es un conector para realizar llamadas a KSBZ o solicitar cualquier tipo de operativa de cifrado
- Es un conector para la comunicación con cualquier servicio REST desde servicios ASO

**P24. ¿Qué es necesario para comenzar a desarrollar servicios ASO en cualquier uuaa/área?**
- Para cualquier uuaa: estar certificado, incluido en el grupo Grass correspondiente y tener permisos Fresno ← CORRECTA
- Solo en el caso de ENAX o ERGO, estar certificado, incluido en el grupo Grass correspondiente y tener permisos Fresno
- Para cualquier uuaa, con estar certificado es suficiente.
- Para cualquier uuaa, estar certificado, incluido en el grupo Grass correspondiente, tener permisos Fresno y tener permisos en ENAX/ERGO.

**P25. ¿Cuándo hay que hacer control de canal en un servicio?**
- Cuando se estén tratando en el servicio clientes o contratos ← CORRECTA
- Solo cuando son servicios de particulares
- Cuando se están tratando en el servicio clientes o contratos en las AAPs atendidas
- Cuando se están tratando en el servicio clientes o contratos en las AAPs desatendidas

**P26. ¿Cuál es la anotación para recuperar información del contexto?**
- ServiceInvocationContext ← CORRECTA
- ContextProvider
- ServiceUtilities
- ArqSpringContext

**P27. ¿Quién decide las fechas de las subidas de las calendadas?**
- Gestión de cambios ← CORRECTA
- Los usuarios integradores
- Los líderes de las líneas
- Gobierno de Arquitectura

**P28. ¿Qué anotación cifra/descifra datos en servicios?**
- @SecurityFunction ← CORRECTA
- @Auditable
- @FunctionSecurity
- @DatoAuditable

**P29. ¿En qué fase se debe documentar un error funcional en un servicio?**
- En su definición ← CORRECTA
- En su construcción
- Durante las pruebas unitarias (JUnits)
- Durante las pruebas integradas

**P30. ¿En qué anotación se incluye el bean del SecurityValidator en la facade de un servicio?**
- @SMC ← CORRECTA
- @Consumes
- @ApiOperation
- @PATH

**P31. ¿Qué tipo de servicio debe llevar paginación?**
- List ← CORRECTA
- Create
- Get
- Modify

**P32. ¿Qué código de HTTP de respuesta se debe utilizar cuando el servicio no devuelve datos?**
- 204 ← CORRECTA
- 200
- 409
- 500

**P33. ¿Qué es el conector WSDL?**
- Es un conector para conectar con un backend del tipo WebService tipo SOAP ← CORRECTA
- Es un conector para obtener el recaptcha de Google
- Es un conector para realizar llamadas a KSZB o solicitar cualquier tipo de operativa de cifrado
- Es un conector para la comunicación con cualquier servicio REST desde servicios ASO

**P34. ¿Qué tipo de pruebas se realiza la noche de la implantación?**
- Pruebas funcionales ← CORRECTA
- Con levantar el WADL vale
- Pruebas técnicas
- Pruebas de los servicios críticos









## TEST N° 7 -------------------------------------------------------------------------------------------------
**P1. ¿Cuál sería un nombre correcto como rama del fork?**
- El ticket GRAP asociado
- El ticket jira asociado ← CORRECTA
- feature/fix Descripciones
- Mi usuario

**P2. ¿En qué casos el responsable del CRQ es el responsable del proyecto?**
- Siempre ← CORRECTA
- Nunca
- Sólo en casos críticos
- Cuando las UUAA no sean ENAX o ERGO

**P3. ¿Qué tipos de tickets Jira existen?**
- Alta Servicio SMC, Modificación SMC, Modificación Exprés de servicios, Eliminación de SMC, Alta Servicio Proxy, Modificación Servicio Proxy y Solicitud de consumo de servicio
- Alta Servicio SMC, Modificación SMC, Modificación Exprés de servicios, Alta Servicio Proxy, Modificación Servicio Proxy
- Alta Servicio SMC, Modificación SMC, Modificación Exprés de servicios, Alta Servicio Proxy, Modificación Servicio Proxy y Solicitud de consumo de servicio ← CORRECTA
- Alta Servicio SMC, Modificación SMC, Modificación Exprés de servicios, Eliminación de SMC y Solicitud de consumo de servicio

**P4. ¿Por qué se considera un ticket, en el estado “In Waiting”, inactivo?**
- Han pasado 15 días desde su modificación
- Han pasado 20 días desde su modificación ← CORRECTA
- Han pasado 10 días desde su modificación
- Han pasado 40 días desde su modificación

**P5. ¿Cuál de estas afirmaciones no es correcta?**
- La aap de net cash es desatendida
- La aap del contact center es atendida
- La aap de oficinas es desatendida ← CORRECTA
- La aap de la net es desatendida

**P6. ¿A qué contextos se puede acceder dentro de los servicios?**
- Al de IMC ← CORRECTA
- Al de Seguridad
- A ambos
- A ninguno

**P7. ¿Qué no se informa nunca en la anotación @SMC?**
- El código asignado por Gobierno al SMC
- Nombre asignado por Gobierno al SMC
- Indica si el servicio es multioperación
- La ruta relativa específica del SMC ← CORRECTA

**P8. ¿Cuál de las siguientes reglas de SONAR para implantar no es de las exigidas para implantar nuestro código?**
- Que la cobertura sea superior a la que había en master
- Que al menos funcionen el 65% de los tests ← CORRECTA
- Que no haya incidencias críticas
- Que no haya incidencias bloqueantes

**P9. ¿En la consola Ether qué rama se puede desplegar en Integrado?**
- Develop
- Feature
- Bugfix/Hotfix
- Integration ← CORRECTA

**P10. ¿Qué es necesario para comenzar a desarrollar servicios ASO en cualquier uuaa/area?**
- Solo en el caso de ENAX o ERGO. estar certificado, incluido en el grupo Grass correspondiente y tener permisos Fresno
- Para cualquier uuaa, con estar certificado es suficiente.
- Para cualquier uuaa: estar certificado, incluido en el grupo Grass correspondiente y tener permisos Fresno ← CORRECTA
- Para cualquier uuaa, estar certificado, incluido en el grupo Grass correspondiente, tener permisos Fresno y tener permisos en ENAX/ERGO.

**P11. ¿Qué no se informa nunca en la anotación @SMC?**
- registryID
- path ← CORRECTA
- securityValidator
- logicalID

**P12. ¿Qué código de respuesta devuelve un servicio de creación cuando ha funcionado correctamente?**
- 400
- 201 ← CORRECTA
- 409
- 204

**P13. ¿Sobre qué tipo de datos se realiza el control de canal?**
- Clientes y contratos ← CORRECTA
- Clientes, contratos y datos personales (teléfono, correo electrónico, etc.)
- Cliente y datos personales (teléfono, correo electrónico, etc.)
- Contratos y datos personales (teléfono, correo electrónico etc.)

**P14. ¿Para qué sirve el ticket ASO Service Modification de tipo Design?**
- Para modificar solamente código. Es decir, no afecta al diseño el componente
- Modificaciones que afectan al código y al diseño, pero no al API
- Modificaciones que afectan al API, al diseño y al código ← CORRECTA
- Modificaciones que vienen motivadas por una incidencia que se ha subido vía ticket exprés (el de abajo), y afectan al diseño

**P15. En el caso de que un servicio pase de mono a multioperación ¿cuáles son los pasos a seguir?**
- Deberá subir primero el servicio y después la catalogación ya que si no fallará el servicio ← CORRECTA
- Deberá subir primero la catalogación y después el servicio ya que si no fallará el servicio
- Habría que hacer un versionado del Servicio
- Es independiente que sube primero ya que no tiene impacto en el Servicio

**P16. ¿Para qué sirve el ticket ASO Service Modification de tipo “Metadata”?**
- Para modificar solamente código. Es decir, no afecta al diseño el componente
- Modificaciones que afectan al código y al diseño, pero no al API ← CORRECTA
- Modificaciones que afectan al API, al diseño y al código
- Modificaciones que vienen motivadas por una incidencia que se ha subida vía ticket exprés (el de abajo) y que afectan al diseño

**P17. ¿Qué tipo de pruebas se realiza la noche de la implantación?**
- Con levantar el wadl vale
- Pruebas técnicas
- Pruebas funcionales ← CORRECTA
- Pruebas de los servicios críticos

**P18. ¿Qué herramienta mide la calidad del código?**
- Cucumber
- Sonar ← CORRECTA
- Samuel
- Jacoco

**P19. ¿Cuáles son todos los datos sensibles?**
- PAN, CVV, Fecha de expiración de tarjeta, Teléfonos, CustomerId, Direcciones de e-mail, Contraseñas y PIN
- PAN, CVV, teléfonos, direcciones de e-mail, contraseñas, PIN y OTP. ← CORRECTA
- PAN, CVV, Fecha de expiración de tarjeta, Nombre del titular de la tarjeta, Teléfonos, Direcciones de e-mail, Contraseñas y OTP
- PAN, Fecha de expiración de tarjeta, Nombre del titular de la tarjeta, Teléfonos, Direcciones de e-mail, Contraseñas y OTP PIN

**P20. ¿De qué tipo pueden ser las AAPs?**
- Particulares y oficinas
- Empresas y oficinas
- Oficinas y desatendidas ← CORRECTA
- Particulares y empresas

**P21. ¿Cuáles no son los datos sensibles?**
- PAN, CVV,
- Teléfono y dirección de e-mail
- Usuario y Fecha de expiración de tarjeta ← CORRECTA
- Pin y OTP

**P22. ¿Cuándo se debe solicitar la implantación de un proxy en Producción?**
- 15 días antes de la implantación en Producción
- 7 días antes de la implantación en Producción ← CORRECTA
- 2 días antes de la implantación en Producción
- El día de antes de la implantación en Producción

**P23. ¿Qué anotación cifrado/descifrado de datos en servicios?**
- @Auditable
- @SecurityFunction ← CORRECTA
- @FunctionSecurity
- @DatoAuditable

**P24. ¿Qué indica la anotación @Produces?**
- Indica el formato de salida de los datos ← CORRECTA
- En caso de que el servicio devuelva un documento, indica la ruta donde se ubicará dicho documento.
- Indica la salida del servicio
- Informa del swagger de salida del servicio

**P25. ¿A quién tengo que poner como responsable de mi CRQ para la subida?**
- A mí mismo
- A Mariano de la Escalera como responsable de Servicios Multicanal
- Al responsable de mi línea ← CORRECTA
- A Integración y Despliegue

**P26. ¿Qué código http devuelve un servicio cuando devuelve un error de petición?**
- 400 ← CORRECTA
- 409
- 412
- 500

**P27. ¿Quién tiene que solicitar el consumo de un servicio?**
- La persona de Gobierno que lleve el ticket
- El responsable de la línea
- El consumidor ← CORRECTA
- El desarrollador

**P28. ¿Quién es el encargado de realizar la subida de un componente a master?**
- El equipo de Integración y Despliegue
- El integrador de la UUAA ← CORRECTA
- El desarrollador mediante un mergeo a Master
- El desarrollador mediante una pull request a master

**P29. ¿Cuándo se considera un ticket, en el estado “Designing Service”, inactivo?**
- Han pasado 15 días desde su modificación
- Han pasado 20 días desde su modificación ← CORRECTA
- Han pasado 10 días desde su modificación
- Han pasado 40 días desde su modificación

**P30. ¿Qué significa CRUD?**
- Conjunto de reglas que hay detrás de los test Cucumber
- Nuevo procedimiento Jira para dar de alta un MSA para un Q determinado
- Funciones básicas en bases de datos o la capa de persistencia en un SW ← CORRECTA
- La nueva uuaa que ha creado Global para los servicios que van a ser implementados en AWS

**P31. En el proceso de solicitar la subida a producción de nuestro servicio, se encuentran las pruebas de rendimiento de OCTA. ¿Cómo se solicitan?**
- Mandando un mail a OCTA
- Abriendo un jira a OCTA
- Abriendo un remedy a OCTA
- Rellenando un formulario de OCTA ← CORRECTA

**P32. ¿En qué fase se debe documentar un error funcional en un servicio?**
- En su definición ← CORRECTA
- En su construcción
- Durante las pruebas unitarias (JUnits)
- Durante las pruebas integradas








## TEST N° 8 -------------------------------------------------------------------------------------------------
**P1. ¿En qué ruta debo incluir el cucumber nuevo?**
- Com.bbva.arch.qe.test
- Acceptane ← CORRECTA
- Com.bbva.enax.stores.bdd
- Cucumber/src/main/java/com/bbva/arch/qe/test

**P2. ¿Cuál de estas afirmaciones no es correcta?**
- La aap de net cash es desatendida
- La aap del contact center es atendida
- La aap de oficinas es desatendida ← CORRECTA
- La aap de la net es desatendida

**P3. ¿Cuándo hay que hacer control de canal en un servicio?**
- Cuando se estén tratando en el servicio clientes o contratos ← CORRECTA
- Solo cuando son servicios de particulares
- Cuando se están tratando en el servicio clientes o contratos en las AAPs atendidas
- Cuando se están tratando en el servicio clientes o contratos en las AAPs desatendidas

**P4. ¿Cuál sería la anotación correcta de la operación 1 de un servicio multioperativo?**
- SMC201700241OP001 ← CORRECTA
- SMC201700241OP01
- SMC201700241OP1
- SMC201700241P01

**P5. ¿Cuándo un servicio devuelve 500?**
- Cuando la entrada no es válida
- Cuando falla la invocación al back ← CORRECTA
- Cuando falla el mapeo a la salida
- Nunca

**P6. ¿Cómo se solicita el consumo de un servicio a SEP de un servicio en construcción?**
- A través de Jira "Solicitud Consumo" ← CORRECTA
- Vía correo a SEP
- No hace falta si está incluido en la Hoja ASO cuando se valida
- Vía correo a Gobierno de Arquitectura

**P7. ¿Qué código de http de respuesta se debe utilizar cuando un servicio devuelve un error funcional en servicios de API Catalog?**
- 400 ← CORRECTA
- 204
- 409
- 500

**P8. En el caso de que un servicio pase de mono a multioperación ¿cuáles son los pasos a seguir?**
- Deberá subir primero el servicio y después la catalogación ya que si no fallará el servicio ← CORRECTA
- Deberá subir primero la catalogación y después el servicio ya que si no fallará el servicio
- Habría que hacer un versionado del Servicio
- Es independiente que sube primero ya que no tiene impacto en el Servicio

**P9. ¿Cuál sería un nombre correcto de un fork?**
- El ticket GRAP asociado
- El ticket jira asociado
- [username]-repositorio ← CORRECTA
- Cualquier nombre

**P10. ¿A quién tengo que poner como responsable de mi CRQ para la subida?**
- A mí mismo
- A Mariano de la Escalera como responsable de Servicios Multicanal
- Al responsable de mi línea ← CORRECTA
- A Integración y Despliegue

**P11. En el proceso de solicitar la subida a producción de nuestro servicio, se encuentran las pruebas de rendimiento de OCTA. ¿Cómo se solicitan?**
- Mandando un mail a OCTA
- Abriendo un jira a OCTA
- Abriendo un remedy a OCTA
- Rellenando un formulario de OCTA ← CORRECTA

**P12. ¿Se debe acceder al contexto del servicio para tomar decisiones en función de la APP?**
- No ← CORRECTA
- Si,siempre
- Si, en el caso de que el consumidor lo requiera
- No, salvo que sea estrictamente necesario

**P13. ¿Qué no se informa nunca en la anotación @SMC?**
- El código asignado por Gobierno al SMC
- Nombre asignado por Gobierno al SMC
- Indica si el servicio es mutioperación
- La ruta relativa específica del SMC ← CORRECTA

**P14. ¿Cuál es el timeout por defecto de los servicios ASO?**
- 10000 ms
- 12000 ms ← CORRECTA
- 20000 ms
- 22000 ms

**P15. Completa la frase. El control de canal valida que…**
- El cliente tiene poder sobre el contrato
- El contrato pertenece al cliente
- El cliente es el titular del contrato
- El cliente puede operar/consultar con ese contrato ← CORRECTA

**P16. ¿Qué anotación ofusca en trazas los datos sensibles?**
- @DatoAuditable ← CORRECTA
- @DataOfuscate
- @Traces
- @SMC

**P17. ¿Por qué se considera un ticket en estado “En Construcción”, inactivo?**
- Han pasado 15 días desde su modificación
- Han pasado 20 días desde su modificación
- Han pasado 10 días desde su modificación
- Han pasado 40 días desde su modificación ← CORRECTA

**P18. Tengo un servicio... ¿qué anotación ASO debo usar si además quiero asegurar el control del canal sobre dicho contrato?**
- @DatoAuditable
- @Format
- @GenerateldOP ← CORRECTA
- @SecurityFunction

**P19. ¿Cómo se dan de alta las variables de Arquitectura?**
- Indicándolo en el jira de Gobierno
- Vía remedy a Gobierno
- Vía remedy a Arquitectura ← CORRECTA
- Por correo a Arquitectura con copia a Gobierno

**P20. ¿Cuánta cobertura debe tener mínimo un servicio para poder subir a producción?**
- 80%
- 70%
- 100%
- 65% ← CORRECTA

**P21. ¿En qué estado del JIRA tiene que estar el ticket mientras prueba el consumidor?**
- En Edición de Datos.
- En construcción ← CORRECTA
- En calidad
- En verificación de repositorio

**P22. ¿Cuándo se desbloquean los Servicios en Integrado (bloqueados por una implantación)?**
- El día de la subida a PRO
- Ya nunca se bloquean ← CORRECTA
- El día de la subida a Piloto
- Cuando se revisa la Calidad

**P23. ¿Qué hace el getUserContractsIDs?**
- Es el control de canal de particulares, recupera los contratos de un usuario.
- Es el control de canal de particulares, obtiene los contratos de un usuario para un CIF determinado,
- Es el control de canal de empresas, recupera los contratos de un usuario.
- Es el control de canal de empresas, obtiene los contratos de un usuario para un CIF determinado. ← CORRECTA

**P24. ¿Cuál es el parámetro que se debe añadir en la anotación @SMC de un servicio que le aplica realizar validaciones de seguridad en el preproceso?**
- securityValidator ← CORRECTA
- securityFunction
- securityMethod
- securityClass

**P25. ¿Qué hay que hacer cuando retrocedo un ticket ASO a “Pendiente Validación Global” por modificación?**
- Añadir las modificaciones en un comentario en el ASO
- Comunicar al API Designer las modificaciones
- Hacer un DFT solo con las modificaciones que aplican
- Indicar las modificaciones con comentarios en DFT original ← CORRECTA

**P26. ¿Qué es necesario para comenzar a desarrollar servicios ASO en cualquier uuaa/area?**
- Solo en el caso de ENAX o ERGO. estar certificado, incluido en el grupo Grass correspondiente y tener permisos Fresno
- Para cualquier uuaa, con estar certificado es suficiente.
- Para cualquier uuaa: estar certificado, incluido en el grupo Grass correspondiente y tener permisos Fresno ← CORRECTA
- Para cualquier uuaa, estar certificado, incluido en el grupo Grass correspondiente, tener permisos Fresno y tener permisos en ENAX/ERGO.

**P27. ¿Cuáles son los datos sensibles?**
- PAN, CVV, teléfonos, direcciones de e-mail, contraseñas, PIN y OTP. ← CORRECTA
- PAN, CVV, Fecha de nacimiento, teléfonos, direcciones de e-mail, contraseñas, PIN y OTP
- PAN, CVV, ID del usuario, contraseñas y PIN
- PAN, CVV, Fecha de expiración de tarjeta, teléfonos y OTP

**P28. ¿Cuál es la anotación que se utiliza para indicar la versión del servicio de negocio?**
- VS
- V
- VE
- VN ← CORRECTA

**P29. ¿Cuál de estos es el orden correcto de despliegue de un servicio por entornos?**
- Desarrollo -> Gremio -> Integrado -> AUS -> Piloto -> Producción ← CORRECTA
- Desarrollo -> Integrado -> AUS -> Piloto -> Producción
- Desarrollo -> Integrado -> AUS -> Producción
- Gremio -> Desarrollo -> Integrado -> AUS -> Piloto -> Producción

**P30. ¿Qué NO es un proceso global de modificación de servicios ASO?**
- Modificar un SMC existente con afectación a código
- Modificar un SMC existente con afectación al API
- Modificar un SMC existente con afectación a Metadatos
- Modificar un SMC existente con afectación a alertas ← CORRECTA

**P31. ¿En qué anotación se incluye el bean del SecurityValidator en la facade de un servicio?**
- @Consumes
- @ApiOperation
- @SMC ← CORRECTA
- @PATH

**P32. ¿Con cuánta antelación debo pedir la integración si no desarrollo ENAX/ERGO?**
- 14 días antes de la implantación
- 7 días antes de la implantación
- Los días que establezca el calendario de I&D de la UUAA en cuestión ← CORRECTA
- Los días que establece el integrador de mi UUAA








## TEST N° 9 -------------------------------------------------------------------------------------------------
**P1. ¿Cuántos features tiene que tener nuestro cucumber si el servicio es un PATCH?**
- 4
- 5 ← CORRECTA
- 6
- 7

**P2. De los siguientes apartados, ¿Cuál indica una documentación que no es exigida por Gestión de Cambios?**
- Informe de OCTA
- Visto bueno del líder técnico
- Pruebas a realizar la noche de la implantación
- Cucumber de las pruebas realizadas ← CORRECTA

**P3. ¿Puedo modificar el código generado automáticamente?**
- Si, pero solo la facade
- Las clases de la facade No se debe modificar por parte del desarrollador
- Las clases de la Bussines No se debe modificar por parte del desarrollador
- paquete de la facade NO se deben modificar por parte del desarrollador, ni tampoco el fichero generado service-schema.json ← CORRECTA

**P4. ¿A qué entorno es preferible subir la rama feature?**
- Integrado
- Desarrollo
- Producción
- Gremio ← CORRECTA

**P5. ¿Cuál de estas afirmaciones sobre cucumber es falsa?**
- Es exigido por Gestión de Cambios para dar el ok al CRQ
- Es requisito para producción
- Comprueba contra entornos previos el correcto funcionamiento de los servicios
- Sirve para validar que el servicio funciona, pero no admite códigos de error de tipo 400 ← CORRECTA

**P6. ¿Puedo realizar un DFT para más de un ticket JIRA?**
- No, nunca
- Siempre y cuando los métodos correspondan al mismo recurso ← CORRECTA
- Sí, siempre
- Siempre y cuando los métodos No correspondan al mismo recurso

**P7. ¿Para qué se abre un ticket de modificación de SMC?**
- Cuando se realiza una modificación sobre un servicio que ya está en producción y que dicha modificación supone un cambio de interfaz o de backend ← CORRECTA
- Cuando haya que realizar una modificación en el servicio haya o no que tocar la hoja ASO
- Cuando se quiere modificar un servicio que aún se está construyendo
- Cuando se quiere añadir en la hoja ASO un nuevo consumidor, pero no se requiere modificar el servicio

**P8. ¿Qué tipo de IMC indica que la AAP es para NO clientes y personas Jurídicas?**
- INDIVIDUAL
- COMMERCIAL
- PROSPECT
- PROSPECTCOMMERCIAL ← CORRECTA

**P9. ¿Cuándo se actualiza la versión del API?**
- Cuando añadas un cambio
- Nunca se actualiza
- Nunca, se actualiza automáticamente ← CORRECTA
- Ninguna de las anteriores

**P10. ¿Por qué se considera un ticket en estado “Revisión de calidad”, inactivo?**
- Han pasado 15 días desde su modificación
- Han pasado 20 días desde su modificación
- Han pasado 10 días desde su modificación ← CORRECTA
- Han pasado 40 días desde su modificación

**P11. ¿Cuál de los siguientes son Roles de un cliente a la salida de un granting ticket?**
- Operativo, pre-operativo, pre activado ← CORRECTA
- No operativo, operativo, caducado
- Operativo, caducado, fallo
- Bloqueado, consulta, completa

**P12. ¿Qué es el CAS?**
- Asegurar que el cliente solo opera con contratos propios o con los que tiene permisos ← CORRECTA
- Son siglas de ASO en castellano
- No existe nada denominado así
- También se lo conoce como IMC

**P13. ¿Debo incluir las anotaciones de seguridad en el código de forma manual?**
- Sí, si no lo has definido en el RAML
- No, se incluyen de forma automática en la generación del scaffolding siempre que se hayan agregado correctamente en la API al construir el RAML ← CORRECTA
- No, hay que solicitarlo mediante Remedy a arquitectura
- Ninguna es correcta

**P14. ¿Cuándo un servicio debe llevar Alarmado?**
- No es necesario llevar alarmado
- Si se trata de un alta o una modificación con versionado ← CORRECTA
- Si se trata de un alta o una modificación
- Solo si es un Alta

**P15. ¿Quién es el encargado de realizar la subida de un componente a master?**
- El equipo de Integración y Despliegue ← CORRECTA
- El integrador de la UUAA
- El desarrollador mediante un mergeo a master
- El desarrollador mediante una pull request a master

**P16. ¿Cuál es el timeout por defecto de los servicios ASO?**
- 12000 ms ← CORRECTA
- 22000 ms
- 10000 ms
- 20000 ms

**P17. ¿A qué conector corresponde la definición “Sustituye al RestConnector para cuando se quieran hacer llamadas a KSZB o solicitar cualquier tipo de operativa de cifrado”?**
- RestConnector
- APIConnector
- Conector generado con WSDL
- CryptoConnector ← CORRECTA

**P18. ¿A qué conector corresponde la definición “comunica con cualquier servicio REST desde servicios ASO”?**
- RestConnector ← CORRECTA
- APIConnector
- Conector generado con WSDL
- Ninguna de las anteriores

**P19. ¿Qué tipo de IMC indica que la AAP es para NO clientes y personas físicas?**
- INDIVIDUAL
- COMMERCIAL
- PROSPECT ← CORRECTA
- PROSPECTCOMMERCIAL

**P20. ¿Qué 3 cosas hace un servicio ASO?**
- Validar entrada, invocar back, mapear salida ← CORRECTA
- Invocar back, validar salida, mapear salida
- Invocar back, generar errores, mapear salida
- Invocar back, mapear salida, generar errores

**P21. ¿Qué ramas debo subir a los entornos de desarrollo e integrado?**
- feature
- Cualquier rama
- Rama de integración ← CORRECTA
- Hotfix

**P22. ¿Qué código devuelve un error de petición?**
- 409
- 400 ← CORRECTA
- 500
- No hay errores de petición

**P23. ¿Cuál sería un nombre correcto como rama del fork?**
- El ticket del GRAP asociado
- El ticket del JIRA asociado ← CORRECTA
- Feature/FixDescripciones
- Mi usuario

**P24. ¿Qué tipo de IMC indica que la AAP es para clientes y para personas físicas?**
- INDIVIDUAL ← CORRECTA
- COMMERCIAL
- PROSPECT
- PROSPECTCOMMERCIAL

**P25. ¿Cuántos features tiene que tener nuestro cucumber si el servicio es un DELETE?**
- 8
- 6
- 5 ← CORRECTA
- 4

**P26. ¿Qué tipo de IMC indica que la AAP es para clientes y para personas Jurídicas?**
- INDIVIDUAL
- COMMERCIAL ← CORRECTA
- PROSPECT
- PROSPECTCOMMERCIAL

**P27. ¿Cuándo se debe pasar OCTA?**
- Cuando, tras rellenar el formulario, OCTA nos lo indique ← CORRECTA
- Cuando, tras enviarles un correo electrónico, OCTA nos lo indique
- Cuando la transacción no pase OCTA
- Cuando Integración y Despliegue nos indiquen que debe pasarlo

**P28. ¿Cuándo se usan las validaciones CAS e IMC?**
- En servicios local - local
- En servicios global - multilocal
- En todos los tipos de servicio, desde local-local hasta global-multilocal ← CORRECTA
- No es necesario usar estas validaciones

**P29. ¿Cuál es el plugin utilizado para importar contextos a nuestro servicio ASO?**
- Roo
- Kermit ← CORRECTA
- hamcrest
- Los servicios ASO no llevan transacciones

**P30. ¿Debo realizar un fork y una rama para la construcción del RAML?**
- No, solo una rama Feature
- Sí, pero no hace falta crear la rama
- Sí, es el procedimiento correcto ← CORRECTA
- No se hace así

**P31. ¿Cuál es el estado de infraestructura multicanal correspondiente a 06?**
- Firma Básica ← CORRECTA
- Firma Avanzada
- BBVA Alto
- Delegado

**P32. En caso de tener que versionar un servicio, ¿en qué fichero se debe incluir el bean de la nueva versión?**
- En el business-service.xml ← CORRECTA
- Se define un xml nuevo que se importa en el business-service.xml
- Ninguna de las anteriores
- Dentro de la anotación @SN(routines=…)

**P33. ¿Qué tipos de control de canal tenemos?**
- Atendidas y desatendidas
- Particulares y empresa ← CORRECTA
- Total y parcial
- Ninguna de las anteriores
