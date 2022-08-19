name: Reporte General de Cambios
description: Reporte de Cambios al Aplicativo

body:
  - type: markdown
    attributes:
      value: |
        Gracias, el objetivo es tener nuestros PR's con información simple pero efectiva!!
  - type: input
    id: mulAsociada
    attributes:
      label: Historia Asociada
      description: En esta casilla debes ingresar la url historia asociada al cambio que estas aplicando.
      placeholder: https://jiranubox.atlassian.net/browse/MUL-6693
    validations:
      required: true
  - type: textarea
    id: what-happened
    attributes:
      label: Cuáles son los cambios?
      description: Sección correspondiente a la descripción general del cambio.
      placeholder: Se ha modificado el módulo que calcula el Rut
      value: "Se ha modificado el módulo que calcula el Rut"
    validations:
      required: true
