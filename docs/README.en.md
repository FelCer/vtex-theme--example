# Example Store Theme IO

<!-- DOCS-IGNORE:start -->
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-2-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->
<!-- DOCS-IGNORE:end -->

Change language from README to [![es](https://img.shields.io/badge/lang-en-red.svg)](https://github.com/FelCer/vtex-theme--example/blob/main/docs/README.md)

<br>

Example Store theme IO is the base on which vtex io for example store is implemened.

<br>

## Preview

![Media Placeholder](./assets/example_use.png 'Imagen de ejemplo de uso')
<br>
<br>

## Configuration

<br>

### Paso 1 - Basic Configuration

Read the [VTEX IO basic configuration guide](https://developers.vtex.com/docs/guides/vtex-io-documentation-vtex-io-cli-installation-and-command-reference) 
and follow all the indicated steps, to be able to start with VTEX IO.

At the end of following the steps and doing the configuration, you should have the VTEX command line interface (Toolbelt) installed.
<br>
<br>

### Paso 2 - Cloning the repository store-theme.{{vendor}}

[Clone this](https://github.com/FelCer/vtex-theme--example) repository to your local files so you can start working in it effectively.
<br>
<br>

### Paso 3 - Edit the `Manifest.json`

Being in the repository directory, it's time to edit the file `manifest.json` of store-theme.{{vendor}}.

You must replace the `vendor` and `account` values. `vendor` is the name of the account you are working on and `account` is the name you want to give the theme. For example:

```json
{
  "vendor": "{{vendor}}",
  "name": "store-theme"
}
```
<br>

### Paso 4 - Install necessary apps

To use the Store Framework and work on the store-theme.{{vendor}} theme, it is necessary to have installed `vtex.store-sitemap` y `vtex.store`.

Execute `vtex list` and check if those apps are already installed.

If they are not, run the following command to install them: `vtex install vtex.store-sitemap vtex.store -f`
<br>
<br>

### Paso 5 - Uninstall the store-theme default

By running `vtex list`, you can check if any themes are installed.

It is common to have the `vtex.store-theme` already installed when you start the store development process.

So if you find it in the list of applications, copy its name and use it together with the `vtex uninstall` command.

```json
vtex uninstall vtex.store-theme
```
<br>

### Paso 6- Run a store preview

To see all the changes you made to your local files to the environment. It is enough to use in the command line, the command

If the process runs without any errors, the following message will be displayed: `Assets build completed successfully`. In the previous line of this message appears the URL where you can see the changes, example: `Store live at: https://{{vendor}}.myvtex.com`

Or if you want to open it directly, run the `vtex browser` command to open a browser window.

Note: If you want to see the changes applied in real time you must have the `vtex link` command running.
<br>
<br>

## Dependencies

All of the store components that you see in this document are also open source. Production-ready, you can find those apps in the VTEX IO GitHub org.

Store framework is the base to create any store using _VTEX IO Web Framework_.

- [Store](https://github.com/vtex-apps/store)

Store GraphQL is a middleware to access all VTEX APIs.

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

## Custom Apps

Additionally, for the store to work correctly with the customs features, you need to use the following apps custom: 

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

## Contributors ✨

Thanks to these wonderful people: ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

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