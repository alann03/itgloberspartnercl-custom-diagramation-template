# Custom Diagramation Template

El componente _Custom Diagramation Template_ permite manipular una distribución de grillas a través del Site Editor.

![Media Placeholder](/assets/img/custom-grid-1.png)

![Media Placeholder](/assets/img/custom-grid-2.png)

>En las imágenes podemos ver dos distribuciones de grillas distinas usando el componente _Custom Diagramation Template_

## Configuración

### Paso 1 - Agregar el componente a las dependencias de su aplicación

Dentro del archivo `manifest.json` de su aplicación, debe agregar la siguiente dependencia: 

```json
"dependencies": {
  ...
  "itgloberspartnercl.special-diagramation": "0.x"
  ...
}
```

### Paso 2 - Declarar el bloque principal en su aplicación

Agregue el bloque `custom-grid` donde requiera utilizarlo dentro de su aplicación. Por ejemplo: 

```json
{
  "custom-grid": {
    ...
    "children": [
      "image#custom__grid--1",
      "image#custom__grid--2",
      "image#custom__grid--3",
      "image#custom__grid--4",
      "image#custom__grid--5"
    ]
    ...
  }
}
```

## Customización

Para aplicar personalizaciones de CSS en este y otros bloques, siga la guía [Uso de identificadores de CSS para la personalización de la tienda](https://developers.vtex.com/docs/guides/vtex-io-documentation-using-css-handles-for-store-customization).


| CSS HANDLES |
| -- |
| `grid__item--big` |
| `grid__item--small` |

## Colaboradores

- **Alan Agustín Huismann**