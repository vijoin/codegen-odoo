# Codegen Odoo V10
Generador de código para Dia adaptado a la versión 10 de Odoo

<strong>Configuración</strong>
---------------------

1- Instale Dia: apt-get install dia

2- Descarga el archivo: codegen_odoov10.py

3- Copie el archivo en la carpeta /usr/share/dia/python/

<strong>Como Usar ?</strong>
---------------------

* Descargue el ejemplo que se adjunta "<a href="https://github.com/amilianm/codegenodoo/blob/master/ejemplo.dia" target="_blank">ejemplo.dia</a>" para ver como están construidas las Clases

* Seleccione en el Menú Superior "Archivo > Exportar"

* En Tipo de Archivo despliegue y seleccione "CODEGEN ODOO V10"

* Guarde el Archivo en Formato ZIP

* Descomprima el Archivo y copielo dentro de la carpeta /usr/lib/python2.7/dist-packages/odoo/addons/

* Diríjase a su Odoo en el menú Configuración haga click en Activar Modo Desarrollador

* Presione Actualizar lista de Aplicaciones en el Tablero de Aplicaciones

* Filtre por el nombre del Módulo que creo y presione en Instalar Aplicación

Enjoy

##Observaciones:
Al definir un One2many o un Many2many es necesario que la etiqueta (label) se especifique con el atributo string='etiqueta' pues codegen necesita convertir eso a un <separator />
## Mejorar esto está incompleto
