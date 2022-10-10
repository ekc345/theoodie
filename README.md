
/*  ---  'base.css'  ---  */
/*  ---  'component-search.css'  ---  */

/*  ---  'component-predictive-search.css'  ---  */
/*  ---  'component-mega-menu.css'  ---  */





/*  ---  'component-price.css'  ---  */
/*  ---  'component-menu-drawer.css'  ---  */
/*  ---  'component-slideshow.css'  ---  */
/*  ---  'component-slider.css'  ---  */

/*  ---  'component-cart-notification.css'  ---  */
/*  ---  'component-cart-items.css'  ---  */



/*  ---  'base.css'  ---  */

/* Color custom properties */
:root,
.color-background-1 {
  --color-foreground-heading: var(--color-base-heading);
  --color-foreground: var(--color-base-text);
  --color-background: var(--color-base-background-1);
  --gradient-background: var(--gradient-base-background-1);
}

.color-background-2 {
  --color-foreground: var(--color-base-text);
  --color-background: var(--color-base-background-2);
  --gradient-background: var(--gradient-base-background-2);
}

.color-inverse {
  --color-foreground: var(--color-base-background-1);
  --color-background: var(--color-base-text);
  --gradient-background: rgb(var(--color-base-text));
}

.color-accent-1 {
  --color-foreground: var(--color-base-solid-button-labels);
  --color-background: var(--color-base-accent-1);
  --gradient-background: var(--gradient-base-accent-1);
}

.color-accent-2 {
  --color-foreground: var(--color-base-solid-button-labels);
  --color-background: var(--color-base-accent-2);
  --gradient-background: var(--gradient-base-accent-2);
}
.color-accent-3 {
  --color-foreground: var(--color-base-solid-button-labels);
  --color-background: var(--color-base-accent-3);
  --gradient-background: var(--gradient-base-accent-3);
}

.color-foreground-outline-button {
  --color-foreground: var(--color-base-outline-button-labels);
}

.color-foreground-accent-1 {
  --color-foreground: var(--color-base-accent-1);
}

.color-foreground-accent-2 {
  --color-foreground: var(--color-base-accent-2);
}
.color-foreground-accent-3 {
  --color-foreground: var(--color-base-accent-3);
}
:root,
.color-background-1 {
  --color-link: var(--color-base-outline-button-labels);
  --alpha-link: 0.85;
}

.color-background-2,
.color-inverse,
.color-accent-1,
.color-accent-2,
.color-accent-3 {
  --color-link: var(--color-foreground);
  --alpha-link: 0.7;
}

:root,
.color-background-1 {
  --color-button: var(--color-base-accent-1);
  --color-button-text: var(--color-base-solid-button-labels);
  --alpha-button-background: 1;
  --alpha-button-border: 1;
}

.color-background-2,
.color-inverse,
.color-accent-1,
.color-accent-2,
.color-accent-3 {
  --color-button: var(--color-foreground);
  --color-button-text: var(--color-background);
}

.button--secondary {
  --color-button: var(--color-base-outline-button-labels);
  --color-button-text: var(--color-base-outline-button-labels);
  --color-button: var(--color-background);
  --alpha-button-background: 1;
}

.color-background-2 .button--secondary,
.color-accent-1 .button--secondary,
.color-accent-2 .button--secondary,
.color-accent-3 .button--secondary {
  --color-button: var(--color-background);
  --color-button-text: var(--color-foreground);
}

.color-inverse .button--secondary {
  --color-button: var(--color-background);
  --color-button-text: var(--color-foreground);
}

.button--tertiary {
  --color-button: var(--color-base-outline-button-labels);
  --color-button-text: var(--color-base-outline-button-labels);
  --alpha-button-background: 0;
  --alpha-button-border: 0.2;
}

.color-background-2 .button--tertiary,
.color-inverse .button--tertiary,
.color-accent-1 .button--tertiary,
.color-accent-2 .button--tertiary,
.color-accent-3 .button--tertiary {
  --color-button: var(--color-foreground);
  --color-button-text: var(--color-foreground);
}

:root,
.color-background-1 {
  --color-badge-background: var(--color-background);
  --color-badge-border: var(--color-foreground);
  --alpha-badge-border: 0.1;
}

.color-background-2,
.color-inverse,
.color-accent-1,
.color-accent-2,
.color-accent-3 {
  --color-badge-background: var(--color-background);
  --color-badge-border: var(--color-background);
  --alpha-badge-border: 1;
}

:root,
.color-background-1,
.color-background-2 {
  --color-card-hover: var(--color-base-text);
}

.color-inverse {
  --color-card-hover: var(--color-base-background-1);
}

.color-accent-1,
.color-accent-2,
.color-accent-3 {
  --color-card-hover: var(--color-base-solid-button-labels);
}

:root,
.color-icon-text {
  --color-icon: rgb(var(--color-base-text));
}

.color-icon-accent-1 {
  --color-icon: rgb(var(--color-base-accent-1));
}

.color-icon-accent-2 {
  --color-icon: rgb(var(--color-base-accent-2));
}
.color-icon-accent-3 {
  --color-icon: rgb(var(--color-base-accent-3));
}

.color-icon-outline-button {
  --color-icon: rgb(var(--color-base-outline-button-labels));
}

.contains-card,
.card {
  --border-radius: var(--card-corner-radius);
  --border-width: var(--card-border-width);
  --border-opacity: var(--card-border-opacity);
  --shadow-horizontal-offset: var(--card-shadow-horizontal-offset);
  --shadow-vertical-offset: var(--card-shadow-vertical-offset);
  --shadow-blur-radius: var(--card-shadow-blur-radius);
  --shadow-opacity: var(--card-shadow-opacity);
}

.contains-content-container,
.content-container {
  --border-radius: var(--text-boxes-radius);
  --border-width: var(--text-boxes-border-width);
  --border-opacity: var(--text-boxes-border-opacity);
  --shadow-horizontal-offset: var(--text-boxes-shadow-horizontal-offset);
  --shadow-vertical-offset: var(--text-boxes-shadow-vertical-offset);
  --shadow-blur-radius: var(--text-boxes-shadow-blur-radius);
  --shadow-opacity: var(--text-boxes-shadow-opacity);
}

.contains-media,
.global-media-settings {
  --border-radius: var(--media-radius);
  --border-width: var(--media-border-width);
  --border-opacity: var(--media-border-opacity);
  --shadow-horizontal-offset: var(--media-shadow-horizontal-offset);
  --shadow-vertical-offset: var(--media-shadow-vertical-offset);
  --shadow-blur-radius: var(--media-shadow-blur-radius);
  --shadow-opacity: var(--media-shadow-opacity);
}
.color-transparent {--color-background: rgba(0,0,0,0); --gradient-background: rgba(0,0,0,0);}

:root {
  --place-self: center;
  --icon-size: 2em;
  --icon-color: var(--color-icon);
}
/* base */

.no-js:not(html) {
  display: none !important;
}

html.no-js .no-js:not(html) {
  display: block !important;
}

.no-js-inline {
  display: none !important;
}

html.no-js .no-js-inline {
  display: inline-block !important;
}

html.no-js .no-js-hidden {
  display: none !important;
}

.isolate {
  position: relative;
  z-index: 0;
}

.section + .section {
  margin-top: var(--spacing-sections);
  }
section.shopify-section, div.shopify-section .spd__flxiSection.space {
  margin-top: var(--spacing-sections);
}

.element-margin-top {
  margin-top: 5rem;
}

@media screen and (min-width: 750px) {
  .element-margin {
    margin-top: calc(5rem + var(--page-width-margin));
  }
}

body,
.color-background-1,
.color-background-2,
.color-inverse,
.color-accent-1,
.color-accent-2,
.color-accent-3 {
  color: rgba(var(--color-foreground), 0.75);
  background-color: rgb(var(--color-background));
}

.background-secondary {
  background-color: rgba(var(--color-foreground), 0.04);
}

.grid-auto-flow {
  display: grid;
  grid-auto-flow: column;
}

.page-margin,
.shopify-challenge__container {
  margin: 7rem auto;
}

.rte-width {
  max-width: 82rem;
  margin: 0 auto 2rem;
}

.list-unstyled {
  margin: 0;
  padding: 0;
  list-style: none;
}

.hidden {
  display: none !important;
}

.visually-hidden {
  position: absolute !important;
  overflow: hidden;
  width: 1px;
  height: 1px;
  margin: -1px;
  padding: 0;
  border: 0;
  clip: rect(0 0 0 0);
  word-wrap: normal !important;
}

.visually-hidden--inline {
  margin: 0;
  height: 1em;
}

.overflow-hidden {
  overflow: hidden;
}

.skip-to-content-link:focus {
  z-index: 9999;
  position: inherit;
  overflow: auto;
  width: auto;
  height: auto;
  clip: auto;
}

.full-width-link {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 2;
}

::selection {
  background-color: rgba(var(--color-foreground), 0.2);
}




.text-body {font-size: 1.5rem;letter-spacing: 0.06rem;line-height: calc(1 + 0.8 / var(--font-body-scale));font-family: var(--font-body-family);font-style: var(--font-body-style);font-weight: var(--font-body-weight);}
h0, .h0, .h0 p, .h0 a, h1, .h1, .h1 p, .h1 a, h2, .h2, .h2 p, .h2 a, h3, .h3, .h3 p, .h3 a, h4, .h4, .h4 p, .h4 a, h5, .h5, .h5 p, .h5 a, h6, .h6, .h6 p, .h6 a {font-family: var(--font-heading-family);font-style: var(--font-heading-style);color: var(--color-foreground-heading);text-align:var(--text-align);line-height: calc(1 + 0.3 / max(1, var(--font-heading-scale)));word-break: break-word;}

h0, .h0, .h0 p, .h0 a {font-size:var(--font-size-h0);font-weight:var(--font-weight-h0);}
h1, .h1, .h1 p, .h1 a {font-size:var(--font-size-h1);font-weight:var(--font-weight-h1);}
h2, .h2, .h2 p, .h2 a {font-size:var(--font-size-h2);font-weight:var(--font-weight-h2);}
h3, .h3, .h3 p, .h3 a {font-size:var(--font-size-h3);font-weight:var(--font-weight-h3);}
h4, .h4, .h4 p, .h4 a {font-size:var(--font-size-h4);font-weight:var(--font-weight-h4);}
h5, .h5, .h5 p, .h5 a {font-size:var(--font-size-h5);font-weight:var(--font-weight-h5);}
h6, .h6, .h6 p, .h6 a {font-size:var(--font-size-h6);font-weight:var(--font-weight-h6);}
body, p, .p, .p a {font-size:var(--font-size-p);font-weight:var(--font-weight-p);font-family:var(--font-body-family);text-align:var(--text-align);color: rgb(var(--color-foreground));}

blockquote {font-style: italic;color: rgba(var(--color-foreground), 0.75);border-left: 0.2rem solid rgba(var(--color-foreground), 0.2);padding-left: 1rem;}
@media screen and (min-width: 750px) {blockquote {padding-left: 1.5rem;}
  }
.caption {font-size: 1rem;letter-spacing: 0.07rem;line-height: calc(1 + 0.7 / var(--font-body-scale));}
@media screen and (min-width: 750px) {.caption {font-size: 1.2rem;}
}
.caption-with-letter-spacing {font-size: 1rem;letter-spacing: 0.13rem;line-height: calc(1 + 0.2 / var(--font-body-scale));text-transform: uppercase;}
.caption-with-letter-spacing--medium {font-size: 1.2rem;letter-spacing: .16rem;}
.caption-with-letter-spacing--large {font-size: 1.4rem;letter-spacing: 0.18rem;}
.caption-large,.customer .field input,.customer select,.field__input,.form__label,.select__select {font-size: 1.3rem;line-height: calc(1 + 0.5 / var(--font-body-scale));letter-spacing: 0.04rem;}
.color-foreground {color: rgb(var(--color-foreground));}
table:not([class]) {table-layout: fixed;border-collapse: collapse;font-size: 1.4rem;border-style: hidden;box-shadow: 0 0 0 0.1rem rgba(var(--color-foreground), 0.2);/* draws the table border  */}
table:not([class]) td,table:not([class]) th {padding: 1em;border: 0.1rem solid rgba(var(--color-foreground), 0.2);}
.hidden {display: none !important;}
@media screen and (max-width: 749px) {.small-hide {display: none !important;}
}
@media screen and (min-width: 750px) and (max-width: 989px) {.medium-hide {display: none !important;}
}
@media screen and (min-width: 990px) {.large-up-hide {display: none !important;}
}
.center {text-align: center;}
.right {text-align: right;}
.uppercase {text-transform: uppercase;}
.lowercase {text-transform: lowercase;}
.light {opacity: 0.7;}

.color-background-1, .color-background-2, .color-inverse, .color-accent-1, .color-accent-2{color: rgb(var(--color-foreground));}

