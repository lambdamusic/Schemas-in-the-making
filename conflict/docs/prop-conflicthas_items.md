Vocabulary: [http://purl.com/net/conflict](index.md) 



---	
	




    


## Property conflict:has_items


### Tree

* rdfs:Property
    * conflict:has_items





*NOTE* this is a leaf node.


### URI
http://purl.com/net/conflict#has_items

### Description
--


### Inherits from:
owl:Thing



### Usage


[conflict:Museum_collection](class-conflictmuseum_collection.md) 
=&gt;&nbsp;_conflict:has_items_&nbsp;=&gt;&nbsp;[conflict:Physical](class-conflictphysical.md)

### Implementation
```
<p>@prefix : &lt;http://purl.com/net/conflict#&gt; .<br />@prefix dc: &lt;http://purl.org/dc/elements/1.1/&gt; .<br />@prefix owl: &lt;http://www.w3.org/2002/07/owl#&gt; .<br />@prefix owl2xml: &lt;http://www.w3.org/2006/12/owl2-xml#&gt; .<br />@prefix rdf: &lt;http://www.w3.org/1999/02/22-rdf-syntax-ns#&gt; .<br />@prefix rdfs: &lt;http://www.w3.org/2000/01/rdf-schema#&gt; .<br />@prefix skos: &lt;http://www.w3.org/2004/02/skos/core#&gt; .<br />@prefix xml: &lt;http://www.w3.org/XML/1998/namespace&gt; .<br />@prefix xsd: &lt;http://www.w3.org/2001/XMLSchema#&gt; .</p>

<p>:has_items a owl:ObjectProperty ;<br />    rdfs:domain :Museum_collection ;<br />    rdfs:range :Physical .</p>

<p></p>
```










---

Documentation automatically generated with [OntoSpy](http://ontospy.readthedocs.org/ "Open") on 30th October 2016 19:14