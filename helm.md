---
title: Helm
description: 
published: true
date: 2026-04-01T16:36:14.128Z
tags: 
editor: markdown
dateCreated: 2026-03-29T21:09:49.098Z
---

# Helm

### Descarga un chart de helm

```
helm repo add kite https://kite-org.github.io/kite/ && helm repo update  
helm pull kite/kite --untar
```

### Instalar desde local
```
helm install kite kite/ -f kite/values.yaml -n kite --create-namespace
```