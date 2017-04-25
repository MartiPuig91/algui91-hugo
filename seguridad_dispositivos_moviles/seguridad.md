+++

title = "Seguridad en dispositivos móviles"

description = "Descubre las amenazas que acechan a estos dispositivos
que llevamos en nuestros bolsillos"

tags = \["seguridad", "móviles"\]

image = ""

mainclass = "artículos"

author = "marti"

date = ""

+++

Siguiendo la misma linea del artículo anterior, voy a seguir presentando
píldoras sobre seguridad informática. En este caso, voy a hablar sobre
la seguridad en dispositivos móviles.

\# Apollo en nuestro bolsillo

Actualmente cada uno de nosotros lleva en el bolsillo un pequeño
ordenador personal. Como curiosidad, el primer cohete que se lanzó en
una expedición a la luna, la CPU que llevaba para controlarlo, tenía
menor potencia que la mayoría de terminales móviles que poseemos hoy en
día.

\# Rastreo masivo

Para que nos podamos comunicar mediante nuestros terminales, hay
distribuida por nuestro entorno una red de telefonía móvil. Esta es una
gran fuente para la vigilancia masiva. Aunque no estemos utilizando el
terminal, este va captando la señal de las diferentes antenas
distribuidas por nuestro alrededor. Estas, a su vez, guardan un
historial de los dispositivos que se han conectado a ellas. Por lo
tanto, es posible hacer un seguimiento del recorrido que ha seguido una
persona de forma muy precisa.

 &lt;figure&gt;

 &lt;amp-img

 on="tap:lightbox1"

 role="button"

 tabindex="0"

 layout="responsive"

 src="/img/security\_cam.jpg"

 sizes="(min-width: 800px) 800px, 100vw"

 width="800"

 height="608"&gt;

 &lt;/amp-img&gt;

 &lt;figcaption&gt;Imagen de stocksnap.io (cc)&lt;/figcaption&gt;

&lt;/figure&gt;

\# Legislación

Además, las operadoras, por ley, tienen la obligación de almacenar todos
los datos asociados a las comunicaciones que sus infraestructuras
reciban o emitan, durante un año y medio. Estos datos, van desde el
identificador del móvil (IMEI), identificador de la tarjeta SIM (IMSI),
remitente y destinatario de las llamadas hasta la duración de esta, el
sitio y hora en que se han realizado. Aunque no puedan tener acceso al
contenido de las llamadas, a partir de todos datos recolectados, sí que
se puede generar un perfil muy preciso sobre las personas implicadas en
estas comunicaciones.

Esta situación viene dada desde 2004 donde Bruselas dictaminó

una “directiva europea“
(<https://quematumovil.pimienta.org/la_retencion_de_datos.html>) que
recomendaba que las operadoras recolectaran toda esta información. En
2014, el Tribunal de la UE invalida esta directiva por vulnerar los
derechos humanos y la privacidad de los usuarios de la red de telefonía.
Al cabo de un año el Comité Europeo vuelve a plantear la propuesta por
si realmente se vulneran los derechos humanos. Y en 2016, el Tribunal
Europeo “se reafirma”
(<https://edri.org/european-court-confirms-strict-safeguards-essential-data-retention/>).

A pesar de haber pasado un año, las operadoras continúan recabando esta
información a pesar de estar vulnerando la privacidad de los usuarios.

Para poner en evidencia estos hechos, diversas personalidades
involucradas en la política (Spitz y Ockenden, eurodiputado y diputado
suizo respectivamente), solicitaron a sus respectivas operadoras estos
metadatos. Los subieron a una “web”
(<http://www.zeit.de/datenschutz/malte-spitz-data-retention>)
(<https://www.digitale-gesellschaft.ch/dr.html>) donde se podía trazar
sus movimientos, posicionando a la persona respecto a las diferentes
antenas de las cuales captaba señal su terminal móvil. De esta forma, se
podía ubicar a en todo momento a la persona de forma muy precisa.

En algún caso, los propios periodistas hicieron la labor de ir
documentando donde se encontraba en cada momento y qué actividad podía
estar realizando en ese momento en el sitio donde se encontraba. Y en la
gran mayoría de casos eran correctas sus sospechas. Llegó a tal
punto,que tuvieron que eliminar la web ya que los aciertos eran
demasiado elevados. Y por cuestiones de seguridad, prefirieron mantener
en secreto la ubicación actual de dichos políticos.

Todos, en nuestro móvil tenemos instalada una \*app\* llamada Google
Maps, que sobretodo en los dispositivo con Android, viene pre-instalada.
Esta aplicación nos rastrea las 24 horas del día los 7 días de la
semana. Y al cabo de un período de tiempo podemos obtener resultados
como este de la imagen:

 &lt;figure&gt;

 &lt;amp-img

 on="tap:lightbox1"

 role="button"

 tabindex="0"

 layout="responsive"

 src="/img/maps.jpg"

 sizes="(min-width: 800px) 800px, 100vw"

 width="800"

 height="608"&gt;

 &lt;/amp-img&gt;

 &lt;figcaption&gt;Imagen de junkee.com (cc)&lt;/figcaption&gt;

&lt;/figure&gt;

Aunque por defecto viene activada esta opción. Tenemos la posibilidad de
que deje de rastrear nuestra ubicación y subirla a los servidores de
Google.

Actualmente, en España, la legislación vigente crea una situación un
poco insólita. El Ministerio de Interior puede hacer escuchas de un
teléfono sin tener ningún tipo de orden judicial. Tiene un límite de 24
horas para comunicarlo al juez pertinente una vez ha empezado las
actividades de investigación. Y a su vez, este tiene 48 horas para
validar o revocar la actuación policial. Por lo tanto, esta puede estar
72 horas escuchando de forma “legal” unas conversaciones, las cuales le
pueden permitir obtener pruebas para poder presentar un siguiente
informe más consistente al juez, en el caso de que este revoque el
anterior por falta de pruebas. Y así, al final, poder abrir un caso, con
pruebas conseguidas sin tener abierta ninguna orden judicial como tal.

A parte los principales cuerpos policiales de nuestro país hace uso de
una herramienta de grabación de llamadas denominada
“\*\*SITEL\*\*”(https://es.wikipedia.org/wiki/SITEL) donde se aprovecha
diversas vulnerabilidades de los dispositivos móviles para poder obtener
datos de estos.

\# Recomendaciones

Como vemos, podemos ser rastreados de muchas maneras y con mucha
facilidad, por eso, para terminar el artículo, os dejo unos cuantos
consejos que podéis implementar:

- Tapar las cámaras de vuestros dispositivos

- No instalar aplicaciones que nos soliciten más permisos de los
imprescindibles

- Utilizar el modo avión en caso de que no queramos que las antenas nos
ubiquen

- Desactivar el \*tracking\* de Google Maps

- No utilizar dispositivos que rastreen la actividad física

- Desactivar la ubicación en tu terminal móvil

- Instalar todas las actualizaciones que tengamos para nuestro
dispositivo ya que muchas de ellas son de seguridad que solventan
brechas de seguridad.

- No conectarnos en redes wifi públicas siempre que sea posible

&gt;Tenemos miedo que nos implanten un chip debajo la piel pero no
tenemos problema en llevar un móvil en el bolsillo o un \*smartwatch\*
en la muñeca


