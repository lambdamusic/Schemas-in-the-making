Vocabulary: [http://www.purl.com/net/feudalism](index.md) 



---	
	




    


## Property feudalism:transaction_Primary


### Tree

* rdfs:Property
    * feudalism:transaction_Primary





*NOTE* this is a leaf node.


### URI
http://www.purl.com/net/feudalism#transaction_Primary

### Description
--


### Inherits from:
owl:Thing



### Usage


[feudalism:Transaction](class-feudalismtransaction.md) 
=&gt;&nbsp;_feudalism:transaction_Primary_&nbsp;=&gt;&nbsp;[](.md)

### Implementation
```
<p>@prefix : &lt;http://www.purl.com/net/feudalism#&gt; .<br />@prefix dc: &lt;http://purl.org/dc/elements/1.1/&gt; .<br />@prefix factoid: &lt;http://purl.com/net/factoid#&gt; .<br />@prefix owl: &lt;http://www.w3.org/2002/07/owl#&gt; .<br />@prefix owl2xml: &lt;http://www.w3.org/2006/12/owl2-xml#&gt; .<br />@prefix rdf: &lt;http://www.w3.org/1999/02/22-rdf-syntax-ns#&gt; .<br />@prefix rdfs: &lt;http://www.w3.org/2000/01/rdf-schema#&gt; .<br />@prefix skos: &lt;http://www.w3.org/2004/02/skos/core#&gt; .<br />@prefix xml: &lt;http://www.w3.org/XML/1998/namespace&gt; .<br />@prefix xsd: &lt;http://www.w3.org/2001/XMLSchema#&gt; .</p>

<p>:transaction_Primary a owl:ObjectProperty ;<br />    rdfs:label &quot;Primary&quot;^^xsd:string ;<br />    rdfs:domain :Transaction ;<br />    rdfs:range factoid:Agent ;<br />    rdfs:subPropertyOf factoid:had_participant .</p>

<p></p>
```










---

Documentation automatically generated with [OntoSpy](http://ontospy.readthedocs.org/ "Open") on 30th October 2016 19:18