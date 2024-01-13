<pre>
&#x003c;rdf:RDF
   xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
   xmlns:rdfs="http://www.w3.org/2000/01/rdf-schema#"
   xmlns:owl="http://www.w3.org/2002/07/owl#" 
   xmlns:dc="http://purl.org/dc/elements/1.1/"&#x003e;

 &#x003c;owl:Ontology 
     rdf:about="http://www.w3.org/1999/02/22-rdf-syntax-ns#"&#x003e;
   &#x003c;dc:title&#x003e;The RDF Vocabulary (RDF)&#x003c;/dc:title&#x003e;
   &#x003c;dc:description&#x003e;This is the RDF Schema for the RDF vocabulary defined in the RDF namespace.&#x003c;/dc:description&#x003e;
 &#x003c;/owl:Ontology&#x003e;

&#x003c;rdf:Property rdf:about="http://www.w3.org/1999/02/22-rdf-syntax-ns#<a id="type">type</a>"&#x003e;
  &#x003c;rdfs:isDefinedBy rdf:resource="http://www.w3.org/1999/02/22-rdf-syntax-ns#"/&#x003e;
  &#x003c;rdfs:label&#x003e;type&#x003c;/rdfs:label&#x003e;
  &#x003c;rdfs:comment&#x003e;The subject is an instance of a class.&#x003c;/rdfs:comment&#x003e;
  &#x003c;rdfs:range rdf:resource="http://www.w3.org/2000/01/rdf-schema#Class"/&#x003e;
  &#x003c;rdfs:domain rdf:resource="http://www.w3.org/2000/01/rdf-schema#Resource"/&#x003e;
&#x003c;/rdf:Property&#x003e;

&#x003c;rdfs:Class rdf:about="http://www.w3.org/1999/02/22-rdf-syntax-ns#Property"&#x003e;
  &#x003c;rdfs:isDefinedBy rdf:resource="http://www.w3.org/1999/02/22-rdf-syntax-ns#"/&#x003e;
  &#x003c;rdfs:label&#x003e;Property&#x003c;/rdfs:label&#x003e;
  &#x003c;rdfs:comment&#x003e;The class of RDF properties.&#x003c;/rdfs:comment&#x003e;
  &#x003c;rdfs:subClassOf rdf:resource="http://www.w3.org/2000/01/rdf-schema#Resource"/&#x003e;
&#x003c;/rdfs:Class&#x003e;

&#x003c;rdfs:Class rdf:about="http://www.w3.org/1999/02/22-rdf-syntax-ns#Statement"&#x003e;
  &#x003c;rdfs:isDefinedBy rdf:resource="http://www.w3.org/1999/02/22-rdf-syntax-ns#"/&#x003e;
  &#x003c;rdfs:label&#x003e;Statement&#x003c;/rdfs:label&#x003e;
  &#x003c;rdfs:subClassOf rdf:resource="http://www.w3.org/2000/01/rdf-schema#Resource"/&#x003e;
  &#x003c;rdfs:comment&#x003e;The class of RDF statements.&#x003c;/rdfs:comment&#x003e;
&#x003c;/rdfs:Class&#x003e;

&#x003c;rdf:Property rdf:about="http://www.w3.org/1999/02/22-rdf-syntax-ns#subject"&#x003e;
  &#x003c;rdfs:isDefinedBy rdf:resource="http://www.w3.org/1999/02/22-rdf-syntax-ns#"/&#x003e;
  &#x003c;rdfs:label&#x003e;subject&#x003c;/rdfs:label&#x003e;
  &#x003c;rdfs:comment&#x003e;The subject of the subject RDF statement.&#x003c;/rdfs:comment&#x003e;
  &#x003c;rdfs:domain rdf:resource="http://www.w3.org/1999/02/22-rdf-syntax-ns#Statement"/&#x003e;
  &#x003c;rdfs:range rdf:resource="http://www.w3.org/2000/01/rdf-schema#Resource"/&#x003e;
&#x003c;/rdf:Property&#x003e;

&#x003c;rdf:Property rdf:about="http://www.w3.org/1999/02/22-rdf-syntax-ns#predicate"&#x003e;
  &#x003c;rdfs:isDefinedBy rdf:resource="http://www.w3.org/1999/02/22-rdf-syntax-ns#"/&#x003e;
  &#x003c;rdfs:label&#x003e;predicate&#x003c;/rdfs:label&#x003e;
  &#x003c;rdfs:comment&#x003e;The predicate of the subject RDF statement.&#x003c;/rdfs:comment&#x003e;
  &#x003c;rdfs:domain rdf:resource="http://www.w3.org/1999/02/22-rdf-syntax-ns#Statement"/&#x003e;
  &#x003c;rdfs:range rdf:resource="http://www.w3.org/2000/01/rdf-schema#Resource"/&#x003e;
&#x003c;/rdf:Property&#x003e;

<rdf:Property rdf:about="http://www.w3.org/1999/02/22-rdf-syntax-ns#object"&#x003e;
  <rdfs:isDefinedBy rdf:resource="http://www.w3.org/1999/02/22-rdf-syntax-ns#"/&#x003e;
  <rdfs:label&#x003e;object</rdfs:label&#x003e;
  <rdfs:comment&#x003e;The object of the subject RDF statement.</rdfs:comment&#x003e;
  <rdfs:domain rdf:resource="http://www.w3.org/1999/02/22-rdf-syntax-ns#Statement"/&#x003e;
  <rdfs:range rdf:resource="http://www.w3.org/2000/01/rdf-schema#Resource"/&#x003e;
