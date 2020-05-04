# Codefresh Pipeline Modules

A Codefresh module is a container for packaging pipelines for reuse, extension and composition.

This over engineered example demonstrates some ideas relating to:

## Features

* pipeline templating (go templates)
* pipeline dependencies (similar to helm 3 dependencies)
* pipeline inheritance (similar to jenkinsx)
* pipeline overlays (similar to openapi 3.1 overlay)
* variable schemas (scheme backed varibales provide a typed consumer API)

## Todo

* multiple pipelines per module 
* evaluate ytt as substitute for go templates
* define lifecycle: init > prerender > render > postrender
* plugins: swappable template provider
* hooks

## inspiration

* helm
* openapi
