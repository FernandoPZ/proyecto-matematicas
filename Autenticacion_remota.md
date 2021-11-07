# Mecanismos de autenticación remota

* Autenticación ligera de terceros

  LTPA (Lightweight Third Party Authentication) está pensado para entornos de máquina y servidor de aplicaciones distribuidos, múltiples. LTPA da soporte a credenciales reenviables y al inicio de sesión único (SSO). LTPA puede dar soporte a la seguridad en un entorno distribuido a través de la criptografía. Este soporte permite a LTPA cifrar, firmar digitalmente y transmitir de forma segura datos relacionados con la autenticación, y posteriormente descifrar y verificar la firma.

* Configuración de LTPA (Lightweight Third Party Authentication) y trabajar con claves

  Debe configurar LTPA (Lightweight Third Party Authentication) cuando configure la seguridad por primera vez. LTPA es el mecanismo de autenticación predeterminado para WebSphere Application Server. Después de haber configurado LTPA, puede generar claves LTPA de forma manual o automática.

* Soporte del mecanismo de autenticación Kerberos (KRB5) para la seguridad

  El mecanismo de autenticación Kerberos permite la interoperatividad con otras aplicaciones (como .NET, DB2 y otras) que dan soporte a la autenticación Kerberos. Proporciona soluciones interoperables de inicio de sesión único (SSO) y conserva la identidad de solicitante original.

* Configuración de Kerberos como mecanismo de autenticación para WebSphere Application Server

  Debe realizar los pasos para configurar Kerberos como mecanismo de autenticación para WebSphere Application Server.

* Mecanismo de autenticación de señales RSA

  El mecanismo de autenticación RSA (Rivest Shamir Adleman) se utiliza para simplificar el entorno de seguridad para la topología de gestión flexible. Da soporte a la capacidad de registrar de forma segura y sencilla nuevos servidores en la topología de Gestión flexible. Con la topología de Gestión flexible, puede enviar y gestionar trabajos administrativos, de forma local o remota, utilizando un gestor de trabajos que gestiona aplicaciones, realiza el mantenimiento del producto, modifica las configuraciones y controla el tiempo de ejecución del servidor de aplicaciones. El mecanismo de autenticación RSA sólo se utiliza para la autenticación administrativa de servidor a servidor, como por ejemplo el conector de administración y las solicitudes de transferencia de archivos. El mecanismo de autenticación RSA no sustituye a LTPA o Kerboros para que los utilicen las aplicaciones.

* Configuración del mecanismo de autenticación de señales RSA

  Utilice la consola administrativa de WebSphere Application Server para configurar el mecanismo de autenticación de señal RSA (Rivest Shamir Adleman). El mecanismo de autenticación de señal RSA sólo se puede utilizar para solicitudes administrativas. Como tal, las opciones del mecanismo de autenticación para la autenticación administrativa forman parte del panel Seguridad global de la consola administrativa.

* Mecanismo de autenticación simple de WebSphere (en desuso)
  
  SWAM (Simple WebSphere Authentication mechanism) define reglas sobre información de seguridad y el formato de cómo se almacena la información de seguridad en credenciales y señales. SWAM está pensado para entornos de ejecución simples, no distribuidos y de un único servidor de aplicaciones.

* Autenticación de capa de mensajes

  Define la información de credenciales y envía esa información a través de la red para que un servidor receptor pueda interpretarla.
