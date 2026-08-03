# Licencias de FacturaSal

Fichero de licencias firmado (Ed25519) que consultan las instalaciones de
FacturaSal. Se gestiona con el panel (`node herramientas/panel-licencias.mjs`)
o la CLI (`herramientas/licencias.mjs`) del proyecto FacturaSal — no editar
`licencias.json` a mano: sin la firma correcta, las aplicaciones lo ignoran.

El contenido no es sensible: solo identificadores de instalación y su estado.
