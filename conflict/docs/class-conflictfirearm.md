Vocabulary: [http://purl.com/net/conflict](index.md) 



---	
	




    


## Class conflict:Firearm


### Tree


* [conflict:Weapon_by_Function](class-conflictweapon_by_function.md)

    * conflict:Firearm





*NOTE* this is a leaf node.


### URI
http://purl.com/net/conflict#Firearm

### Description
&quot;A firearm is a device that launches single or multiple projectiles at high velocity through a controlled explosion, using a propellant such as cordite or gunpowder. Firearms include &#39;small arms&#39; such as handguns (e.g. pistols and revolvers), long guns (e.g. rifles and shotguns),and  automatic weapons (e.g. Lewis gun, machine guns and automatic rifles).&quot;



### Inherits from (4)

- [conflict:Weapon_by_Function](class-conflictweapon_by_function.md)

- [conflict:Weapon](class-conflictweapon.md)

- [conflict:Single_Thing](class-conflictsingle_thing.md)

- [conflict:Physical](class-conflictphysical.md)





### Implementation
```
<p>@prefix : &lt;http://purl.com/net/conflict#&gt; .<br />@prefix dc: &lt;http://purl.org/dc/elements/1.1/&gt; .<br />@prefix owl: &lt;http://www.w3.org/2002/07/owl#&gt; .<br />@prefix owl2xml: &lt;http://www.w3.org/2006/12/owl2-xml#&gt; .<br />@prefix rdf: &lt;http://www.w3.org/1999/02/22-rdf-syntax-ns#&gt; .<br />@prefix rdfs: &lt;http://www.w3.org/2000/01/rdf-schema#&gt; .<br />@prefix skos: &lt;http://www.w3.org/2004/02/skos/core#&gt; .<br />@prefix xml: &lt;http://www.w3.org/XML/1998/namespace&gt; .<br />@prefix xsd: &lt;http://www.w3.org/2001/XMLSchema#&gt; .</p>

<p>:Firearm a owl:Class ;<br />    rdfs:comment &quot;A firearm is a device that launches single or multiple projectiles at high velocity through a controlled explosion, using a propellant such as cordite or gunpowder. Firearms include &#39;small arms&#39; such as handguns (e.g. pistols and revolvers), long guns (e.g. rifles and shotguns),and  automatic weapons (e.g. Lewis gun, machine guns and automatic rifles).&quot;^^xsd:string ;<br />    rdfs:subClassOf :Weapon_by_Function .</p>

<p></p>
```




### Instances of conflict:Firearm can have the following properties:

<table border="1" cellspacing="3" cellpadding="5" class="classproperties table-hover ">

    <tr>
        <th height="40">Property</th><th>Description</th><th>Expected Type</th>
    </tr>

          

        
            
        
        <tr style="background: lightcyan;text-align: left;">
            <th colspan="3" height="10" class="treeinfo"><span style="font-size: 80%;">
            From <a title="conflict:Firearm" href="class-conflictfirearm.md" class="rdfclass">conflict:Firearm</a></span>
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