.accent-1, .accent-1 p, .accent-1 a, .accent1, .accent1 p, .accent1 a {color:rgb(var(--color-base-accent-1));}
.accent-2, .accent-2 p, .accent-2 a, .accent2, .accent2 p, .accent2 a {color:rgb(var(--color-base-accent-2));}
.accent-3, .accent-3 p, .accent-3 a, .accent3, .accent3 p, .accent3 a {color:rgb(var(--color-base-accent-3));}
.background-1, .background-1 p, .background-1 a, .background1, .background1 p, .background1 a {color:var(--color-base-background-1);}
.background-2, .background-2 p, .background-2 a, .background2, .background2 p, .background2 a {color:var(--color-base-background-2);}
.colorWhite, .colorWhite p, .colorWhite a {color:#ffffff;}
.colorBlack, .colorBlack p, .colorBlack a {color:#000000;}
.font-heading, .font-heading p {font-family:var(--font-heading-family);}
.font-body, .font-body p {font-family:var(--font-body-family);}
a:empty,
ul:empty,
dl:empty,
div:empty,
section:empty,
article:empty,
p:empty,
h1:empty,
h2:empty,
h3:empty,
h4:empty,
h5:empty,
h6:empty {
  display: none;
}

.link,
.customer a {
  cursor: pointer;
  display: inline-block;
  border: none;
  box-shadow: none;
  text-decoration: underline;
  text-underline-offset: 0.3rem;
  color: rgb(var(--color-link));
  background-color: transparent;
  font-size: var(--font-size-p);
  font-family: inherit;
}

.link--text {
  color: rgb(var(--color-foreground));
}

.link--text:hover {
  color: rgba(var(--color-foreground), 0.75);
}

.link-with-icon {
  display: inline-flex;
  font-size: 1.4rem;
  font-weight: 600;
  letter-spacing: 0.1rem;
  text-decoration: none;
  margin-bottom: 4.5rem;
  white-space: nowrap;
}

.link-with-icon .icon {
  width: 1.5rem;
  margin-left: 1rem;
}

a:not([href]) {
  cursor: not-allowed;
}

.circle-divider::after {
  content: '\2022';
  margin: 0 1.3rem 0 1.5rem;
}

.circle-divider:last-of-type::after {
  display: none;
}

hr {
  border: none;
  height: 0.1rem;
  background-color: rgba(var(--color-foreground), 0.2);
  display: block;
  margin: 5rem 0;
}

@media screen and (min-width: 750px) {
  hr {
    margin: 7rem 0;
  }
}

.full-unstyled-link {
  text-decoration: none;
  color: currentColor;
  display: block;
}

.placeholder {
  background-color: rgba(var(--color-foreground), 0.04);
  color: rgba(var(--color-foreground), 0.55);
  fill: rgba(var(--color-foreground), 0.55);
}

details > * {
  box-sizing: border-box;
}

.break {
  word-break: break-word;
}

.visibility-hidden {
  visibility: hidden;
}

@media (prefers-reduced-motion) {
  .motion-reduce {
    transition: none !important;
    animation: none !important;
  }
}

:root {
  --duration-short: 100ms;
  --duration-default: 200ms;
  --duration-long: 500ms;
}

.underlined-link,
.customer a {
  color: rgba(var(--color-link), var(--alpha-link));
  text-underline-offset: 0.3rem;
  text-decoration-thickness: 0.1rem;
  transition: text-decoration-thickness ease 100ms;
}

.underlined-link:hover,
.customer a:hover {
  color: rgb(var(--color-link));
  text-decoration-thickness: 0.2rem;
}

.icon-arrow {
  width: 1.5rem;
}

h3 .icon-arrow,
.h3 .icon-arrow {
  width: calc(var(--font-heading-scale) * 1.5rem);
}

/* arrow animation */
.animate-arrow .icon-arrow path {
  transform: translateX(-0.25rem);
  transition: transform var(--duration-short) ease;
}

.animate-arrow:hover .icon-arrow path {
  transform: translateX(-0.05rem);
}

/* base-details-summary */
summary {
  cursor: pointer;
  list-style: none;
  position: relative;
}

summary .icon-caret {
  position: absolute;
  height: 0.6rem;
  right: 1.5rem;
  top: calc(50% - 0.2rem);
}

summary::-webkit-details-marker {
  display: none;
}

.disclosure-has-popup {
  position: relative;
}

.disclosure-has-popup[open] > summary::before {
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 2;
  display: block;
  cursor: default;
  content: ' ';
  background: transparent;
}

.disclosure-has-popup > summary::before {
  display: none;
}

.disclosure-has-popup[open] > summary + * {
  z-index: 100;
}

@media screen and (min-width: 750px) {
  .disclosure-has-popup[open] > summary + * {
    z-index: 4;
  }

  .facets .disclosure-has-popup[open] > summary + * {
    z-index: 2;
  }
}

/* base-focus */
/*
  Focus ring - default (with offset)
*/

*:focus {
  outline: 0;
  box-shadow: none;
}

*:focus-visible {
  outline: 0.2rem solid rgba(var(--color-foreground), 0.5);
  outline-offset: 0.3rem;
  box-shadow: 0 0 0 0.3rem rgb(var(--color-background)),
    0 0 0.5rem 0.4rem rgba(var(--color-foreground), 0.3);
}

/* Fallback - for browsers that don't support :focus-visible, a fallback is set for :focus */
.focused,
.no-js *:focus {
  outline: 0.2rem solid rgba(var(--color-foreground), 0.5);
  outline-offset: 0.3rem;
  box-shadow: 0 0 0 0.3rem rgb(var(--color-background)),
    0 0 0.5rem 0.4rem rgba(var(--color-foreground), 0.3);
}

/* Negate the fallback side-effect for browsers that support :focus-visible */
.no-js *:focus:not(:focus-visible) {
  outline: 0;
  box-shadow: none;
}

/*
  Focus ring - inset
*/

.focus-inset:focus-visible {
  outline: 0.2rem solid rgba(var(--color-foreground), 0.5);
  outline-offset: -0.2rem;
  box-shadow: 0 0 0.2rem 0 rgba(var(--color-foreground), 0.3);
}

.focused.focus-inset,
.no-js .focus-inset:focus {
  outline: 0.2rem solid rgba(var(--color-foreground), 0.5);
  outline-offset: -0.2rem;
  box-shadow: 0 0 0.2rem 0 rgba(var(--color-foreground), 0.3);
}

.no-js .focus-inset:focus:not(:focus-visible) {
  outline: 0;
  box-shadow: none;
}

/*
  Focus ring - none
*/

/* Dangerous for a11y - Use with care */
.focus-none {
  box-shadow: none !important;
  outline: 0 !important;
}

.focus-offset:focus-visible {
  outline: 0.2rem solid rgba(var(--color-foreground), 0.5);
  outline-offset: 1rem;
  box-shadow: 0 0 0 1rem rgb(var(--color-background)),
    0 0 0.2rem 1.2rem rgba(var(--color-foreground), 0.3);
}

.focus-offset.focused,
.no-js .focus-offset:focus {
  outline: 0.2rem solid rgba(var(--color-foreground), 0.5);
  outline-offset: 1rem;
  box-shadow: 0 0 0 1rem rgb(var(--color-background)),
    0 0 0.2rem 1.2rem rgba(var(--color-foreground), 0.3);
}

.no-js .focus-offset:focus:not(:focus-visible) {
  outline: 0;
  box-shadow: none;
}

/* component-title */
.title,
.title-wrapper-with-link {
  margin: 3rem 0 2rem;
}

.title-wrapper-with-link .title {
  margin: 0;
}

.title .link {
  font-size: inherit;
}

.title-wrapper {
  margin-bottom: 3rem;
}

.title-wrapper-with-link {
  display: flex;
  justify-content: space-between;
  align-items: flex-end;
  gap: 1rem;
  margin-bottom: 3rem;
  flex-wrap: wrap;
}

.title--primary {
  margin: 4rem 0;
}

.title-wrapper--self-padded-tablet-down,
.title-wrapper--self-padded-mobile {
  padding-left: 1.5rem;
  padding-right: 1.5rem;
}

@media screen and (min-width: 750px) {
  .title-wrapper--self-padded-mobile {
    padding-left: 0;
    padding-right: 0;
  }
}

@media screen and (min-width: 990px) {
  .title,
  .title-wrapper-with-link {
    margin: 5rem 0 3rem;
  }

  .title--primary {
    margin: 2rem 0;
  }

  .title-wrapper-with-link {
    align-items: center;
  }

  .title-wrapper-with-link .title {
    margin-bottom: 0;
  }

  .title-wrapper--self-padded-tablet-down {
    padding-left: 0;
    padding-right: 0;
  }
}

.title-wrapper-with-link .link-with-icon {
  margin: 0;
  flex-shrink: 0;
  display: flex;
  align-items: center;
}

.title-wrapper-with-link .link-with-icon svg {
  width: 1.5rem;
}

.title-wrapper-with-link a {
  color: rgb(var(--color-link));
  margin-top: 0;
  flex-shrink: 0;
}

.title-wrapper--no-top-margin {
  margin-top: 0;
}

.title-wrapper--no-top-margin > .title {
  margin-top: 0;
}

.subtitle {
  font-size: 1.8rem;
  line-height: calc(1 + 0.8 / var(--font-body-scale));
  letter-spacing: 0.06rem;
  color: rgba(var(--color-foreground), 0.7);
}

.subtitle--small {
  font-size: 1.4rem;
  letter-spacing: 0.1rem;
}

.subtitle--medium {
  font-size: 1.6rem;
  letter-spacing: 0.08rem;
}

/* component-grid */
.grid {
  display: flex;
  flex-wrap: wrap;
  margin-bottom: 2rem;
  padding: 0;
  list-style: none;
  column-gap: var(--grid-mobile-horizontal-spacing);
  row-gap: var(--grid-mobile-vertical-spacing);
}

@media screen and (min-width: 750px) {
  .grid {
    column-gap: var(--grid-desktop-horizontal-spacing);
    row-gap: var(--grid-desktop-vertical-spacing);
  }
}

.grid:last-child {
  margin-bottom: 0;
}

.grid__item {
  width: calc(25% - var(--grid-mobile-horizontal-spacing) * 3 / 4);
  max-width: calc(50% - var(--grid-mobile-horizontal-spacing) / 2);
  flex-grow: 1;
  flex-shrink: 0;
}

@media screen and (min-width: 750px) {
  .grid__item {
    width: calc(25% - var(--grid-desktop-horizontal-spacing) * 3 / 4);
    max-width: calc(50% - var(--grid-desktop-horizontal-spacing) / 2);
  }
}

.grid--gapless.grid {
  column-gap: 0;
  row-gap: 0;
}

@media screen and (max-width: 749px) {
  .grid__item.slider__slide--full-width {
    width: 100%;
    max-width: none;
  }
}

.grid--1-col .grid__item {
  max-width: 100%;
  width: 100%;
}

.grid--3-col .grid__item {
  width: calc(33.33% - var(--grid-mobile-horizontal-spacing) * 2 / 3);
}

@media screen and (min-width: 750px) {
  .grid--3-col .grid__item {
    width: calc(33.33% - var(--grid-desktop-horizontal-spacing) * 2 / 3);
  }
}

.grid--2-col .grid__item {
  width: calc(50% - var(--grid-mobile-horizontal-spacing) / 2);
}

@media screen and (min-width: 750px) {
  .grid--2-col .grid__item {
    width: calc(50% - var(--grid-desktop-horizontal-spacing) / 2);
  }

  .grid--4-col-tablet .grid__item {
    width: calc(25% - var(--grid-desktop-horizontal-spacing) * 3 / 4);
  }

  .grid--3-col-tablet .grid__item {
    width: calc(33.33% - var(--grid-desktop-horizontal-spacing) * 2 / 3);
  }

  .grid--2-col-tablet .grid__item {
    width: calc(50% - var(--grid-desktop-horizontal-spacing) / 2);
  }
}

@media screen and (max-width: 989px) {
  .grid--1-col-tablet-down .grid__item {
    width: 100%;
    max-width: 100%;
  }

  .slider--tablet.grid--peek {
    margin: 0;
    width: 100%;
  }

  .slider--tablet.grid--peek .grid__item {
    box-sizing: content-box;
    margin: 0;
  }
}

@media screen and (min-width: 990px) {
  .grid--6-col-desktop .grid__item {
    width: calc(16.66% - var(--grid-desktop-horizontal-spacing) * 5 / 6);
    max-width: calc(16.66% - var(--grid-desktop-horizontal-spacing) * 5 / 6);
  }

  .grid--5-col-desktop .grid__item {
    width: calc(20% - var(--grid-desktop-horizontal-spacing) * 4 / 5);
    max-width: calc(20% - var(--grid-desktop-horizontal-spacing) * 4 / 5);
  }

  .grid--4-col-desktop .grid__item {
    width: calc(25% - var(--grid-desktop-horizontal-spacing) * 3 / 4);
    max-width: calc(25% - var(--grid-desktop-horizontal-spacing) * 3 / 4);
  }

  .grid--3-col-desktop .grid__item {
    width: calc(33.33% - var(--grid-desktop-horizontal-spacing) * 2 / 3);
    max-width: calc(33.33% - var(--grid-desktop-horizontal-spacing) * 2 / 3);
  }

  .grid--2-col-desktop .grid__item {
    width: calc(50% - var(--grid-desktop-horizontal-spacing) / 2);
    max-width: calc(50% - var(--grid-desktop-horizontal-spacing) / 2);
  }
}

@media screen and (min-width: 990px) {
  .grid--1-col-desktop {
    flex: 0 0 100%;
    max-width: 100%;
  }

  .grid--1-col-desktop .grid__item {
    width: 100%;
    max-width: 100%;
  }
}

@media screen and (max-width: 749px) {
  .grid--peek.slider--mobile {
    margin: 0;
    width: 100%;
  }

  .grid--peek.slider--mobile .grid__item {
    box-sizing: content-box;
    margin: 0;
  }

  .grid--peek .grid__item {
    min-width: 35%;
  }

  .grid--peek.slider .grid__item:first-of-type {
    margin-left: 1.5rem;
  }

  .grid--peek.slider .grid__item:last-of-type {
    margin-right: 1.5rem;
  }

  .grid--2-col-tablet-down .grid__item {
    width: calc(50% - var(--grid-mobile-horizontal-spacing) / 2);
  }

  .slider--tablet.grid--peek.grid--2-col-tablet-down .grid__item,
  .grid--peek .grid__item {
    width: calc(50% - var(--grid-mobile-horizontal-spacing) - 3rem);
  }

  .slider--tablet.grid--peek.grid--1-col-tablet-down .grid__item,
  .slider--mobile.grid--peek.grid--1-col-tablet-down .grid__item  {
    width: calc(100% - var(--grid-mobile-horizontal-spacing) - 3rem);
  }
}

@media screen and (min-width: 750px) and (max-width: 989px) {
  .slider--tablet.grid--peek .grid__item {
    width: calc(25% - var(--grid-desktop-horizontal-spacing) - 3rem);
  }

  .slider--tablet.grid--peek.grid--3-col-tablet .grid__item {
    width: calc(33.33% - var(--grid-desktop-horizontal-spacing) - 3rem);
  }

  .slider--tablet.grid--peek.grid--2-col-tablet .grid__item,
  .slider--tablet.grid--peek.grid--2-col-tablet-down .grid__item {
    width: calc(50% - var(--grid-desktop-horizontal-spacing) - 3rem);
  }

  .slider--tablet.grid--peek .grid__item:first-of-type {
    margin-left: 1.5rem;
  }

  .slider--tablet.grid--peek .grid__item:last-of-type {
    margin-right: 1.5rem;
  }

  .grid--2-col-tablet-down .grid__item {
    width: calc(50% - var(--grid-desktop-horizontal-spacing) / 2);
  }

  .grid--1-col-tablet-down.grid--peek .grid__item {
    width: calc(100% - var(--grid-desktop-horizontal-spacing) - 3rem);
  }
}

/* component-media */
.media {
  display: block;
  background-color: rgba(var(--color-foreground), 0.1);
  position: relative;
  overflow: hidden;
}

.media--transparent {
  background-color: transparent;
}

.media > *:not(.zoom):not(.deferred-media__poster-button),
.media model-viewer {
  display: block;
  max-width: 100%;
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  width: 100%;
}

.media > img {
  object-fit: cover;
  object-position: center center;
  transition: opacity 0.4s cubic-bezier(0.25, 0.46, 0.45, 0.94);
}

.media--square {
  padding-bottom: 100%;
}

.media--portrait {
  padding-bottom: 125%;
}

.media--landscape {
  padding-bottom: 66.6%;
}

.media--cropped {
  padding-bottom: 56%;
}

.media--16-9 {
  padding-bottom: 56.25%;
}

.media--circle {
  padding-bottom: 100%;
  border-radius: 50%;
}

.media.media--hover-effect > img + img {
  opacity: 0;
}

@media screen and (min-width: 990px) {
  .media--cropped {
    padding-bottom: 63%;
  }
}

deferred-media {
  display: block;
}

/* component-button */
/* Button - default */


.shopify-challenge__button,
.customer button,
button.shopify-payment-button__button--unbranded,
.cart__dynamic-checkout-buttons [role='button'],
.cart__dynamic-checkout-buttons iframe {
  --shadow-horizontal-offset: var(--buttons-shadow-horizontal-offset);
  --shadow-vertical-offset: var(--buttons-shadow-vertical-offset);
  --shadow-blur-radius: var(--buttons-shadow-blur-radius);
  --shadow-opacity: var(--buttons-shadow-opacity);
  --border-offset: var(--buttons-border-offset); /* reduce radius edge artifacts */
  --border-opacity: calc(1 - var(--buttons-border-opacity));
  border-radius: var(--buttons-radius-outset);
  position: relative;
}

.button,
.shopify-challenge__button,
.customer button,
button.shopify-payment-button__button--unbranded,
.btn {
  min-width: calc(12rem + var(--buttons-border-width) * 2);
  min-height: calc(4.5rem + var(--buttons-border-width) * 2);
}

.shopify-payment-button__button--branded {
  z-index: auto;
}

.cart__dynamic-checkout-buttons iframe {
  box-shadow: var(--shadow-horizontal-offset) var(--shadow-vertical-offset) var(--shadow-blur-radius) rgba(var(--color-base-text), var(--shadow-opacity));
}

.button,
.shopify-challenge__button,
.customer button,
.btn{
  display: inline-flex;
  justify-content: center;
  align-items: center;
  border: 0;
  padding: 0 3rem;
  cursor: pointer;
  font: inherit;
  font-size: 1.5rem;
  text-decoration: none;
  color: rgb(var(--color-button-text));
  transition: box-shadow var(--duration-short) ease;
  -webkit-appearance: none;
  appearance: none;
  background-color: rgba(var(--color-button), var(--alpha-button-background));
}


.shopify-challenge__button:before,
.customer button:before,
.shopify-payment-button__button--unbranded:before,
.cart__dynamic-checkout-buttons [role='button']:before {
  content: '';
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: -1;
  border-radius: var(--buttons-radius-outset);
  box-shadow: var(--shadow-horizontal-offset) var(--shadow-vertical-offset) var(--shadow-blur-radius) rgba(var(--color-shadow), var(--shadow-opacity));
}


.shopify-challenge__button:after,
.customer button:after,
.shopify-payment-button__button--unbranded:after {
  content: '';
  position: absolute;
  top: var(--buttons-border-width);
  right: var(--buttons-border-width);
  bottom: var(--buttons-border-width);
  left: var(--buttons-border-width);
  z-index: 1;
  border-radius: var(--buttons-radius);
  box-shadow: 0 0 0 calc(var(--buttons-border-width) + var(--border-offset)) rgba(var(--color-button-text), var(--border-opacity)),
    0 0 0 var(--buttons-border-width) rgba(var(--color-button), var(--alpha-button-background));
  transition: box-shadow var(--duration-short) ease;
}

.button:not([disabled]):hover::after,
.shopify-challenge__button:hover::after,
.customer button:hover::after,
.shopify-payment-button__button--unbranded:hover::after {
  --border-offset: 1.3px;
  box-shadow: 0 0 0 calc(var(--buttons-border-width) + var(--border-offset)) rgba(var(--color-button-text), var(--border-opacity)),
    0 0 0 calc(var(--buttons-border-width) + 1px) rgba(var(--color-button), var(--alpha-button-background));
}

.button--secondary:after {
  --border-opacity: var(--buttons-border-opacity);
}




.shopify-payment-button__button--unbranded:focus-visible,
.shopify-payment-button__button--unbranded:focus
 {
  outline: 0;
  box-shadow: 0 0 0 0.3rem rgb(var(--color-background)),
    0 0 0 0.5rem rgba(var(--color-foreground), 0.5),
    0 0 0.5rem 0.4rem rgba(var(--color-foreground), 0.3);
}

.button:focus:not(:focus-visible):not(.focused),
.shopify-payment-button__button--unbranded:focus:not(:focus-visible):not(.focused),
.shopify-payment-button [role="button"]:focus:not(:focus-visible):not(.focused) {
  box-shadow: inherit;
}

.button::selection,
.shopify-challenge__button::selection,
.customer button::selection {
  background-color: rgba(var(--color-button-text), 0.3);
}

.button,
.button-label,
.shopify-challenge__button,
.customer button,
.btn{
  font-size: 1.5rem;
  letter-spacing: 0.1rem;
  line-height: calc(1 + 0.2 / var(--font-body-scale));
}

.button--tertiary {
  font-size: 1.2rem;
  padding: 1rem 1.5rem;
  min-width: calc(9rem + var(--buttons-border-width) * 2);
  min-height: calc(3.5rem + var(--buttons-border-width) * 2);
}

.button--small {
  padding: 1.2rem 2.6rem;
}

/* Button - other */

.button:disabled,
.button[aria-disabled='true'],
.button.disabled,
.customer button:disabled,
.customer button[aria-disabled='true'],
.customer button.disabled {
  cursor: not-allowed;
  opacity: 0.5;
}

.button--full-width {
  display: flex;
  width: 100%;
}

.button.loading {
  color: transparent;
  position: relative;
}

@media screen and (forced-colors: active) {
  .button.loading {
    color: rgb(var(--color-foreground));
  }
}

.button.loading > .loading-overlay__spinner {
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  position: absolute;
  height: 100%;
  display: flex;
}

.button.loading > .loading-overlay__spinner .path {
  stroke: rgb(var(--color-button-text));
}

/* Button - social share */

.share-button {
  display: block;
  position: relative;
}

.share-button details {
  width: fit-content;
}

.share-button__button {
  font-size: 1.4rem;
  display: flex;
  min-height: 2.4rem;
  align-items: center;
  color: rgb(var(--color-link));
  margin-left: 0;
  padding-left: 0;
}

details[open] > .share-button__fallback {
  animation: animateMenuOpen var(--duration-default) ease;
}

.share-button__button:hover {
  text-decoration: underline;
  text-underline-offset: 0.3rem;
}

.share-button__button,
.share-button__fallback button {
  cursor: pointer;
  background-color: transparent;
  border: none;
}

.share-button__button .icon-share {
  height: 1.2rem;
  margin-right: 1rem;
  width: 1.3rem;
}

.share-button__fallback {
  display: flex;
  align-items: center;
  position: absolute;
  top: 3rem;
  left: 0.1rem;
  z-index: 3;
  width: 100%;
  min-width: max-content;
  border-radius: var(--inputs-radius);
  border: 0;
}

.share-button__fallback:after {
  pointer-events: none;
  content: '';
  position: absolute;
  top: var(--inputs-border-width);
  right: var(--inputs-border-width);
  bottom: var(--inputs-border-width);
  left: var(--inputs-border-width);
  border: 0.1rem solid transparent;
  border-radius: var(--inputs-radius);
  box-shadow: 0 0 0 var(--inputs-border-width) rgba(var(--color-foreground), var(--inputs-border-opacity));
  transition: box-shadow var(--duration-short) ease;
  z-index: 1;
}

.share-button__fallback:before {
  background: rgb(var(--color-background));
  pointer-events: none;
  content: '';
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  border-radius: var(--inputs-radius-outset);
  box-shadow: var(--inputs-shadow-horizontal-offset) var(--inputs-shadow-vertical-offset) var(--inputs-shadow-blur-radius) rgba(var(--color-base-text), var(--inputs-shadow-opacity));
  z-index: -1;
}

.share-button__fallback button {
  width: 4.4rem;
  height: 4.4rem;
  padding: 0;
  flex-shrink: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  position: relative;
  right: var(--inputs-border-width);
}

.share-button__fallback button:hover {
  color: rgba(var(--color-foreground), 0.75);
}

.share-button__fallback button:hover svg {
  transform: scale(1.07);
}

.share-button__close:not(.hidden) + .share-button__copy {
  display: none;
}

.share-button__close,
.share-button__copy {
  background-color: transparent;
  color: rgb(var(--color-foreground));
}

.share-button__copy:focus-visible,
.share-button__close:focus-visible {
  background-color: rgb(var(--color-background));
  z-index: 2;
}

.share-button__copy:focus,
.share-button__close:focus {
  background-color: rgb(var(--color-background));
  z-index: 2;
}

.field:not(:focus-visible):not(.focused) + .share-button__copy:not(:focus-visible):not(.focused),
.field:not(:focus-visible):not(.focused) + .share-button__close:not(:focus-visible):not(.focused) {
  background-color: inherit;
}

.share-button__fallback .field:after,
.share-button__fallback .field:before {
  content: none;
}

.share-button__fallback .field {
  border-radius: 0;
  min-width: auto;
  min-height: auto;
  transition: none;
}

.share-button__fallback .field__input:focus,
.share-button__fallback .field__input:-webkit-autofill {
  outline: 0.2rem solid rgba(var(--color-foreground),.5);
  outline-offset: 0.1rem;
  box-shadow: 0 0 0 0.1rem rgb(var(--color-background)),0 0 0.5rem 0.4rem rgba(var(--color-foreground),.3);
}

.share-button__fallback .field__input {
  box-shadow: none;
  text-overflow: ellipsis;
  white-space: nowrap;
  overflow: hidden;
  filter: none;
  min-width: auto;
  min-height: auto;
}

.share-button__fallback .field__input:hover {
  box-shadow: none;
}

.share-button__fallback .icon {
  width: 1.5rem;
  height: 1.5rem;
}

.share-button__message:not(:empty) {
  display: flex;
  align-items: center;
  width: 100%;
  height: 100%;
  margin-top: 0;
  padding: 0.8rem 0 0.8rem 1.5rem;
  margin: var(--inputs-border-width);
}

.share-button__message:not(:empty):not(.hidden) ~ * {
  display: none;
}

/* component-form */
.field__input,
.select__select,
.customer .field input,
.customer select {
  -webkit-appearance: none;
  appearance: none;
  background-color: rgb(var(--color-background));
  color: rgb(var(--color-foreground));
  font-size: 1.6rem;
  width: 100%;
  box-sizing: border-box;
  transition: box-shadow var(--duration-short) ease;
  border-radius: var(--inputs-radius);
  height: 4.5rem;
  min-height: calc(var(--inputs-border-width) * 2);
  min-width: calc(7rem + (var(--inputs-border-width) * 2));
  position: relative;
  border: 0;
}

.field:before,
.select:before,
.customer .field:before,
.customer select:before,
.localization-form__select:before {
  pointer-events: none;
  content: '';
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  border-radius: var(--inputs-radius-outset);
  box-shadow: var(--inputs-shadow-horizontal-offset) var(--inputs-shadow-vertical-offset) var(--inputs-shadow-blur-radius) rgba(var(--color-base-text), var(--inputs-shadow-opacity));
  z-index: -1;
}

.field:after,
.select:after,
.customer .field:after,
.customer select:after,
.localization-form__select:after {
  pointer-events: none;
  content: '';
  position: absolute;
  top: var(--inputs-border-width);
  right: var(--inputs-border-width);
  bottom: var(--inputs-border-width);
  left: var(--inputs-border-width);
  border: 0.1rem solid transparent;
  border-radius: var(--inputs-radius);
  box-shadow: 0 0 0 var(--inputs-border-width) rgba(var(--color-foreground), var(--inputs-border-opacity));
  transition: box-shadow var(--duration-short) ease;
  z-index: 1;
}

.select__select {
  font-family: var(--font-body-family);
  font-style: var(--font-body-style);
  font-weight: var(--font-body-weight);
  font-size: 1.2rem;
  color: rgba(var(--color-foreground), 0.75);
}

.field:hover.field:after,
.select:hover.select:after,
.select__select:hover.select__select:after,
.customer .field:hover.field:after,
.customer select:hover.select:after,
.localization-form__select:hover.localization-form__select:after {
  box-shadow: 0 0 0 calc(0.1rem + var(--inputs-border-width)) rgba(var(--color-foreground),var(--inputs-border-opacity));
  outline: 0;
  border-radius: var(--inputs-radius);
}

.field__input:focus-visible,
.select__select:focus-visible,
.customer .field input:focus-visible,
.customer select:focus-visible,
.localization-form__select:focus-visible.localization-form__select:after {
  box-shadow: 0 0 0 calc(0.1rem + var(--inputs-border-width)) rgba(var(--color-foreground));
  outline: 0;
  border-radius: var(--inputs-radius);
}

.field__input:focus,
.select__select:focus,
.customer .field input:focus,
.customer select:focus,
.localization-form__select:focus.localization-form__select:after {
  box-shadow: 0 0 0 calc(0.1rem + var(--inputs-border-width)) rgba(var(--color-foreground));
  outline: 0;
  border-radius: var(--inputs-radius);
}

.localization-form__select:focus {
  outline: 0;
  box-shadow: none;
}

.text-area,
.select {
  display: flex;
  position: relative;
  width: 100%;
}

/* Select */

.select .icon-caret,
.customer select + svg {
  height: 0.6rem;
  pointer-events: none;
  position: absolute;
  top: calc(50% - 0.2rem);
  right: calc(var(--inputs-border-width) + 1.5rem);
}

.select__select,
.customer select {
  cursor: pointer;
  line-height: calc(1 + 0.6 / var(--font-body-scale));
  padding: 0 2rem;
  margin: var(--inputs-border-width);
  min-height: calc(var(--inputs-border-width) * 2);
}

/* Field */

.field {
  position: relative;
  width: 100%;
  display: flex;
  transition: box-shadow var(--duration-short) ease;
}

.customer .field {
  display: flex;
}

.field--with-error {
  flex-wrap: wrap;
}

.field__input,
.customer .field input {
  flex-grow: 1;
  text-align: left;
  padding: 1.5rem;
  margin: var(--inputs-border-width);
  transition: box-shadow var(--duration-short) ease;
}

.field__label,
.customer .field label {
  font-size: 1.6rem;
  left: calc(var(--inputs-border-width) + 2rem);
  top: calc(1rem + var(--inputs-border-width));
  margin-bottom: 0;
  pointer-events: none;
  position: absolute;
  transition: top var(--duration-short) ease,
    font-size var(--duration-short) ease;
  color: rgba(var(--color-foreground), 0.75);
  letter-spacing: 0.1rem;
  line-height: 1.5;
}

.field__input:focus ~ .field__label,
.field__input:not(:placeholder-shown) ~ .field__label,
.field__input:-webkit-autofill ~ .field__label,
.customer .field input:focus ~ label,
.customer .field input:not(:placeholder-shown) ~ label,
.customer .field input:-webkit-autofill ~ label {
  font-size: 1rem;
  top: calc(var(--inputs-border-width) + 0.5rem);
  left: calc(var(--inputs-border-width) + 2rem);
  letter-spacing: 0.04rem;
}

.field__input:focus,
.field__input:not(:placeholder-shown),
.field__input:-webkit-autofill,
.customer .field input:focus,
.customer .field input:not(:placeholder-shown),
.customer .field input:-webkit-autofill {
  padding: 2.2rem 1.5rem 0.8rem 2rem;
  margin: var(--inputs-border-width);
}

.field__input::-webkit-search-cancel-button,
.customer .field input::-webkit-search-cancel-button {
  display: none;
}

.field__input::placeholder,
.customer .field input::placeholder {
  opacity: 0;
}

.field__button {
  align-items: center;
  background-color: transparent;
  border: 0;
  color: currentColor;
  cursor: pointer;
  display: flex;
  height: 4.4rem;
  justify-content: center;
  overflow: hidden;
  padding: 0;
  position: absolute;
  right: 0;
  top: 0;
  width: 4.4rem;
}

.field__button > svg {
  height: 2.5rem;
  width: 2.5rem;
}

.field__input:-webkit-autofill ~ .field__button,
.field__input:-webkit-autofill ~ .field__label,
.customer .field input:-webkit-autofill ~ label {
  color: rgb(0, 0, 0);
}

/* Text area */

.text-area {
  font-family: var(--font-body-family);
  font-style: var(--font-body-style);
  font-weight: var(--font-body-weight);
  min-height: 10rem;
  resize: none;
}

input[type='checkbox'] {
  display: inline-block;
  width: auto;
  margin-right: 0.5rem;
}

/* Form global */

.form__label {
  display: block;
  margin-bottom: 0.6rem;
}

.form__message {
  align-items: center;
  display: flex;
  font-size: 1.4rem;
  line-height: 1;
  margin-top: 1rem;
}

.form__message--large {
  font-size: 1.6rem;
}

.customer .field .form__message {
  font-size: 1.4rem;
  text-align: left;
}

.form__message .icon,
.customer .form__message svg {
  flex-shrink: 0;
  height: 1.3rem;
  margin-right: 0.5rem;
  width: 1.3rem;
}

.form__message--large .icon,
.customer .form__message svg {
  height: 1.5rem;
  width: 1.5rem;
  margin-right: 1rem;
}

.customer .field .form__message svg {
  align-self: start;
}

.form-status {
  margin: 0;
  font-size: 1.6rem;
}

.form-status-list {
  padding: 0;
  margin: 2rem 0 4rem;
}

.form-status-list li {
  list-style-position: inside;
}

.form-status-list .link::first-letter {
  text-transform: capitalize;
}

/* component-quantity */
.quantity {
  color: rgba(var(--color-foreground));
  position: relative;
  width: calc(14rem / var(--font-body-scale) + var(--inputs-border-width) * 2);
  display: flex;
  border-radius: var(--inputs-radius);
  min-height: calc((var(--inputs-border-width) * 2) + 4.5rem);
}

.quantity:after {
  pointer-events: none;
  content: '';
  position: absolute;
  top: var(--inputs-border-width);
  right: var(--inputs-border-width);
  bottom: var(--inputs-border-width);
  left: var(--inputs-border-width);
  border: 0.1rem solid transparent;
  border-radius: var(--inputs-radius);
  box-shadow: 0 0 0 var(--inputs-border-width) rgba(var(--color-foreground), var(--inputs-border-opacity));
  transition: box-shadow var(--duration-short) ease;
  z-index: 1;
}

.quantity:before {
  background: rgb(var(--color-background));
  pointer-events: none;
  content: '';
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  border-radius: var(--inputs-radius-outset);
  box-shadow: var(--inputs-shadow-horizontal-offset) var(--inputs-shadow-vertical-offset) var(--inputs-shadow-blur-radius) rgba(var(--color-base-text), var(--inputs-shadow-opacity));
  z-index: -1;
}

.quantity__input {
  color: currentColor;
  font-size: 1.4rem;
  font-weight: 500;
  opacity: 0.85;
  text-align: center;
  background-color: transparent;
  border: 0;
  padding: 0 0.5rem;
  width: 100%;
  flex-grow: 1;
  -webkit-appearance: none;
  appearance: none;
}

.quantity__button {
  width: calc(4.5rem / var(--font-body-scale));
  flex-shrink: 0;
  font-size: 1.8rem;
  border: 0;
  background-color: transparent;
  cursor: pointer;
  display: flex;
  align-items: center;
  justify-content: center;
  color: rgb(var(--color-foreground));
  padding: 0;
}

.quantity__button:first-child {
  margin-left: calc(var(--inputs-border-width));
}

.quantity__button:last-child {
  margin-right: calc(var(--inputs-border-width));
}

.quantity__button svg {
  width: 1rem;
  pointer-events: none;
}

.quantity__button:focus-visible,
.quantity__input:focus-visible {
  background-color: rgb(var(--color-background));
  z-index: 2;
}

.quantity__button:focus,
.quantity__input:focus {
  background-color: rgb(var(--color-background));
  z-index: 1;
}

.quantity__button:not(:focus-visible):not(.focused),
.quantity__input:not(:focus-visible):not(.focused) {
  box-shadow: inherit;
  background-color: inherit;
}

.quantity__input:-webkit-autofill,
.quantity__input:-webkit-autofill:hover,
.quantity__input:-webkit-autofill:active {
  box-shadow: 0 0 0 10rem rgb(var(--color-background)) inset !important;
  -webkit-box-shadow: 0 0 0 10rem rgb(var(--color-background)) inset !important;
}

.quantity__input::-webkit-outer-spin-button,
.quantity__input::-webkit-inner-spin-button {
  -webkit-appearance: none;
  margin: 0;
}

.quantity__input[type='number'] {
  -moz-appearance: textfield;
}

/* component-modal */
.modal__toggle {
  list-style-type: none;
}

.no-js details[open] .modal__toggle {
  position: absolute;
  z-index: 5;
}

.modal__toggle-close {
  display: none;
}

.no-js details[open] svg.modal__toggle-close {
  display: flex;
  z-index: 1;
  height: 1.7rem;
  width: 1.7rem;
}

.modal__toggle-open {
  display: flex;
}

.no-js details[open] .modal__toggle-open {
  display: none;
}

.no-js .modal__close-button.link {
  display: none;
}

.modal__close-button.link {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 0rem;
  height: 4.4rem;
  width: 4.4rem;
  background-color: transparent;
}

.modal__close-button .icon {
  width: 1.7rem;
  height: 1.7rem;
}

.modal__content {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: rgb(var(--color-background));
  z-index: 4;
  display: flex;
  justify-content: center;
  align-items: center;
}

.media-modal {
  cursor: zoom-out;
}

.media-modal .deferred-media {
  cursor: initial;
}

/* component-cart-count-bubble */
.cart-count-bubble:empty {
  display: none;
}

.cart-count-bubble {
  position: absolute;
  background-color: rgb(var(--color-button));
  color: rgb(var(--color-button-text));
  height: 1.7rem;
  width: 1.7rem;
  border-radius: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 0.9rem;
  bottom: -0.3em;
  right: -0.3em;
  line-height: calc(1 + 0.1 / var(--font-body-scale));
}

/* section-announcement-bar */
#shopify-section-announcement-bar {
  z-index: 4;
}

.announcement-bar {
  border-bottom: 0.1rem solid rgba(var(--color-foreground), 0.08);
  color: rgb(var(--color-foreground));
}

.announcement-bar__link {
  display: block;
  width: 100%;
  padding: 0.3rem 2rem;
  text-decoration: none;
}

.announcement-bar__link:hover {
  color: rgb(var(--color-foreground));
  background-color: rgba(var(--color-card-hover), 0.06);
}

.announcement-bar__link .icon-arrow {
  display: inline-block;
  pointer-events: none;
  margin-left: 0.8rem;
  vertical-align: middle;
  margin-bottom: 0.2rem;
}

.announcement-bar__link .announcement-bar__message {
  padding: 0;
}

.announcement-bar__message {
  text-align: center;
  margin: 0;
}

/* section-header */
div.shopify-section.section-header {
  z-index: 3;
}

.shopify-section-header-sticky {
  position: sticky;
  top: 0;
}

.shopify-section-header-hidden {
  transform: translateY(-100%);
}

.shopify-section-header-hidden.menu-open {
  transform: translateY(0);
}

#shopify-section-header.animate {
  transition: transform 0.15s ease-out;
}

