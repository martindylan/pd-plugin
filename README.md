# notas del fork
Host para correr plugins LADSPA dentro de Pure Data.  
El código es idéntico a la versión 0.2.1 del (paquete)[https://puredata.info/downloads/plugin], con la excepción de una línea de código comentada (línea 126 en plugin~.c) para evitar que el nombre del plugin LADSPA correctamente inicializado se imprima en la consola de pd. También incluyo en el repositorio el paquete compilado para linux.

# pd-plugin
LADSPA and VST plug-in hosting for Pd

This is a Pd tilde object for hosting LADSPA audio plug-ins. The
LADSPA plug-in interface is supported completely. The object will
search your LADSPA path for plugins, which are loadable by name as an
argument to the plugin~ object.

Jarno Seppänen, jams@cs.tut.fi
