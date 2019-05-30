# MGS-Events
Administra eventos para wordpress

El plugin trae unos estilos basicos, permite el treemplazo y sobreescritura de la visualización, dentro de la carpeta del pluin se encuentro una sub carpeta *templates* esta contiene los distintos elemento, puede crear una carpeta *mgs-events* dentro de su theme y copiar en esta los elementos que desea sobre escribir, de esta forma podra personalizar la visualización.

## Shortcodes

### [mgs_events_map]
Muestra un mapa con los eventos

#### Parametros:
- **show_ev_pasados** *Opcional, 1* Solo acepta el numero uno (1) para indicar que se desea mostrar los eventos ya pasados, de lo contrario no se muestran.
- **zoom** *Opcional, numerico* Determina cuantos niveles se modificara el zoom automatico del mapa al ajustarce a los marcadores. El mapa ajusta automaticamente el zoom para mostrar todos los marcadores, este valos puede modificar este ajuste para alejar o acercar dicho zoom, si se omite, no se modifica.

### [mgs_events_list]
Muestra listado de eventos

#### Parametros:
- **count** *Opcional, numerico* Cantidad de registros que se mostraran. Por defecto: 3
- **pagination** *Opcional, 1|0* Determina se se muestra la paginación, por defecto 1
- **show_ev_pasados** *Opcional, 1* Solo acepta el numero uno (1) para indicar que se desea mostrar los eventos ya pasados, de lo contrario no se muestran.

### [mgs_events_grid]
Muestra grilla de eventos por meses, semano o dia.

#### Parametros:
Por el momento esta opción no tienen parametros.
