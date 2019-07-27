# XML and HTML character entity references

In SGML, HTML and XML documents, the logical constructs known as _character data_ and _attribute values_ consist of sequences of characters, in which each character can manifest directly (representing itself), or can be represented by a series of characters called a _character reference_, of which there are two types: a _numeric character reference_and a _**character entity reference**_. This article lists the character entity references that are valid in HTML and XML documents.

A character entity reference refers to the content of a named entity. An entity declaration is created by using the `<!ENTIT name "value">` syntax in a Document Type Definition (DTD).

## Character reference overview

A _numeric character reference_ refers to a character by its [Universal Character Set](https://en.wikipedia.org/wiki/Universal_Character_Set "Universal Character Set")/[Unicode](https://en.wikipedia.org/wiki/Unicode "Unicode") _code point_, and uses the format:

<dl>

<dd>`&#`_nnnn_`;`</dd>

</dl>

or

<dl>

<dd>`&#x`_hhhh_`;`</dd>

</dl>

where _nnnn_ is the code point in [decimal](https://en.wikipedia.org/wiki/Decimal "Decimal") form, and _hhhh_ is the code point in [hexadecimal](https://en.wikipedia.org/wiki/Hexadecimal "Hexadecimal") form. The _x_ must be lowercase in XML documents. The _nnnn_ or _hhhh_ may be any number of digits and may include leading zeros. The _hhhh_ may mix uppercase and lowercase, though uppercase is the usual style.

In contrast, a _character entity reference_ refers to a character by the name of an _[entity](https://en.wikipedia.org/wiki/SGML_entity "SGML entity")_ which has the desired character as its _replacement text_. The entity must either be predefined (built into the markup language) or explicitly declared in a [Document Type Definition](https://en.wikipedia.org/wiki/Document_Type_Definition "Document Type Definition") (DTD). The format is the same as for any entity reference:

<dl>

<dd>`&`_name_`;`</dd>

</dl>

where _name_ is the case-sensitive name of the entity. The semicolon is required.XML 

## Standard public entity sets for characters

**ISO Entity Sets**: [SGML](https://en.wikipedia.org/wiki/SGML "SGML") supplied a comprehensive set of entity declarations for characters widely used in Western technical and reference publishing, for Latin, Greek and Cyrillic scripts. The [American Mathematical Society](https://en.wikipedia.org/wiki/American_Mathematical_Society "American Mathematical Society")also contributed entities for mathematical characters.

**HTML Entity Sets**: Early versions of [HTML](https://en.wikipedia.org/wiki/HTML "HTML") built in small subsets of these, relating to characters found in three Western 8-bit fonts.

**MathML Entity Sets**: The [W3C](https://en.wikipedia.org/wiki/W3C "W3C") developed a set of entity declarations for [MathML](https://en.wikipedia.org/wiki/MathML "MathML") characters.

**XML Entity Sets**: The [W3C](https://en.wikipedia.org/wiki/W3C "W3C") MathML Working Group took over maintenance of the ISO public entity sets, combined with the MathML and documents them in [XML Entity Definitions for Characters](http://www.w3.org/TR/xml-entity-names/). This set can support the requirements of [XHTML](https://en.wikipedia.org/wiki/XHTML "XHTML"), [MathML](https://en.wikipedia.org/wiki/MathML "MathML") and as an input to future versions of HTML.

**HTML 5**: [HTML5](https://en.wikipedia.org/wiki/HTML5 "HTML5") adopts the XML entities as [named character references](http://www.w3.org/TR/html5/syntax.html#named-character-references), however it restates them without reference to their sources and does not group them into sets. The HTML 5 specification additionally provides mappings from the names to Unicode character sequences using [JSON](https://en.wikipedia.org/wiki/JSON "JSON").

Numerous other entity sets have been developed for special requirements, and for major and minority scripts. However, the advent of [Unicode](https://en.wikipedia.org/wiki/Unicode "Unicode") has largely superseded them.

...


<div className="text-right"> 
    [From wiki](https://en.wikipedia.org/wiki/List_of_XML_and_HTML_character_entity_references)
</div>
