---
title: "{{ replace .Name "-" " " | title }}" # Uses the filename as the default title
date: {{ .Date }} # Automatically sets the current date and time
draft: false # Marks the content as a draft initially
summary: "" # Optional summary field
tags: [] # Optional tags
categories: [] # Optional categories
---
