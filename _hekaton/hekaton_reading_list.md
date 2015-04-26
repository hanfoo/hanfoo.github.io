---
layout: post
title: Hekaton Reading List
---

# Hekaton Reading List

## Papers published by Microsoft

1. [Hekaton: SQL Server’s Memory-Optimized OLTP Engine](http://research.microsoft.com/pubs/193594/Hekaton%20-%20Sigmod2013%20final.pdf)
> The overview of the Hekaton In-Memory Database Engine covering the architecture, query compilation, in-memory storage, transaction management, gabage collection, etc.

1. [SQL Server In-Memory OLTP Internals Overview](http://download.microsoft.com/download/5/F/8/5F8D223F-E08B-41CC-8CE5-95B79908A872/SQL_Server_2014_In-Memory_OLTP_TDM_White_Paper.pdf)
> Written by Kalen Delaney. This paper is updated with the most current infomation about Hekaton and published in MSDN. It describes more technique details than the previous paper.

1. [High-Performance Concurrency Control Mechanisms for Main-Memory Databases](http://vldb.org/pvldb/vol5/p298_per-akelarson_vldb2012.pdf)
> This paper focuses on the transaction concurrency control mechanism.

1. [The Bw-Tree: A B-tree for New Hardware Platforms](http://research.microsoft.com/pubs/178758/bw-tree-icde2013-final.pdf)
> This paper focuses on the in-memory lock-free bw-tree data structure.

## Other Techniques Hekaton Based On

1. [Efficiently Compiling Efficient Query Plans for Modern Hardware](http://www.vldb.org/pvldb/vol4/p539-neumann.pdf)
> Written by Thomas Neumann. Hekaton uses a kind of query compilation to generate native code. This technique is first described by this paper.

1. [High Performance Dynamic Lock-Free Hash Tables and List-Based Sets](http://www.research.ibm.com/people/m/michael/spaa-2002.pdf)
> Written by Maged M. Michael. The lock-free linked list implementation of Hekaton is base on this paper.

1. [Hazard Pointers: Safe Memory Reclamation for Lock-Free Objects](http://web.cecs.pdx.edu/~walpole/class/cs510/papers/11.pdf)
> Written by Maged M. Michael. Maged proposes a general method to reclycle memory safely usually used in lock-free data structure.
