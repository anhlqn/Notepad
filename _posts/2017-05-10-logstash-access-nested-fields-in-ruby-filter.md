---
layout: post
published: true
mathjax: false
featured: false
comments: false
title: 'Logstash: Access nested fields in Ruby filter'
categories:
  - IT
tags: elastic logstash
---
The syntax to access nested fields in Ruby filter is quite similar to the one we use in mutate filter	
    
    event['parent_field']['child_field']
