---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

## Investigating Entity Resolution in Text-to-SQL Models
April 2024\ 
<u><a href="https://jmoorefield.github.io/files/investigatingentityresolution.pdf" target="_blank">PDF available here</a>.</u>

This project explores using SQL views generated
by object-relational mapping (ORM) as input to a Text-to-SQL
model. This novel technique is intended to ease entity resolution,
the key to a model’s understanding of how database objects
can be described in natural language. I constructed a software
pipeline to automatically generate views to represent the entities
in a given database and generate corresponding training data to
be fed into an encoder-decoder model. My undergraduate thesis
provides an in-depth explanation of leveraging object-relational
mapping as the cornerstone of creating the views. While
experimental results were inconclusive, I discuss factors that may
have influenced the model’s performance and future directions
for the technique.



## Leveraging Object-Relational Mapping to Reduce Entity Impedance In Natural Language Interfaces for Relational Databases 
April 2022\
<u><a href="https://jmoorefield.github.io/files/leveragingobject-relational.pdf" target="_blank">PDF available here</a>.</u>

This thesis demonstrates the use of an object-relational mapping (ORM) framework to reduce entity impedance in a natural language interface for relational databases (NLI-DB). Specifically, we present a database-agnostic SQL view construction algorithm that partitions an arbitrary database into entities that maximize performance of a natural language understanding (NLU) model. This model represents an important contribution to automating the creation of a natural language interface for a single database in two ways. First, it eliminates ambiguity when mapping a user’s information need to a specific database table. Second, it allows for the use of simple natural language models for generating SQL queries to service a given information need. Practically, our approach aims to increase database access for non-technical users by minimizing their need for SQL knowledge. We accomplish this by mapping a user’s information need to a specific set of database columns exposed by a specific entity view.
