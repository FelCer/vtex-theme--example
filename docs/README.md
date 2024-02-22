# Example Store Theme IO

<!-- DOCS-IGNORE:start -->
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-2-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->
<!-- DOCS-IGNORE:end -->

Cambiar lenguaje de README a [![en](https://img.shields.io/badge/lang-en-red.svg)](https://github.com/FelCer/vtex-theme--example/blob/main/docs/README.en.md)

<br>

Example Store theme IO es la base sobre la cual se implementa vtex io para la tienda.

<br>

## Previsualización

![Media Placeholder](./assets/example_use.png 'Imagen de ejemplo de uso')
<br>
<br>

## Configuración

<br>

### Paso 1 - Configuración Básica

Leer la [guía de configuración básica de VTEX IO](https://developers.vtex.com/docs/guides/vtex-io-documentation-vtex-io-cli-installation-and-command-reference) y siga todos los pasos indicados, para poder iniciar con VTEX IO.

Al final de seguir los pasos y hacer la configuración, debe tener instalada la interfaz de línea de comandos de VTEX (Toolbelt).
<br>
<br>

### Paso 2 - Clonación del repositorio store-theme.{{vendor}}

[Clone este](https://github.com/FelCer/vtex-theme--example) repositorio a sus archivos locales para poder comenzar a trabajar en él de manera efectiva.
<br>
<br>

### Paso 3 - Editar el `Manifest.json`

Estando en el directorio del repositorio, es hora de editar el archivo `manifest.json` de store-theme.{{vendor}}.

Debes reemplazar los valores `vendor` y `account`. `vendor` es el nombre de la cuenta en la que esta trabajando y `account` es el nombre que deseas colocar al tema. por ejemplo:

```json
{
  "vendor": "{{vendor}}",
  "name": "store-theme"
}
```
<br>

### Paso 4 - Instalar apps necesarias

Para usar Store Framework y trabajar en el tema store-theme.{{vendor}}, es necesario tener instalados `vtex.store-sitemap` y `vtex.store`.

Ejecute `vtex list` y verifique si esas aplicaciones ya están instaladas.

Si no lo están, ejecute el siguiente comando para instalarlos: `vtex install vtex.store-sitemap vtex.store -f`
<br>
<br>

### Paso 5 - Desinstalar el store-theme predeterminado(default)

Al ejecutar `vtex list`, puede verificar si algún tema está instalado.

Es común tener ya instalado el `vtex.store-theme` cuando inicia el proceso de desarrollo de la tienda.

Por lo tanto, si lo encuentra en la lista de aplicaciones, copie su nombre y utilícelo junto con el comando `vtex uninstall`. Por ejemplo:

```json
vtex uninstall vtex.store-theme
```
<br>

### Paso 6- Ejecute un preview de la tienda

Para ver todos los cambios que realizó en sus archivos locales al ambiente. Basta con usar en la linea de comandos, el comando `vtex link`.

Si el proceso se ejecuta sin ningún error, se mostrará el siguiente mensaje: `Assets build completed successfully`. En la anterior linea a este mensaje aparece la Url donde puede ver los cambios, ejemplo: `Store live at: https://{{vendor}}.myvtex.com`

O si desea abrirlo directamente, ejecute el comando `vtex browser` para abrir una ventana del navegador.

Nota: Si desea ver los cambios aplicados en tiempo real debe estar el comando `vtex link` corriendo.
<br>
<br>

## Dependencias

Todos los componentes de la tienda que ve en este documento también son de código abierto. Listo para la producción, puede encontrar esas aplicaciones en la organización de GitHub VTEX IO.

Store framework es la base para crear cualquier tienda utilizando _VTEX IO Web Framework_.

- [Store](https://github.com/vtex-apps/store)

Store GraphQL es un middleware para acceder a todas las APIs VTEX.

- [Store GraphQL](https://github.com/vtex-apps/store-graphql)
<br>
<br>

## Store Component Apps

- "vtex.store"
- "vtex.store-header"
- "vtex.store-image"
- "vtex.product-summary"
- "vtex.store-footer"
- "vtex.store-components"
- "vtex.styleguide"
- "vtex.slider"
- "vtex.carousel"
- "vtex.shelf"
- "vtex.menu"
- "vtex.minicart"
- "vtex.product-details"
- "vtex.product-kit"
- "vtex.search-result"
- "vtex.login"
- "vtex.my-account"
- "vtex.flex-layout"
- "vtex.rich-text"
- "vtex.store-drawer"
- "vtex.locale-switcher"
- "vtex.product-quantity"
- "vtex.product-highlights"
- "vtex.product-identifier"
- "vtex.product-price"
- "vtex.product-specification-badges"
- "vtex.product-review-interfaces"
- "vtex.telemarketing"
- "vtex.order-placed"
- "vtex.stack-layout"
- "vtex.tab-layout"
- "vtex.responsive-layout"
- "vtex.slider-layout"
- "vtex.iframe"
- "vtex.breadcrumb"
- "vtex.sticky-layout"
- "vtex.add-to-cart-button"
- "vtex.store-icons"
- "vtex.product-list"
- "vtex.checkout-summary"
- "vtex.search"
- "vtex.modal-layout"
- "vtex.disclosure-layout"
- "vtex.product-availability"
- "vtex.product-specifications"
- "vtex.store-link"
- "vtex.my-orders-app
<br>

## Apps personalizadas

Adicionalmente para que la tienda funcione correctamente con las funcionalidades customs, se necesita usar las siguientes apps custom: 

- ["{{vendor}}.whatsapp-button"](https://github.com/FelCer/vtex-whatsapp-button)
- ["{{vendor}}.bullet-group"](https://github.com/FelCer/vtex-bullet-group)
- ["{{vendor}}.list-context.bullet-group"](https://github.com/FelCer/vtex-custom-departament-search)
- ["{{vendor}}.pdf-reader"](https://github.com/FelCer/vtex-pdf-reader)
- ["{{vendor}}.quick-order"](https://github.com/FelCer/vtex-quick-order)
- ["{{vendor}}.grid"](https://github.com/FelCer/vtex-custom-grid)
<br>

<!-- ## Contributing

Check it out [how to contribute](https://github.com/vtex-apps/awesome-io#contributing) with this project. -->
<br>
<br>

## Colaboradores ✨

Gracias a estas maravillosas personas: ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->

<table>
  <tr>
    <td align="center"><img src="https://avatars.githubusercontent.com/u/22477264?v=4" width="100px;" alt=""/><br /><sub><b>Luis Felipe Cerero Garcia</b></sub></a><br /><a href="https://github.com/FelCer/vtex-theme--example/commits?author=felcer" title="Documentation">📖</td>
  </tr>
</table>
<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->
<!-- DOCS-IGNORE:end -->
