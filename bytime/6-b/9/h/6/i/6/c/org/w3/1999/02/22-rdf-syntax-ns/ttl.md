<pre>
&#x003c;?xml version="1.0"?&#x003e;

&#x003c;RDF
  xmlns="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
  xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
  xmlns:s="http://www.w3.org/TR/WD-rdf-schema#"&#x003e;

&#x003c;!--
  This is the RDF Schema for the RDF data model as described in the
  Resource Description Framework (RDF) Model and Syntax Specification
  http://www.w3.org/TR/REC-rdf-syntax --&#x003e;

&#x003c;s:Class rdf:ID="Statement"
  s:comment="A triple consisting of a predicate, a subject, and an object." /&#x003e;

&#x003c;s:Class rdf:ID="Property"
  s:comment="A name of a property, defining specific meaning for the property" /&#x003e;

&#x003c;s:Class rdf:ID="Bag"
  s:comment="An unordered collection" /&#x003e;

&#x003c;s:Class rdf:ID="Seq"
  s:comment="An ordered collection" /&#x003e;

&#x003c;s:Class rdf:ID="Alt"
  s:comment="A collection of alternatives" /&#x003e;

&#x003c;Property ID="predicate"
  s:comment="Identifies the property used in a statement when representing the statement in reified form"&#x003e;
  &#x003c;s:domain rdf:resource="#Statement" /&#x003e;
  &#x003c;s:range rdf:resource="#Property" /&#x003e;
&#x003c;/Property>

&#x003c;Property ID="subject"
  s:comment="Identifies the resource that a statement is describing when representing the statement in reified form"&#x003e;
  &#x003c;s:domain rdf:resource="#Statement" /&#x003e;
&#x003c;/Property&#x003e;

&#x003c;Property ID="object"
  s:comment="Identifies the object of a statement when representing the statement in reified form" /&#x003e;

&#x003c;Property ID="<a id="type">type</a>"
  s:comment="Identifies the Class of a resource" /&#x003e;

&#x003c;Property ID="value"
  s:comment="Identifies the principal value (usually a string) of a property when the property value is a structured resource" /&#x003e;

&#x003c;/RDF&#x003e;
</pre>
