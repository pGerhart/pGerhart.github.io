---
date: {{ .Date }}
title: "{{ replace .Name "-" " " | title }}"
draft: false
resources:
    images:
    - name: "Image"
      src: "/images/blog/"
---
