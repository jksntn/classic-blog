---
title: "{{ replace .Name "-" " " | humanize }}"
date: {{ dateFormat "2006-01-02" .Date }}
author: jksntn
slug: {{ .Name | urlize }}
images: 
 - /{{ .Name | urlize }}/
description:
draft: true
categories:
  -
tags:
  -
---
tl;dr

<!--more-->
