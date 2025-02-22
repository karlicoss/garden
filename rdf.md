# RDF

- [[go]] https://www.w3.org/RDF/
  - [[RDF 1.1]] documents: 
    - [[RDF 1.1 Primer]]
    - [[RDF 1.1 Concepts and Abstract Syntax]]
    - [[RDF 1.1 XML Syntax]]
    - [[RDF 1.1 Semantics]]
    - [[RDF Schema 1.1]]
    - [[RDF 1.1 Test Cases]]
- [[wikipedia]] https://en.wikipedia.org/wiki/Resource_Description_Framework
- [[relevant]] for [[go links]], [[agora]].
- [[ZornGerhard]] knows about it.
	- Also mentioned the [[SPARQL]] query language: https://twitter.com/ZornGerhard/status/1310645329587560448
- I should ask [[s.-s.]] about it.
- [[see also]] [[turtle]], [[semantic triples]], [[solid]].
- [[hypothesis]] RDF is enough to maintain a [[distributed knowledge graph]] collaboratively over the internet.
	- [[hypothesis]] RDF is a good base for the [[agora protocol]].
- [[twitter]] https://twitter.com/flancian/status/1342895193071230977

## [[2020-12-26]]

- I started a [[pomodoro]] of this but [[procrastination]] came up, interesting -- it's not like I'm not interested in this, but it just tends to happen I don't *get* to it because I'm busy with work and other things, so I ended up associating it with a frustrated feeling? Unsure. It could also be I have a fear of it being *precisely* the Agora, what that would mean. I should be elated if that happened, but on some level perhaps.
  - [[the agora is a social network built by the people for the people]] feels like something that I wanted to write, so no regrets.