/* Main Header Layout */
.header-wrapper {
  display: block;
  position: relative;
  background-color: rgb(var(--color-background));
}
.header-wrapper--shadow-bottom {
  box-shadow: 0px 2px 4px 0px rgb(0 0 0 / 28%);
}
header.header{
  display: grid;
  padding-top: 1rem;
  padding-bottom: 1rem;
  place-items:center;
}
header.header.fullwidth{
  padding:10px 30px
}
header.header.default {
  grid-template-areas: 'logo inlineMenu searchIcon accountIcon cartIcon';
  grid-template-columns: 300px auto 100px 100px 100px;
  grid-template-rows: auto;
  align-items: center;
}
header.header.defaultDawn {
  grid-template-areas: 'logo inlineMenu headerIcons';
  grid-template-columns: 200px auto 80px;
  grid-template-rows: auto;
  align-items: center;
}
.defaultDawn .header__icons {grid-area:headerIcons;}


header.header.default.noAccount {
  grid-template-areas: 'logo inlineMenu searchIcon cartIcon';
  grid-template-columns: 300px auto 200px 100px;
}

@media screen and (min-width: 990px) {
  .header {
    padding-top: 2rem;
    padding-bottom: 2rem;
  }

  .header--has-menu:not(.header--middle-left) {
    padding-bottom: 0;
  }
}

