
# @neuri/primeflex-containers

Lightweight library that adds `.container` and `.container-fluid` classes compatible with PrimeFlex.

## Installation

```bash
npm i @neuri/primeflex-containers
```

or via CDN

```html
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/npm/@neuri/primeflex-containers@1.0.0/dist/primeflex-containers.min.css"
/>
```

## Usage

```html
<link rel="stylesheet" href="https://unpkg.com/primeflex@latest/primeflex.css">
<!-- PrimeFlex -->
<link rel="stylesheet" href="primeflex-containers.min.css" />
<!-- This package -->

<div class="container">
  <div class="grid">
    <div class="col">Content</div>
  </div>
</div>

<div class="container-fluid">
  <section>Full width</section>
</div>
```

## Included Variants

* `.container-nogutter`
* `.container-lg`
* `.container-fluid-max`

## Build

`npm run build` → generates `dist/*`

## License

This project is licensed under the MIT License.
