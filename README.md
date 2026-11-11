# DragonsLauncher (GreenDragonMCstudio / Nexus Engineering)


Mods 
Pestaña MODS: catálogo de Modrinth (mods, modpacks, texturas, shaders). Los mods instalan también sus dependencias obligatorias (por ejemplo Fabric API). Los modpacks (.mrpack) crean una instancia nueva.


Servidores 
Pestaña SERVIDORES: crea servidores Vanilla, Paper, Fabric, Forge o Neoforge en tu PC (carpeta %APPDATA%\.dragonslauncher\servers). Nacen con cuentas verificadas (online-mode=true). Paper se descarga con la API Fill v3 (la v2 fue retirada).

Puente para amigos de otras redes 
Pestaña SERVIDORES > RED > «ABRIR PUENTE»: descarga el agente oficial de playit.gg a %APPDATA%.dragonslauncher\tools\playit, lo abre en su ventana (ahí sale el enlace para vincular tu cuenta gratis y crear el túnel «Minecraft Java»). La dirección que te da playit.gg se pega en el launcher (se guarda en la carpeta del servidor). Funciona aunque el proveedor use CGNAT. El puente se cierra al salir del launcher. 


Servidores: Forge, NeoForge y pestana MODS
Al crear un servidor ahora puedes elegir Vanilla, Paper, Fabric, Forge (1.12.2+) o NeoForge (1.20.2+). Forge y NeoForge se instalan con su instalador oficial (--installServer) dentro de la carpeta del servidor; puede tardar unos minutos. La pestana MODS (PLUGINS en Paper) muestra cada .jar con su icono, version y autor (leidos del propio archivo), permite activar/desactivar (.jar <-> .jar.disabled), quitar, anadir archivos o arrastrarlos, y buscar/instalar desde Modrinth (con dependencias; solo mods que sirven en servidor). Con el servidor encendido Windows puede impedir cambiar archivos: detenlo y reinicialo para aplicar los cambios. En SERVIDORES > RED Y AMIGOS hay una GUIA PASO A PASO para crear el puente (playit.gg).

Ficha de mods y CurseForge en servidores
En SERVIDORES > MODS se puede buscar en Modrinth o CurseForge. Al pulsar un mod (de la busqueda o ya instalado) se abre su ficha: descripcion, imagenes y versiones disponibles (por defecto solo las compatibles con tu servidor; se puede quitar el filtro) con un boton INSTALAR por version. 


Modpacks en servidores y fichas en instancias
SERVIDORES > MODS tiene ahora BUSCAR MODS y BUSCAR MODPACKS (Modrinth y CurseForge). En un modpack, CREAR SERVIDOR (pide aceptar el EULA con un segundo clic) crea un servidor nuevo con el Minecraft y el loader del modpack (Fabric, Forge o NeoForge; Quilt no), instala el servidor base y luego sus mods y configuracion. Modrinth: solo los archivos que el modpack marca como compatibles con servidor. CurseForge: usa el server pack del autor si existe; si no, el modpack normal (puede traer mods de cliente. De los modpacks solo se copian mods, config, defaultconfigs, kubejs, scripts y datapacks. Si el modpack pide una version exacta de Forge/NeoForge se usa; si ya no existe se usa la recomendada. MODS (menu lateral, instancias): al pulsar un resultado se abre la ficha con descripcion, imagenes y versiones, y se puede instalar una version concreta.

Actualizaciones automaticas (GitHub)

Skins 3D y efectos
SKINS: visor 3D (girar, zoom, 10 poses, capas) y editor (lapiz, borrador, relleno, gotero, simetria, guias, deshacer; tambien se pinta sobre el modelo). AJUSTES > EFECTOS VISUALES: fondo animado y transiciones (completos, suaves o apagados).

Neon giratorio, Bedrock y Dragons Plus
Neon: una luz recorre el borde de la ventana y de la tarjeta «Continuar jugando» (AJUSTES > EFECTOS: completos = animado, suaves = fijo, apagados = nada). BEDROCK (menu lateral): solo con cuenta premium (Microsoft). Detecta Minecraft para Windows (Microsoft Store), la abre, entra directo a un servidor (minecraft://connect), abre carpetas de mundos/packs, importa .mcworld/.mcpack/.mcaddon y hace copias de seguridad de los mundos. NO la descarga ni la modifica. DRAGONS PLUS (★ en la barra superior): suscripcion con ventajas (sin patrocinadores, neon con tu color y arcoiris, insignia). 
Compartir e importar instancias
INSTANCIAS: boton ⇪ en cada tarjeta (Compartir) y IMPORTAR arriba. Formas: CODIGO (DRAGONS1:..., texto para pegar), ENLACE (se sube la receta a paste.rs, gratis y sin cuenta; cualquiera con el enlace la ve y puede caducar), ZIP LIGERO (receta + config + solo los archivos sin enlace) y ZIP COMPLETO (con todos los archivos de mods; ojo con las licencias). Al importar se crea una instancia nueva y se bajan los mods de Modrinth/CurseForge. Los que su autor solo deja bajar desde CurseForge salen en una lista con boton ABRIR PAGINA y YA LO TENGO. Todo lo que llega de fuera se valida (nombres de archivo, ids, loader, rutas del ZIP) y los enlaces solo se aceptan de paste.rs, dpaste.org y GitHub.

Amigos (chat), temas completos y Plus v2
AMIGOS (barra superior): cada uno tiene un buzon secreto y un par de claves X25519; el codigo de amigo (DLAMIGO1:...) se intercambia una vez y desde ahi los mensajes van cifrados de extremo a extremo (AES-GCM) por ntfy.sh (gratis, sin cuentas; guarda ~12 h para quien esta desconectado). Solicitudes con aceptar/rechazar/bloquear. Para usar tu propio servidor ntfy cambia NtfyCanal. TEMA COMPLETO (Plus): el CSS usa variables -dl-cN (styles.css, bloque .root) y TemaCss las recalcula desde el color elegido: botones, bordes, letras y brillos. PLUS: cada clave se puede activar en 2 equipos (Plus.MAX_EQUIPOS); activar/cambiar se aplica al instante. Ventajas: sin patrocinadores, tema completo, neon arcoiris, 4 fondos, copia automatica de mundos, poses exclusivas, estrella con amigos. ACTUALIZAR a tus amigos.
