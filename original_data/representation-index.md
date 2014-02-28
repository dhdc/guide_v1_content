-   [DH Curation Guide](../index.html)
-   [Contents](../contents/)
    -   [Introduction to Humanities Data Curation](../intro/)
    -   [Data Representation](../representation/)
    -   [Classics & “Digital Classics”](../research-practices/classics/)
    -   [Digital Collections](../collections/)
    -   [Standards](../collections/standards/)
    -   [Policy, Practice, & Law](../legal/policy/)
    -   [Metadata (stub)](../metadata/)
    -   [Digital Preservation (stub)](../preservation/)
    -   [*Full table of contents*](../contents/)

-   [About](../about/)
-   [FAQ/DC](../faq/)
-   [Editors](../editors/)
-   [Glossary](../glossary.html)

[▲](#top)

[**DH Curation Guide**](../index.html)

Data Representation [C. M. Sperberg-McQueen, Black Mesa
Technology](../editors/#michaelsperbergmcqueen "Contributor page")
[David Dubin, University of Illinois,
Urbana-Champaign](../editors/#davedubin "Contributor page")

[![Save to
Delicious](../images/del-20.gif "Save to Delicious")](https://www.delicious.com/save)

[Tweet](https://twitter.com/share)

[![image](../images/pdf.png "Download as PDF") Download PDF](pdf.php)

### Article contents [±]

-   Introduction
-   Analog and digital representations
-   Resources: Representations
-   Layers of representation
-   Resources: Layers of representation
-   Curatorial requirements for data representations
-   Bit preservation and information preservation
-   Resources: Bit preservation and information preservation
-   Format Information
-   Resources: Format information and identification
-   Documents
-   Word-Processor Formats
-   Resources: Word-Processor Formats
-   HTML
-   Resources: HTML
-   SGML, XML, and their Applications
-   Resources: SGML, XML, and their Applications
-   Other Formats
-   Resources: Other document formats
-   Images
-   Resources: Raster Graphics
-   Resources: Vector Graphics
-   Databases
-   Resources: Databases
-   Numbers
-   Resources: Numbers
-   General article comments

[§ 1](#formats)

[What is Data Representation?](#formats)

-   [](#) Add introduction comment

By data representation is meant, in general, any convention for the
arrangement of things in the physical world in such a way as to enable
information to be encoded and later decoded by suitable automatic
systems.

[¶ 1](#p1 "Permalink")

-   [](#) Add section comment

We specify conventions because information can be conveyed by other
means as well. A dog may know by sniffing the air who has passed a given
way in the preceding hour or so, but does not in doing so rely on any
agreed conventions for information transfer. This and similar exchanges
of information do not involve data representation in the sense we mean
it here.

[¶ 2](#p2 "Permalink")

-   [](#) Add section comment

We specify automatic systems to distinguish data representation from the
more general topic of the representation or encoding of information,
which includes conventional writing systems, paper drawings, and other
representations of information used by human beings.

[¶ 3](#p3 "Permalink")

-   [](#) Add section comment

We do not specify what physical objects are to be arranged, or how, or
what kind of information they are to be used to encode, because data
representation might in theory involve any kind of physical object and
any kind of information. In practice both the physical objects involved
and the conventions for their arrangement have varied a good deal over
the short history of automatic information processing by means of
machines. Holes punched in stiff cards, magnetic charges on a thin
coating applied to plastic tape or flat metal disks, holes in paper
tape, variations in the optical properties of the surface of a thin
plastic disk, dials controlling electrical circuits, the positions and
lengths of cables, and the positions of spools and sticks in a Tinkertoy
construction have all been used successfully to represent data.

[¶ 4](#p4 "Permalink")

-   [](#) Add section comment

A particular convention for data representation is often referred to as
a [data format](../glossary.html#dataformat).

[¶ 5](#p5 "Permalink")

-   [](#) Add section comment

An understanding of principles and issues of data representation is
essential for data curators because only curators who understand how
information is represented by the digital objects in their care can take
effective steps to ensure that the information represented is not lost.
The long-term sustainability of digital objects is materially affected
by the methods of data representation relied on by those objects;
tradeoffs between different courses of curatorial action can be
correctly assessed only with an understanding of how the information to
be preserved is represented by physical objects.

[[back to top]](#top)

[¶ 6](#p6 "Permalink")

-   [](#) Add section comment

[§ 2](#data_representation)

[Analog and digital representations](#data_representation)

-   [](#) Add section comment

One way to represent information is to create and sustain a direct
analogy between salient properties of the system being modeled (the
information) and the physical representation of the information. When
the physical representation is astutely chosen, operations on the
physical representation can correspond to operations on the objects
being represented and the representation can be used for (for example)
calculation.

[¶ 7](#p7 "Permalink")

-   [](#) Add paragraph comment

Real numbers, for example, can be represented in an intuitive way using
lengths of string or wood. Numbers with similar values will have
physically similar representations, and the addition of a set of numbers
can be represented by placing the representations of the numbers end to
end; the sum is represented by a string or piece of wood whose length
just equals the distance from one end of the sequence of addends to the
other. The addition of numbers using a slide rule is based on precisely
such a representation. (A more common use of a slide rule, of course, is
to multiply numbers; in this case, each number is represented by a
length of rule proportional to the logarithm of the number, and
multiplication is represented as the addition, using the convention just
described, of the logs of the multiplicands.)

[¶ 8](#p8 "Permalink")

-   [](#) Add paragraph comment

Because it is based on an analogy of properties between the
representation and the represented, this form of information
representation is called analog. A fundamental property of an analog
representation of information is that representations with similar
physical properties represent similar things: infinitesimally small
differences in the state of a representation correspond to
infinitesimally small differences in the information represented, and
there are uncountably many different meaningful states. It is a
consequence of this property that small errors in the representation
will result in small (though often tolerable) errors in the results of
an calculation.

[¶ 9](#p9 "Permalink")

-   [](#) Add paragraph comment

Among the best-known uses of analog representations for complex
information are the tide-predicting machines developed in the 19th
century and in use in some locations until the 1970s, which predicted
tides using ingenious systems of cables, wheels, and pulleys.

[¶ 10](#p10 "Permalink")

-   [](#) Add paragraph comment

A different family of representations uses a purely arbitrary or
symbolic relation between an object and its representation; the physical
representation serves to record a symbolic expression or notation of
some sort, and the expression has an arbitrary relation, defined by
convention, to the information it represents. The arbitrariness of the
relation will be familiar to some readers from many other discussions of
signs and signifiers.

[¶ 11](#p11 "Permalink")

-   [](#) Add paragraph comment

The data representations used in modern computer systems all fall into
this family. Their fundamental property is they represent information
indirectly: physical phenomena are used to represent sequences of binary
digits (zero or one), and sequences of binary digits are then
interpreted as integers, real numbers, characters, or other “primitive”
data types. From the use of binary digits as a fundamental building
block (and more generally from the similarity of these representations
to the use of fingers as symbolic units in counting), these
representations are termed digital.

[¶ 12](#p12 "Permalink")

-   [](#) Add paragraph comment

The fundamental property of digital representations is that they are
based on the use of a finite number of discrete symbols to represent
information. Because finite systems can represent only a finite number
of symbols, in any such system there is only a finite number of possible
meaningful states; this is a fundamental difference between digital and
analog representations of information. (In practice, the number of
states distinguishable in a digital system is large enough that it often
simplifies reasoning to pretend that it is infinite.) In digital
systems, the physical similarity of two representations of information
is no guide to the similarity of the information they represent. (For
example, the bit sequences 0000 0000 and 1000 0000 differ only in the
value of a single bit, but if they are taken as unsigned integers, they
denote 0 and 128; many numbers much closer to zero than 128 have
representations very different from either.) Small errors occurring in
the physical representation of information (e.g. the accidental flipping
of a single bit) can and often do lead to wildly erratic results.

[¶ 13](#p13 "Permalink")

-   [](#) Add paragraph comment

The early years of electronic computing machinery were marked by
competition between digital and analog (or more frequently
digital/analog hybrid) computers, but eventually digital devices swept
the analog and hybrid devices from the marketplace so thoroughly that
early descriptions of electronic binary digital stored-program computing
machines now seem quaintly dated, and the representation of pre-existing
materials in machine-processable form is referred to as digitization, as
if no other form of machine processing were conceivable. Those early
descriptions now serve as reminders that not all computational devices
need be digital, or binary, or electronic. A key element in the
commercial victory of digital devices was the development of methods for
simulating the behavior of analog devices using digital representations.
So even in environments which are strictly speaking digital it is
sometimes useful to distinguish methods of representation which are more
purely digital from those which have, or seek to have, analog
properties. In the context of contemporary digital machines, therefore,
the term analog may be applied to representations of a thing which model
selected physical properties of that thing as closely as possible,
typically using (digital representations of) real numbers; in contrast a
digital representation represents the thing in symbolic form, typically
using symbols from a (relatively) small number of discrete, enumerable
atomic symbols.

[¶ 14](#p14 "Permalink")

-   [](#) Add paragraph comment

A text, for example, can be represented by a scanned image of a page on
which the text has been written, in which the data format records
information about the hue and brightness of the light reflected from
different points on the paper; this is an analog representation of the
text (or more precisely, of the page), in the sense just described. The
text (and the page) can also, however, be represented by a sequence of
characters, each character represented internally by a distinct pattern
of bits, with no attempt to record the physical appearance of the paper
or the writing on it, only to record the identities of the symbols used
to encode the text. In the sense just given, this is a digital
representation of the text.

[¶ 15](#p15 "Permalink")

-   [](#) Add paragraph comment

As illustrated by this example, analog representations often mimic
physical attributes without any distinction between those which carry
meaning and those which do not, while digital representations require an
understanding of the properties of the thing being represented. For this
reason, analog representations are sometimes associated with the act of
perception and digital representations with the act of cognition (e.g.
by Devlin 1991). Typically, digital representations provide better
access to information of interest than do analog representations.
Full-text search of digital representations is a straightforward
operation, while full-text search of images representing pages of text
is possibly only via a detour through a textual representation (often
created automatically by optical character recognition, with the high
error rates entailed by that operation). Because purely digital
representations can omit extraneous information, they tend to be more
compact than analog representations. An image of a page typically
requires many times the storage space needed for a character-based
transcription of the page. Conversely, because analog representations do
not discriminate between relevant and extraneous information, they will
typically convey information omitted from a purely digital
representation of the same thing. Sometimes this extra information will
prove useful or important.

[[back to top]](#top)

[¶ 16](#p16 "Permalink")

-   [](#) Add paragraph comment

[Resources: Representations](#analog-digital_representations_resources)
Collapse annotations

[The computer and the
brain](http://books.google.com/books/about/The_computer_and_the_brain.html?id=Q30MqJjRv1gC)
: John von Neumann.

Lectures intended for a popular audience which include a lucid
discussion of digital and analog representations of numeric quantities
and the different properties of such representations. [full citation ±]
John von Neumann. *The computer and the brain.* 1958. Second Edition,
with a foreword by Paul M. Churchland and Patricia S. Churchland. New
Haven: Yale University Press, 2000.

[¶ 17](#r1 "Permalink")

[Logic and
information](http://books.google.com/books/about/Logic_and_information.html?id=AqrwD8PYbakC)
: Keith Devlin.

Pages 17-19 carry a discussion of the digital/analog distinction and its
relevance to cognition and the extraction of information from context.
[full citation ±] Keith Devlin. *Logic and information.* Cambridge:
Cambridge University Press, 1991

Add resource

### Add a resource

We encourage you to contribute a resource that would be useful for the
humanities data curation community! The most helpful and relevant
resources include best practices documents, high-quality internal
documentation, official standards or recommendations, articles that
describe or analyze best practices, and case studies or projects whose
practice is exemplary. **All content is verified by the managing
editors. Please see our [submission guidelines](../../submissions/) if
you are submitting something for the first time.**

Your name:\*

This is the name to which your submission will be credited

Your e-mail:\*

Your email address will not be published. We will only use it to contact
you regarding this submission.

Your website:

Opt. Your name can be linked to a bio page, Twitter account, or other
website.

* * * * *

Add to resource group:

Title of resource:\*

\

Author(s):\*

e.g., W. Smith and S. Monroe; Dublin Core Metadata Initiative

Publication info:

Publication name or publisher e.g., Digital Digest 20:1 or University
Press

Date of publication:

e.g., 2009, Spring 2010, Jan. 2011

URL:

\
 \

Annotation:\*

What value do you find in this resource? Describe the resource and
explain its relevance.

E.g., "This volume of the International Journal of Digital Curation
offers an excellent overview of the field of data curation through a
combination of peer-reviewed papers and topical articles. For those new
to the field, browsing through the archives of this journal will form an
excellent introduction to both the practice and theory of curation." \
 Add more resources [+]

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

After submission, the editors will respond to you by email. \
 \
 \
 \

[[back to top]](#top)

[¶ 18](#r2 "Permalink")

[§ 3](#layers_of_representation)

[Layers of representation](#layers_of_representation)

-   [](#) Add section comment

In existing computer systems there is typically a long chain of
relations connecting the physical phenomena by which data are
represented with the data being represented. Each link in the chain
connects two layers of representation: each layer organizes information
available at the next lower level into structures at a higher (or at
least different) layer of abstraction, and in this way provides
information used in turn by the next higher level in the representation.
For example, the representation of an email message may involve the
following layers:

-   Physical layer: holes in cards or tape, magnetic charges, color
    changes on optical disks or scan codes, tones on a telephone
    connection, or similar phenomena are interpreted as representing
    sequences of bits.
-   Bit layer: those sequences of bits may be interpreted as
    representations of other different sequences of bits (for example
    five bits may be written to the physical medium to represent four
    bits of data, in such a way as to guarantee a minimum and maximum
    amount of space between magnetic flux events in the media).
-   Byte / octet layer: the sequences of bits read from the storage
    device are grouped into octets: units of eight bits often referred
    to as [bytes](../glossary.html#byte). (Historically different
    machines had bytes of different sizes, but it has been some decades
    since any prominent system had bytes of other than eight bits.)
-   Character layer: an octet sequence may be interpreted as a sequence
    of characters. For conventional email, each octet will be
    interpreted as one character, as defined by the appropriate
    character-set standard.
-   Application-specific data structure layer: the email reader will
    read the character stream and distinguish the mail header from the
    message body, and may distinguish multiple alternative
    representations of the message and attachments within the message
    body. Within the mail header, mail software will distinguish
    important fields like date, sender, and addressee.
-   Presentation layer: the email reader will display the message on the
    user's screen.

The human reader of the mail will of course read the screen and (in the
normal case) discern letters, words, and sentences, as well as (perhaps)
images.

[¶ 19](#p17 "Permalink")

-   [](#) Add paragraph comment

This hierarchy of layers of abstraction is characteristic of many
information technologies, not just data representations. It has
parallels to the structuralist idealization of natural language as
organized into phonological, morphological, lexical, syntactic,
semantic, and pragmatic layers. In the case of natural language,
different layers sometimes interact in ways that conflict with the
hierarchical model. Artificial systems of data representation, in
contrast, may follow more frequently than natural languages the ideal of
a strict hierarchy of layers in which no layer depends on or interacts
with layers other than the immediately adjacent ones. In the design of
technologies, such layering helps limit the complexity of the system and
reduces the likelihood of error in its construction. From the metaphor
of several pieces of software, each layered on top of the next, systems
constructed in this way are often referred to as a software (or
technology) [stack](../glossary.html#stack). Software that supports
network connectivity is often referred to as “the network stack”; the
technologies available for working with XML documents are sometimes
referred to as “the XML stack”; and so on.

[¶ 21](#p18 "Permalink")

-   [](#) Add paragraph comment

There is no single hierarchy of data representation layers that applies
to all data representations; other software running on the same machine
may have a chain of representations and layers rather different from the
chain described above for email messages. In particular, different
applications will almost always have different application-specific data
structures. Moreover, proprietary applications frequently use binary
data formats which have no distinguishable character-level
representation.

[¶ 22](#p19 "Permalink")

-   [](#) Add paragraph comment

Despite the manifold opportunities for variation, however, some
properties are shared by many data representations in wide use today:

-   Unlike proprietary applications, non-proprietary applications often
    define character-level representations as a way of allowing
    interoperability between different implementations.
-   Historically, machines from different manufacturers often used
    different character encodings. Since the development of the
    so-called Universal Character Set (UCS) of ISO 10646 and Unicode in
    the 1990s, however, hardware manufacturers, software developers, and
    the writers of non-proprietary specifications have been slowly
    converging on the use of the UCS as a standard character
    representation level. Examples include the use of the UCS as the
    fundamental character representation in the Java programming
    language, in HTML beginning with HTML 4.0, and in XML. In
    consequence, character-set variation is likely to pose practical
    problems primarily in the case of formats or data material from the
    1990s or earlier.
-   Most applications on most systems share the lowest levels of the
    representation and diverge only in their treatment of the octet
    sequence.
-   Many applications designed for use on a single computer system also
    assume that the operating system within which they are used provides
    a file system (which can be described abstractly as a mapping from
    file names to octet sequences). This is not a universal property,
    however: not all computing devices provide file systems, and (in the
    interests of speed and/or reliability) many database management
    systems bypass the file system to deal directly with the interface
    to the hard disk or other storage media. Network protocols, in
    contrast, typically avoid assuming the existence of a file system
    and rely instead on concepts of messages, data transmissions, or
    (especially in the context of the World Wide Web)
    [resources](../glossary.html#resources).

[¶ 23](#p20 "Permalink")

-   [](#) Add paragraph comment

In practice, the issues of concern for data curation are almost all at
or above the octet level. Partly this is because lower levels are
normally highly reliable (and thus seldom need attention), partly
because intervention at lower levels requires specialized engineering
knowledge and equipment, and partly because application formats are
designed to rely only on the octet level, precisely in order to make
them independent of the precise implementation of the lower levels. (But
see the discussion of bit preservation below.)

[[back to top]](#top)

[¶ 25](#p21 "Permalink")

-   [](#) Add paragraph comment

[Resources: Layers of
representation](#layers_of_representation_resources) Collapse
annotations

[Line code](http://en.wikipedia.org/wiki/Line_code) : Wikipedia.

The set of Wikipedia articles on line codes provide a helpful
introduction to the many ingenious ways in which engineers have used
electrical, auditory, or visual signals to represent sequences of bits.
Readers who are not themselves network engineers need not memorize any
of the details of different line codes, but scanning the articles can
help correct the misconception propagated by many non-technical
introductions to computing which suggest that there is only one way to
represent bits (on = 1, off = 0). [full citation ±] Wikipedia. “Line
code.” *Wikipedia*.

[¶ 26](#r3 "Permalink")

[Standard for the Format of ARPA Internet Text
Messages](http://tools.ietf.org/html/rfc822) : David H. Crocker, rev.
ed.

This networking specification (long since made obsolete by later
specifications) illustrates the way in which standards of the Internet
Engineering Task Force (IETF) are systematically constructed to be blind
to variations in layers below the layer used as the basis of the
specification. This specifications is built on the character layer;
later IETF specifications typically use a similar formalism to define
the protocol, but specify that the characters used as primitive concepts
in the definition of the protocol are to be taken as denoting octets,
not characters. [full citation ±] David H. Crocker, rev. ed. RFC 822:
Standard for the Format of ARPA Internet Text Messages. W3C, August 13,
1982.

[¶ 27](#r4 "Permalink")

[A Standard for the Transmission of IP Datagrams on Avian
Carriers](http://tools.ietf.org/html/rfc1149) : D. Waitzman, ed.

A specification of the use of homing pigeons to implement the Internet
Protocol (IP). The specification is written tongue-in-cheek (note its
publication date), but it has in fact been implemented (though with poor
latency and high packet loss), which illustrates the independence of
higher and lower layers in the internet [software
stack](../glossary.html#stack). [full citation ±] D. Waitzman, ed.
Network Working Group RFC 1149: A Standard for the Transmission of IP
Datagrams on Avian Carriers. IETF, 1 April 1990.

Add resource

### Add a resource

We encourage you to contribute a resource that would be useful for the
humanities data curation community! The most helpful and relevant
resources include best practices documents, high-quality internal
documentation, official standards or recommendations, articles that
describe or analyze best practices, and case studies or projects whose
practice is exemplary. **All content is verified by the managing
editors. Please see our [submission guidelines](../../submissions/) if
you are submitting something for the first time.**

Your name:\*

This is the name to which your submission will be credited

Your e-mail:\*

Your email address will not be published. We will only use it to contact
you regarding this submission.

Your website:

Opt. Your name can be linked to a bio page, Twitter account, or other
website.

* * * * *

Add to resource group:

Title of resource:\*

\

Author(s):\*

e.g., W. Smith and S. Monroe; Dublin Core Metadata Initiative

Publication info:

Publication name or publisher e.g., Digital Digest 20:1 or University
Press

Date of publication:

e.g., 2009, Spring 2010, Jan. 2011

URL:

\
 \

Annotation:\*

What value do you find in this resource? Describe the resource and
explain its relevance.

E.g., "This volume of the International Journal of Digital Curation
offers an excellent overview of the field of data curation through a
combination of peer-reviewed papers and topical articles. For those new
to the field, browsing through the archives of this journal will form an
excellent introduction to both the practice and theory of curation." \
 Add more resources [+]

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

After submission, the editors will respond to you by email. \
 \
 \
 \

[[back to top]](#top)

[¶ 28](#r5 "Permalink")

[§ 4](#curatorial_requirements)

[Curatorial requirements for data
representations](#curatorial_requirements)

-   [](#) Add section comment

For data curation purposes there are two fundamental requirements: all
other requirements derive from these (or are not requirements but
negotiable desiderata):

-   Permanence: the data representation must last a long time without
    corruption, degradation, decay, or loss.
-   Usability: it must be possible to use the information being
    preserved. Using the information provides a check that the
    information has thus far been successfully preserved without the
    loss of some crucial bits, and in any case if the data have become
    unusable there may be little point in spending further resources to
    preserve them longer.

[¶ 29](#p22 "Permalink")

-   [](#) Add paragraph comment

From the essential requirements others follow; all of these are
desiderata only.

-   Any data representation relied on for long-term preservation of
    information must have clear, well written, published documentation.
    If the format is not documented, the likelihood that the information
    it represents can be preserved without loss across media conversions
    is small; the likelihood that it can be preserved without loss
    across format conversions is nil. One of the most effective methods
    available for confirming that digital objects have been successfully
    preserved so far is to provide effective intellectual access to the
    material; active users of the material provide a far better monitor
    of data quality than any automated system could ever do. But if the
    format of the data is not documented, it is much harder, if not
    always impossible, to provide effective intellectual access to the
    material.
-   The specification documents for preservation formats should be
    controlled by public bodies, preferably consensus-based
    organizations in the international standardization system or by
    relevant industry consortia. Proprietary formats are subject to
    change and abandonment by their owners in ways that make them a poor
    bet for long-term access to information.
-   Other things being equal, a data representation that is widely
    supported has a better chance of long-term utility than one with a
    much smaller user community. Larger numbers of users mean it's
    easier to share costs of maintenance and development across a larger
    pool of resources, understanding and documentation of the format are
    likely to be more widespread, and there are better prospects for
    commercial support for the format. There are limits to this
    principle, however: a suitable format used by a small specialized
    community will often be preferable to a format used by a much larger
    community that does not provide a suitable representation of the
    information. (The mostly widely supported representations of
    human-readable documents, for example, are those of word-processor
    software. But many scholars using computers for the analysis of
    language and literature prefer other formats for the data they work
    on, because word-processor formats are not oriented to linguistic
    and literary concerns. It would not be a good idea to translate data
    from a well designed XML format into a proprietary word-processor
    format on the grounds that the word-processor format is more widely
    used.)

[[back to top]](#top)

[¶ 31](#p23 "Permalink")

-   [](#) Add paragraph comment

[Bit preservation and information preservation](#bit-pres-info-pres)

-   [](#) Add comment

Practical work on data curation can usefully divided into two classes:
efforts focused on the preservation of information at the bit or octet
level (bit preservation) and efforts focused on higher levels. Efforts
at both levels are essential to the successful preservation of digital
materials; which area more urgently requires the attention and resources
of data curators is an area of active controversy.

[¶ 33](#p24 "Permalink")

-   [](#) Add comment

Briefly, bit preservation is the act of ensuring that devices in the
future will be able to reproduce the sequence of bits, or octets,
currently used to represent the information to be conserved. Bit
preservation protects against bit rot and media failure, but not against
other threats to digital preservation and access.

[¶ 34](#p25 "Permalink")

-   [](#) Add comment

Information preservation is the act of ensuring that the information
represented in a resource is preserved, possibly by translating it from
an obsolescent format into a more current format. Note that format
conversion protects against file-format obsolescence, but not against
other possible threats to digital preservation.

[¶ 35](#p26 "Permalink")

-   [](#) Add comment

Preservation of bits is a necessary part of digital preservation: since
the bit sequence is the foundation for all the higher levels in the
representation of the information, if the bit sequence is lost, the
information will be lost as well. But bit preservation is not
sufficient: a future user interested in a WordStar 1.3 document (for
example) will be able to make use of the document effectively only if
software capable of reading the WordStar 1.3 file format is available.
Since WordStar was a very popular program for its day, such software may
very possibly be available in practice. For the formats of less popular
software, however, the situation looks less promising.

[[back to top]](#top)

[¶ 36](#p27 "Permalink")

-   [](#) Add comment

[Resources: Bit preservation and information
preservation](#bit-information_preservation_resources) Collapse
annotations

[How Are We Ensuring the Longevity of Digital
Documents?](http://blog.dshr.org/2009/04/spring-cni-plenary-remix.html)
: David S. H. Rosenthal.

Rosenthal argues that Rothenberg's analysis of 1995 has been proven
wrong by experience. In particular he argues (1) that problems of media
longevity are non-issues because information should be and is being kept
online, on active storage devices (which are typically replaced when
they become technologically obsolete and whose lifetimes are not crucial
because as live systems they will be backed up regularly). Also, (2)
format conversion is not as difficult a problem as originally expected,
because for all sufficiently popular formats there are satisfactory
commercial conversion solutions. Rosenthal's talk is thought-provoking
and deserves attention, even if (as it seems to the authors of this
essay) his arguments are circular and vague: any format for which there
are not good conversion routines can, presumably, be labeled
insufficiently widespread for Rosenthal's claims to apply. There is
serious danger in assuming that all the material of intellectual or
cultural importance which a library or archive might wish to preserve
will be represented in “popular” formats. And finally, the claim that
widespread formats are always supported in perpetuity, either directly
or by conversion routines, will not withstand serious scrutiny of (for
example) existing commercial conversions into and out of widespread
word-processing formats, which routinely introduce changes in content or
formatting of information. Video recordings of the talk are available at
[Youtube](http://www.google.com/url?sa=t&rct=j&q=david%20rosenthal%20cni&source=web&cd=2&ved=0CCUQtwIwAQ&url=http://www.youtube.com/watch?v=h53DMtBUxsk&ei=asahTo2vBbSCsgLHhqSKBQ&usg=AFQjCNGyav5pn8QOqUNPf3DcNCYl9TpLFg)
and
[vimeo.com](http://www.google.com/url?sa=t&rct=j&q=david%20rosenthal%20cni&source=web&cd=3&ved=0CCsQtwIwAg&url=http://vimeo.com/5407401&ei=asahTo2vBbSCsgLHhqSKBQ&usg=AFQjCNFhsESvkQeXMvuOrTItRZnv41Eu9g).
[full citation ±] David S. H. Rosenthal. “How Are We Ensuring the
Longevity of Digital Documents?” Talk at the Coalition for Networked
Information (CNI) Spring 2009. Task Force meeting.

[¶ 37](#r7 "Permalink")

[Ensuring the Longevity of Digital
Documents](http://www.sciamdigital.com/browse.cfm?ITEMIDCHAR=07FBACA7-7185-43C8-B9E7-E07B5343F87&methodnameCHAR=&interfacenameCHAR=browse.cfm&ISSUEID_CHAR=C4AEE5CE-6FFE-49D4-9BF2-5D5BC40A8CB&ArticleTypeSubInclude_BIT=0&sequencenameCHAR=itemP)
: Jeff Rothenberg.

An influential paper enunciating a framework for digital preservation
and stressing the importance of higher-level format conversion and
preservation; this paper is the target of Rosenthal's rebuttal in his
2009 talk. Online versions of the paper (including an expanded version)
are linked from [the author's web
site](http://www.panix.com/~jeffr/Prof/digilong.html). [full citation ±]
Jeff Rothenberg. “Ensuring the Longevity of Digital Documents.”
*Scientific American* 272.1 (1995): 42-47.

[¶ 38](#r8 "Permalink")

[Bit preservation: a solved
problem?](http://www.ijdc.net/index.php/ijdc/article/view/151) : David
S. H. Rosenthal.

Another cogent exploration of the challenges of bit preservation,
offering a review of research into how bit preservation has been
implemented (and how such systems fail), and some policy
recommendations. [full citation ±] David S. H. Rosenthal. “Bit
preservation: a solved problem?” *International Journal of Digital
Curation* 5.1 (2010).

[¶ 39](#r9 "Permalink")

[Keeping bits safe: how hard can it
be?](http://delivery.acm.org/10.1145/1840000/1839692/p47-rosenthal.pdf?ip=173.14.236.25&acc=PUBLIC&CFID=50049987&CFTOKEN=19044588&v__acm__=1319224738_dfba2e633ab3e517118ca7600929bac6)
: David S. H. Rosenthal.

A useful summary of issues relating to bit preservation and an estimate
of the resources needed to achieve it with a desired level of
reliability; also discusses the difficulty of achieving reliable
estimates of the probability of failure in a given system. [full
citation ±] David S. H. Rosenthal. “Keeping bits safe: how hard can it
be?” *Communications of the ACM* 32.11 (November 2010): 47-55.

[¶ 40](#r10 "Permalink")

[The LOCKSS peer-to-peer digital preservation
system](http://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&ved=0CCQQFjAA&url=http://cdn.dejanseo.com.au/wp-content/uploads/2011/11/10.1.1.60.2234.pdf&ei=w_MtT6auFMmO0QHK4bz2Bg&usg=AFQjCNFkPU0dCV1pu7NE28ztllsKmnDw-Q)
: Petros Maniatis et al.

A report on a well known effort to promote cooperative bit preservation
through redundant multiple storage of data at different institutions.
The home page of the LOCKSS project is at
[http://www.lockss.org/lockss/Home](http://www.lockss.org/lockss/Home).
[full citation ±] Petros Maniatis et al. “The LOCKSS peer-to-peer
digital preservation system.” *ACM Transactions on Computer Systems
(TOCS)* 23.1 (February 2005): 2-50.

[¶ 41](#r11 "Permalink")

[Preservation of New
Technology](http://www.clir.org/pubs/reports/lesk/lesk2.html) : Michael
Lesk.

Though technically substantive, this report also serves as a good
orientation for those getting acquainted with the field of preservation.
[full citation ±] Michael Lesk. *Preservation of New Technology: A
report of the Technology Advisory Committee to the Commission on
Preservation and Access.* Washington, D.C.: Commission on Preservation
and Access. October, 1992.

[¶ 42](#r12 "Permalink")

[What Constitutes Successful Format Conversion? Towards a Formalization
of “Intellectual
Content”](http://ijdc.net/index.php/ijdc/article/view/170) : C. M.
Sperberg-McQueen.

This article introduces the question of semantics and how meaning may be
preserved (or lost) in the course of format conversions. [full citation
±] C. M. Sperberg-McQueen. “What Constitutes Successful Format
Conversion? Towards a Formalization of “Intellectual Content”.”
*International Journal of Data Curation* 6.1 (2011): 153-164.

Add resource

### Add a resource

We encourage you to contribute a resource that would be useful for the
humanities data curation community! The most helpful and relevant
resources include best practices documents, high-quality internal
documentation, official standards or recommendations, articles that
describe or analyze best practices, and case studies or projects whose
practice is exemplary. **All content is verified by the managing
editors. Please see our [submission guidelines](../../submissions/) if
you are submitting something for the first time.**

Your name:\*

This is the name to which your submission will be credited

Your e-mail:\*

Your email address will not be published. We will only use it to contact
you regarding this submission.

Your website:

Opt. Your name can be linked to a bio page, Twitter account, or other
website.

* * * * *

Add to resource group:

Title of resource:\*

\

Author(s):\*

e.g., W. Smith and S. Monroe; Dublin Core Metadata Initiative

Publication info:

Publication name or publisher e.g., Digital Digest 20:1 or University
Press

Date of publication:

e.g., 2009, Spring 2010, Jan. 2011

URL:

\
 \

Annotation:\*

What value do you find in this resource? Describe the resource and
explain its relevance.

E.g., "This volume of the International Journal of Digital Curation
offers an excellent overview of the field of data curation through a
combination of peer-reviewed papers and topical articles. For those new
to the field, browsing through the archives of this journal will form an
excellent introduction to both the practice and theory of curation." \
 Add more resources [+]

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

After submission, the editors will respond to you by email. \
 \
 \
 \

[[back to top]](#top)

[¶ 43](#r13 "Permalink")

[§ 6](#format_identification)

[Format Information](#format_identification)

-   [](#) Add section comment

Since the set of formats potentially faced by a digital curator is
unbounded, it is not feasible to a guide to all relevant formats. This
section mentions a few of the most common and most important formats and
points to other resources for further information.

[[back to top]](#top)

[¶ 44](#p28 "Permalink")

-   [](#) Add paragraph comment

[Resources: Format information and
identification](#general_format_resources) Collapse annotations

[Sustainability of Digital
Formats](http://www.digitalpreservation.gov/formats/) : National Digital
Information Infrastructure and Preservation Program, United States
Library of Congress

The Library of Congress provides an inventory of digital file formats,
categorized by content type (e.g. moving image, datasets). This resource
includes a listing sustainability factors for content types and the
"curator's view" of significant content type characteristics and
preferred formats. *—Contributed by [Robin Camille
Davis](http://twitter.com/robincamille)* [full citation ±] National
Digital Information Infrastructure and Preservation Program, United
States Library of Congress Sustainability of Digital Formats.

Add resource

### Add a resource

We encourage you to contribute a resource that would be useful for the
humanities data curation community! The most helpful and relevant
resources include best practices documents, high-quality internal
documentation, official standards or recommendations, articles that
describe or analyze best practices, and case studies or projects whose
practice is exemplary. **All content is verified by the managing
editors. Please see our [submission guidelines](../../submissions/) if
you are submitting something for the first time.**

Your name:\*

This is the name to which your submission will be credited

Your e-mail:\*

Your email address will not be published. We will only use it to contact
you regarding this submission.

Your website:

Opt. Your name can be linked to a bio page, Twitter account, or other
website.

* * * * *

Add to resource group:

Title of resource:\*

\

Author(s):\*

e.g., W. Smith and S. Monroe; Dublin Core Metadata Initiative

Publication info:

Publication name or publisher e.g., Digital Digest 20:1 or University
Press

Date of publication:

e.g., 2009, Spring 2010, Jan. 2011

URL:

\
 \

Annotation:\*

What value do you find in this resource? Describe the resource and
explain its relevance.

E.g., "This volume of the International Journal of Digital Curation
offers an excellent overview of the field of data curation through a
combination of peer-reviewed papers and topical articles. For those new
to the field, browsing through the archives of this journal will form an
excellent introduction to both the practice and theory of curation." \
 Add more resources [+]

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

After submission, the editors will respond to you by email. \
 \
 \
 \

[[back to top]](#top)

[¶ 45](#r120 "Permalink")

[Documents](#documents)

-   [](#) Add comment

For conventional prose documents, two classes of format can be
distinguished: formats originally designed for a particular application
(often for a single piece of software) and formats originally designed
for the application-independent representation of documents. Families of
formats defined in a common metalanguage (e.g. SGML and XML) are a third
area of interest.

[[back to top]](#top)

[¶ 46](#p29 "Permalink")

-   [](#) Add comment

[Word-Processor Formats](#word-processor_formats)

-   [](#) Add comment

Most widespread are word-processor and other office-document formats.
When this material was compiled, two of these formats were more or less
reliably documented in international standards, namely the Open Document
Format, and the Office Open XML File Format. For other word-processor
formats, there is rarely any technical documentation. It is often
possible for technical people of sufficient skill and patience to
reverse engineer a format, if well understood sample documents in the
format are available for examination. In such efforts, partial success
is often attainable; perfect success is a theoretical possibility.

[[back to top]](#top)

[¶ 47](#p30 "Permalink")

-   [](#) Add comment

[Resources: Word-Processor Formats](#word-process_formats_resources)
Collapse annotations

[Information technology — Open Document Format for Office Applications
(OpenDocument) v1.0]() : ISO: International Organization for
Standardization.

The Open Document format is based on the formats used by the Star Office
and Open Office software suites and is implemented by those and other
programs. [full citation ±] ISO: International Organization for
Standardization. *ISO/IEC 26300:2006 Information technology — Open
Document Format for Office Applications (OpenDocument) v1.0.*

[¶ 48](#r14 "Permalink")

[Information technology — Document description and processing languages
— Office Open XML File Formats]() : ISO: International Organization for
Standardization.

This standard “defines a set of XML vocabularies for representing
word-processing documents, spreadsheets and presentations, based on the
Microsoft Office 2008 applications.” It consists of several parts:

Part 1: Fundamentals and Markup Language Reference

Part 2: Open Packaging Conventions

Part 3: Markup Compatibility and Extensibility

Part 4: Transitional Migration Features

There may be discrepancies between the formats defined by this
specification and the behavior of existing commercial software, but this
international standard is by a large margin the best technical
documentation publicly available for the formats used by the Microsoft
Office suite. [full citation ±] ISO: International Organization for
Standardization. *ISO/IEC 29500:2011 Information technology — Document
description and processing languages — Office Open XML File Formats.*

Add resource

### Add a resource

We encourage you to contribute a resource that would be useful for the
humanities data curation community! The most helpful and relevant
resources include best practices documents, high-quality internal
documentation, official standards or recommendations, articles that
describe or analyze best practices, and case studies or projects whose
practice is exemplary. **All content is verified by the managing
editors. Please see our [submission guidelines](../../submissions/) if
you are submitting something for the first time.**

Your name:\*

This is the name to which your submission will be credited

Your e-mail:\*

Your email address will not be published. We will only use it to contact
you regarding this submission.

Your website:

Opt. Your name can be linked to a bio page, Twitter account, or other
website.

* * * * *

Add to resource group:

Title of resource:\*

\

Author(s):\*

e.g., W. Smith and S. Monroe; Dublin Core Metadata Initiative

Publication info:

Publication name or publisher e.g., Digital Digest 20:1 or University
Press

Date of publication:

e.g., 2009, Spring 2010, Jan. 2011

URL:

\
 \

Annotation:\*

What value do you find in this resource? Describe the resource and
explain its relevance.

E.g., "This volume of the International Journal of Digital Curation
offers an excellent overview of the field of data curation through a
combination of peer-reviewed papers and topical articles. For those new
to the field, browsing through the archives of this journal will form an
excellent introduction to both the practice and theory of curation." \
 Add more resources [+]

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

After submission, the editors will respond to you by email. \
 \
 \
 \

[[back to top]](#top)

[¶ 49](#r15 "Permalink")

[HTML](#html)

-   [](#) Add comment

A second widely used application format is defined for the display of
documents on the World Wide Web. In addition to the resources listed
below, the W3C has published a number of ancillary documents related to
HTML; see the [W3C Technical Reports](http://www.w3.org/TR/) page.

[[back to top]](#top)

[¶ 51](#p31 "Permalink")

-   [](#) Add comment

[Resources: HTML](#html_resources) Collapse annotations

[XHTML™ 1.0](http://www.w3.org/TR/xhtml1) : World Wide Web Consortium
(W3C).

A good source for authoritative information on the XHTML language. [full
citation ±] World Wide Web Consortium (W3C). *XHTML™ 1.0: The extensible
hypertext markup language (second edition). A reformulation of HTML 4 in
XML 1.0*W3C Recommendation 26 January 2000, revised 1 August 2002.
Cambridge, Sophia-Antipolis, Tokyo: World Wide Web Consortium, 2002.

[¶ 52](#r16 "Permalink")

[HTML 5](http://www.w3.org/TR/html5/) : World Wide Web Consortium (W3C).

With HTML 5, the HTML specification moves away from conventional
formalisms for specifying document formats and relies solely on prose
rules. This is unlikely to improve the interoperability of software
intended to process HTML. [full citation ±] World Wide Web Consortium
(W3C). *HTML5: A vocabulary and associated APIs for HTML and XHTML.* W3C
Working Draft 25 May 2011. Cambridge, Sophia-Antipolis, Tokyo: World
Wide Web Consortium, 2011.

Add resource

### Add a resource

We encourage you to contribute a resource that would be useful for the
humanities data curation community! The most helpful and relevant
resources include best practices documents, high-quality internal
documentation, official standards or recommendations, articles that
describe or analyze best practices, and case studies or projects whose
practice is exemplary. **All content is verified by the managing
editors. Please see our [submission guidelines](../../submissions/) if
you are submitting something for the first time.**

Your name:\*

This is the name to which your submission will be credited

Your e-mail:\*

Your email address will not be published. We will only use it to contact
you regarding this submission.

Your website:

Opt. Your name can be linked to a bio page, Twitter account, or other
website.

* * * * *

Add to resource group:

Title of resource:\*

\

Author(s):\*

e.g., W. Smith and S. Monroe; Dublin Core Metadata Initiative

Publication info:

Publication name or publisher e.g., Digital Digest 20:1 or University
Press

Date of publication:

e.g., 2009, Spring 2010, Jan. 2011

URL:

\
 \

Annotation:\*

What value do you find in this resource? Describe the resource and
explain its relevance.

E.g., "This volume of the International Journal of Digital Curation
offers an excellent overview of the field of data curation through a
combination of peer-reviewed papers and topical articles. For those new
to the field, browsing through the archives of this journal will form an
excellent introduction to both the practice and theory of curation." \
 Add more resources [+]

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

After submission, the editors will respond to you by email. \
 \
 \
 \

[[back to top]](#top)

[¶ 53](#r17 "Permalink")

[SGML, XML, and their Applications](#sgml_xml)

-   [](#) Add comment

Less widely used than word-processor formats or HTML, but perhaps more
popular among digitization projects concerned with data longevity and
reuse, are document formats designed for the software-independent
representation of documents. These are of particular interest and
importance for data curators because they seek, by design, to make the
documents represented independent of any single piece of software. They
thus avoid the single most common cause of format obsolescence, which is
discontinuation of the software supporting the format. The desire for
software independence also forces the designers of such formats to
document the meaning of the format somewhat more carefully and
completely than is usual among creators of software-specific formats.

[¶ 54](#p32 "Permalink")

-   [](#) Add comment

While in theory there is no end to the methods that might be used to
define document formats in a software-independent way, in practice
almost all recent efforts in this direction have used SGML or XML.

[¶ 55](#p33 "Permalink")

-   [](#) Add comment

There are a very large number of XML-based vocabularies; the single most
useful source of information about them, and more generally about XML
and related technologies, is [The Cover
Pages](http://xml.coverpages.org/), compiled by Robin Cover and
currently hosted by the Organization for the Advancement of Structured
Information Standards, OASIS.

[[back to top]](#top)

[¶ 56](#p34 "Permalink")

-   [](#) Add comment

[Resources: SGML, XML, and their Applications](#sgml_xml_resources)
Collapse annotations

[The Cover Pages](http://xml.coverpages.org/) : Robin Cover, ed.

An extensive and carefully curated compilation of resources on XML and
XML-related standards. [full citation ±] Robin Cover, ed. The Cover
Pages: Online resource for markup language technologies. OASIS, 1986- .

[¶ 57](#r18 "Permalink")

[JATS: Journal Article Tag Suite](http://jats.nlm.nih.gov/z39.96/0.4/) :
NISO: National Information Standards Organization.

A standardized version of a document vocabulary originally developed by
and for the U.S. National Library of Medicine's National Center for
Biotechnology Information. The vocabulary is in wide use for archiving
scholarly journal literature. A high-level description is available on
[the NISO Web
site](http://www.niso.org/kst/reports/standards?step=2&gid=None&project_key:ustring:iso-8859-1=ff80fac0a0513ccb0f8d7c0cf651b895ba655ce6).
A Web site devoted to the JATS family of vocabularies for journal
articles is maintained by the U.S. National Library of Medicine at
[http://jats.nlm.nih.gov/](http://jats.nlm.nih.gov/). [full citation ±]
NISO: National Information Standards Organization. JATS: Journal Article
Tag Suite. NISO Z39.96-201x. A draft American National Standard
Developed by the National Information Standards Organization. Baltimore,
Maryland: National Information Standards Organization, 2011.

[¶ 58](#r19 "Permalink")

[DocBook 5: The Definitive Guide]() : Norman Walsh.

Detailed description of the DocBook vocabulary for the markup of
computer documentation, also widely used for other kinds of materials.
[full citation ±] Norman Walsh. *DocBook 5: The Definitive Guide.*
Sebastopol, California: O'Reilly Media, 2010.

[¶ 59](#r20 "Permalink")

[DocBook.org](http://docbook.org/) : Norman Walsh, ed.

This site offers an electronic version of Walsh's book on the DocBook
markup language, as well as other DocBook-related material. [full
citation ±] Norman Walsh, ed. DocBook.org. 2011.

[¶ 60](#r21 "Permalink")

[TEI P5](http://www.tei-c.org/release/doc/tei-p5-doc/en/html/index.html)
: Lou Burnard and Syd Bauman, eds.

The TEI Guidelines are the authoritative source of information on the
TEI standard, and the first few chapters in particular are extremely
valuable reading for anyone working in humanities data curation
(particularly for text-based resources). The TEI Consortium Web site at
[http://www.tei-c.org/](http://www.tei-c.org/) has a variety of
supporting materials. [full citation ±] Lou Burnard and Syd Bauman, eds.
*TEI P5: Guidelines for Electronic Text Encoding and Interchange.* TEI
Consortium, 2007. Originally edited by C. M. Sperberg-McQueen and Lou
Burnard for the ACH-ALLC-ACL Text Encoding Initiative. Now entirely
revised and expanded under the supervision of the Technical Council of
the TEI Consortium. 1.9.1. Last updated on March 5th 2011. Oxford,
Providence, Charlottesville, Nancy: TEI Consortium, 2011.

Add resource

### Add a resource

We encourage you to contribute a resource that would be useful for the
humanities data curation community! The most helpful and relevant
resources include best practices documents, high-quality internal
documentation, official standards or recommendations, articles that
describe or analyze best practices, and case studies or projects whose
practice is exemplary. **All content is verified by the managing
editors. Please see our [submission guidelines](../../submissions/) if
you are submitting something for the first time.**

Your name:\*

This is the name to which your submission will be credited

Your e-mail:\*

Your email address will not be published. We will only use it to contact
you regarding this submission.

Your website:

Opt. Your name can be linked to a bio page, Twitter account, or other
website.

* * * * *

Add to resource group:

Title of resource:\*

\

Author(s):\*

e.g., W. Smith and S. Monroe; Dublin Core Metadata Initiative

Publication info:

Publication name or publisher e.g., Digital Digest 20:1 or University
Press

Date of publication:

e.g., 2009, Spring 2010, Jan. 2011

URL:

\
 \

Annotation:\*

What value do you find in this resource? Describe the resource and
explain its relevance.

E.g., "This volume of the International Journal of Digital Curation
offers an excellent overview of the field of data curation through a
combination of peer-reviewed papers and topical articles. For those new
to the field, browsing through the archives of this journal will form an
excellent introduction to both the practice and theory of curation." \
 Add more resources [+]

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

After submission, the editors will respond to you by email. \
 \
 \
 \

[[back to top]](#top)

[¶ 61](#r22 "Permalink")

[Other Formats](#other_formats)

-   [](#) Add comment

[TeX](../glossary.html#tex) is a batch document-formatting program
written by the computer scientist Donald Knuth; its capabilities for
formatting mathematical expressions are particularly well thought of.
Since the formatting commands intrinsic to TeX operate at an extremely
low level, it is customary to use TeX by defining higher level commands
called macros. Over the years, a number of TeX macro sets have been
written.

[¶ 62](#p36 "Permalink")

-   [](#) Add comment

By far the most commonly used set of macros for TeX is
[LaTeX](../glossary.html#latex), originally written by the computer
scientist Leslie Lamport.

[¶ 63](#p37 "Permalink")

-   [](#) Add comment

TeX and LaTeX are in wide use for the creation of technical and
scientific documents, particularly among academics. Unfortunately, the
data format is defined exclusively in terms of the operational semantics
provided by the executable TeX program; while it is possible in
principle to define a declarative semantics for most of LaTeX, in
practice many LaTeX authors extend the system with macros of their own.
For preservation purposes, therefore, TeX and LaTeX documents rely on
the continued existence of software to process them. Fortunately, the
source code for TeX and LaTeX is publicly available and written with a
great deal of care to be device- and system-independent.

[¶ 64](#p38 "Permalink")

-   [](#) Add comment

PostScript is a programming language devised by Adobe Systems
Incorporated; PDF (Portable Document Format) is a document format
devised by the same organization, which uses a subset of PostScript and
provides rules for embedding fonts in a document and for bundling all
the pieces of a document together.

[¶ 65](#p40 "Permalink")

-   [](#) Add comment

While originally a proprietary format, PDF has more recently been
standardized and Adobe has issued a public license allowing the use of
its patented technology in the creation of PDF software that supports
the ISO standard definition of PDF.

[[back to top]](#top)

[¶ 66](#p41 "Permalink")

-   [](#) Add comment

[Resources: Other document formats](#other_document_formats) Collapse
annotations

[TeX Users Group Home Page](http://www.tug.org/) : TeX Users Group.

The TeX Users Group is probably the best source of information about TeX
and related software. [full citation ±] TeX Users Group. TeX Users Group
Home Page.

[¶ 67](#r23 "Permalink")

[Document management — Portable document format]() : ISO: International
Organization for Standardization.

The ISO catalog entry for this specification is available [on the
Web](http://www.iso.org/iso/iso_catalogue/catalogue_tc/catalogue_detail.htm?csnumber=51502).
[full citation ±] ISO: International Organization for Standardization.
ISO 32000-1:2008. Document management — Portable document format — Part
1: PDF 1.7. Geneva: ISO, 2008.

[¶ 68](#r24 "Permalink")

[Portable Document
Format](http://en.wikipedia.org/wiki/Portable_Document_Format) :
Wikipedia.

The Wikipedia article on PDF provides a compact overview of the ways in
which the format and software for it have developed over the years.
[full citation ±] Wikipedia. “Portable Document Format.” Wikipedia.

Add resource

### Add a resource

We encourage you to contribute a resource that would be useful for the
humanities data curation community! The most helpful and relevant
resources include best practices documents, high-quality internal
documentation, official standards or recommendations, articles that
describe or analyze best practices, and case studies or projects whose
practice is exemplary. **All content is verified by the managing
editors. Please see our [submission guidelines](../../submissions/) if
you are submitting something for the first time.**

Your name:\*

This is the name to which your submission will be credited

Your e-mail:\*

Your email address will not be published. We will only use it to contact
you regarding this submission.

Your website:

Opt. Your name can be linked to a bio page, Twitter account, or other
website.

* * * * *

Add to resource group:

Title of resource:\*

\

Author(s):\*

e.g., W. Smith and S. Monroe; Dublin Core Metadata Initiative

Publication info:

Publication name or publisher e.g., Digital Digest 20:1 or University
Press

Date of publication:

e.g., 2009, Spring 2010, Jan. 2011

URL:

\
 \

Annotation:\*

What value do you find in this resource? Describe the resource and
explain its relevance.

E.g., "This volume of the International Journal of Digital Curation
offers an excellent overview of the field of data curation through a
combination of peer-reviewed papers and topical articles. For those new
to the field, browsing through the archives of this journal will form an
excellent introduction to both the practice and theory of curation." \
 Add more resources [+]

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

After submission, the editors will respond to you by email. \
 \
 \
 \

[[back to top]](#top)

[¶ 69](#r25 "Permalink")

[Images](#images)

-   [](#) Add comment

Image formats fall into two classes: raster graphics, which represent
images as an array of picture elements (pixels) coded for color, and
vector graphics, which represent images as sets of geometric shapes
(lines, rectangles, circles, ellipses, curves of various degrees of
complexity, and text).

[¶ 70](#p42 "Permalink")

-   [](#) Add comment

Vector graphics are more often used for the creation of new graphics
than for the digitization of pre-existing non-digital graphic material,
so for curatorial purposes the reader is more likely to encounter raster
graphics than vector graphics. Vector graphics have a number of
properties that make them attractive for the creation of new images,
however (they are often more compact, and they do not degrade when the
user zooms in on details), and the reader may wish to use vector
graphics when creating new materials.

[¶ 71](#p43 "Permalink")

-   [](#) Add comment

Several formats can contain graphic elements in either raster or vector
format.

[[back to top]](#top)

[¶ 72](#p44 "Permalink")

-   [](#) Add comment

[Resources: Raster Graphics](#raster_graphics) Collapse annotations

[Digital images for the information
professional.](http://books.google.com/books/about/Digital_images_for_the_information_profe.html?id=Yyt6rnJmJjoC)
: Melissa M. Terras.

A clear introduction to the principles of raster-based image formats and
survey of widely used and historically significant formats, with a very
explicit focus on digitization of culturally significant materials and
the long-term preservation and use of the resulting data.
(Astonishingly, the book manages to be clear even without itself
containing any graphic images.) [full citation ±] Melissa M. Terras.
*Digital images for the information professional.* Aldershot, Hampshire;
Burlington, Vermont: Ashgate, 2008.

[¶ 73](#r26 "Permalink")

[Portable Network Graphics (PNG), ISO/IEC
15948:2004](http://www.w3.org/TR/2003/REC-PNG-20031110/) : David Duce,
ed.

A useful specification for those who must work with image formats. [full
citation ±] David Duce, ed. *Portable Network Graphics (PNG)
Specification (Second Edition). Information technology — Computer
graphics and image processing — Portable Network Graphics (PNG):
Functional specification. ISO/IEC 15948:2003 (E).* W3C Recommendation 10
November 2003. Cambridge, Mass., Sophia-Antipolis, Tokyo: W3C, 2003.

Add resource

### Add a resource

We encourage you to contribute a resource that would be useful for the
humanities data curation community! The most helpful and relevant
resources include best practices documents, high-quality internal
documentation, official standards or recommendations, articles that
describe or analyze best practices, and case studies or projects whose
practice is exemplary. **All content is verified by the managing
editors. Please see our [submission guidelines](../../submissions/) if
you are submitting something for the first time.**

Your name:\*

This is the name to which your submission will be credited

Your e-mail:\*

Your email address will not be published. We will only use it to contact
you regarding this submission.

Your website:

Opt. Your name can be linked to a bio page, Twitter account, or other
website.

* * * * *

Add to resource group:

Title of resource:\*

\

Author(s):\*

e.g., W. Smith and S. Monroe; Dublin Core Metadata Initiative

Publication info:

Publication name or publisher e.g., Digital Digest 20:1 or University
Press

Date of publication:

e.g., 2009, Spring 2010, Jan. 2011

URL:

\
 \

Annotation:\*

What value do you find in this resource? Describe the resource and
explain its relevance.

E.g., "This volume of the International Journal of Digital Curation
offers an excellent overview of the field of data curation through a
combination of peer-reviewed papers and topical articles. For those new
to the field, browsing through the archives of this journal will form an
excellent introduction to both the practice and theory of curation." \
 Add more resources [+]

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

After submission, the editors will respond to you by email. \
 \
 \
 \

[[back to top]](#top)

[¶ 74](#r27 "Permalink")

[Resources: Vector Graphics](#vector_graphics) Collapse annotations

[Scalable Vector Graphics
(SVG)](http://www.w3.org/TR/2011/REC-SVG11-20110816/) : World Wide Web
Consortium.

The vector format in widest use on the World Wide Web. [full citation ±]
World Wide Web Consortium. Scalable Vector Graphics (SVG) 1.1 (Second
Edition). W3C Recommendation 16 August 2011. Cambridge, Mass.,
Sophia-Antipolis, Tokyo: World Wide Web Consortium, 2011.

Add resource

### Add a resource

We encourage you to contribute a resource that would be useful for the
humanities data curation community! The most helpful and relevant
resources include best practices documents, high-quality internal
documentation, official standards or recommendations, articles that
describe or analyze best practices, and case studies or projects whose
practice is exemplary. **All content is verified by the managing
editors. Please see our [submission guidelines](../../submissions/) if
you are submitting something for the first time.**

Your name:\*

This is the name to which your submission will be credited

Your e-mail:\*

Your email address will not be published. We will only use it to contact
you regarding this submission.

Your website:

Opt. Your name can be linked to a bio page, Twitter account, or other
website.

* * * * *

Add to resource group:

Title of resource:\*

\

Author(s):\*

e.g., W. Smith and S. Monroe; Dublin Core Metadata Initiative

Publication info:

Publication name or publisher e.g., Digital Digest 20:1 or University
Press

Date of publication:

e.g., 2009, Spring 2010, Jan. 2011

URL:

\
 \

Annotation:\*

What value do you find in this resource? Describe the resource and
explain its relevance.

E.g., "This volume of the International Journal of Digital Curation
offers an excellent overview of the field of data curation through a
combination of peer-reviewed papers and topical articles. For those new
to the field, browsing through the archives of this journal will form an
excellent introduction to both the practice and theory of curation." \
 Add more resources [+]

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

After submission, the editors will respond to you by email. \
 \
 \
 \

[[back to top]](#top)

[¶ 75](#r28 "Permalink")

[Databases](#databases)

-   [](#) Add comment

It is central to the conception of database management systems that the
internal data representation of material in the database should not be
visible to users of the database, except through a defined
application-program interface (API) such as SQL. Discussions of the
formats used internally are thus of no particular use to users of
database management systems. They are in any case not standardized;
competing systems strive to find data representations that allow faster
indexing or retrieval and/or more compact storage, and in the case of
commercial products the details of the representation are likely to be a
closely guarded trade secret.

[¶ 76](#p45 "Permalink")

-   [](#) Add comment

In order to allow mass imports or exports of data, however, database
management systems typically provide one or more dump formats which can
be read and written by the system. These are again apt to be
implementation-specific, though comma-separated-value (CSV) formats are
common. There is no standard definition of the CSV format, however, and
implementations vary a good deal in punctuation rules and character
sets. Occasional attempts have been made to write out a coherent
specification for the CSV format, but these appear not to have any
influence on the majority of implementors. The problems inherent in such
variation led database vendors to adopt XML for inter-database exchange
very early in the life of the XML specification.

[[back to top]](#top)

[¶ 77](#p46 "Permalink")

-   [](#) Add comment

[Resources: Databases](#databases_resources) Collapse annotations

[Architecture of a Database
System](http://db.cs.berkeley.edu/papers/fntdb07-architecture.pdf) :
Joseph Hellerstein, Michael Stonebraker, and James Hamilton.

Questions of internal data representation (on disk or in memory) for
databases are tightly intertwined up with overall questions of database
architecture and system design; this resource provides a good, though
very technical, overview of system architecture for database management
systems. Non-technical readers should expect to skim. [full citation ±]
Joseph Hellerstein, Michael Stonebraker, and James Hamilton.
“Architecture of a Database System.” *Foundations and Trends in
Databases* 1, no. 2 (2007): 141-259.

[¶ 78](#r29 "Permalink")

[Readings in Database
Systems](http://books.google.com/books/about/Readings_in_database_systems.html?id=7a48qSMuVcUC)
: Joseph Hellerstein and Michael Stonebraker, eds.

Many of the papers in this collection touch on questions of data
representation. This text is routinely used in graduate computer science
courses, so non-technical readers should expect to skim. [full citation
±] Joseph Hellerstein and Michael Stonebraker, eds. *Readings in
Database Systems.* San Francisco: Morgan Kaufman. First ed. 1988. Third
ed. 1998. Fourth ed. 2005.

Add resource

### Add a resource

We encourage you to contribute a resource that would be useful for the
humanities data curation community! The most helpful and relevant
resources include best practices documents, high-quality internal
documentation, official standards or recommendations, articles that
describe or analyze best practices, and case studies or projects whose
practice is exemplary. **All content is verified by the managing
editors. Please see our [submission guidelines](../../submissions/) if
you are submitting something for the first time.**

Your name:\*

This is the name to which your submission will be credited

Your e-mail:\*

Your email address will not be published. We will only use it to contact
you regarding this submission.

Your website:

Opt. Your name can be linked to a bio page, Twitter account, or other
website.

* * * * *

Add to resource group:

Title of resource:\*

\

Author(s):\*

e.g., W. Smith and S. Monroe; Dublin Core Metadata Initiative

Publication info:

Publication name or publisher e.g., Digital Digest 20:1 or University
Press

Date of publication:

e.g., 2009, Spring 2010, Jan. 2011

URL:

\
 \

Annotation:\*

What value do you find in this resource? Describe the resource and
explain its relevance.

E.g., "This volume of the International Journal of Digital Curation
offers an excellent overview of the field of data curation through a
combination of peer-reviewed papers and topical articles. For those new
to the field, browsing through the archives of this journal will form an
excellent introduction to both the practice and theory of curation." \
 Add more resources [+]

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

After submission, the editors will respond to you by email. \
 \
 \
 \

[[back to top]](#top)

[¶ 79](#r30 "Permalink")

[Numbers](#numbers)

-   [](#) Add comment

Historically, the representation of numbers in electronic form has been
a fundamental design question for computer systems, with analog and
digital representations competing with each other for adoption. In
modern digital systems, four main families of representations can be
distinguished:

-   Integers are typically represented in a fixed-width field of bits,
    either as unsigned base-2 numbers (so the possible values
    representable in a field of n bits range from 0 to 2n) or as signed
    numbers. Different methods of representing negative numbers are
    possible; virtually all current systems use the so-called
    “twos-complement” representation (which will not be explained here).
-   Since binary numbers have rounding properties that differ from those
    of decimal numbers, they can cause problems for financial
    applications (which conventionally assume and require rounding
    behaviors suitable for decimal numbers). For this reason, systems
    intended for commercial use (most notably mainframe computers
    manufactured by IBM) often use binary-coded decimal representations
    of numbers. In this system, groups of four bits are used to
    represent the decimal digits, and a number is represented as a
    sequence of such decimal digits. Fractional numbers are handled by
    conventions at the programming-language level or higher which supply
    an implicit decimal point at a fixed location. The number of bits
    used to represent a number may vary. Computer hardware other than
    IBM mainframes seldom has hardware support for binary-coded decimal
    arithmetic, but software systems designed to support computation
    with large numbers often use binary-coded decimal representations.
-   Real numbers pose a particularly thorny problem for digital systems,
    since one of the fundamental properties of the real number continuum
    (the fact that given any two real numbers we can identify a third
    midway between them) is very difficult to model with a digital
    system. For most purposes, real numbers are represented in modern
    computer systems using floating-point binary numbers, which use a
    fixed-width bit field to represent numbers with a range of values
    and arithmetic precisions. Over the years, the width of the bit
    field commonly used for floating-point numbers has grown from 32
    bits to 64 and 128 bits. The standard representation of
    floating-point binary is defined by IEEE 754, which is supported by
    virtually all current hardware; other floating-point binary formats
    survive in some specialized markets. A 2010 revision of IEEE 754
    specifies not only a floating-point binary but also a floating-point
    decimal format.

[¶ 80](#p47 "Permalink")

-   [](#) Add comment

Those involved with data curation will probably seldom have need for
detailed technical understanding of the formats historically or now used
to represent numbers in computing. (Exceptions may arise when dealing
with material which uses non-standard number formats for any reason.)
But it may be worth while to scan the descriptions of number
representations in Wikipedia, if only to dispel the notion that computer
representations of numbers are somehow natural and thus simpler and less
problematic than computer representations of other datatypes. The
treatment in Wikipedia is reasonably sound, though by nature it will
strike some readers as a bit dry.

[[back to top]](#top)

[¶ 82](#p48 "Permalink")

-   [](#) Add comment

[Resources: Numbers](#numbers_resources) Collapse annotations

[How to Read Floating Point Numbers
Accurately](http://dl.acm.org/citation.cfm?id=93557&dl=ACM&coll=DL&CFID=63750865&CFTOKEN=57767992)
: W. D. Clinger.

For anyone dealing seriously with floating-point binary numbers, this
treatment of reading and writing such numbers is essential reading [full
citation ±] W. D. Clinger. “How to Read Floating Point Numbers
Accurately.” *PLDI '90: Proceedings of the ACM SIGPLAN 1990 conference
on Programming language design and implementation.* New York, NY: ACM,
1990. Rpt. ACM SIGPLAN Notices Volume 25 Issue 6, Jun. 1990, pp. 92-101.

[¶ 83](#r31 "Permalink")

[IEEE Standard for Floating-Point
Arithmetic](http://ieeexplore.ieee.org/xpl/mostRecentIssue.jsp?punumber=4610933)
: IEEE.

Another essential reading for anyone dealing seriously with
floating-point binary numbers. [full citation ±] IEEE. *IEEE 754-2008.
IEEE Standard for Floating-Point Arithmetic* New York: Institute of
Electrical and Electronics Engineers, 2008.

Add resource

### Add a resource

We encourage you to contribute a resource that would be useful for the
humanities data curation community! The most helpful and relevant
resources include best practices documents, high-quality internal
documentation, official standards or recommendations, articles that
describe or analyze best practices, and case studies or projects whose
practice is exemplary. **All content is verified by the managing
editors. Please see our [submission guidelines](../../submissions/) if
you are submitting something for the first time.**

Your name:\*

This is the name to which your submission will be credited

Your e-mail:\*

Your email address will not be published. We will only use it to contact
you regarding this submission.

Your website:

Opt. Your name can be linked to a bio page, Twitter account, or other
website.

* * * * *

Add to resource group:

Title of resource:\*

\

Author(s):\*

e.g., W. Smith and S. Monroe; Dublin Core Metadata Initiative

Publication info:

Publication name or publisher e.g., Digital Digest 20:1 or University
Press

Date of publication:

e.g., 2009, Spring 2010, Jan. 2011

URL:

\
 \

Annotation:\*

What value do you find in this resource? Describe the resource and
explain its relevance.

E.g., "This volume of the International Journal of Digital Curation
offers an excellent overview of the field of data curation through a
combination of peer-reviewed papers and topical articles. For those new
to the field, browsing through the archives of this journal will form an
excellent introduction to both the practice and theory of curation." \
 Add more resources [+]

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

Title:\*

\

Author(s):\*

Publication:

Date:

URL:

\
 \

Annotation:\*

* * * * *

After submission, the editors will respond to you by email. \
 \
 \
 \

[[back to top]](#top)

[¶ 84](#r32 "Permalink")

* * * * *

[General article comments](#allArticleComments)

\
 \

-   [](#) Add comment

**Welcome to the discussion!** \
 [Sign in](#) with Google, Twitter, Yahoo!, or Facebook.

\

Read our [privacy policy »](../privacy/)

Sign out »

Comment: \
 \

[![Institute of Museum and Library
Services](../images/imls-logo.gif)](http://www.imls.gov/) [![Center for
Informatics Research in Science and
Scholarship](../images/cirss-logo-sm.gif)](http://cirss.lis.illinois.edu)
[![Graduate School of Library and Information
Science](../images/gslis36.gif)](http://lis.illinois.edu) [![University
of Illinois at
Urbana-Champaign](../images/black26.gif)](http://illinois.edu)
[![Creative Commons
License](http://i.creativecommons.org/l/by-nc-nd/3.0/80x15.png)](http://creativecommons.org/licenses/by-nc-nd/3.0/)

This work is licensed under a [Creative Commons
Attribution-NonCommercial-NoDerivs 3.0 Unported
License](http://creativecommons.org/licenses/by-nc-nd/3.0/). \
 **How to cite:**C. M. Sperberg-McQueen, . David Dubin. "Data
Representation", *DH Curation Guide: a community resource guide to data
curation in the digital humanities*,

.

[DH Curation Guide home](../index.html) \
 [About this site](../about/) [Contents](../contents/) [FAQ about data
curation](../faq/) [Contributing editors](../editors/)
[Glossary](../glossary.html) [Privacy](../privacy/) [Contact
us](../about#contact) [Sitemap](../sitemap.html) \
 \

Page updated 2012-06-25

[[back to top]](#top)

ce436b201a344c7eb12e8086def3ace5
