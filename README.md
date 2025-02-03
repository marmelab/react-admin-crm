# Atomic CRM

[Atomic CRM](https://marmelab.com/atomic-crm/) is a CRM template built with [react-admin](https://github.com/marmelab/react-admin) and Supabse. You can test it online at https://marmelab.com/react-admin-crm.

https://user-images.githubusercontent.com/99944/116970434-4a926480-acb8-11eb-8ce2-0602c680e45e.mp4

This repo stores a local demo of Atomic CRM. React-admin usually requires a REST/GraphQL server to provide data. In this demo however, the API is simulated by the browser (using [FakeRest](https://github.com/marmelab/FakeRest)). The source data is generated at runtime by a package called [data-generator](https://github.com/marmelab/react-admin/tree/master/examples/data-generator).

To explore the source code, head to [marmelab/atomic-crm](https://github.com/marmelab/atomic-crm).

## How to run

This demo is a static website, so you just need a web server to serve the HTML, JS and JSS files. For example, with Python:

```sh
python3 -m http.server
```