.header *[tabindex='-1']:focus {
  outline: none;
}

.header__heading {
  margin: 0;
  line-height: 0;
}

.header > .header__heading-link {
  line-height: 0;
}

.header__heading-link {
  display: inline-block;
  padding: 0.75rem;
  text-decoration: none;
  word-break: break-word;
}

.header__heading-link:hover .h2 {
  color: rgb(var(--color-foreground));
}

.header__heading-link .h2 {
  line-height: 1;
  color: rgba(var(--color-foreground), 0.75);
}

.header__heading-logo {
  height: auto;
  width: 100%;
}

@media screen and (max-width: 989px) {
  .header__heading,
  .header__heading-link {
    text-align: center;
  }
}

@media screen and (min-width: 990px) {
  .header__heading-link {
    margin-left: -0.75rem;
  }

  .header__heading,
  .header__heading-link {
    justify-self: start;
  }

  .header--top-center .header__heading-link,
  .header--top-center .header__heading {
    justify-self: center;
    text-align: center;
  }
}

/* Header icons */
.header__icons {
  display: flex;
  justify-self: end;
}

header .spd__headerDrawer {grid-area: headerDrawer; place-self:var(--place-self);}
header .header__heading, header .header__heading-link {grid-area: logo; place-self:var(--place-self);}
header .header__inline-menu.spd__menu-1 {grid-area: inlineMenu; place-self:var(--place-self);}
header .header__inline-menu.spd__menu-2 {grid-area: inlineMenu2; place-self:var(--place-self);}
header .spd__searchBar {grid-area: searchBar; place-self:var(--place-self);}
header .spd__searchIcon {grid-area: searchIcon; place-self:var(--place-self);}
header .spd__accountIcon {grid-area: accountIcon; place-self:var(--place-self);}
header .spd__cartIcon {grid-area: cartIcon; place-self:var(--place-self);}

