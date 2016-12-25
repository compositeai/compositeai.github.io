---
layout: post
comments: true
title: "Cassandra Data Modelling Issues"
date: 2016-05-17
---

Cassandra Data Modelling refers to model tables in Cassandra Platform  considering the advantages and disadvantages of data stroing and retrivationg cost in distributed environment. 

deepnet_0.2.tar.gz


download.file('http://stat-athens.aueb.gr/~jbn/papers/files/14/14_bivpois_RDATA.zip', 
              f <- tempfile())
unzip(f, exdir=tempdir())
file.copy(file.path(tempdir(), '.RData'), 'bivpois.RData')
# the above copies the .RData file to a file called bivpois.RData in your current 
# working directory.
load('bivpois.RData')