</rdf:Property&#x003e;

<rdfs:Class rdf:about="http://www.w3.org/1999/02/22-rdf-syntax-ns#Bag">
  <rdfs:isDefinedBy rdf:resource="http://www.w3.org/1999/02/22-rdf-syntax-ns#"/>
  <rdfs:label>Bag</rdfs:label>
  <rdfs:comment>The class of unordered containers.</rdfs:comment>
  <rdfs:subClassOf rdf:resource="http://www.w3.org/2000/01/rdf-schema#Container"/>
</rdfs:Class>

<rdfs:Class rdf:about="http://www.w3.org/1999/02/22-rdf-syntax-ns#Seq">
  <rdfs:isDefinedBy rdf:resource="http://www.w3.org/1999/02/22-rdf-syntax-ns#"/>
  <rdfs:label>Seq</rdfs:label>
  <rdfs:comment>The class of ordered containers.</rdfs:comment>
  <rdfs:subClassOf rdf:resource="http://www.w3.org/2000/01/rdf-schema#Container"/>
</rdfs:Class>

<rdfs:Class rdf:about="http://www.w3.org/1999/02/22-rdf-syntax-ns#Alt">
  <rdfs:isDefinedBy rdf:resource="http://www.w3.org/1999/02/22-rdf-syntax-ns#"/>
  <rdfs:label>Alt</rdfs:label>
  <rdfs:comment>The class of containers of alternatives.</rdfs:comment>
  <rdfs:subClassOf rdf:resource="http://www.w3.org/2000/01/rdf-schema#Container"/>
</rdfs:Class>

<rdf:Property rdf:about="http://www.w3.org/1999/02/22-rdf-syntax-ns#value">
  <rdfs:isDefinedBy rdf:resource="http://www.w3.org/1999/02/22-rdf-syntax-ns#"/>
  <rdfs:label>value</rdfs:label>
  <rdfs:comment>Idiomatic property used for structured values.</rdfs:comment>
  <rdfs:domain rdf:resource="http://www.w3.org/2000/01/rdf-schema#Resource"/>
  <rdfs:range rdf:resource="http://www.w3.org/2000/01/rdf-schema#Resource"/>
</rdf:Property>

<!-- the following are new additions, Nov 2002 -->

<rdfs:Class rdf:about="http://www.w3.org/1999/02/22-rdf-syntax-ns#List">
  <rdfs:isDefinedBy rdf:resource="http://www.w3.org/1999/02/22-rdf-syntax-ns#"/>
  <rdfs:label>List</rdfs:label>
  <rdfs:comment>The class of RDF Lists.</rdfs:comment>
  <rdfs:subClassOf rdf:resource="http://www.w3.org/2000/01/rdf-schema#Resource"/>
</rdfs:Class>

<rdf:List rdf:about="http://www.w3.org/1999/02/22-rdf-syntax-ns#nil">
  <rdfs:isDefinedBy rdf:resource="http://www.w3.org/1999/02/22-rdf-syntax-ns#"/>
  <rdfs:label>nil</rdfs:label>
  <rdfs:comment>The empty list, with no items in it. If the rest of a list is nil then the list has no more items in it.</rdfs:comment>
</rdf:List>

<rdf:Property rdf:about="http://www.w3.org/1999/02/22-rdf-syntax-ns#first">
  <rdfs:isDefinedBy rdf:resource="http://www.w3.org/1999/02/22-rdf-syntax-ns#"/>
  <rdfs:label>first</rdfs:label>
  <rdfs:comment>The first item in the subject RDF list.</rdfs:comment>
  <rdfs:domain rdf:resource="http://www.w3.org/1999/02/22-rdf-syntax-ns#List"/>
  <rdfs:range rdf:resource="http://www.w3.org/2000/01/rdf-schema#Resource"/>
</rdf:Property>

<rdf:Property rdf:about="http://www.w3.org/1999/02/22-rdf-syntax-ns#rest">
  <rdfs:isDefinedBy rdf:resource="http://www.w3.org/1999/02/22-rdf-syntax-ns#"/>
  <rdfs:label>rest</rdfs:label>
  <rdfs:comment>The rest of the subject RDF list after the first item.</rdfs:comment>
  <rdfs:domain rdf:resource="http://www.w3.org/1999/02/22-rdf-syntax-ns#List"/>
  <rdfs:range rdf:resource="http://www.w3.org/1999/02/22-rdf-syntax-ns#List"/>
</rdf:Property>
	
<rdfs:Datatype rdf:about="http://www.w3.org/1999/02/22-rdf-syntax-ns#XMLLiteral">
  <rdfs:subClassOf rdf:resource="http://www.w3.org/2000/01/rdf-schema#Literal"/> 
  <rdfs:isDefinedBy rdf:resource="http://www.w3.org/1999/02/22-rdf-syntax-ns#"/>
  <rdfs:label>XMLLiteral</rdfs:label>
  <rdfs:comment>The class of XML literal values.</rdfs:comment>
</rdfs:Datatype>

<rdf:Description rdf:about="http://www.w3.org/1999/02/22-rdf-syntax-ns#">
  <rdfs:seeAlso rdf:resource="http://www.w3.org/2000/01/rdf-schema-more"/>
</rdf:Description>

</rdf:RDF>

</pre>