.header__icon:not(.header__icon--summary),
.header__icon span {
  display: flex;
  align-items: center;
  justify-content: center;
}

.header__icon {
  color: var(--icon-color);
}

.header__icon span {
  height: 100%;
}

.header__icon::after {
  content: none;
}

.header__icon:hover .icon,
.modal__close-button:hover .icon {
  transform: scale(1.07);
}

.header__icon .icon {
  height: var(--icon-size);
  width: var(--icon-size);
}

.header__icon--cart {
  position: relative;
}

@media screen and (max-width: 989px) {
  menu-drawer ~ .header__icons .header__icon--account {
    display: none;
  }
}

.header__icon--menu[aria-expanded="true"]::before {
  content: "";
  top: 100%;
  left: 0;
  height: calc(var(--viewport-height, 100vh) - (var(--header-bottom-position, 100%)));
  width: 100%;
  display: block;
  position: absolute;
  background: rgba(var(--color-foreground), 0.5);
}

/* Search */
menu-drawer + .header__search {
  display: none;
}

.header > .header__search {
  grid-area: left-icon;
  justify-self: start;
}

.header:not(.header--has-menu) * > .header__search {
  display: none;
}

.header__search {
  display: inline-flex;
  line-height: 0;
}

.header--top-center > .header__search {
  display: none;
}

.header--top-center * > .header__search {
  display: inline-flex;
}

@media screen and (min-width: 990px) {
  .header:not(.header--top-center) * > .header__search,
  .header--top-center > .header__search {
    display: inline-flex;
  }

  .header:not(.header--top-center) > .header__search,
  .header--top-center * > .header__search {
    display: none;
  }
}

.no-js .predictive-search {
  display: none;
}

details[open] > .search-modal {
  opacity: 1;
  animation: animateMenuOpen var(--duration-default) ease;
}

details[open] .modal-overlay {
  display: block;
}

details[open] .modal-overlay::after {
  position: absolute;
  content: '';
  background-color: rgb(var(--color-foreground), 0.5);
  top: 100%;
  left: 0;
  right: 0;
  height: 100vh;
}

.no-js details[open] > .header__icon--search {
  top: 1rem;
  right: 0.5rem;
}

.search-modal {
  opacity: 0;
  border-bottom: 0.1rem solid rgba(var(--color-foreground), 0.08);
  min-height: calc(100% + var(--inputs-margin-offset) + (2 * var(--inputs-border-width)));
  height: 100%;
}

.search-modal__content {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 100%;
  height: 100%;
  padding: 0 5rem 0 1rem;
  line-height: calc(1 + 0.8 / var(--font-body-scale));
  position: relative;
}

.search-modal__content-bottom {
  bottom: calc((var(--inputs-margin-offset) / 2) );
}

.search-modal__content-top {
  top: calc((var(--inputs-margin-offset) / 2) );
}

.search-modal__form {
  width: 100%;
}

.search-modal__close-button {
  position: absolute;
  right: 0.3rem;
}

@media screen and (min-width: 750px) {
  .search-modal__close-button {
    right: 1rem;
  }

  .search-modal__content {
    padding: 0 6rem;
  }
}

@media screen and (min-width: 990px) {
  .search-modal__form {
    max-width: 47.8rem;
  }
  .spd__searchBar .search-modal__form {
    max-width: 100%;
  }
  .search-modal__close-button {
    position: initial;
    margin-left: 0.5rem;
  }
}

/* Header menu drawer */
.header__icon--menu .icon {
  display: block;
  position: absolute;
  opacity: 1;
  transform: scale(1);
  transition: transform 150ms ease, opacity 150ms ease;
}

details:not([open]) > .header__icon--menu .icon-close,
details[open] > .header__icon--menu .icon-hamburger {
  visibility: hidden;
  opacity: 0;
  transform: scale(0.8);
}

.js details[open]:not(.menu-opening) > .header__icon--menu .icon-close {
  visibility: hidden;
}

.js details[open]:not(.menu-opening) > .header__icon--menu .icon-hamburger {
  visibility: visible;
  opacity: 1;
  transform: scale(1.07);
}

.js details > .header__submenu {
  opacity: 0;
  transform: translateY(-1.5rem);
}

details[open] > .header__submenu {
  animation: animateMenuOpen var(--duration-default) ease;
  animation-fill-mode: forwards;
  z-index: 3;
}

@media (prefers-reduced-motion) {
  details[open] > .header__submenu {
    opacity: 1;
    transform: translateY(0);
  }
}

/* Header menu */

.header--top-center .header__inline-menu,
.header--top-center .header__heading-link {
  margin-left: 0;
}

@media screen and (min-width: 990px) {
  .header__inline-menu {
    display: block;
  }

  .header--top-center .header__inline-menu {
    justify-self: center;
  }

  .header--top-center .header__inline-menu > .list-menu--inline {
    justify-content: center;
  }

  .header--middle-left .header__inline-menu {
    margin-left: 0;
  }
}

.header__menu {
  padding: 0 1rem;
}

.header__menu-item {
  padding: 1.2rem;
  text-decoration: none;
  color: rgb(var(--color-foreground));
}

.header__menu-item:hover {
  color: rgb(var(--color-foreground));
}

.header__menu-item span {
  transition: text-decoration var(--duration-short) ease;
}

.header__menu-item:hover span {
  text-decoration: underline;
  text-underline-offset: 0.3rem;
}

details[open] > .header__menu-item {
  text-decoration: underline;
}

details[open]:hover > .header__menu-item {
  text-decoration-thickness: 0.2rem;
}

details[open] > .header__menu-item .icon-caret {
  transform: rotate(180deg);
}

.header__active-menu-item {
  transition: text-decoration-thickness var(--duration-short) ease;
  color: rgb(var(--color-foreground));
  text-decoration: underline;
  text-underline-offset: 0.3rem;
}

.header__menu-item:hover .header__active-menu-item {
  text-decoration-thickness: 0.2rem;
}

.header__submenu {
  transition: opacity var(--duration-default) ease,
    transform var(--duration-default) ease;
}

.global-settings-popup,
.header__submenu.global-settings-popup {
  border-radius: var(--popup-corner-radius);
  border-color: rgba(var(--color-foreground), var(--popup-border-opacity));
  border-style: solid;
  border-width: var(--popup-border-width);
  box-shadow: var(--popup-shadow-horizontal-offset) var(--popup-shadow-vertical-offset) var(--popup-shadow-blur-radius) rgba(var(--color-shadow), var(--popup-shadow-opacity));
}

.header__submenu.list-menu {
  padding: 2.4rem 0;
}

.header__submenu .header__submenu {
  background-color: rgba(var(--color-foreground), 0.03);
  padding: 0.5rem 0;
  margin: 0.5rem 0;
}

.header__submenu .header__menu-item:after {
  right: 2rem;
}

.header__submenu .header__menu-item {
  justify-content: space-between;
  padding: 0.8rem 2.4rem;
}

.header__submenu .header__submenu .header__menu-item {
  padding-left: 3.4rem;
}

.header__menu-item .icon-caret {
  right: 0.8rem;
}

.header__submenu .icon-caret {
  flex-shrink: 0;
  margin-left: 1rem;
  position: static;
}

header-menu > details,
details-disclosure > details {
  position: relative;
}

@keyframes animateMenuOpen {
  0% {
    opacity: 0;
    transform: translateY(-1.5rem);
  }

  100% {
    opacity: 1;
    transform: translateY(0);
  }
}

.overflow-hidden-mobile,
.overflow-hidden-tablet {
  overflow: hidden;
}

@media screen and (min-width: 750px) {
  .overflow-hidden-mobile {
    overflow: auto;
  }
}

@media screen and (min-width: 990px) {
  .overflow-hidden-tablet {
    overflow: auto;
  }
}

.badge {
  border: 1px solid transparent;
  border-radius: var(--badge-corner-radius);
  display: inline-block;
  font-size: 1.2rem;
  letter-spacing: 0.1rem;
  line-height: 1;
  padding: 0.6rem 1.3rem;
  text-align: center;
  background-color: rgb(var(--color-badge-background));
  border-color: rgba(var(--color-badge-border), var(--alpha-badge-border));
  color: rgb(var(--color-foreground));
  word-break: break-word;
}

