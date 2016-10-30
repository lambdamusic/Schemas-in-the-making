Vocabulary: [http://purl.com/net/conflict](index.md) 



---	
	




    


## Class conflict:Merchant_Ship


### Tree


* [conflict:Ship](class-conflictship.md)

    * conflict:Merchant_Ship


        * [conflict:Q-Ship](class-conflictq-ship.md) 
        






### URI
http://purl.com/net/conflict#Merchant_Ship

### Description
&quot;any sort of ship (eg a cargo ship or freighter) or vessel that carries cargo, goods, and materials from one port to another.

Note that (from Wikipedia) &amp;quot;In wartime, the distinction between warships and merchant ships is often blurred. In war, merchant ships are often armed and used as auxiliary warships, such as the Q-ships of the First World War and the armed merchant cruisers of the Second World War.&amp;quot;

TIP: we&#39;ll have to think about adding an &#39;AUXILIARY SHIP class..&quot;



### Inherits from (4)

- [conflict:Ship](class-conflictship.md)

- [conflict:Watercraft](class-conflictwatercraft.md)

- [conflict:Single_Thing](class-conflictsingle_thing.md)

- [conflict:Physical](class-conflictphysical.md)





### Implementation
```
<p>@prefix : &lt;http://purl.com/net/conflict#&gt; .<br />@prefix dc: &lt;http://purl.org/dc/elements/1.1/&gt; .<br />@prefix owl: &lt;http://www.w3.org/2002/07/owl#&gt; .<br />@prefix owl2xml: &lt;http://www.w3.org/2006/12/owl2-xml#&gt; .<br />@prefix rdf: &lt;http://www.w3.org/1999/02/22-rdf-syntax-ns#&gt; .<br />@prefix rdfs: &lt;http://www.w3.org/2000/01/rdf-schema#&gt; .<br />@prefix skos: &lt;http://www.w3.org/2004/02/skos/core#&gt; .<br />@prefix xml: &lt;http://www.w3.org/XML/1998/namespace&gt; .<br />@prefix xsd: &lt;http://www.w3.org/2001/XMLSchema#&gt; .</p>

<p>:Merchant_Ship a owl:Class ;<br />    rdfs:comment &quot;&quot;&quot;any sort of ship (eg a cargo ship or freighter) or vessel that carries cargo, goods, and materials from one port to another.</p>

<p>Note that (from Wikipedia) &amp;quot;In wartime, the distinction between warships and merchant ships is often blurred. In war, merchant ships are often armed and used as auxiliary warships, such as the Q-ships of the First World War and the armed merchant cruisers of the Second World War.&amp;quot;</p>

<p>TIP: we&#39;ll have to think about adding an &#39;AUXILIARY SHIP class..&quot;&quot;&quot;^^rdf:XMLLiteral ;<br />    rdfs:subClassOf :Ship .</p>

<p></p>
```




### Instances of conflict:Merchant_Ship can have the following properties:

<table border="1" cellspacing="3" cellpadding="5" class="classproperties table-hover ">

    <tr>
        <th height="40">Property</th><th>Description</th><th>Expected Type</th>
    </tr>

          

        
            
        
        <tr style="background: lightcyan;text-align: left;">
            <th colspan="3" height="10" class="treeinfo"><span style="font-size: 80%;">
            From <a title="conflict:Merchant_Ship" href="class-conflictmerchant_ship.md" class="rdfclass">conflict:Merchant_Ship</a></span>
            </th>
        </tr>       

            

        

          

        
            
        
        <tr style="background: lightcyan;text-align: left;">
            <th colspan="3" height="10" class="treeinfo"><span style="font-size: 80%;">
            From <a title="owl:Thing" href="class-owlthing.md" class="rdfclass">owl:Thing</a></span>
            </th>
        </tr>       

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="dc:creator" href="prop-dccreator.md">dc:creator</a>         
                </td>
                <td class="thirdtd">
                    <span></span>
                </td>
                <td class="secondtd">
                    
                        <i>owl:Thing</i>
                    
                </td>
            </tr>

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="dc:description" href="prop-dcdescription.md">dc:description</a>         
                </td>
                <td class="thirdtd">
                    <span></span>
                </td>
                <td class="secondtd">
                    
                        <i>owl:Thing</i>
                    
                </td>
            </tr>

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="dc:title" href="prop-dctitle.md">dc:title</a>         
                </td>
                <td class="thirdtd">
                    <span></span>
                </td>
                <td class="secondtd">
                    
                        <i>owl:Thing</i>
                    
                </td>
            </tr>

            

        

    

</table>













---

Documentation automatically generated with [OntoSpy](http://ontospy.readthedocs.org/ "Open") on 30th October 2016 19:14