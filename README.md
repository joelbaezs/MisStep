MisStep v2.2
Descripción

MisStep es una herramienta de laboratorio diseñada para emular un punto de acceso falso (Fake AP) con fines educativos y de investigación. Permite configurar un entorno controlado para simular diferentes tipos de accesos inalámbricos y capturar interacciones de dispositivos en la red. El uso del script debe ser exclusivamente ético y bajo los límites de la ley.
Características

    Configuración automática de servicios necesarios como dnsmasq y hostapd.
    Validación y personalización de direcciones IP para el punto de acceso.
    Selección de plantillas predefinidas para simular portales de inicio de sesión.
    Módulos de validación de dependencias y recuperación del sistema en caso de interrupción.
    Limpieza automática de recursos temporales al finalizar o interrumpir el script.

Requisitos del sistema

    Distribución Linux basada en Debian (como Ubuntu o Kali Linux).
    Acceso root para ejecutar el script.
    Dependencias necesarias:
        php
        dnsmasq
        hostapd
        airmon-ng
        ifconfig
        iwconfig

Instalación

    Clona el repositorio o descarga el script:

git clone https://github.com/joelbaezs/misstep.git
cd misstep

Haz el script ejecutable:

    chmod +x misstep.sh

Uso

    Ejecuta el script como root:

    sudo ./misstep.sh -m terminal

    Sigue las instrucciones interactivas para:
        Configurar la red y los rangos de direcciones IP.
        Seleccionar la plantilla deseada.
        Iniciar el punto de acceso falso.

    Para interrumpir el script, presiona Ctrl + C. El sistema limpiará los recursos automáticamente.

Advertencia

Este script es únicamente para fines educativos y pruebas en laboratorios controlados. El uso indebido de esta herramienta puede violar leyes locales o internacionales. Asegúrate de tener los permisos necesarios antes de usarlo.
Contribución

Si deseas contribuir con mejoras o reportar problemas, crea un issue o realiza un pull request en el repositorio oficial.
Licencia

Este proyecto está licenciado bajo Licencia MIT.
