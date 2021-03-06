Turpial
=======

**Sumario:** Cliente Twitter escrito en Python. Ligero, funcional e integrado
al escritorio del usuario

*Turpial* es un cliente alternativo para la red *Twitter* con multiples
interfaces. Esta escrito en *Python* y tiene como meta ser una aplicacion con
bajo consumo de recursos y que se integre al escritorio del usuario pero sin
renunciar a ninguna funcionalidad.

Actualmente *Turpial* se encuentra en estado de desarrollo, por lo que 
pueden presentarse errores y fallos inesperados. Es por esto que se invita a
los usuarios que detecten algun fallo lo reporten en la siguiente direccion: 

http://code.google.com/p/turpial/issues/list

*Turpial*, las imagenes y los sonidos han sido publicados bajo una licencia 
*GPL v3*. Vea el archivo ``COPYING`` para mas detalles o visite 
http://www.gnu.org/licenses/gpl-3.0.html

Requisitos
----------

Turpial necesita los siguientes paquetes para funcionar correctamente:

 * ``python >= 2.5``
 * ``python-simplejson >= 1.9.2``
 * ``python-gtk2 >= 2.12``
 * ``python-notify >= 0.1.1``
 * ``python-pygame >= 1.7``
 * ``python-pybabel >= 0.9.1``
 * ``python-gtkspell >= 2.25.3``
  
Una instalacion estandar de *Python* (como la que viene en la mayoria de las
distribuciones GNU/Linux) es mas que suficiente. El resto de los modulos se 
pueden instalar en las distribuciones basadas en Debian con el siguiente 
comando (como superusuario)::

    # aptitude install python-simplejson \
                       python-gtk2 \
                       python-notify \
                       python-pygame \
                       python-pybabel \
                       python-gtkspell

o si dispone de ``sudo``::

    $ sudo aptitude install python-simplejson \
                            python-gtk2 \
                            python-notify \
                            python-pygame \
                            python-pybabel \
                            python-gtkspell

Instalacion
-----------

El proceso de instalacion de la aplicacion puede hacerlo de la siguiente
manera (como superusuario)::

    # python setup.py install

o si dispone de ``sudo``::

    $ sudo python setup.py install

Ejecutar
--------

Si desea ejecutar la aplicacion solo debe escribir el comando ``turpial``::

    $ turpial [OPCIONES]

Por defecto, Turpial carga la interfaz ``gtk`` pero se pueden especificar los 
siguientes parametros opcionales:

 * ``-d``: ejecuta Turpial en Modo Depuracion. 
 * ``-i interfaz``: para seleccionar la interfaz a cargar (``gtk`` | ``cmd``).

Si usted cumple con los requisitos para ejecutar *Turpial* pero no cuenta
con los permisos necesarios para instalarlo, puede ejecutar los siguientes
pasos desde el directorio ``Turpial``::

    $ export PYTHONPATH=$PWD
    $ python turpial/main.py [OPCIONES]

Para mas informacion visita la pagina de Preguntas y Respuestas Frecuentes:

http://code.google.com/p/turpial/wiki/FAQ

Contacto
--------

Puedes ponerte en contacto con el equipo de Turpial a través de cualquiera de 
las siguientes direcciones (todas @gmail.com):

wil.alejandro
meza.eleazar
milmazz
kstnshadows

A través de Twitter:

@satanas82
@elshaka
@milmazz
@Azrael37

O a través de @turpialve en Twitter para hacer recomendaciones, reportar bugs o 
simplemente para mantenerte al día en el desarrollo y los cambios de Turpial

