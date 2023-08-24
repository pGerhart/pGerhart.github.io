---
date: {{ .Date }}
title: "{{ replace .Name "-" " " | title }}"
draft: false
math: true
resources:
    images:
    - name: "Image"
      src: "/images/blog/"
---
