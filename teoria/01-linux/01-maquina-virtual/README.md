# Maquina Virtual GNU/Linux

## Introducción

GNU/Linux es un sistema operativo FOSS (Free and Open Source Software) que se basa en el núcleo Linux y en el sistema GNU. Un sistema muy poderoso pues nos permite observar como cada uno de los componentes del sistema se comporta sin ninguna restricción. Gracias a esto, podemos aprender y entender como funciona un sistema operativo, administrarlo y por que no, incluso romperlo.

## Instrucciones

A lo largo de esta capacitación necesitamos contar con una plataforma de trabajo. Para ello utilizaremos una máquina virtual con GNU/Linux. En este caso utilizaremos la distribución **Debian**. Esto para que todos puedan contar con la misma plataforma de trabajo, si desean ocupar otra distribución pueden hacerlo, pero no se garantiza que los pasos o las soluciones sean las mismas.

Debemos empezar a configurar los sistemas sin interfaz gráfica, en el mundo real los servidores no cuentan con una interfaz gráfica y debemos estar preparados para ello.

### Requisitos

- Utilizar como virtualizador **virt-manager** (KVM/QEMU).
- Utilizar la imagen netinstall de la última versión de Debian.
- La máquina virtual debe tener al menos 4GB de RAM y 40GB de disco duro.
- El almacenamiento virtual debe ser del tipo **qcow2**.
- La máquina debe estar configurada para utilizar **NAT** como red virtual, se debe poder acceder a internet desde la máquina virtual y a la máquina virtual desde el host.

## Archivos de entrega

- Captura de pantalla de la máquina virtual funcionando dentro del virt-manager.
- Captura de una conexión por ssh ejecutando el comando `uname -a`.

## Material de lectura

- [Debian](https://www.debian.org/)
- [KVM](https://www.linux-kvm.org/)
- [virt-manager](https://virt-manager.org/)
