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
