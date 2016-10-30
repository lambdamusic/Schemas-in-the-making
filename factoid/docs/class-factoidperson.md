Vocabulary: [http://purl.com/net/factoid](index.md) 



---	
	




    


## Class factoid:Person


### Tree


* [factoid:Agent](class-factoidagent.md)

    * factoid:Person





*NOTE* this is a leaf node.


### URI
http://purl.com/net/factoid#Person

### Description
--



### Inherits from (1)

- [factoid:Agent](class-factoidagent.md)





### Implementation
```
<p>@prefix : &lt;http://purl.com/net/factoid#&gt; .<br />@prefix cidoc_crm: &lt;http://www.cidoc-crm.org/rdfs/cidoc_crm_v5.0.4_english_label.rdfs#&gt; .<br />@prefix owl: &lt;http://www.w3.org/2002/07/owl#&gt; .<br />@prefix rdf: &lt;http://www.w3.org/1999/02/22-rdf-syntax-ns#&gt; .<br />@prefix rdfs: &lt;http://www.w3.org/2000/01/rdf-schema#&gt; .<br />@prefix skos: &lt;http://www.w3.org/2004/02/skos/core#&gt; .<br />@prefix sp: &lt;http://spinrdf.org/sp#&gt; .<br />@prefix xml: &lt;http://www.w3.org/XML/1998/namespace&gt; .<br />@prefix xsd: &lt;http://www.w3.org/2001/XMLSchema#&gt; .</p>

<p>:Person a owl:Class ;<br />    rdfs:label &quot;Person&quot;^^xsd:string ;<br />    rdfs:subClassOf :Agent ;<br />    owl:disjointWith :Organization .</p>

<p></p>
```




### Instances of factoid:Person can have the following properties:

<table border="1" cellspacing="3" cellpadding="5" class="classproperties table-hover ">

    <tr>
        <th height="40">Property</th><th>Description</th><th>Expected Type</th>
    </tr>

          

        
            
        
        <tr style="background: lightcyan;text-align: left;">
            <th colspan="3" height="10" class="treeinfo"><span style="font-size: 80%;">
            From <a title="factoid:Person" href="class-factoidperson.md" class="rdfclass">factoid:Person</a></span>
            </th>
        </tr>       

            

        

          

        
            
        
        <tr style="background: lightcyan;text-align: left;">
            <th colspan="3" height="10" class="treeinfo"><span style="font-size: 80%;">
            From <a title="factoid:Agent" href="class-factoidagent.md" class="rdfclass">factoid:Agent</a></span>
            </th>
        </tr>       

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="factoid:took_part_in" href="prop-factoidtook_part_in.md">factoid:took_part_in</a>         
                </td>
                <td class="thirdtd">
                    <span></span>
                </td>
                <td class="secondtd">
                    
                    

                        <a title="factoid:Temporal_Entity" href="class-factoidtemporal_entity.md" class="rdfclass">factoid:Temporal_Entity</a>

                    
                    
                </td>
            </tr>

            

        

    

</table>













---

Documentation automatically generated with [OntoSpy](http://ontospy.readthedocs.org/ "Open") on 30th October 2016 19:16