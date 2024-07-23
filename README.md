# NLP_tools_performance

The data we work on is in the form of a perfectly structured RDF graph and semanticized according to the DOREMUS musical model.

DOREMUS, a project involving research on the semantic web, aims to develop tools and methods to publish, share, connect, enrich catalogs of works and musical events in the web of data. Its overall objective is to facilitate access to data and musical knowledge via the construction of a common knowledge model (an ontology).

With the aim of creating a relationship of equivalence between works coming from two institutions different, several approaches and methods have been put in place. 
Naturally the first approach is to compare them directly since they have been represented according to the same model. That is to say, on the one hand, comparing the classes, which are resources or raw data, with each other and on the other hand the properties or predicates.  ![image](https://github.com/user-attachments/assets/972e7f7c-43a1-4885-b5cf-df05b634954c)

It turns out that a few problems were encountered in this step, including comparing string classes. These are raw, unstructured data and therefore difficult to compare at the computer level.

Our work is to extract these data which represents an important description of the work and to structure it. To achieve this, named entity recognition methods, in certain ways, address such problems. They consist of recognizing and then extracting from textual data the terms used in a specific context. We must choose the most reliable ones and apply them to our data in order to choose the most efficient or effective one.

From there, our objective will be to first study the DOREMUS model including semantic web technologies as well as named entity recognition and extraction methods.
Followed by the extraction and processing of these data (cleaning, classification, etc.) Then, we will present the experimental process followed, meaning the Benchmark built for the tests, tool’s evaluation techniques before moving on to the analysis where we will describe the results obtained.

The tools chosen were developed, some in Java and others in Python.
The extraction will also be done with sparql using either java or python
The choice of language is conditioned by the libraries and/or packages available for the tools.

