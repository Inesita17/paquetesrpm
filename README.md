# Paquetes RPM

Los paquetes RPM (Red Hat Package Manager) destacan como un formato de empaquetado de software empleado principalmente en distribuciones de Linux basadas en Red Hat, como Fedora y CentOS. Estos paquetes incorporan archivos binarios, scripts de instalación y metadatos esenciales para realizar la instalación, actualización o desinstalación de software en sistemas Linux.

## Rasgos Distintivos

- **Organización:** Un paquete RPM se estructura de forma ordenada, siguiendo una jerarquía de directorios predefinida que abarca carpetas destinadas a binarios, bibliotecas, documentos y más.

- **Relaciones de Dependencia:** Los paquetes RPM pueden especificar dependencias, asegurando que las bibliotecas y componentes necesarios estén presentes antes de permitir la instalación de un paquete.

- **Scripts Dinámicos:** Incluyen scripts de preinstalación, postinstalación, preremoval y postremoval, posibilitando la ejecución de acciones específicas antes o después de la instalación o desinstalación del paquete.

- **Checksums:** Cada paquete RPM posee un control de integridad basado en suma de verificación (checksum) para verificar la autenticidad de los archivos.

## Administración con Herramientas RPM

La gestión de paquetes RPM se lleva a cabo comúnmente mediante herramientas como `rpm` y `yum` (o `dnf`). Algunas operaciones habituales incluyen:

- `rpm -i paquete.rpm`: Instala un paquete RPM.
- `rpm -e nombre_paquete`: Desinstala un paquete RPM.
- `rpm -q nombre_paquete`: Verifica si un paquete está instalado.
- `yum install nombre_paquete`: Instala automáticamente un paquete y sus dependencias.







# Características de Rocky Linux


Rocky Linux es una distribución Linux centrada en la estabilidad y la compatibilidad binaria, diseñada como sucesora espiritual de CentOS. Algunas de sus características notables son:

- **Compatibilidad CentOS:**
  - Rocky Linux nace como respuesta a los cambios en la estrategia de CentOS. Busca ofrecer una transición suave para los usuarios de CentOS, proporcionando una plataforma compatible con el ecosistema de Red Hat Enterprise Linux (RHEL).

- **Enfoque en la Estabilidad:**
  - La estabilidad es un pilar fundamental. Rocky Linux está diseñado para ser una opción confiable, especialmente en entornos empresariales y de producción que requieren consistencia y predictibilidad.

- **Licencia de Código Abierto:**
  - Al adoptar una licencia de código abierto, Rocky Linux promueve la libertad de distribuir, modificar y mejorar el sistema. Esto fomenta la colaboración y permite que la comunidad participe en el desarrollo y mejora continua.

- **Comunidad Activa:**
  - Rocky Linux se beneficia de la participación activa de la comunidad de usuarios y desarrolladores. El desarrollo abierto permite a la comunidad aportar ideas, solucionar problemas y contribuir al crecimiento y evolución del sistema.

- **Documentación y Recursos Comunitarios:**
  - Proporciona una documentación completa y recursos comunitarios para facilitar la implementación y administración del sistema. Esto incluye guías, tutoriales y foros donde la comunidad puede compartir conocimientos y experiencias.

- **Herramientas de Gestión de Paquetes:**
  - Hereda el sistema de gestión de paquetes de CentOS, lo que facilita la administración del software. Los usuarios pueden utilizar las herramientas familiares para instalar, actualizar y gestionar paquetes en sus sistemas.

- **Actualizaciones y Parches:**
  - Garantiza la entrega oportuna de actualizaciones y parches de seguridad para abordar vulnerabilidades conocidas y mantener el sistema protegido contra amenazas potenciales.

- **Seguridad:**
  - Pone un énfasis significativo en la seguridad, implementando prácticas recomendadas y medidas para proteger el sistema contra amenazas cibernéticas. Esto incluye la participación en programas de divulgación de vulnerabilidades y la colaboración con la comunidad de seguridad.