.gradient {
  background: rgb(var(--color-background));
  background: var(--gradient-background);
  background-attachment: fixed;
}

@media screen and (forced-colors: active) {
  .icon {
    color: CanvasText;
    fill: CanvasText !important;
  }

  .icon-close-small path {
    stroke: CanvasText;
  }
}

.ratio {
  display: flex;
  position: relative;
  align-items: stretch;
}

.ratio::before {
  content: '';
  width: 0;
  height: 0;
  padding-bottom: var(--ratio-percent);
}

.content-container {
  border-radius: var(--text-boxes-radius);
  border: var(--text-boxes-border-width) solid rgba(var(--color-foreground), var(--text-boxes-border-opacity));
  position: relative;
}

.content-container:after {
  content: '';
  position: absolute;
  top: calc(var(--text-boxes-border-width) * -1);
  right: calc(var(--text-boxes-border-width) * -1);
  bottom: calc(var(--text-boxes-border-width) * -1);
  left: calc(var(--text-boxes-border-width) * -1);
  border-radius: var(--text-boxes-radius);
  box-shadow: var(--text-boxes-shadow-horizontal-offset)
    var(--text-boxes-shadow-vertical-offset)
    var(--text-boxes-shadow-blur-radius)
    rgba(var(--color-shadow), var(--text-boxes-shadow-opacity));
  z-index: -1;
}

.content-container--full-width:after {
  left: 0;
  right: 0;
  border-radius: 0;
}

@media screen and (max-width: 749px) {
  .content-container--full-width-mobile {
    border-left: none;
    border-right: none;
    border-radius: 0;
  }
  .content-container--full-width-mobile:after {
    display: none;
  }
}

.global-media-settings {
  position: relative;
  border: var(--media-border-width) solid rgba(var(--color-foreground), var(--media-border-opacity));
  border-radius: var(--media-radius);
  overflow: visible !important;
  background-color: rgb(var(--color-background));
}

.global-media-settings:after {
  content: '';
  position: absolute;
  top: calc(var(--media-border-width) * -1);
  right: calc(var(--media-border-width) * -1);
  bottom: calc(var(--media-border-width) * -1);
  left: calc(var(--media-border-width) * -1);
  border-radius: var(--media-radius);
  box-shadow: var(--media-shadow-horizontal-offset) var(--media-shadow-vertical-offset) var(--media-shadow-blur-radius) rgba(var(--color-shadow), var(--media-shadow-opacity));
  z-index: -1;
}

.global-media-settings--no-shadow {
  overflow: hidden !important;
}

.global-media-settings--no-shadow:after {
  content: none;
}

.global-media-settings img,
.global-media-settings iframe,
.global-media-settings model-viewer,
.global-media-settings video {
  border-radius: calc(var(--media-radius) - var(--media-border-width));
}

.content-container--full-width,
.global-media-settings--full-width,
.global-media-settings--full-width img {
  border-radius: 0;
  border-left: none;
  border-right: none;
}

/* check for flexbox gap in older Safari versions */
@supports not (inset: 10px) {
  .grid {
    margin-left: calc(-1 * var(--grid-mobile-horizontal-spacing));
  }

  .grid__item {
    padding-left: var(--grid-mobile-horizontal-spacing);
    padding-bottom: var(--grid-mobile-vertical-spacing);
  }

  @media screen and (min-width: 750px) {
    .grid {
      margin-left: calc(-1 * var(--grid-desktop-horizontal-spacing));
    }

    .grid__item {
      padding-left: var(--grid-desktop-horizontal-spacing);
      padding-bottom: var(--grid-desktop-vertical-spacing);
    }
  }

  .grid--gapless .grid__item {
    padding-left: 0;
    padding-bottom: 0;
  }

  @media screen and (min-width: 750px) {
    .grid--peek .grid__item {
      padding-left: var(--grid-mobile-horizontal-spacing);
    }
  }

  .product-grid .grid__item {
    padding-bottom: var(--grid-mobile-vertical-spacing);
  }

  @media screen and (min-width: 750px) {
    .product-grid .grid__item {
      padding-bottom: var(--grid-desktop-vertical-spacing);
    }
  }
}

.font-body-bold {
  font-weight: var(--font-body-weight-bold);
}








/*  ---  'component-search.css'  ---  */
.search__input.field__input {padding-right: 5rem;}
.search__button {right: var(--inputs-border-width);top: var(--inputs-border-width);}
.search__button:focus-visible {background-color: rgb(var(--color-background));z-index: 2;}
.search__button:focus {background-color: rgb(var(--color-background));z-index: 2;}