- [[reading]] https://www.w3.org/RDF/
  - "RDF is a standard model for data interchange on the Web. RDF has features that facilitate data merging even if the underlying schemas differ, and it specifically supports the evolution of schemas over time without requiring all the data consumers to be changed." 
    - Nice.
  - "RDF extends the linking structure of the Web to use URIs to name the relationship between things as well as the two ends of the link (this is usually referred to as a “triple”). Using this simple model, it allows structured and semi-structured data to be mixed, exposed, and shared across different applications."
		- I feel like the Agora plays well with this, and this plays well with the Agora.
  		- [[actions]] for example are semantic triples:
    		- They happen in a node that serves as current context; usually a [[subject]]. 
				- They point to another Agora node or a [[url]], an [[object]]. 
				- They contain a [[relationship]], the [[action]].
  - "This linking structure forms a directed, labeled graph, where the edges represent the named link between two resources, represented by the graph nodes. This graph view is the easiest possible mental model for RDF and is often used in easy-to-understand visual explanations."
		- It sounds like RDF allows us to run a fully distributed [[graph]] / [[hypergraph]] over the internet.
		- Why has it not "taken over"?
		- What would "take over" mean?
  - Related [[tools]]: 
		- [[4store]] (triple store).
		- [[outdated-ARC RDF Store]] (triple store). Directly usable from PHP
		- [[AllegroGraph RDF Store]] (triple store programming environment reasoner development environment rdfs reasoner). Directly usable from Java LISP Python Prolog C Ruby Perl
		- [[Apache Jena]] (triple store programming environment reasoner rule reasoner owl reasoner rdfs reasoner parser). Directly usable from Java
		- [[Dojo.data]] (triple store programming environment). Directly usable from Javascript
		- [[FRED]] (rdf generator tagging knowledge graph extractor).
		- [[Mobi]] (programming environment development environment). Directly usable from Java Javascript
		- [[Mulgara Semantic Store]] (triple store). Directly usable from Java
		- [[OpenLink Virtuoso]] (triple store reasoner rdf generator sparql endpoint owl reasoner rdfs reasoner rdb2rdf). Directly usable from C C++ Python PHP Java Javascript ActionScript Tcl Perl Ruby Obj-C
		- [[Oracle Spatial and Graph 19c]] (triple store reasoner owl reasoner). Directly usable from Java
		- [[RDFLib]] (triple store programming environment). Directly usable from Python
		- [[RDFox]] (triple store reasoner owl reasoner rdfs reasoner rule reasoner). Directly usable from C++ Java
		- [[Redland RDF Application Framework]] (programming environment). Directly usable from C C-sharp Python Obj-C PHP Java Tcl Ruby Perl
		- [[Altova's SemanticWorks]] (editor development environment).
		- [[Sesame]] (triple store programming environment reasoner rdfs reasoner parser). Directly usable from Java Python PHP
		- [[Talis Platform]] (triple store sparql endpoint).
		- [[XMP (ISO 16684)]] (editor development environment).
- [[reading]] [[wikipedia]] https://en.wikipedia.org/wiki/Resource_Description_Framework
  - [[first public draft]] in [[1997]]. Backed by companies such as [[ibm]] [[microsoft]] [[netscape]].
  - [[1.0]] was published as a standard in [[1999]], [[1.1]] in [[2014]].
	- "The RDF data model is similar to classical conceptual modeling approaches (such as [[entity–relationship diagrams]] or [[class diagrams]]). It is based on the idea of making statements about resources (in particular web resources) in expressions of the form subject–predicate–object, known as triples. The subject denotes the resource, and the predicate denotes traits or aspects of the resource, and expresses a relationship between the subject and the object. "
	- "For example, one way to represent the notion "The sky has the color blue" in RDF is as the triple: 
  	- [[sky]] [[has the color]] [[blue]].
  	- Or [[sky]] [[color]] [[blue]]?
  	- "Therefore, RDF uses subject instead of object (or entity) in contrast to the typical approach of an entity–attribute–value model in object-oriented design: entity (sky), attribute (color), and value (blue)."
	- RDF is an [[abstract model]]. There are several [[rdf serialization formats]].
	- See also: [[W3C]]'s [[Semantic Web]] activity: an evolutionary stage of the [[World Wide Web]] in which "automated software can store, exchange, and use [[machine-readable information]] distributed throughout the [[Web]], in turn enabling users to deal with the information with greater [[efficiency]] and [[certainty]]." Also used in [[knowledge management applications]] unrelated to Semantic Web activity.
	- [[RDFS]] and [[OWL]] are ontology languages built opon RDF. 
	- [[common misunderstandings]]:
  	- [[RDF]] [[is not]] for representing [[metadata]] only.
  	- [[RDF]] [[is not]] an XML format, it rather is an [[abstract data model]]. 
- Known applications 
  - [[RSS]] and [[FOAM]] are applications for RDF.
	  - [[do]] check if RSS > 1.0 is an RDF application; [[wikipedia]] only mentions 1.0
	

[//begin]: # "Autogenerated link references for markdown compatibility"
[go]: go "Go"
[wikipedia]: wikipedia "Wikipedia"
[agora]: agora "Agora"
[SPARQL]: sparql "SPARQL"
[s.-s.]: s.-s. "S  S"
[turtle]: turtle "Turtle"
[hypothesis]: hypothesis "Hypothesis"
[distributed knowledge graph]: distributed-knowledge-graph "Distributed Knowledge Graph"
[agora protocol]: agora-protocol "Agora Protocol"
[twitter]: twitter "Twitter"
[2020-12-26]: journal/2020-12-26 "2020-12-26"
[pomodoro]: pomodoro "Pomodoro"
[procrastination]: procrastination "Procrastination"
[the agora is a social network built by the people for the people]: the-agora-is-a-social-network-built-by-the-people-for-the-people "The Agora Is a Social Network Built by the People for the People"
[action]: action "Action"
[graph]: graph "Graph"
[tools]: tools "Tools"
[rdf serialization formats]: rdf-serialization-formats "Rdf Serialization Formats"
[knowledge management applications]: knowledge-management-applications "Knowledge Management Applications"
[RDF]: rdf "RDF"
[FOAM]: foam "Foam"
[do]: do "Do"
[//end]: # "Autogenerated link references"