.search__button .icon {height: 1.8rem;width: 1.8rem;}
/* Remove extra spacing for search inputs in Safari */
input::-webkit-search-decoration {-webkit-appearance: none;}
/*  ---  'component-list-menu.css'  ---  */
.list-menu--right {right: 0;}
.list-menu--disclosure {position: absolute;min-width: 100%;width: 20rem;border: 1px solid rgba(var(--color-foreground), 0.2);box-shadow: -4px 15px 20px 3px rgb(0 0 0 / 50%)!important;}
ul.header__submenu.list-menu.list-menu--disclosure.global-settings-popup li:hover {background-color: #f0f0f0;}
.list-menu--disclosure:focus {outline: none;}
.list-menu__item--active {text-decoration: underline;text-underline-offset: 0.3rem;}
.list-menu__item--active:hover {text-decoration-thickness: 0.2rem;}
.list-menu--disclosure.localization-selector {max-height: 18rem;overflow: auto;width: 10rem;padding: 0.5rem;}

/*  ---  'component-price.css'  ---  */
.price {font-size: 1.6rem;letter-spacing: 0.1rem;line-height: calc(1 + 0.5 / var(--font-body-scale));color: rgb(var(--color-foreground));}
.price > * {display: inline-block;vertical-align: top;}
.price.price--unavailable {visibility: hidden;}
.price--end {text-align: right;}
.price .price-item {margin: 0 1rem 0 0;}
.price__regular .price-item--regular {margin-right: 0;}
.price:not(.price--show-badge) .price-item--last:last-of-type {margin: 0;}
@media screen and (min-width: 750px) {
  .price {margin-bottom: 0;}
}
.price--large {font-size: 1.6rem;line-height: calc(1 + 0.5 / var(--font-body-scale));letter-spacing: 0.13rem;}
@media screen and (min-width: 750px) {
  .price--large {font-size: 1.8rem;}
}
.price--sold-out .price__availability,.price__regular {display: block;}
.price__availability,.price .price__badge-sale,.price .price__badge-sold-out,.price--on-sale .price__regular,.price--on-sale .price__availability {display: none;}
.price--sold-out .price__badge-sold-out,.price--on-sale .price__badge-sale {display: inline-block;}
.price--on-sale .price__sale {display: initial;flex-direction: row;flex-wrap: wrap;}
.price--center {display: initial;justify-content: center;}
.price--on-sale .price-item--regular {text-decoration: line-through;color: rgba(var(--color-foreground), 0.75);font-size: 1.3rem;}
.unit-price {display: block;font-size: 1.1rem;letter-spacing: 0.04rem;line-height: calc(1 + 0.2 / var(--font-body-scale));margin-top: 0.2rem;text-transform: uppercase;color: rgba(var(--color-foreground), 0.7);}


/*  ---  'component-rte.css'  ---  */
.rte:after{clear:both;content:"";display:block}
.rte>p:first-child{margin-top:0}
.rte>p:last-child{margin-bottom:0}
.rte table{table-layout:fixed}
@media screen and (min-width: 750px){
	.rte table td{padding-left:1.2rem;padding-right:1.2rem}
}
.rte img{height:auto;max-width:100%;border:var(--media-border-width) solid rgba(var(--color-foreground),var(--media-border-opacity));border-radius:var(--media-radius);box-shadow:var(--media-shadow-horizontal-offset) var(--media-shadow-vertical-offset) var(--media-shadow-blur-radius) rgba(var(--color-shadow),var(--media-shadow-opacity));margin-bottom:var(--media-shadow-vertical-offset)}
.rte ul{padding-left:2rem}
.rte li{list-style:inherit}
.rte li:last-child{margin-bottom:0}
.rte a{color:rgba(var(--color-link),var(--alpha-link));text-underline-offset:.3rem;text-decoration-thickness:.1rem;transition:text-decoration-thickness var(--duration-short) ease}
.rte a:hover{color:rgb(var(--color-link));text-decoration-thickness:.2rem}
.rte blockquote{display:inline-flex}
.rte blockquote>*{margin:-.5rem 0}


/*  ---  'component-slider.css'  ---  */
slider-component{--desktop-margin-left-first-item: max(5rem, calc((100vw - var(--page-width) + 10rem - var(--grid-desktop-horizontal-spacing)) / 2));position:relative;display:block}
slider-component.slider-component-full-width{--desktop-margin-left-first-item: 1.5rem}
@media screen and (max-width: 749px){slider-component.page-width{padding:0 1.5rem}
}
@media screen and (min-width: 749px) and (max-width: 990px){slider-component.page-width{padding:0 5rem}
}
@media screen and (max-width: 989px) {
	.no-js slider-component .slider{padding-bottom:3rem}
}
.slider__slide{--focus-outline-padding: .5rem;--shadow-padding-top: calc(var(--shadow-vertical-offset) * -1 + var(--shadow-blur-radius));--shadow-padding-bottom: calc(var(--shadow-vertical-offset) + var(--shadow-blur-radius));scroll-snap-align:start;flex-shrink:0;padding-bottom:0}
@media screen and (max-width: 749px) {
	.slider.slider--mobile{position:relative;flex-wrap:inherit;overflow-x:auto;overflow-y:hidden;scroll-snap-type:x mandatory;scroll-behavior:smooth;scroll-padding-left:1.5rem;-webkit-overflow-scrolling:touch;margin-bottom:1rem}
.slider.slider--mobile .slider__slide{margin-bottom:0;padding-top:max(var(--focus-outline-padding),var(--shadow-padding-top));padding-bottom:max(var(--focus-outline-padding),var(--shadow-padding-bottom))}
.slider.slider--mobile.contains-card--standard .slider__slide:not(.collection-list__item--no-media){padding-bottom:var(--focus-outline-padding)}
.slider.slider--mobile.contains-content-container .slider__slide{--focus-outline-padding: 0rem}
}
@media screen and (min-width: 750px) {
	.slider.slider--tablet-up{position:relative;flex-wrap:inherit;overflow-x:auto;overflow-y:hidden;scroll-snap-type:x mandatory;scroll-behavior:smooth;scroll-padding-left:1rem;-webkit-overflow-scrolling:touch}
.slider.slider--tablet-up .slider__slide{margin-bottom:0}
}
@media screen and (max-width: 989px) {
	.slider.slider--tablet{position:relative;flex-wrap:inherit;overflow-x:auto;overflow-y:hidden;scroll-snap-type:x mandatory;scroll-behavior:smooth;scroll-padding-left:1.5rem;-webkit-overflow-scrolling:touch;margin-bottom:1rem}
.slider.slider--tablet .slider__slide{margin-bottom:0;padding-top:max(var(--focus-outline-padding),var(--shadow-padding-top));padding-bottom:max(var(--focus-outline-padding),var(--shadow-padding-bottom))}
.slider.slider--tablet.contains-card--standard .slider__slide:not(.collection-list__item--no-media){padding-bottom:var(--focus-outline-padding)}
.slider.slider--tablet.contains-content-container .slider__slide{--focus-outline-padding: 0rem}
}
.slider--everywhere{position:relative;flex-wrap:inherit;overflow-x:auto;overflow-y:hidden;scroll-snap-type:x mandatory;scroll-behavior:smooth;-webkit-overflow-scrolling:touch;margin-bottom:1rem}
.slider.slider--everywhere .slider__slide{margin-bottom:0;scroll-snap-align:center}
@media screen and (min-width: 990px) {
	.slider-component-desktop.page-width{max-width:none}
.slider--desktop{position:relative;flex-wrap:inherit;overflow-x:auto;overflow-y:hidden;scroll-snap-type:x mandatory;scroll-behavior:smooth;-webkit-overflow-scrolling:touch;margin-bottom:1rem;scroll-padding-left:var(--desktop-margin-left-first-item)}
.slider.slider--desktop .slider__slide{margin-bottom:0;padding-top:max(var(--focus-outline-padding),var(--shadow-padding-top));padding-bottom:max(var(--focus-outline-padding),var(--shadow-padding-bottom))}
.slider--desktop .slider__slide:first-child{margin-left:var(--desktop-margin-left-first-item);scroll-margin-left:var(--desktop-margin-left-first-item)}
.slider.slider--desktop .slider__slide:last-child{margin-right:5rem}
.slider-component-full-width .slider--desktop{scroll-padding-left:1.5rem}
.slider-component-full-width .slider--desktop .slider__slide:first-child{margin-left:1.5rem;scroll-margin-left:1.5rem}
.slider-component-full-width .slider--desktop .slider__slide:last-child{margin-right:1.5rem}
.slider--desktop.grid--5-col-desktop .grid__item{width:calc((100% - var(--desktop-margin-left-first-item)) / 5 - var(--grid-desktop-horizontal-spacing) * 2)}
.slider--desktop.grid--4-col-desktop .grid__item{width:calc((100% - var(--desktop-margin-left-first-item)) / 4 - var(--grid-desktop-horizontal-spacing) * 3)}
.slider--desktop.grid--3-col-desktop .grid__item{width:calc((100% - var(--desktop-margin-left-first-item)) / 3 - var(--grid-desktop-horizontal-spacing) * 4)}
.slider--desktop.grid--2-col-desktop .grid__item{width:calc((100% - var(--desktop-margin-left-first-item)) / 2 - var(--grid-desktop-horizontal-spacing) * 5)}
.slider--desktop.grid--1-col-desktop .grid__item{width:calc((100% - var(--desktop-margin-left-first-item)) - var(--grid-desktop-horizontal-spacing) * 9)}
.slider.slider--desktop.contains-card--standard .slider__slide:not(.collection-list__item--no-media){padding-bottom:var(--focus-outline-padding)}
.slider.slider--desktop.contains-content-container .slider__slide{--focus-outline-padding: 0rem}
}
@media (prefers-reduced-motion) {
	.slider{scroll-behavior:auto}
}
.slider{scrollbar-color:rgb(var(--color-foreground)) rgba(var(--color-foreground),.04);-ms-overflow-style:none;scrollbar-width:none}
.slider::-webkit-scrollbar{height:.4rem;width:.4rem;display:none}
.no-js .slider{-ms-overflow-style:auto;scrollbar-width:auto}
.no-js .slider::-webkit-scrollbar{display:initial}
.slider::-webkit-scrollbar-thumb{background-color:rgb(var(--color-foreground));border-radius:.4rem;border:0}
.slider::-webkit-scrollbar-track{background:rgba(var(--color-foreground),.04);border-radius:.4rem}
.slider-counter{display:flex;justify-content:center;min-width:4.4rem}
@media screen and (min-width: 750px) {
	.slider-counter--dots{margin:0 1.2rem}
}
.slider-counter__link{padding:1rem}
@media screen and (max-width: 749px) {
	.slider-counter__link{padding:.7rem}
}
.slider-counter__link--dots .dot{width:1rem;height:1rem;border-radius:50%;border:.1rem solid rgba(var(--color-foreground),.5);padding:0;display:block}
.slider-counter__link--active.slider-counter__link--dots .dot{background-color:rgb(var(--color-foreground))}
@media screen and (forced-colors: active) {
	.slider-counter__link--active.slider-counter__link--dots .dot{background-color:CanvasText}
}
.slider-counter__link--dots:not(.slider-counter__link--active):hover .dot{border-color:rgb(var(--color-foreground))}
.slider-counter__link--dots .dot,.slider-counter__link--numbers{transition:transform .2s ease-in-out}
.slider-counter__link--active.slider-counter__link--numbers,.slider-counter__link--dots:not(.slider-counter__link--active):hover .dot,.slider-counter__link--numbers:hover{transform:scale(1.1)}
.slider-counter__link--numbers{color:rgba(var(--color-foreground),.5);text-decoration:none}
.slider-counter__link--numbers:hover{color:rgb(var(--color-foreground))}
.slider-counter__link--active.slider-counter__link--numbers{text-decoration:underline;color:rgb(var(--color-foreground))}
.slider-buttons{display:flex;align-items:center;justify-content:center}
@media screen and (min-width: 990px) {
	.slider:not(.slider--everywhere):not(.slider--desktop)+.slider-buttons{display:none}
}
@media screen and (max-width: 989px) {
	.slider--desktop:not(.slider--tablet)+.slider-buttons{display:none}
}
@media screen and (min-width: 750px) {
	.slider--mobile+.slider-buttons{display:none}
}
.slider-button{color:rgba(var(--color-foreground),.75);background:transparent;border:none;cursor:pointer;width:44px;height:44px;display:flex;align-items:center;justify-content:center}
.slider-button:not([disabled]):hover{color:rgb(var(--color-foreground))}
.slider-button .icon{height:.6rem}
.slider-button[disabled] .icon{color:rgba(var(--color-foreground),.3);cursor:not-allowed}
.slider-button--next .icon{transform:rotate(-90deg)}
.slider-button--prev .icon{transform:rotate(90deg)}
.slider-button--next:not([disabled]):hover .icon{transform:rotate(-90deg) scale(1.1)}
.slider-button--prev:not([disabled]):hover .icon{transform:rotate(90deg) scale(1.1)}

.spd__flxiSlider.slideshow.banner.snap {scroll-behavior:unset;}

/*  ---  'component-slideshow.css'  ---  */
slideshow-component{position:relative;display:flex;flex-direction:column}
@media screen and (max-width: 989px) {
	.no-js slideshow-component .slider{padding-bottom:3rem}
}
slideshow-component .slideshow.banner{flex-direction:row;flex-wrap:nowrap;margin:0;gap:0}
.slideshow__slide{padding:0;position:relative;display:flex;flex-direction:column}
@media screen and (max-width: 749px) {
	.slideshow--placeholder.banner--mobile-bottom.banner--adapt_image .slideshow__media,.slideshow--placeholder.banner--adapt_image:not(.banner--mobile-bottom){height:28rem}
}
@media screen and (min-width: 750px) {
	.slideshow--placeholder.banner--adapt_image{height:56rem}
}
.slideshow__text.banner__box{display:flex;flex-direction:column;justify-content:center;max-width:54.5rem}
.slideshow__text>*{max-width:100%}
@media screen and (max-width: 749px){slideshow-component.page-width .slideshow__text{border-right:var(--text-boxes-border-width) solid rgba(var(--color-foreground),var(--text-boxes-border-opacity));border-left:var(--text-boxes-border-width) solid rgba(var(--color-foreground),var(--text-boxes-border-opacity))}
.banner--mobile-bottom .slideshow__text.banner__box{max-width:100%}
.banner--mobile-bottom .slideshow__text-wrapper{flex-grow:1}
.banner--mobile-bottom .slideshow__text.banner__box{height:100%}
.banner--mobile-bottom .slideshow__text .button{flex-grow:0}
.slideshow__text.slideshow__text-mobile--left{align-items:flex-start;text-align:left}
.slideshow__text.slideshow__text-mobile--right{align-items:flex-end;text-align:right}
}
@media screen and (min-width: 750px) {
	.slideshow__text.slideshow__text--left{align-items:flex-start;text-align:left}
.slideshow__text.slideshow__text--right{align-items:flex-end;text-align:right}
}
.slideshow:not(.banner--mobile-bottom) .slideshow__text-wrapper{height:100%}
@media screen and (min-width: 750px) {
	.slideshow__text-wrapper.banner__content{height:100%;padding:5rem}
}
.slideshow__controls{border:.1rem solid rgba(var(--color-foreground),.08)}
.slideshow__controls--top{order:2;z-index:1}
@media screen and (max-width: 749px) {
	.slideshow__controls--border-radius-mobile{border-bottom-right-radius:var(--text-boxes-radius);border-bottom-left-radius:var(--text-boxes-radius)}
}
.spaced-section--full-width:last-child slideshow-component:not(.page-width) .slideshow__controls{border-bottom:none}
@media screen and (min-width: 750px) {
	.slideshow__controls{position:relative}
}
slideshow-component:not(.page-width) .slider-buttons{border-right:0;border-left:0}
.slideshow__control-wrapper{display:flex}
.slideshow__autoplay{position:absolute;right:0;border-left:none;display:flex;justify-content:center;align-items:center}
@media screen and (max-width: 749px){slideshow-component.page-width .slideshow__autoplay{right:1.5rem}
}
@media screen and (min-width: 750px) {
	.slideshow__autoplay.slider-button{position:inherit;margin-left:.6rem;padding:0 0 0 .6rem;border-left:.1rem solid rgba(var(--color-foreground),.08)}
}
.slideshow__autoplay .icon.icon-play,.slideshow__autoplay .icon.icon-pause{display:block;position:absolute;opacity:1;transform:scale(1);transition:transform .15s ease,opacity .15s ease;width:.8rem;height:1.2rem}
.slideshow__autoplay .icon.icon-play{height:1rem}
.slideshow__autoplay path{fill:rgba(var(--color-foreground),.75)}
.slideshow__autoplay:hover path{fill:rgb(var(--color-foreground))}
@media screen and (forced-colors: active) {
	.slideshow__autoplay path,.slideshow__autoplay:hover path{fill:CanvasText}
}
.slideshow__autoplay:hover svg{transform:scale(1.1)}
.slideshow__autoplay--paused .icon-pause,.slideshow__autoplay:not(.slideshow__autoplay--paused) .icon-play{visibility:hidden;opacity:0;transform:scale(.8)}



/*  ---  'component-accordion.css'  ---  */
.accordion summary{display:flex;position:relative;line-height:1;padding:1.5rem 0}
.accordion .summary__title{display:flex;flex:1}
.accordion .summary__title+.icon-caret{height:calc(var(--font-heading-scale) * .6rem)}
.accordion+.accordion{margin-top:0;border-top:none}
.accordion {margin-top:2.5rem;margin-bottom:0;border-top:.1rem solid rgba(var(--color-foreground),.08);border-bottom:.1rem solid rgba(var(--color-foreground),.08); width:100%;}
.accordion__title{display:inline-block;max-width:calc(100% - 6rem);min-height:1.6rem;margin:0;word-break:break-word}
.accordion .icon-accordion{align-self:center;fill:rgb(var(--color-foreground));height:calc(var(--font-heading-scale) * 2rem);margin-right:calc(var(--font-heading-scale) * 1rem);width:calc(var(--font-heading-scale) * 2rem)}
.accordion details[open]>summary .icon-caret{transform:rotate(180deg)}
.accordion__content{margin-bottom:1.5rem;word-break:break-word;overflow-x:auto;padding:0 .6rem}
.accordion__content img{max-width:100%}




/*  ---  'component-loading-overlay.css'  ---  */

.loading-overlay {
  position: absolute;
  z-index: 1;
  width: 1.8rem;
}

@media screen and (max-width: 749px) {
  .loading-overlay {
    top: 0;
    right: 0;
  }
}

@media screen and (min-width: 750px) {
  .loading-overlay {
    left: 0;
  }
}

.loading-overlay__spinner {
  width: 1.8rem;
  display: inline-block;
}

.spinner {
  animation: rotator 1.4s linear infinite;
}

@keyframes rotator {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(270deg);
  }
}

.path {
  stroke-dasharray: 280;
  stroke-dashoffset: 0;
  transform-origin: center;
  stroke: rgb(var(--color-foreground));
  animation: dash 1.4s ease-in-out infinite;
}

@media screen and (forced-colors: active) {
  .path{
    stroke: CanvasText;
  }
}

@keyframes dash {
  0% {
    stroke-dashoffset: 280;
  }
  50% {
    stroke-dashoffset: 75;
    transform: rotate(135deg);
  }
  100% {
    stroke-dashoffset: 280;
    transform: rotate(450deg);
  }
}

.loading-overlay:not(.hidden) + .cart-item__price-wrapper,
.loading-overlay:not(.hidden) ~ cart-remove-button {
  opacity: 50%;
}

.loading-overlay:not(.hidden) ~ cart-remove-button {
  pointer-events: none;
  cursor: default;
}

/*   SIZE GUIDE */
  .sizeGuideButton{
/*   	width: auto;
    text-align: right;
    background-color: transparent;
    text-transform: unset; */
/*     padding: 10px 0px 6px 0px; */
/*     letter-spacing: 0;
    cursor : pointer;
    position: absolute;
    right: 0;
    top: -15px; */
  }
  .size-guide-btn{
  	text-align: right;
    top: -73px;
    position: relative;
  }
  .sizeGuideButton:hover{
  	text-decoration : underline;
  }
  .size-guide-btn{
/*     max-width : 37rem; */
  	position : relative;
  }
  .size-guide-btn a,
  .size-guide-btn a:hover{
  	text-decoration : none ;
    color: var(--color-base-heading); 
  }
  .sizeGuide{
  	width: 100%;
    max-width: 350px;
    position: fixed;
    background-color: #fff;
    z-index: 101;
    right: 0;
    min-height: 100vh;
    top: 0;
    -webkit-transform: translateX(100%);
    transform: translateX(100%);
    -webkit-transition: .5s;
    transition: .5s;
    -webkit-box-shadow: 0 0 5px rgb(0 0 0 / 20%);
    box-shadow: 0 0 5px rgb(0 0 0 / 20%);
    overflow-x: scroll;
    height: 100%;
    padding: 15px;
    margin : 0 !important;
  }
  body.guide-open .sizeGuide-overlap {
      z-index: 100;
  }
  .sizeGuide-overlap{
  	position: fixed;
    width: 100%;
    height: 100vh;
    background-color: #b1b1b133;
    -webkit-transition: .5s;
    transition: .5s;
    top: -17px;
    left: 0;
    z-index: 99;
  }
  body.guide-open .sizeGuide-overlap{
  	display : block !important;
  }
  body.guide-open .sizeGuide {
      -webkit-transform: none;
      transform: none;
  }
  .sizeGuide .heading{
  	text-align : center;
  }
  .sizeGuide .heading p{
  	font-weight: bold;
    font-size: 22px;
  }
  .sizeGuide .sec-heading p{
  	font-weight: bold;
    font-size : 20
  }
  .sizeGuide .sec-heading{
  	text-align : left;
  }
  
  .guide-content table{
  	width : 100%;
  }
  .guide-content table th{
  	color : white;
    background-color :black;
  }
  .guide-content table tr{
  	color : black;
  }
  .guide-content table tr:nth-child(even) {
    background: #e7e6e6;
  }
  .sizeGuide__close{
  	position: absolute;
    top: 1px;
    right: 8px;
    font-size: 20px;
    cursor: pointer;
    font-weight: bold;
  }
/*   SIZE GUIDE */ 
  
  
    /*   Related Products */
  color-swatches .color-swatches span {
    min-width: 10%;
    max-width: 20%;
    max-height: 20%;
    cursor: pointer;
    min-height: 10%;
    margin-right: 20px;
  }
  color-swatches .color-swatches {
  	width: 100%;
    height: 58px;
    display: flex;
    max-width: var(--product-form-width);
  }
  .swatch .swatch-element {
      float: left;
      -webkit-transform: translateZ(0);
      -webkit-font-smoothing: antialiased;
      margin: 0px 10px 10px 0;
      position: relative;
  }
  .swatch label {
    -webkit-border-radius: 50%;
    -moz-border-radius: 50%;
    border-radius: 50%;
    float: left;
    min-width: 20px!important;
    height: 20px !important;
    margin: 0;
    background-color: #ddd;
    font-size: 13px;
    text-align: center;
    line-height: 35px;
    white-space: nowrap;
    text-transform: uppercase;
    cursor : pointer;
  }
  .color.swatch-element label {
      padding: 0;
  }
  .clearfix1 {
    overflow: auto;
  }
  .swatch-heading{
  	font-weight: bold;
    padding-bottom: 10px;
  }  
  
  /*   Related Products */
  @media (max-width:750px){
    .footer-block.text-5{
      margin-top: 38px !important;
    }
    .footer-block.opz__social-6 {
      margin-top: 20px !important;
    }
    .product-popup-modal__content{
      width: 90% !important;
      height: 80% !important;
    }
    .product-popup-modal__button{
    	height: 9.4rem !important;
    }
  }
  
  .color_text{
  	color: rgb(110, 110, 110);
    font-size:16px;
  }
  @media screen and (max-width: 750px) {
    .financeGrid-wrapper .financeGrid{
    	margin: 20px 0 0 0px !important;
    }
    modal-opener.finance-paragraph{
    	width: 43% !important;
    }
/*     modal-opener.finance-paragraph .spd-finance-logo {
      width: 56px;
    } */
  }  
  
  @media screen and (min-width: 750px) {
    .cart-item__details p.spd__badge{
      max-width: 145px !important;
      min-width: 145px !important;
    }
  }

  .video-container {
        position: relative;
        padding-bottom: 56.25%; /* 16:9 */
        height: 0;
  }
  .video-container iframe,
  .video-container video{
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
  }
  .video-container iframe{
  		border: 0;
    	border-radius: 5px;
  }
  @media (max-width: 749px) {
    .prodCallout.tag__new{
      top: 10px;
      left: 10px;
    }
  }

.cart__ctas .button{
      color : black;
  }
.cart__warnings a{
      color : black;
      font-weight : bold;
}
div[data-prdpavail="false"]+button#SI_trigger{
  display: unset !important; 
  margin-top : 10px;
}

button#SI_trigger {
/*     display: unset !important; */
    background: #f87c56;
  color : black;
    font-weight : bold;
}
.si-reset .SI_trigger{
    font-family : unset !important;
    font-weight : bold !important;
    color : black !important;
    text-shadow: unset;
}
#SIModal #submit-btn{
    color : black; 
}
/*
tabs css start
*/
.tab {
  overflow: hidden;
/*   border: 1px solid #ccc;
  background-color: #f1f1f1; */
}

/* Style the buttons inside the tab */
.tab button {
  background-color: inherit;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 14px 16px;
  transition: 0.3s;
  font-size: 17px;
}

/* Create an active/current tablink class */
.tab button.active {
  text-decoration: underline;
}

/* Style the tab content */
.tabcontent {
  display: none;
  padding: 6px 12px;
  border-top: none;
}

/* Style the buttons inside the tab */
.tab button {
  background-color: inherit;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 14px 16px;
  transition: 0.3s;
  font-size: 17px;
}

/* Change background color of buttons on hover */
.tab button:hover {
  text-decoration: underline;
}

/* Create an active/current tablink class */
.tab button.active {
  text-decoration: underline;
}

/* Style the tab content */
.tabcontent {
  display: none;
  padding: 6px 12px;
  border-top: none;
}

.html_with_image{
    display: flex;
    flex-direction: column;
    align-items: center;
}
@media only screen and (min-width: 48rem){
  .html_with_image{
      flex-direction: row;
      justify-content: space-between;
  }
}
.tabcontent .table-wrapper {
  overflow: auto;
    max-width: 100%;
    margin: 2rem 0;
    width: 100%;
}
.html_with_image img {
    max-width: 170px;
    margin-top: 2rem;
    height: 100%;
}
.guide-content-extend.x tr p {
    margin: 0;
    padding: 2px 3px;
}
.guide-content-extend.x tr h5 {
    margin: 0;
    padding: 8px 1px;
}
.only-image img {
    max-width: 500px;
    margin-top: 2rem;
    height: 100%;
}
/*
tabs css end
*/
.tab.innertab{
  margin-bottom : 20px;
}
.tab button.tablinksInner.active{
    text-decoration: none;
    background : black;
    color : white;
}
.tab button.tablinksInner{
  border: 1px solid black;
}
.sizeGuide.sizeGuideExtended{
    max-width: 550px;
  }
  /* 
Tabs and accordion 2
*/

  .ootb-tabcordion {
  background: #fff;
/*   margin: 1rem auto 4rem auto; */
}
.ootb-tabcordion.has-tabs .ootb-tabcordion--tabs {
  opacity: 1;
  height: auto;
  visibility: visible;
}
.ootb-tabcordion.has-tabs .ootb-tabcordion--entry {
  min-height: 0;
}
.ootb-tabcordion.has-tabs .ootb-tabcordion--entry::before {
  display: none;
}
.ootb-tabcordion.has-tabs .ootb-tabcordion--entry.is-active .ootb-tabcordion--entry-content {
  opacity: 1;
  transition: opacity 400ms ease-in-out;
}
.ootb-tabcordion.has-tabs .ootb-tabcordion--entry .ootb-tabcordion--entry-content {
  opacity: 0;
  transition: opacity 400ms ease-in-out;
}

.ootb-tabcordion--tabs {
  opacity: 0;
  height: 0;
  visibility: hidden;
  display: flex;
  flex-flow: wrap;
  margin: 0;
  list-style: none;
  padding: 0;
}
.ootb-tabcordion--tabs .tab {
  display: block;
  background: transparent;
  color: #dfdada;
  padding: 0.5rem 5rem;
  font-size: 16px;
  font-weight: 300;
  font-family: "Roboto", sans-serif;
  margin: 0 0 1px 7px;
  border: none;
  border-bottom: 1px solid;
  cursor: pointer;
/* -webkit-box-flex: 2;  */
/*   flex-grow: 2; */
}
.ootb-tabcordion--tabs .tab:hover, .ootb-tabcordion--tabs .tab:focus {
  background: transparent;
  border-bottom : 1px solid;
  color : black;
}
.ootb-tabcordion--tabs .tab.is-active {
   background: transparent;
  border-bottom : 1px solid;
  color : black;
}
.ootb-tabcordion--tabs .tab.is-active:hover, .ootb-tabcordion--tabs .tab.is-active:focus {
  background: transparent;
  border-bottom : 1px solid;
  color : black;
}

.ootb-tabcordion--entry {
  overflow: hidden;
}
.ootb-tabcordion--entry::before {
  position: relative;
  content: attr(data-title);
  cursor: pointer;
  z-index: 1;
  background: transparent;
  color: black;
  padding: 0.5rem 1rem;
  display: block;
  border-bottom: 1px solid;
}
.ootb-tabcordion--entry:hover, .ootb-tabcordion--entry:focus {
  outline: none;
}
.ootb-tabcordion--entry:hover::before, .ootb-tabcordion--entry:focus::before {
  background: #535353;
}
.ootb-tabcordion--entry.is-active .ootb-tabcordion--entry-content {
  margin-top: 0;
  height: auto;
  opacity: 1;
  transition: margin 400ms ease-out -100ms;
}
.ootb-tabcordion--entry.is-active::before {
  background: transparent;
}
.ootb-tabcordion--entry.is-active:hover::before, .ootb-tabcordion--entry.is-active:focus::before {
/*   background: #1c9fff; */
}

.ootb-tabcordion--entry-container {
  overflow: hidden;
  margin-bottom: 1px;
}

.ootb-tabcordion--entry-content {
  position: relative;
  margin-top: -100%;
  height: 0;
  opacity: 0;
  transition: margin 500ms ease-in;
  padding: 1rem;
}
.ootb-tabcordion--entry-content a.more {
  color: #444;
}
.ootb-tabcordion--entry-content a.more:hover {
  color: #3bacff;
}
  .ootb-tabcordion--entry-content table{
    width  : 100%;
    border-collapse: collapse;
  }
  .ootb-tabcordion{
    width  : 100%;
  }  
  @media only screen and (min-device-width: 750px)
  {
  .ootb-tabcordion--tabs {
      display: grid;
      grid-auto-flow: column;
  }
  }
  .ootb-tabcordion--entry-content table.minimal.sizes tr td {
      border-bottom: 1px solid;
      padding: 10px 16px;
  }
  
  @media screen and (max-width: 749px) {
    section.ootb-tabcordion--entry {
      position: relative;
  }
    .ootb-tabcordion--entry-container {
      overflow-x: scroll;
    }
    .ootb-tabcordion--entry.is-active::after{
      content : '\2212';
    }
    .ootb-tabcordion--entry::after {
      content: "\002B";
      position: absolute;
      right: 18px;
      top: -10px;
      font-size: 3rem;
    }
  }
    /* 
Tabs and accordion 2 end
*/
bundle-selects label{
  position : relative;
}
summary.has-error,
bundle-selects:not(.selects):not(.radios) label.has-error{
    border  :2px solid red;
/*     margin-bottom: -2px; */
    border-radius: 7px;
    padding-left: 5px;
}
summary.is-checked,
bundle-selects:not(.selects):not(.radios) label.is-checked{
    border-radius: 7px;
    border  :2px solid green;
    padding-left: 5px;
}
summary.is-checked::after,
bundle-selects:not(.selects):not(.radios) label.is-checked::after{
    content: "";
    background: green;
    position: absolute;
    width: 1.2em;
    height: 1.2em;
    top: 50%;
    right: 45px;
    border-radius: 2em;
    transform: translate(-16%,-50%);
    z-index: 0;
}
summary.is-checked::before,
bundle-selects:not(.selects):not(.radios) label.is-checked::before{
    background-color: #fff;
    color: var(--icon-color);
    font-family: none;
    content: "";
    width: 15px;
    height: 15px;
    transform: translate(var(--transform-x),var(--transform-y)) rotate(var(--icon-rotate));
    border-radius: var(--icon-width);
    z-index: 1;
    position: absolute;
    top: 50%;
    right: 52px;
}
summary.is-checked::before,
bundle-selects:not(.selects):not(.radios) label.is-checked::before{
    -webkit-mask-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' class='icon fa-icon icon-check-solid' fill='currentColor' viewBox='0 0 512 512'%3E%3Cpath d='M173.898 439.404l-166.4-166.4c-9.997-9.997-9.997-26.206 0-36.204l36.203-36.204c9.997-9.998 26.207-9.998 36.204 0L192 312.69 432.095 72.596c9.997-9.997 26.207-9.997 36.204 0l36.203 36.204c9.997 9.997 9.997 26.206 0 36.204l-294.4 294.401c-9.998 9.997-26.207 9.997-36.204-.001z'%3E%3C/path%3E%3C/svg%3E");
}
@media screen and (max-width: 749px) {
  summary.is-checked:before,
bundle-selects:not(.selects):not(.radios) label.is-checked:before{
    right: 50px;
  }
}
