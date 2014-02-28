-   [DH Curation Guide](../../index.html)
-   [Contents](../../contents/)
    -   [Introduction to Humanities Data Curation](../../intro/)
    -   [Data Representation](../../representation/)
    -   [Classics & “Digital
        Classics”](../../research-practices/classics/)
    -   [Digital Collections](../../collections/)
    -   [Standards](../../collections/standards/)
    -   [Policy, Practice, & Law](../../legal/policy/)
    -   [Metadata (stub)](../../metadata/)
    -   [Digital Preservation (stub)](../../preservation/)
    -   [*Full table of contents*](../../contents/)

-   [About](../../about/)
-   [FAQ/DC](../../faq/)
-   [Editors](../../editors/)
-   [Glossary](../../glossary.html)

[▲](#top)

[**DH Curation Guide**](../../index.html)

Classics, “Digital Classics” and Issues for Data Curation [Alison Babeu,
Perseus Project, Tufts
University](../editors/#alisonbabeu "Contributor page")

[![Save to
Delicious](../../images/del-20.gif "Save to Delicious")](https://www.delicious.com/save)

[Tweet](https://twitter.com/share)

[![image](../../images/pdf.png "Download as PDF") Download PDF](pdf.php)

### Article contents [±]

-   Introduction
-   Cyberinfrastructure for Digital Classics
-   Resources: Cyberinfrastructure for Digital Classics
-   Virtual Research Environments and Research Portals/Projects
-   Resources: General Classics portals
-   Resources: Ancient Near Eastern Studies portals
-   Resources: Archaeology portals
-   Resources: Manuscript Resources and Philology portals
-   Resources: Papyrology portals
-   Digital Repositories
-   Primary Sources and Research Data
-   Resources: Archaeology research data
-   Resources: Epigraphy research data
-   Resources: Manuscript Studies research data
-   Secondary Scholarship
-   Resources: Working papers
-   Federated Collections and Research Databases
-   Resources: Federated Collections and Research Databases
-   Standards
-   Resources: Ancient Near Eastern Studies standards
-   Resources: Archaeology standards
-   Resources: Epigraphy standards
-   Resources: Manuscript Studies standards
-   Resources: Papyrology
-   Resources: Philology
-   Collaborative and Communication Tools
-   Resources: Collaborative and Communication Tools
-   Model Digital Resources
-   Resources: Epigraphy best practices models
-   Resources: Manuscript Studies best practices models
-   Resources: Papyrology best practices models
-   Digital Preservation Lessons from Classics
-   Resources: Digital Preservation Lessons from Classics
-   Research Practices
-   Archaeology
-   Epigraphy
-   Manuscript Studies and Related Classical Disciplines
-   Papyrology
-   General article comments

[§ 1](#classics)

[Introduction](#classics)

-   [](#) Add introduction comment

The field of classics encompasses a large number of related disciplines
such as archaeology, epigraphy, manuscript studies, numismatics,
philology and papyrology, each with their own unique set of research
methods, objects of study (including various types of artifacts, ancient
monuments, ancient documentary and literary texts, coins, inscriptions,
papyri, etc.), and various ways of sharing and preserving data.
Classical studies is thus an inherently interdisciplinary field that has
also long made use of advanced digital technologies (e.g. advanced
imaging and document recognition for classical languages such as
Sumerian, Ancient Greek and Latin, the 3D reconstruction and
visualization of ancient monuments, and the use of
[TEI-XML](../../glossary.html#TEI) to create digital editions of
classical texts). The relatively advanced digital nature of many
classical disciplines has in turn shaped both the research practices of
the field and increased the need for data curation strategies that
address the complex needs both of specific disciplinary research methods
and specific types of digital data that are created as part of the
research process. While the field of classics has long faced the issue
of preserving fragile physical artifacts such as damaged manuscripts and
centuries old fragments of papyri, it now increasingly faces the
challenges of preserving digital objects created to represent these
artifacts as well.

[¶ 1](#p01 "Permalink")

-   [](#) Add section comment

Complicating matters is the fact that for many of the disciplines of
classics, preserving the interpretative stages and individual decisions
involved in creating a “final” scholarly argument can be as important as
preserving the final result of such scholarship, such as a virtual
reconstruction or digital edition of an inscription. For example, the
digital reconstructions of archaeological monuments typically involve a
large amount of uncertainty and individual scholarly interpretation, yet
many visualizations are often viewed by students as complete and
accurate representations of “reality.” Similarly, in creating a digital
edition of a classical text (e.g. a play of Aeschylus with many
manuscript sources), many individual scholarly decisions are made in
terms of what text variants to include or what manuscript witnesses are
considered more reliable, yet many digital editions lack the “[apparatus
criticus](../../glossary.html#appcrit)” that contains such decisions and
can give the illusion of one text. These issues and projects/solutions
that have been created to address them will receive further attention
below.

[¶ 2](#p02 "Permalink")

-   [](#) Add section comment

For data curators, the key question to consider is how the research
practices of “digital classics” are creating new challenges for data
curation, and indeed a number of significant projects across the
disciplines are currently working to address some of these challenges.
Despite often seemingly huge differences between various disciplines in
the field of classics, there are a number of common themes that will
require further research and collaboration between classical scholars
and those working in data curation.

[¶ 3](#p03 "Permalink")

-   [](#) Add section comment

To begin with, the difficulties of defining both the complex semantics
and structure of classical data that needs to be preserved must be
addressed. Data in classics is extensively multi-lingual and
multi-script (with many different languages such as Ancient Greek,
Latin, Sumerian, Sanskrit, etc.) The same data (e.g. data about the same
classical place, person or other named entity, descriptions of the same
archaeological object, multiple images of the same inscription) found
across different projects is also often described using very different
vocabularies. Similarly, more research will need to focus on how
meaningful data integration might be used to create larger digital
classical resources that could then possibly be more effectively
curated. A variety of issues complicate this process, including the fact
that multiple digital facsimiles of objects exist in various digital
data collections (often with greatly varying levels of metadata). To
solve this issue, many projects have chosen to create virtual data
centers or utilized a federated approach allowing data to remain
distributed and independent. In fact, complete interoperability or full
data integration may be impossible to attain and is also not necessarily
an ideal solution according to many practitioners.

[¶ 4](#p04 "Permalink")

-   [](#) Add section comment

As indicated by the projects that will be covered here, the process of
data curation and of ensuring data sustainability has many components.
Many consider the technical components of sustainability to be the
easiest task for the long run and stress that long-term financial
planning for the organization (or organizations) that will host and
curate the data is far more essential. Similarly, political
considerations of both the needs of data contributors/partners and users
(both current and future) must be taken into consideration.

[¶ 5](#p05 "Permalink")

-   [](#) Add section comment

The issue of standards and digital preservation/curation is also of
great importance, and many projects emphasized the potential use of
[XML](../../glossary.html#xml) as a preservation format for digital
humanities data. Standard formats are required to ensure some level of
data conformity for both interoperability and long-term curation, and
tools were frequently developed by projects to help scholars and other
contributors create data that conforms to standard formats or
[ontologies](../../glossary.html#ontology).

[¶ 6](#p06 "Permalink")

-   [](#) Add section comment

Regardless of the discipline, a number of basic requirements for a
digital repository or data curation system have been clearly identified.
To begin with, systems must provide for clear authorship of data
contributors to ensure proper attribution and credit. Varying levels of
editorial control and authorization will also typically be required, and
many system developers also note that the ability to support at least
temporary embargoing of data in both the short and long term is a
frequently desired feature of users. While all data must be clearly
[versioned](../../glossary.html#version), it is clear that earlier
versions of data must also be kept available in order to ensure
persistent citation and a fully traceable scholarly record. To assist in
this process, standard identifiers should thus be used whenever possible
to encourage persistent citation and linking. Another important feature
was providing for different levels of participation (e.g. supporting
full service hosting of content vs. allowing users to act as digital
curation partners).

[¶ 7](#p07 "Permalink")

-   [](#) Add section comment

Another significant issue is the challenge of curating humanities
research as well as digital data. Many projects and resources have
illustrated that the scholarly interpretations of digital objects need
to be encoded and stored as one form of metadata along with other more
traditional types of metadata (e.g. technical, administrative, etc.)
Curators will need to understand how digital data is used by scholars in
their research in order to best support both active curation and to help
plan for future use of that data. One potential research topic is
studying how to develop collaborative workspaces that save and curate
data as it is being created: for instance, how does one effectively
curate a distributed editing environment? Similarly, further research is
needed in how best to curate algorithms and computational processes that
are used in the creation of digital data and now often serve as a key
part of creating humanities scholarship.

[¶ 8](#p08 "Permalink")

-   [](#) Add section comment

A final topic frequently raised is how active curation that supports
data reuse might serve as one method of effective long-term
preservation. To begin with, open licensing schemes are required (in
order to make multiple copies of data for preservation and to support
reuse). Additionally, at least some minimal metadata must be encoded
with digital data to support greater reuse in the future. An essential
role for curators in this task is to promote the development of
"communities of use" around the digital objects they curate.

[¶ 9](#p09 "Permalink")

-   [](#) Add section comment

As illustrated above, a number of important issues for data curation
exist across the classical disciplines, and a number of projects seeking
to address these issues will be examined in greater detail here. The
resources presented here have been grouped by important themes and drawn
from across the related disciplines.

[[back to top]](#top)

[¶ 10](#p10 "Permalink")

-   [](#) Add section comment

[§ 2](#cyberinfrastructure_for_digital_classics)

[Cyberinfrastructure for Digital
Classics](#cyberinfrastructure_for_digital_classics)

-   [](#) Add section comment

In order to support data curation and digital preservation across the
spectrum of classical disciplines, there have been increasing calls from
within the discipline to build a sophisticated cyberinfrastructure that
can support a wide variety of research needs. A recent issue of the
Digital Humanities Quarterly (DHQ) entitled [Changing the Center of
Gravity: Transforming Classical Studies Through
Cyberinfrastructure](http://www.digitalhumanities.org/dhq/vol/3/1/index.html)
included a series of articles that addressed different aspects of such a
cyberinfrastructure. There have also been calls to create a
comprehensive digital library or repository that can preserve a variety
of digital classical scholarship, as addressed by the articles listed
below.

[[back to top]](#top)

[¶ 11](#p11 "Permalink")

-   [](#) Add paragraph comment

[Resources: Cyberinfrastructure for Digital
Classics](#cyberinfrastructure_for_digital_classics_resources) Collapse
annotations

[Conclusion: Cyberinfrastructure, the Scaife Digital Library and
Classics in a Digital
Age](http://www.digitalhumanities.org/dhq/vol/3/1/000035.html) : G.
Crane and C. Blackwell.

This article summarizes the requirements for a cyberinfrastructure in
classics including the need for open access data, comprehensive
collections, “curated knowledge sources” and “advanced, domain optimized
services” such as advanced [OCR](../../glossary.html#ocr), morphological
analysis, citation identification and text alignment. It also introduces
the Scaife Digital Library (currently in development) that will serve as
a long term digital repository for classics and will require that all of
the digital objects deposited in it meet four basic criteria: 1) the
content must be of wide-ranging interest to those other than its
creators 2) it must be in a format that can be both preserved and used
over the long-term 3) it must have at least one other long-term home 4)
it must be able to circulate freely. [full citation ±] G. Crane and C.
Blackwell. “Conclusion: Cyberinfrastructure, the Scaife Digital Library
and Classics in a Digital Age.” *Digital Humanities Quarterly* 3(1)
(2009).

[¶ 12](#r100 "Permalink")

[Cyberinfrastructure for Classical
Philology](http://www.digitalhumanities.org/dhq/vol/3/1/000023.html#) :
G. Crane, B. Seales, and M. Terras.

An overview is provided here of the digital resources and
cyberinfrastructure required to support a new level of “digital
philology.” [full citation ±] G. Crane, B. Seales, and M. Terras.
“Cyberinfrastructure for Classical Philology.” *Digital Humanities
Quarterly* 3(1) (2009).

[¶ 13](#r101 "Permalink")

[Tools for Thinking: ePhilology and
Cyberinfrastructure](http://www.clir.org/activities/digitalscholar2/crane11_11.pdf)
: G. Crane, A. Babeu, D. Bamman, L. Cerrato, and R. Singhal.

Crane et al. present an overview of the types of primary and secondary
source data that will be required for a cyberinfrastructure for
classical philology, including “digital representations of the human
record” —page images of manuscripts and printed books; “labeled
information about the human record”—annotations (e.g. named entities);
and finally, “access to automatically generated knowledge”—or the
processes of algorithms. [full citation ±] G. Crane, A. Babeu, D.
Bamman, L. Cerrato, and R. Singhal. “Tools for Thinking: ePhilology and
Cyberinfrastructure.” In *Working Together or Apart: Promoting the Next
Generation of Digital Scholarship: Report of a Workshop Cosponsored by
the Council on Library and Information Resources and The National
Endowment for the Humanities* (2009), 16-26.

[¶ 14](#r102 "Permalink")

[Archaeology Case
Study](http://escholarship.org/uc/item/15x7385g#page-37) : D. Harley,
S.K. Acord, S. Earl-Novell, S. Lawrence, and C.J. King.

This subsection of a far larger report provides detailed analysis of
scholarly communication in the field of archaeology, including
traditional and digital publishing, types of archaeological data, data
sharing and long-term preservation issues. [full citation ±] D. Harley,
S.K. Acord, S. Earl-Novell, S. Lawrence, and C.J. King. “Archaeology
Case Study.” In *eScholarship: Assessing the Future Landscape of
Scholarly Communication*. Center for Studies in Higher Education,
University of California-Berkeley (2010), 29-135.

[¶ 15](#r103 "Permalink")

[Going AWOL
(ancientworldonline.blogspot.com/)](http://csanet.org/newsletter/winter10/nlw1001.html)
: Chuck Jones.

Chuck Jones, director of the library at the Institute for the Study of
the Ancient World (ISAW), describes in this article both his work in
creating the online [Abzu bibliography](http://www.etana.org/abzubib)and
on finding open access resources for his blog the [Ancient World
Online](http://ancientworldonline.blogspot.com/). He also provides some
initial detail on plans by ISAW to develop an “Ancient World Digital
Library” (AWDL), a sample book viewer of which [has just been
announced](http://dlib.nyu.edu/awdl/). [full citation ±] Chuck Jones.
“Going AWOL (ancientworldonline.blogspot.com/): Thoughts on Developing a
Tool for the Organization and Discovery of Open Access Scholarly
Resources for the Study of the Ancient World.” *CSA Newsletter* XXII (3)
(2010).

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

[¶ 16](#r104 "Permalink")

[§ 3](#virtual_research_environments_and_research_portals_and_projects)

[Virtual Research Environments and Research
Portals/Projects](#virtual_research_environments_and_research_portals_and_projects)

-   [](#) Add section comment

Another major challenge for data curation in classics and across the
humanities will be determining how to curate data that is created
through increasing scholarly use of [virtual research
environments](../../glossary.html#vre) (VREs) or disciplinary research
portals that are currently being created in a number of humanities
disciplines. Data is broadly construed here not just as the structured
or unstructured data sources that are made available through such
environments, but also the algorithms and computational processes that
are often used in the creation of digital scholarship. There are many
projects across the classical disciplines that have sought to develop
VREs or portals that have already and will continue to create large
amounts of digital data, and this list of resources has been grouped by
larger discipline.

[[back to top]](#top)

[¶ 17](#p12 "Permalink")

-   [](#) Add paragraph comment

[Resources: General Classics portals](#general_classics) Collapse
annotations

[eAQUA—Extraction of Structured Knowledge from Ancient
Sources](http://www.eaqua.net/en/index.php) : eAQUA.

The German research project eAQUA is currently developing a research
portal that will provide access to corpora from a number of research
partners through a standardized data interface as well as access to a
number of text mining algorithms. A large part of their research has
involved exploring how traditional research questions in classics (e.g.
the study of text reuse in ancient sources) can be served by different
[natural language processing](../../glossary.html#nlp) (NLP) algorithms
by having classicists work together with computer scientists on actual
research tasks. This model of having domain specialists and technical
staff work together to inform infrastructure development is an important
model for both cyberinfrastructure and curation efforts, as defining
both humanities data and research processes will require the active
involvement of both curators and scholars. The website provides further
information about the general architecture of eAQUA and specific
information on the various research sub-projects. [full citation ±]
eAQUA. *eAQUA—Extraction of Structured Knowledge from Ancient Sources.*

[¶ 18](#r105 "Permalink")

[eAQUA—Bringing Modern Text Mining Approaches to Two Thousand Years Old
Ancient
Texts](http://www.clarin.eu/system/files/2008-09-05-IEEE2008-eAQUA-project.pdf)
: M. Büchler, G. Heyer, and S. Grunder.

This article provides an overview of the German research project eAQUA,
which is currently developing a research portal to provide access to
corpora from a number of research partners through a standardized data
interface as well as access to a number of text mining algorithms. It
also situates the project in relation to the current state of the art,
and offers an analysis of the challenges involved in applying natural
language processing to data in classics. [full citation ±] M. Büchler,
G. Heyer, and S. Grunder. “eAQUA—Bringing Modern Text Mining Approaches
to Two Thousand Years Old Ancient Texts.” In *e-Humanities—an emerging
discipline: Workshop in the 4th IEEE International Conference on
e-Science* 2008.

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

[¶ 19](#r106 "Permalink")

[Resources: Ancient Near Eastern Studies
portals](#ancient_near_eastern_studies) Collapse annotations

[Digital Hammurabi](http://www.jhu.edu/digitalhammurabi/index.html) :
Johns Hopkins University.

The Digital Hammurabi project was founded in 1999 at Johns Hopkins
University with a focus on solving three technological problems:

the creation of a standard computer encoding for Cuneiform text

the creation of comprehensive online Cuneiform collections

solutions for 3d scanning and visualization of the tablets

By 2011, the project had successfully invented a 3d surface scanner for
Cuneiform tablets, overseen a [Unicode](../../glossary.html#unicode)
adoption of the first international standard representation for
Cuneiform, and the creation of iClay, a “a cross-platform,
Internet-deployable, Java applet that allows for the viewing and
manipulation of 2D+ images of cuneiform tablets” [(see Cohen et al.
2004)](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.73.87&rep=rep1&type=pdf).
[full citation ±] Johns Hopkins University. *Digital Hammurabi.*

[¶ 20](#r107 "Permalink")

[Digital Preservation of Ancient Cuneiform Tablets Using
3D-Scanning](%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.58.9706&rep=rep1&type=pdf%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20)
: S. Kumar D. Snyder D. Duncan J. Cohen J. Cooper.

Kumar et al. discuss the importance of using 3D scanning as one method
of preserving cuneiform tablets. As cuneiform tablets frequently exhibit
three-dimensional writing on three-dimensional surfaces, high-resolution
3D models of tablets provide far greater visual access of the text to
scholars, will help limit physical contact with fragile tablets, and can
also provide redundant archival copies. [full citation ±] S. Kumar D.
Snyder D. Duncan J. Cohen J. Cooper. “Digital Preservation of Ancient
Cuneiform Tablets Using 3D-Scanning.” In *Proceedings of the Fourth
International Conference on 3-D Digital Imaging and Modeling* 2003,
326-333.

[¶ 22](#r108 "Permalink")

[Open Richly Annotated Cuneiform Corpus
(ORACC)](http://oracc.museum.upenn.edu/index.html) : University of
Pennsylvania.

The ORACC project has grown out of the CDLI and also makes use of
technology developed by the [Pennsylvania Sumerian Dictionary
(PSD)](http://psd.museum.upenn.edu/epsd/index.html). The project website
explains that ORACC has been designed as a “workspace and toolkit for
the development of a complete corpus of cuneiform whose rich annotation
and open licensing support the next generation of scholarly research”.
The CDLI, PSD, and a number of other digital cuneiform projects are
collaborating on the ORACC project, which is intended to function as a
“corpus building cooperative” that will provide both technical
assistance and a long-term infrastructure for building freely available
editions of cuneiform texts. The ORACC project wishes to promote both
open and reusable data so they plan to recommend that all participating
projects use Creative Commons licenses for their materials. The ORACC
project has outlined six major roles for potential contributors with
specific documentation for each role:

users or scholars who will use the ORACC corpora,

builders or individuals who are working on texts to build up the corpus
such as through data entry or transcription,

managers or someone who is actively managing a ORACC sub-project,

developers or individuals who wish to contribute code,

system administrators, and

steerers (senior ORACC users).

As ORACC is a growing project, they are also actively encouraging
researchers to contribute texts through either a donation or curation
model. Through the donation model, text editions and metadata are sent
to ORACC and they handle all installation, conversion and maintenance
(proper identification and credit for all data will be given with all
revisers identified). In the curation model, the ORACC team helps a user
set up their texts as a separate research project on the ORACC servers
and that user/curator is then responsible for maintaining their own
texts (this model provides greater control over one’s texts). ORACC
provides an excellent model of data curation and reuse through the use
of CC licenses, common standards, and documentation on data storage,
creation and maintenance. In addition, by encouraging two different data
contribution models, they recognize that there may be many scholars who
wish to share their data but who lack the desire, time or skills to
maintain it online. [full citation ±] University of Pennsylvania. *Open
Richly Annotated Cuneiform Corpus (ORACC).*

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

[¶ 23](#r109 "Permalink")

[Resources: Archaeology portals](#archaeology) Collapse annotations

[Dealing with the Complexity Deluge: VREs in the Arts and
Humanities](http://dx.doi.org/10.1108/07378830910968164) : S. Dunn.

Dunn describes the development of a [VRE](../../glossary.html#vre) in
archaeology, the importance of depositing archaeological data into
digital repositories or VREs, the challenges of preserving copyright and
intellectual property rights for such data, and the importance of both
peer review and authentication of data. [full citation ±] S. Dunn.
“Dealing with the Complexity Deluge: VREs in the Arts and Humanities.”
*Library Hi Tech* 27.2 (2009), 205-216.

[¶ 25](#r110 "Permalink")

[VERA: A Virtual Environment for Research in
Archaeology](http://www.ncess.org/events/conference/programme/fri/3abaker.pdf)
: M. Baker, C. Fisher, E. O'Riordan, M. Grove, M. Fulford, C. Warwick,
A. Clarke, M. Rains, and

This article gives an overview of the [VERA
project](http://vera.rdg.ac.uk/), which explored how the use of digital
technology (e.g. direct entry into a database through PDAs, or the use
of digital pens to take notes) in the field might lead to more effective
and accurate entry of archaeological data. One major goal was to explore
if digital data entry in the field led to improved data quality in the
long run. The VERA project team had archaeologists keep diaries,
conducted interviews and a workshop, and implemented user testing with
the [Integrated Archaeological Database
(IADB)](http://www.iadb.org.uk/). They discovered that higher data
quality was actually obtained by maintaining paper recording of contexts
and continuing the role of an individual supervisor in collating the
reports and entering them into the database. This project illustrates
the importance of observing actual research practices before determining
long-term data entry and curation strategies, and warns against assuming
that disciplinary practices will be automatically improved through the
addition of technology. [full citation ±] M. Baker, C. Fisher, E.
O'Riordan, M. Grove, M. Fulford, C. Warwick, A. Clarke, M. Rains, and
“VERA: A Virtual Environment for Research in Archaeology.” *Fourth
International Conference on e-Social Science, University of Manchester,
June 18-20, 2008*. 2008.

[¶ 26](#r111 "Permalink")

[Virtual Environment for Research in Archaeology
(VERA)](http://vera.rdg.ac.uk/) : VERA.

This website provides access to the results of this research project,
the project blog, and other useful information about what they learned.
[full citation ±] VERA. *Virtual Environment for Research in Archaeology
(VERA).*

[¶ 27](#r112 "Permalink")

[Integrated Archaeological Database (IADB)](http://www.iadb.org.uk/) :
IADB.

This database for managing and archiving archaeological information was
first developed in the 1980s, and is currently available as a web-based
application that makes use of Ajax, MySQL and PHP. It has been used in a
number of archaeological research projects including VERA and the
[Silchester Roman Town Project](http://www.silchester.rdg.ac.uk/). [full
citation ±] IADB. *Integrated Archaeological Database (IADB).*

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

[¶ 28](#r113 "Permalink")

[Resources: Manuscript Resources and Philology
portals](#manuscript_resources_and_philology) Collapse annotations

[TextGrid](http://www.textgrid.de/en/startseite.html) :

The TextGrid project first began in 2006 with a primary focus on
philology but has grown over the last five years into a
cyberinfrastructure in the humanities project with over 10 partners.
TextGrid is working to create a VRE for the humanities that includes two
key components:

a repository that will serve as a long term data archive for humanities
research embedded in a grid environment that will ensure both the
availability and interoperability of data.

a downloadable “TextGrid laboratory” that will serve as the entry point
to the VRE and provide access to both existing and new tools as they
develop.

The website provides extensive technical documentation for both the
repository design and the TextGrid laboratory, a full list of reports
and publications (many available in full text), and a [downloadable beta
version of
TextGridLab](http://www.textgrid.de/en/beta/installation.html). [full
citation ±] TextGrid

[¶ 29](#r114 "Permalink")

[Open eHumanities Digital Ecosystems and the Role of Resource
Registries](http://dx.doi.org/10.1109/DEST.2009.5276672) : A.
Aschenbrenner, M.W. Kuster, C. Ludwig, and T. Vitt.

While this article offers many details about the TextGrid architecture
and project, it also posits larger thoughts on developing what
Aschenbrenner et al. describe as “eHumanities digital ecosystems”.
Aschenbrenner et al. argue that data, “knowledge about data” and
services that can be used with that data are all key resources in the
humanities, and consequently state that the greatest challenge is to
find efficient and meaningful ways to connect these resources. While
intellectual content (textual and image resources contributed from a
variety of partners) is key to TextGrid, they also note that the
community that uses it is just as important. The model of TextGrid’s
development is as an open infrastructure with fairly generic services
being developed in the beginning, while also promoting community
creation of specialized applications and workflows that can then be made
available through the TextGrid system. Aschenbrenner et al. explain that
active community building has been one of their most important tasks,
with documentation designed and outreach conducted for three specific
user groups (visitors/users, data providers, tool developers). TextGrid
has thus been designed as a [service oriented
architecture](../../glossary.html#soa) (SOA) with multiple layers:

an Eclipse-based application environment (the user interface or
TextGridLab),

generic services for textual analysis and processing (with a platform
that can be customized for new services),

TextGrid middleware, and

stable data archives.

[full citation ±] A. Aschenbrenner, M.W. Kuster, C. Ludwig, and T. Vitt.
“Open eHumanities Digital Ecosystems and the Role of Resource
Registries.” *DEST '09-3rd IEEE International Conference on Digital
Ecosystems and Technologies*. 2009), 745-750.

[¶ 31](#r115 "Permalink")

[Teuchos](http://beta.teuchos.uni-hamburg.de/) : University of Hamburg
and Aristotle Archive.

The Teuchos project is based at the University of Hamburg and is working
in partnership with the Aristotle Archive at the free university of
Berlin. They are focused on building a research infrastructure for
philology that includes the digitization, encoding and description of
manuscripts, the development of an XML encoding for manuscript
watermarks, the creation of a web-based environment for philological
research that includes a [Fedora](../../glossary.html#fedora)
repository, the management of heterogeneous data, and the support of
multi-lingual research. The website (in German) provides further details
on all of these aspects. [full citation ±] University of Hamburg and
Aristotle Archive. *Teuchos.*

[¶ 33](#r116 "Permalink")

[Representation and Encoding of Heterogeneous Data in a Web Based
Research Environment for Manuscript and Textual
Studies](http://kups.ub.uni-koeln.de/volltexte/2009/2962/) : D. Deckers,
L. Koll, and C. Vertan.

Deckers et al. give a detailed examination of the data encoding and
representation being developed for manuscripts (with a focus on the
importance of encoding both structural and intellectual content), as
well as a thorough technical overview of the open-source Teuchos
platform. The major goal of their “web based research environment” is to
provide access to both primary (e.g. images of multiple manuscripts,
transcriptions of manuscripts) and secondary source data (reference
works, scholarly papers) and to tools that philologists working in
manuscript and textual studies can use to capture, exchange and
collaboratively edit philological data. Teuchos hopes to make all of the
data created by their project available as “primary or raw data in order
to be reusable as source material for various individual or
collaborative research projects” and will use Creative Commons licenses
whenever possible (though the authors acknowledge that access to
digitized manuscript images will depend on the policy of the
contributing institution). The Teuchos platform will also support three
kinds of users who can interact with the repository:

system administrators

registered users that can contribute resources, and

public users who can view resources

. In addition, the Teuchos Fedora repository has also been designed to
accommodate a variety of heterogeneous digital objects including
manuscript watermarks (digital images and custom XML documents),
digitized manuscripts and manuscript information (digital images of
pages, aggregated image files, codicological descriptions, transcription
files in [TEI-XML](../../glossary.html#tei)), digitized works (full
critical editions of classical texts, translations, commentaries),
reference works, and published research papers. The Teuchos project
illustrates the need for digital repositories to accommodate vastly
different types of data even within a limited area of humanities study.
[full citation ±] D. Deckers, L. Koll, and C. Vertan. “Representation
and Encoding of Heterogeneous Data in a Web Based Research Environment
for Manuscript and Textual Studies.” *Kodikologie und Paläographie im
digitalen Zeitalter-Codicology and Palaeography in the Digital Age*,
2009).

[¶ 34](#r117 "Permalink")

[Virtual Manuscript Room (VMR)](http://vmr.bham.ac.uk/) : University of
Birmingham.

The VMR, based at the University of Birmingham, seeks to provide
advanced access to an important collection of manuscripts, namely the
Mingana Collection of Middle Eastern Manuscripts. While high-resolution
images and extensive manuscript descriptions will be provided, the next
phase of VMR work seeks to develop a comprehensive framework for digital
manuscripts that will “bring together digital resources related to
manuscript materials (digital images, descriptions and other metadata,
transcripts) in an environment which will permit libraries to add
images, scholars to add and edit metadata and transcripts online, and
users to access material” ([About](http://vmr.bham.ac.uk/about/)). In
this next phase they will join with a parallel VMR being built at the
University of Munster, Germany. Some key features that distinguish the
VMR are that it is designed around highly granular metadata, for example
records are presented for each manuscript page with varying levels of
data, such as if there is a text transcription for that page. All VMR
materials are also stored in the UB institutional repository and made
available through the online catalog, and the VMR is also supporting
full reuse of its materials, not just basic web access to them. All
metadata created will be made available through a syndicated RSS feed,
and users will be able to create their own interfaces to VMR data. Users
will also be able to add material to the VMR by creating metadata
records using VMR protocols. [full citation ±] University of Birmingham.
*Virtual Manuscript Room (VMR).*

[¶ 36](#r118 "Permalink")

[Editing Without
Walls](http://dx.doi.org/10.1111/j.1741-4113.2009.00676.x) : Peter
Robinson.

In this piece, Robinson discusses the need for new collaborative editing
models, such as the [VMR](#r118), in order to invigorate the field of
creating digital critical edition (e.g. of classical authors, medieval
manuscripts, etc.). He suggests that the digital world has made a new
collaborative model possible where libraries could put up images of
manuscripts, multiple scholars/students could make transcriptions that
link to these images, other scholars could collate these transcriptions
and publish editions online linking to both the transcriptions and
images, and yet more scholars could analyze these collations and create
an apparatus or commentaries, and other scholars could then link to
these commentaries. All of these activities could occur independently or
together. He also encourages humanists to actively participate in the
development of any infrastructure that is targeted at them. [full
citation ±] Peter Robinson. “Editing Without Walls.” *Literature
Compass* 7 (2010), 57-61.

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

[¶ 37](#r119 "Permalink")

[Resources: Papyrology portals](#papyrology) Collapse annotations

[eScience and Ancient Documents (eSAD)](http://esad.classics.ox.ac.uk) :
University of Oxford.

The eSAD project, a research collaboration between the e-Research Centre
and the Centre for the Study of Ancient Documents and Engineering
Science at the University of Oxford, has examined how to develop
e-Science tools that will assist scholars in interpreting damaged texts
and also developed a number of image analysis algorithms that can be
used with digitized images of ancient texts. This website provides
access to their results, as well as to a myriad of publications that are
all available for download, two of which are described in greater detail
below, with a focus on the lessons they provide for data curation. [full
citation ±] University of Oxford. *eScience and Ancient Documents
(eSAD).*

[¶ 38](#r120 "Permalink")

[An Image Processing Portal and Web-service for the Study of Ancient
Documents](http://ieeexplore.ieee.org/xpls/abs_all.jsp?arnumber=5380891)
: S.M. Tarte, D. Wallow, P. Hu, K. Tang, and T. Ma.

This article examines the development of the [Virtual Research
Environment for the Study of Documents and Manuscripts
(VRE-SDM)](http://bvreh.humanities.ox.ac.uk/VRE-SDM.html) that was
expanded by the eSAD project to provide a collaborative environment
where scholars could work on images of ancient texts stored on the grid
and make use of a variety of advanced document processing algorithms.
[full citation ±] S.M. Tarte, D. Wallow, P. Hu, K. Tang, and T. Ma. “An
Image Processing Portal and Web-service for the Study of Ancient
Documents.” *5th IEEE conference on e-Science 2009*. 2009), 14-19.

[¶ 39](#r121 "Permalink")

[The Case of the Disappearing Ox: Seeing Through Digital Images to an
Analysis of Ancient
Texts](https://www.sugarsync.com/pf/D259396_79_12126677) : G. de la
Flor, P. Luff, M. Jirotka, J. Pybus, R. Kirkham, and A. Carusi.

The work of de la Flor et al. (2010) documents (through videotaping and
interviews) the collaborative work session of three domain experts
working with an ancient tablet using their system prototype. They hoped
to discover and document the scholarly practices and logical processes
being used by the scholars in their work and determine how a
[VRE](../../glossary.html#vre) might emulate and support those methods.
Observing scholars realistically work with actual objects in their
prototype system helped identify key deductive processes (e.g. the
iterative identification of shapes and letters by scholars and the
importance of different types of background knowledge for textual
analysis) that provided greater insights for the system designers.
Useful information in particular was made available to the system
designers in terms of what types of contextual data should be made
available to scholars in such a prototype, what types of data that
scholars created would be most useful to be preserved, what types of
data should be made available to share between researchers, and what
types of algorithms were most useful for working with different types of
data (e.g. images, annotations, etc.). They conclude that relevant
lessons for e-infrastructure and data curation include the importance of
sharing specialized knowledge resources between systems and allowing
scholars to record and support different interpretations of a text.
[full citation ±] G. de la Flor, P. Luff, M. Jirotka, J. Pybus, R.
Kirkham, and A. Carusi. “The Case of the Disappearing Ox: Seeing Through
Digital Images to an Analysis of Ancient Texts.” *CHI '10: Proceedings
of the 28th international conference on Human factors in computing
systems*. New York: ACM, 2010). 473-482.

[¶ 40](#r122 "Permalink")

[Integrating Digital Papyrology
(IDP)](http://idp.atlantides.org/trac/idp/wiki/) : Duke Databank of
Documentary Papyri, Heidelberger Gesamtverzeichnis der griechischen
Papyrusurkunden Ägyptens, and theAdvanced Papyrological Information
System.

This website provides an extensive overview of the IDP project and its
participating partners, the [Duke Databank of Documentary Papyri
(DDbDP)](http://www.papyri.info/ddbdp/), the [Heidelberger
Gesamtverzeichnis der griechischen Papyrusurkunden Ägyptens
(HGV)](http://aquila.papy.uni-heidelberg.de/gvzFM.html), and the
[Advanced Papyrological Information System
(APIS)](http://www.columbia.edu/cu/lweb/projects/digital/apis/index.html).
The IDP project is currently working to create a single research
interface to these three collections of metadata, full text and
papyrological information, a goal that has largely been realized through
the creation of the [Papryological Navigator
(PN)](http://www.papyri.info) (http://www.papyri.info), a website where
users can search across these three resources as well as find links to
the [Trismegistos Texts papyrological
database](http://www.trismegistos.org/). Another key component of the
IDP work is the development of the “Son of Suda Online” (SoSOL)
collaborative editing environment for developing digital editions of
papyri. When the IDP project is “finished” both the HGV and DDbDP plan
to release archival copies of their XML data using CC licenses. [full
citation ±] Duke Databank of Documentary Papyri, Heidelberger
Gesamtverzeichnis der griechischen Papyrusurkunden Ägyptens, and
theAdvanced Papyrological Information System. *Integrating Digital
Papyrology (IDP).*

[¶ 41](#r123 "Permalink")

[Integrating Digital Papyrology](http://hdl.handle.net/2451/29592) :
Roger Bagnall.

In this article, Roger Bagnall explains the larger goals of the IDP
project and how it has changed over the last 20 years. He notes that two
major shifts have occurred simultaneously, one towards openness and one
towards dynamism. Rather than conceptualizing the IDP as a static
project-based and centrally controlled “digital-silo”, they view it as a
dynamic community-maintained resource, where both data and participation
will be open to all scholars who wish to participate. To promote
openness, the IDP plans to expose both their data and the code used to
create their system. All data in the IDP is encoded using the
[EpiDoc](http://epidoc.sourceforge.net/) standard, which although
initially created for the encoding of inscriptions is now being used for
papyri and coins as well. Bagnall also lists some of the solutions
developed by the IDP to not only promote openness but also to encourage
scholarly contribution (e.g. the SoSOL editing environment) through
assuring proper vetting, credit and maintenance of data. Nonetheless, he
notes that many scholars are still worried about the visibility of their
work disappearing within a larger system. While acknowledging the
legitimacy of scholarly and digital partner concerns in terms of
branding and proper attribution (due to the ever present issues of
funding, credit and tenure), Bagnall also concludes that creating closed
collections is not a viable solution to these concerns. Another major
concern of many potential contributing scholars is quality control, and
Bagnall points out that the editorial structure of the IDP in some ways
offers stronger quality control measures in that changes can be made
online far more quickly than in print, and there are often far more
editors involved in online projects and available to detect errors than
there are for printed volumes. One other useful insight for data
curation Bagnall offers is that disciplines within classics need to
become far less concerned with preserving individual projects and
instead seek larger sustainability in the form of “sharing in an
organizational and technological infrastructure maintained to serve a
much wider range of resources for the ancient world (and perhaps not
necessarily limited to antiquity, either).” [full citation ±] Roger
Bagnall. “Integrating Digital Papyrology.” *Online Humanities
Scholarship: The Shape of Things to Come*, 2010.

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

[¶ 42](#r124 "Permalink")

[§ 4](#digital_repositories)

[Digital Repositories](#digital_repositories)

-   [](#) Add section comment

While many VREs and research portals listed above also include some
basic data preservation functions, most have likely not been designed
with the long-term curation of the digital research data that has been
created within them in mind. To address issues of longer term
sustainability and curation of both digitally created research data and
digitized copies of analog data, digital repositories have been
developed for a number of disciplines within the field of classics, with
the largest number by far within the discipline of archaeology.

[[back to top]](#top)

[¶ 43](#p13 "Permalink")

-   [](#) Add paragraph comment

[Primary Sources and Research Data](#research_data)

-   [](#) Add section comment

Much research within the classical disciplines as well as within the
humanities involves the use of primary sources and data, from
manuscripts and early printed editions of classical texts, to ancient
inscriptions, scraps of papyri, excavated artifacts, ancient coins,
images of classical art objects (as well as the analog objects
themselves), and virtual reconstructions, among many other types of
sources. Although research in the humanities is often not considered to
produce much in the way of “research data,” increasingly digital
research across many classics disciplines (as well as “traditional”
research in many fields such as archaeology) in fact has produced a
wealth of data that now needs active curation. In addition to curating
already existing legacy and born digital data, curators will also need
to explore new ways to encourage researchers to contribute the data that
they are actively creating as well.

[[back to top]](#top)

[¶ 44](#p14 "Permalink")

-   [](#) Add paragraph comment

[Resources: Archaeology research data](#archaeology2) Collapse
annotations

[Archaeology Data Service (ADS)](http://ads.ahds.ac.uk/) : University of
York.

The Archaeology Data Service, or ADS, is based at the University of York
in the United Kingdom. The ADS provides digital archiving services for
projects within the UK, a public searchable catalog of archived projects
and their data, and provides access to a number of best practices
standards and documents in terms of digitization of materials, database
management, and digital preservation. [full citation ±] University of
York. *Archaeology Data Service (ADS).*

[¶ 45](#r125 "Permalink")

[Past, Present and Future: XML, Archaeology and Digital
Preservation](http://www.csanet.org/newsletter/winter05/nlw0502.html) :
W. Kilbride.

Kilbride reviews the insights gained during the first 10 years of the
existence of the ADS, and urges creators of archaeological data to
consider how their data might be used in the future and also promotes
active curation of archaeological data. [full citation ±] W. Kilbride.
“Past, Present and Future: XML, Archaeology and Digital Preservation.”
*CSA Newsletter* XVII 3 (2005).

[¶ 46](#r126 "Permalink")

[Archiving Archaeology: Introducing the Guides to Good
Practice](http://www.ifs.tuwien.ac.at/dp/ipres2010/papers/mitcham-54.pdf)
: J. Mitcham, K. Niven, and J. Richards.

This article details current work between the ADS and Digital Antiquity
to define best practices in terms of the digital preservation of
archaeological data that will also help to increase is potential re-use.
[full citation ±] J. Mitcham, K. Niven, and J. Richards. “Archiving
Archaeology: Introducing the Guides to Good Practice.” *Proceedings of
the 7th International Conference on Preservation of Digital Objects.
iPRES 2010. Vienna, Austria, September 19-24, 2010*. Ed. A. Rauber, M.
Kaiser, R. Guenther, and P. Constantopoulos, 2010).

[¶ 47](#r127 "Permalink")

[Digital Antiquity](http://www.digitalantiquity.org/) : Digital
Antiquity.

Digital Antiquity is a “collaborative organization devoted to enhancing
preservation and access to digital records of archaeological
investigation.” Through funding from both the Mellon Foundation and the
National Science Foundation (NSF), they have built a digital repository
named [tDAR (the Digital Archaeological Record](http://www.tdar.org/),
which provides preservation, access and discovery for archaeological
data and documents that are deposited by registered projects. All
information resources that are deposited into tDAR include a variety of
metadata (technical, descriptive, administrative, etc.) that is provided
by the user. While general users can access the tDAR archive through the
website, the uploading of resources requires registration and approval.
The tDAR repository also requires detailed authorship information for
all contributed resources and allows varying levels of access control
and embargoing of data. In order to encourage proper citation and
credit, the developers of tDAR also plan to ensure that individual
repository data sets and documents will have persistent URLs and make
sure that all content is automatically versioned whenever changes are
made. The tDAR repository supports the uploading of a variety of data
formats, and while all original formats are preserved at the bit level,
tDAR also stores all resources in a preservation format to support
long-term migration of all content. [full citation ±] Digital Antiquity.
*Digital Antiquity.*

[¶ 48](#r128 "Permalink")

[Digital Antiquity and the Digital Archaeological Record (tDAR):
Broadening Access and Ensuring Long-Term Preservation for Digital
Archaeological Data](http://csanet.org/newsletter/fall10/nlf1002.html) :
F.P. McManamon, K.W. Kintigh, and A. Brin.

This article outlines the two major goals of Digital Antiquity and tDAR:
to provide greater access to archaeological data and to provide a
preservation repository for that data. It also provides extensive
technical details on the tDAR repository architecture, and precise
information on data migration and preservation procedures. [full
citation ±] F.P. McManamon, K.W. Kintigh, and A. Brin. “Digital
Antiquity and the Digital Archaeological Record (tDAR): Broadening
Access and Ensuring Long-Term Preservation for Digital Archaeological
Data.” *CSA Newsletter* XXIII 2 (2010).

[¶ 49](#r129 "Permalink")

[Digital Antiquity: Transforming Archaeological Data into
Knowledge](http://www.tdar.org/images/SAA-McM-Kintigh.pdf) : F.P.
McManamon and K.W. Kintigh.

As with the above article, this report provides an overview of tDAR, but
also documents the development and long-term sustainability plans of the
Digital Antiquity organization. It describes their plans to utilize a
data curation model, where archaeologists and other stakeholders will
pay fees for the deposit and maintenance of data, which will then be
provided freely over the Internet. They also noted that in order to
encourage more large-scale deposit of data that archaeological practice
would need to be transformed so that archiving of data and metadata
became a “standard part of all archaeological project workflows.” This
is indeed a great challenge for most repository and curation projects,
or how to make the practice of archiving a standard part of humanities
research practice. [full citation ±] F.P. McManamon and K.W. Kintigh.
“Digital Antiquity: Transforming Archaeological Data into Knowledge.”
*SAA Archaeological Record* (2010): 37-40.

[¶ 50](#r130 "Permalink")

[Online Cultural Heritage Research Environment
(OCHRE)](http://ochre.lib.uchicago.edu/index.htm) : University of
Chicago.

OCHRE is an Internet database system that has been designed to manage
archaeological and cultural heritage research information. The project
is based at the University of Chicago and uses ArchaeoML, an XML schema
for archaeological information as the basis for its XML database. OCHRE
also implements a core [ontology](../../glossary.html#ontology) for
cultural heritage information and uses this as a global schema with
which to map the schemas of various projects in order to facilitate data
integration. At this website, users can access a number of
archaeological research projects that make use of OCHRE. The website
also offers a [useful
comparison](http://ochre.lib.uchicago.edu/index_files/Page794.htm) of
how their data integration system compares to the use of the CIDOC-CRM
and tDAR of Digital Antiquity. [full citation ±] University of Chicago.
*Online Cultural Heritage Research Environment (OCHRE).*

[¶ 51](#r131 "Permalink")

[OpenContext](http://opencontext.org/) : Alexandria Archive Institute.

OpenContext has been created by the Alexandria Archive Institute as an
“open access data publication service for archaeology,” with a focus on
data sharing between archaeologists, open access publication and making
data dissemination easier within the discipline of archaeology. Its
basic architecture is a flexible database that allows researchers to
publish structured data, textual documents, and other media on the web
using only open source technologies, and it utilizes a subset of
ArchaeoML for its data structure. The use of this ArchaeoML subset
allows for integrated searching across diverse archaeological data sets.
OpenContext contributors retain copyright to their content and are also
encouraged to publish their data in other locations as well. In addition
to encourage proper citation and reuse of data, all collections that are
entered are time stamped, authorship of all data is clearly attributed,
and permanent citable URLs are provided for all data items. [full
citation ±] Alexandria Archive Institute. *OpenContext.*

[¶ 52](#r132 "Permalink")

[An Open Context for Near Eastern
Archaeology](http://alexandriaarchive.org/wp-content/uploads/2008/KansaKansaSchultz_NEADec07.pdf)
: S.W. Kansa, E.C. Kansa, and J.M. Schultz.

A comparison of approaches to creating structured data in the form of
descriptive markup and databases using examples from Digital Humanities
research. [full citation ±] S.W. Kansa, E.C. Kansa, and J.M. Schultz.
“An Open Context for Near Eastern Archaeology.” *Near Eastern
Archaeology* 70.4 (2007): 188-194.

[¶ 53](#r133 "Permalink")

[Saving and Archiving Virtual Environments
(SAVE)](http://vwhl.clas.virginia.edu/save.html) : Virtual World
Heritage Library.

This project website explains the plans and future architecture for
SAVE, a project of the [Virtual World Heritage
Library](http://vwhl.clas.virginia.edu/) at the University of Virginia.
SAVE will be the “world’s first on-line, peer-reviewed journal in which
scholars can publish 3D digital models of the world’s cultural heritage
(CH) sites and monuments.” The SAVE project plans to develop a secure
digital repository that will allow scholars to archive or “publish”
their models, provide peer review mechanisms for these models, as well
as to develop a system for updating models and preserving them. [full
citation ±] Virtual World Heritage Library. *Saving and Archiving
Virtual Environments (SAVE).*

[¶ 54](#r134 "Permalink")

[Research Challenges for Digital Archives of 3D Cultural Heritage
Models](http://dl.acm.org/citation.cfm?doid=1658346.1658347) : D.
Koller, B. Frischer, and G. Humphreys.

A full discussion of the technical, disciplinary and sustainability
challenges of developing a digital archive for 3D models is included in
this article, with an overview of research to date. Koller et al.
recommend that such archives only accession “3D models that are clearly
identified with authors with appropriate professional qualifications,
and whose underlying design documents and metadata are published along
with the model.” [full citation ±] D. Koller, B. Frischer, and G.
Humphreys. “Research Challenges for Digital Archives of 3D Cultural
Heritage Models.” *Journal of Computing and Cultural Heritage* 2.3
(2009): 1-17.

[¶ 55](#r135 "Permalink")

[CyArk](http://archive.cyark.org/) : CyArk.

CyArk is a non-profit organization with a stated mission to digitally
preserve “cultural heritage sites through collecting, archiving and
providing open access to data created by laser scanning, digital
modeling, and other state-of-the-art technologies.” The website includes
information about the organization as well as online access through a
map interface to those projects that are virtually archived at the
website (e.g. virtual models and digital photographs of [Ancient
Thebes](http://archive.cyark.org/ancient-thebes-intro). [full citation
±] CyArk. *CyArk.*

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

[¶ 56](#r136 "Permalink")

[Resources: Epigraphy research data](#epigraphy) Collapse annotations

[Epigraphy in
2017](http://www.digitalhumanities.org/dhq/vol/3/1/000030.html) : H.
Cayless, C. Roueché, T. Elliott, and G. Bodard.

Cayless et al. offer an overview of the state-of-the-art in digital
epigraphy and also define requirements for effective digital corpora of
inscriptions. They heavily promote the use of EpiDoc, an XML standard
for encoding inscriptions, since it serves not just as a data
interchange format but also supports the creation of sophisticated
digital editions and corpora of inscriptions that are “fully queryable
and manipulable.” After highlighting a number of issues with current
inscription databases, they conclude with a number of requirements for
digital repositories of inscriptions, including the ability to export
part or all of the data in standard formats (e.g. EpiDoc) and the need
for persistent identifiers (e.g. [DOIs](../../glossary.html#doi)) at the
level of individual digital objects so that inscriptions can be cited
independent of their physical location. They also suggest that EpiDoc
could be potentially used as a way of storing, preserving and
distributing epigraphic data in a digital format. [full citation ±] H.
Cayless, C. Roueché, T. Elliott, and G. Bodard. “Epigraphy in 2017.”
*Digital Humanities Quarterly* 3.1 (2009).

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

[¶ 57](#r137 "Permalink")

[Resources: Manuscript Studies research data](#manuscript_studies)
Collapse annotations

[Digital Scriptorium](http://bancroft.berkeley.edu/digitalscriptorium/)
: University of California Berkeley Library.

At this website, users can access an online image database of
manuscripts from both the Middle Ages and the Renaissance from over 30
libraries. It includes records for over 5300 manuscripts and over 24,000
images. Each individual manuscript record contains an extensive
bibliographic and physical description with links to individual page
images and to the fully digitized manuscript at its home institution
(when available). [full citation ±] University of California Berkeley
Library. *Digital Scriptorium.*

[¶ 58](#r138 "Permalink")

[Digital Scriptorium: Ten Years Young, and Working on
Survival](http://www.storicamente.org/02_tecnostoria/filologia_digitale/dutschke.html#_ftn1)
: C.W. Dutschke.

This piece by Consuelo Dutschke includes a brief history of the Digital
Scriptorium (DS, first established in 1997) and the plans it has made
for long-term sustainability. The DS has established standards for
bibliographic data collection and image capture of manuscripts that are
regularly updated, and this level of documentation has provided a level
of technical sustainability. Other important factors in both technical
and financial sustainability that Dutschke lists are extensive
documentation, technical transparency, simplicity, and sensible file
naming. Although the DS currently uses Microsoft Access for data entry
and collection, every DS partner is required on a regular basis to
export their collection specific information into XML and forward that
XML to the central DS organization. As XML is both non-proprietary and
“platform independent” they have chosen to use it for “data transport,
long-term storage and manipulation.” Another key component of
sustainability that Dutschke identifies is “political” or whether DS
partners are committed to sustaining it in the long-term, and if the
larger user community values the project. She urges digital projects to
consider both their current and future user demands, as “the will to
sustainability lies not only within the project and its
creators/partners; it also lies with its users.” [full citation ±] C.W.
Dutschke. “Digital Scriptorium: Ten Years Young, and Working on
Survival.” *Storicamente* (2008): 4.

[¶ 59](#r139 "Permalink")

[Manuscriptorium](http://beta.manuscriptorium.com/) : Manuscriptorium
Virtual Library.

The Manuscriptorium Virtual Library provides access to more than 5
million digital manuscripts images from dozens of libraries across
Europe as well as a number from Asia. According to the project website,
their goal is to provide a [VRE](../../glossary.html#vre) that supports
“access to all existing digital documents in the sphere of historic book
resources (manuscripts, incunabula, early printed books, maps, charters
and other types of documents).” Each manuscript description includes
full bibliographic information, physical description and links to
partial or full digital facsimiles as available. [full citation ±]
Manuscriptorium Virtual Library. *Manuscriptorium.*

[¶ 60](#r140 "Permalink")

[Creation of an International Digital Library of Manuscripts: Seamless
Access to Data from Heterogeneous
Resources](http://conferences.aepic.it/index.php/elpub/elpub2009/paper/view/71/30)
: J. Mitcham, K. Niven, and J. Richards.

This recent article by Knoll et al. supplies a brief history of the
Manuscriptorium and its technical design to ensure long-term
sustainability. Institutions can make their data available through
Manuscriptorium by either making their online collections OAI
harvestable or by creating compliant data and making their collections
available online through the Manuscriptorium Digital Library (a solution
chosen by many smaller libraries). In order to provide more scalable and
robust solutions for long-term data storage and exchange of manuscript
information, the Manuscriptorium project worked with the Oxford
University Computer Services to develop a TEI P5 compliant DTD that
would accommodate manuscript descriptions of varying granularity (e.g. a
MARC record vs. a TEI description). All existing documents in the
digital library were migrated to this DTD and both harvested and
uploaded documents must conform to it as well. Another data integration
issue they faced was that many participating libraries provided access
to manuscript images through PDFs or DjVu rather than through XML based
structural mapping. Since this level of access does not support
manipulation of manuscript pages as individual digital objects, all
participating libraries thus must convert such files into individual
JPEG images for each page. In order to assist libraries in creating
compliant data, the Manuscriptorium Project has created two tools:
M-Tool for metadata entry either to create new Manuscriptorium records
or edit records for import and M-Can, for uploading and evaluating
records. [full citation ±] J. Mitcham, K. Niven, and J. Richards.
“Creation of an International Digital Library of Manuscripts: Seamless
Access to Data from Heterogeneous Resources (ENRICH Project).” *ELPUB
2009: 13th International Conference on Electronic Publishing: Rethinking
Electronic Publishing: Innovation in Communication Paradigms and
Technologies*, 2009). 335-347.

[¶ 61](#r141 "Permalink")

[Digital Ecosystems of eHumanities Resources and
Services](http://dx.doi.org/10.1109/DEST.2008.4635178) : C. Ludwig and
M.W. Küster.

This article by Ludwig and Küster explains the “virtual library” design
of TextGrid, where the ultimate repository will use the Globus toolkit
grid to provide seamless searching over federated archives, allowing
data to remain distributed and also supporting the addition of new
organizations and their data. One major point they highlight is the
difficulty of creating digital content that will need to be both used
and preserved for far longer than any system can be designed to provide
access to it. They note that in philology and eHumanities projects in
general, many resources that are created (e.g. historical dictionaries
of word usage) can be in continuous development for decades. Further
research into both content stability and portability are thus required
according to Ludwig and Küster. Content that is created with either
TextGridLab or imported from external data partners is saved unchanged
to the TextGrid repository where metadata is extracted and normalized
and then stored in central metadata storage. A full text index is
extracted from the raw data repository and updated regularly. [full
citation ±] C. Ludwig and M.W. Küster. “Digital Ecosystems of
eHumanities Resources and Services.” *Digital Ecosystems and
Technologies, 2008. DEST 2008. 2nd IEEE International Conference*,
2008). 476-481.

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

[¶ 62](#r142 "Permalink")

[Secondary Scholarship](#secondary_scholarship)

-   [](#) Add section comment

As with most humanities disciplines, effective data curation strategies
for classics will require preserving both the data used in creating
scholarship as well as the final products of that scholarship, including
publications such as journal articles and monographs. The preservation
and curation of formally published scholarship in digital repositories
(either institutionally based or disciplinary) is perhaps the most
well-established and supported form of digital preservation, but
classics has lagged somewhat behind in this area.

[[back to top]](#top)

[¶ 63](#p36 "Permalink")

-   [](#) Add paragraph comment

[Resources: Working papers](#working_papers) Collapse annotations

[Princeton-Stanford Working Papers in Classics
(PSWPC)](http://www.princeton.edu/~pswpc/index.html) : Princeton
Universityand Stanford University.

The PSWPC is an open access working papers repository (vs. the deposit
of formal pre-prints or postprints) and has been created as one step
towards promoting both open access to scholarship in the field of
classics as well as to create new opportunities for collaboration
between interested scholars. This website provides access to the PSWPC
repository that was created in collaboration between the Classics
departments of Stanford and Princeton Universities, and the papers can
be browsed by author, date, department or subject. Two recent articles
listed below have also explored the greater implications of the PSWPC in
terms of classics, open access, scholarly publishing and long term
archiving of research papers. [full citation ±] Princeton Universityand
Stanford University. *Princeton-Stanford Working Papers in Classics
(PSWPC).*

[¶ 64](#r143 "Permalink")

[Toward Open Access in Ancient Studies: The Princeton-Stanford Working
Papers in
Classics](http://www.princeton.edu/~pswpc/pdfs/ober/020702.pdf) : J.
Ober, W. Scheidel, B.D. Shaw, and D. Sanclemente.

This article explains the development of the PSWPC and presents a list
of issues and solutions for supporting greater open access to classical
scholarship. [full citation ±] J. Ober, W. Scheidel, B.D. Shaw, and D.
Sanclemente. “Toward Open Access in Ancient Studies: The
Princeton-Stanford Working Papers in Classics.” *Hesperia* 76.1 (2007):
229-242.

[¶ 65](#r144 "Permalink")

[Working Papers, Open Access and Cyber-Infrastructure in Classical
Studies](http://ses.library.usyd.edu.au/handle/2123/2226) : D.
Pritchard.

In this article, Pritchard provides a brief review of the PSWPC,
outlines reasons for its success, and considers the future of open
access publishing within classical studies. [full citation ±] D.
Pritchard. “Working Papers, Open Access and Cyber-Infrastructure in
Classical Studies.” *Literary & Linguistic Computing* 23.2 (2008):
149-162.

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

[¶ 66](#r145 "Permalink")

[§ 7](#federated_collections_and_research_databases)

[Federated Collections and Research
Databases](#federated_collections_and_research_databases)

-   [](#) Add section comment

One long-term challenge for data curation in classics and indeed across
the humanities is the large number of individual digital projects that
have idiosyncratic or “fuzzy” data, and even when complementary projects
have data regarding the same object (e.g. an image of a classical vase
or a Latin inscription) it may have been described using very different
metadata vocabularies or ontologies. The need to allow individual
projects to maintain their autonomy while also providing a long-term
infrastructure that can provide greater semantic interoperability and
integration, more sophisticated levels of access, and ideally long term
curation of federated data sets is currently being explored in greater
detail by a number of projects.

[[back to top]](#top)

[¶ 67](#p15 "Permalink")

-   [](#) Add paragraph comment

[Resources: Federated Collections and Research
Databases](#federated_collections_and_research_databases_resources)
Collapse annotations

[Classical Art Research Online Services
(CLAROS)](http://www.clarosnet.org) : Oxford University.

The CLAROS project, led by Oxford University and its e-Research center,
is creating a “data web” that is integrating the collections of various
partners with classical art and archaeological databases. The project is
using the CIDOC-CRM (http://www.cidoc-crm.org/) cultural heritage
ontology and various Semantic Web technologies (RDF, SPARQL) to
integrate these different collections. CLAROS ultimately hopes to create
an architecture that will allow them to integrate additional classical
art collections by mapping them to their core ontology, while also
allowing individual projects to maintain their own databases and
independence. Access to the integrated collections will be made
available through the project website sometime in 2011. [full citation
±] Oxford University. *Classical Art Research Online Services (CLAROS).*

[¶ 68](#r146 "Permalink")

[CLAROS - Bringing Classical Art to a Global
Public](http://www.clarosnet.org/PID1023719.pdf) : Kurtz, D., Parker,
G., Shotton, D., Klyne, G., Schroff, F., Zisserman, A., and Wilks, Y.

This article describes the data integration process for the CLAROS
project as well as innovative research into a vase recognition
algorithm. [full citation ±] Kurtz, D., Parker, G., Shotton, D., Klyne,
G., Schroff, F., Zisserman, A., and Wilks, Y. “CLAROS - Bringing
Classical Art to a Global Public.” 2009. In *Fifth IEEE International
Conference on e-Science '09*, pages 20-27.

[¶ 69](#r147 "Permalink")

[Cuneiform Digital Library Initiative (CDLI)](http://cdli.ucla.edu/) :
Max Planck Institute for the History of Science in Germany and the
University of California Los Angeles (UCLA)

The CDLI is a joint project of the Max Planck Institute for the History
of Science in Germany and the University of California Los Angeles
(UCLA). This extensive digital library represents the efforts of an
“international group of Assyriologists, museum curators and historians
of science” to provide digital access to both images (digital images,
hand sketches, etc.) and texts of Cuneiform tablets from collections
scattered around the world. The CDLI research group estimates that there
are about 500,000 documents in both private and public collections
across the world, and the current digital library provides advanced
access to more than 225,000 objects from dozens of collections. One
important feature of this website is extensive documentation is provided
regarding how data is entered, how the Cuneiform texts are
transliterated, and how the online catalog was created, all important
information for the long term preservation of the digital contents.
[full citation ±] Max Planck Institute for the History of Science in
Germany and the University of California Los Angeles (UCLA) uneiform
Digital Library Initiative

[¶ 70](#r148 "Permalink")

[Supporting Productive Queries for Research
(SPQR)](http://spqr.cerch.kcl.ac.uk/) : King's College London,
University of Edinburgh, Humboldt University Berlin.

The recently launched SPQR project, is seeking to make use of a “linked
data” approach, Semantic Web technologies, and the Europeana Data Model
(the recently proposed top level ontology for structuring the data
delivered to the Europeana digital portal
([http://www.europeana.eu/portal/](http://www.europeana.eu/portal/)) by
contributing cultural heritage institutions) to provide sophisticated
access to an integrated dataset of multiple digital classics resources.
This project is driven by the research outcomes of an earlier project
entitled LaQuAT (Linking and Querying of Ancient Texts) that sought to
expose digital classics resources (typically stored in XML or relational
databases) onto the grid using OGSA-DAI (an open source distributed data
management software) with the ultimate purpose of providing integrated
access to different databases (rather than integrating the 3 databases
into a new database). Since each of the three databases had a different
format, this project illustrated the challenges of linking up diverse
data sets in the humanities. Similar to the CLAROS project, one insight
of the LaQuAT project is that any larger infrastructure for digital
humanities should consider providing virtual data centers that can
integrate access to various resources while allowing individual
resources to maintain unique formats. The current SPQR website provides
technical documentation on their proposed architecture as well as
progress and project updates. [full citation ±] King's College London,
University of Edinburgh, Humboldt University Berlin. Supporting
Productive Queries for Research

[¶ 71](#r149 "Permalink")

[Building Bridges between Islands of Data - an Investigation into
Distributed Data Management in the
Humanities](http://dx.doi.org/10.1109/e-Science.2009.13) : Jackson, M.,
Antonioletti, M., Hume, A., Blanke, T., Bodard, G., Hedges, M., and
Rajbhandari, S.

This article describes in detail the technical solutions explored by the
LaQuAT project to integrate three different digital classics resources,
the problems it encountered, and future research directions. [full
citation ±] Jackson, M., Antonioletti, M., Hume, A., Blanke, T., Bodard,
G., Hedges, M., and Rajbhandari, S. “Building Bridges between Islands of
Data - an Investigation into Distributed Data Management in the
Humanities.” (2009) In *e-Science '09: Fifth IEEE International
Conference on e-Science, 2009*, pages 33-39.

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

[¶ 72](#r150 "Permalink")

[§ 8](#standards)

[Standards](#standards)

-   [](#) Add section comment

The existence of standards in well-understood formats can be one key
component for the long-term curation of digital data, and various
standards have been developed for different classical disciplines and
the larger digital humanities including the Text Encoding Initiative
(TEI), EpiDoc, and ArchaeoML. TEI in particular has proved particularly
important and adaptable across different classical disciplines, and is
often used as the core standard to promote interoperability. Standards
proved to be important not just for the integration of data from
different projects, but also at times served as a tool that could be
used to support the reuse of data created for an earlier project by
later research.

[[back to top]](#top)

[¶ 73](#p17 "Permalink")

-   [](#) Add paragraph comment

[Resources: Ancient Near Eastern Studies
standards](#ancient_near_eastern_studies_standards) Collapse annotations

[iClay: Digitizing
Cuneiform.](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.73.87&rep=rep1&type=pdf)
: Cohen, J., Duncan, D., Snyder, D., Cooper, J., Kumar, S., Hahn, D.,
Chen, Y., Purnomo, B., and Graettinger, J.

This article describes the algorithms developed by the Digital Hammurabi
project for Cuneiform tablet reconstruction and visualization and the
creation of an encoding standard for Cuneiform by the “Initiative for
Cuneiform
Encoding”-(ICE-[http://www.jhu.edu/digitalhammurabi/ice/ice.html](http://www.jhu.edu/digitalhammurabi/ice/ice.html)).
[full citation ±] Cohen, J., Duncan, D., Snyder, D., Cooper, J., Kumar,
S., Hahn, D., Chen, Y., Purnomo, B., and Graettinger, J. “iClay:
Digitizing Cuneiform.” (2004). “iClay: Digitizing Cuneiform.” In
*Proceedings of the Fifth International Symposium on Virtual Reality,
Archaeology, and Cultural Heritage*, pages 135-143.

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

[¶ 74](#r151 "Permalink")

[Resources: Archaeology standards](#archaeology_standards) Collapse
annotations

[Archaeological Data Models and Web Publication using
XML.](http://dx.doi.org/10.1023/A:1002471112790) : Schloen, J.

This article provides a through overview of the ArchaeoML standard,
which was first proposed as a “standardized data model” based on XML to
support both digital publication and data analysis for archaeological
data on the web. ArchaeoML has been designed as a “hierarchical,
item-based data model” to facilitate the description and integration of
archaeological data, which can be described using very different
standards in widely different formats. This standard has been utilized
at least in part by both the OCHRE and the OpenContext projects. [full
citation ±] Schloen, J. “Archaeological Data Models and Web Publication
using XML” (2001). *Computers and the Humanities*, 35(2): 123-152.

[¶ 75](#r152 "Permalink")

[The Publication of Archaeological Excavation Reports Using
XML.](http://dx.doi.org/10.1093/llc/18.1.63) : Meckseper, C. and
Warwick, C.

This article describes the development of a TEI encoding scheme for
archaeological reports, the need to distinguish between data and
scholarly interpretations of that data, and the potential of XML as a
long-term preservation format for archaeological data and publications.
[full citation ±] Meckseper, C. and Warwick, C. “The Publication of
Archaeological Excavation Reports Using XML” (2003). *Literary &
Linguistic Computing*, 18(1): 63-75.

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

[¶ 76](#r153 "Permalink")

[Resources: Epigraphy standards](#epigraphy_standards) Collapse
annotations

[EpiDoc](http://epidoc.sourceforge.net/) : Elliott, T.

EpiDoc is a standard for encoding inscriptions in XML that is relatively
mature and has been used by a large number of digital epigraphy
projects, such as the Inscriptions of Aphrodisias (see Model Digital
Resources, below). The EpiDoc standard was first developed by Tom
Elliott in the early 1990s, and has been in active development since
this time. At this website, a full explanation of the standard can be
found, an introduction for epigraphers, a number of resources and tools
for working with EpiDoc, as well as sample EpiDoc files. [full citation
±] Elliott, T. Epidoc

[¶ 77](#r154 "Permalink")

[HypereiDoc – an XML Based Framework Supporting Cooperative Text
Editions](ttp://dx.doi.org/10.1007/978-3-540-85713-6_3) : Bauer, P.,
Hernáth, Z., Horváth, Z., Mayer, G., Parragi, Z., Porkoláb, Z., and
Sztupák, Z.

This article offers a critique of the EpiDoc standard, particularly in
terms of the development of philological editions, and proposes a
modified encoding approach called Hypereidoc
([http://hypereidoc.elte.hu/](http://hypereidoc.elte.hu/)) an “XML based
framework supporting distributed, multi-layered, version-controlled
processing of epigraphical, papyrological or similar texts in a modern
critical edition.” At the project website listed above, scholars can
download both the Hypereidoc XML schema and an XML editor developed to
work with it. [full citation ±] Bauer, P., Hernáth, Z., Horváth, Z.,
Mayer, G., Parragi, Z., Porkoláb, Z., and Sztupák, Z. “HypereiDoc – an
XML Based Framework Supporting Cooperative Text Editions” (2008).
*Advances in Databases and Information Systems, Lecture Notes in
Computer Science*, chapter 3, pages 14-29.

[¶ 78](#r155 "Permalink")

[Sharing Epigraphic Information as Linked
Data](http://dx.doi.org/10.1007/978-3-642-16552-8_21) : Álvarez, F.-L.,
García-Barriocanal, E., and Gómez-Pantoja, J.-L.

The research presented by Alvarez et al. in this article proposes the
creation of an ontological schema based on EpiDoc, noting that the use
of EpiDoc alone would not support the creation of “open linked data”
since it provides no way to encode computational semantics and relies on
“structured metadata with text fields.” They conclude that if epigraphic
data could be encoded with computational semantics it could then be
reused by various Semantic Web applications. Alvarez et al. consequently
map the EpiDoc schema to an ontological representation in OWL and
provide some sample inscriptions. [full citation ±] Álvarez, F.-L.,
García-Barriocanal, E., and Gómez-Pantoja, J.-L. “Sharing Epigraphic
Information as Linked Data” (2010). *Metadata and Semantic Research*,
volume 108 of *Communications in Computer and Information Science,*
pages 222-234. Springer Berlin Heidelberg.

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

[¶ 79](#r156 "Permalink")

[Resources: Manuscript Studies standards](#manuscript_studies_standards)
Collapse annotations

[Integrating Images and Text with Common Data and Metadata Standards in
the Archimedes
Palimpsest](http://www.mith2.umd.edu/dh09/wp-content/uploads/dh09_conferencepreceedings_final.pdf)
: Emery, D. and Toth, M. B.

Emery and Toth describe the creation of the Archimedes Digital
Palimpsest, which released over 1 terabyte of integrated image and
transcription data. The authors explain that highly standardized
metadata is required for image processing and enhancement, management of
image transcription, and linking images with transcriptions. Another key
insight they offer is that as many different types of scholars have
worked with the palimpsest (philologists, historians of science, etc.),
they needed to be able to capture data from a range of scholars in a
standard digital format. This thus led them to develop a “Transcription
Integration Plan” that made use of Unicode, Dublin Core, TEI, and the
Federal Geographic Data Committee Content Standard for Digital
Geospatial Metadata. Emery and Toth argue that common standards were
chosen and the integration of metadata and data were emphasized in order
to ensure that the digital archive of the Archimedes Digital Palimpsest
data that was created would be useful not just in the short term but
also for future scholars and libraries. The data set that was finally
released was also modeled on the principles of the Open Archival
Information System (OAIS), so all images include relevant metadata in
their headers and each image file or folio directory serves as a
self-contained preservation unit that includes all the images of a given
folio side, XMP metadata files, checksum data and the spatially mapped
TEI-XML transcriptions. [full citation ±] Emery, D. and Toth, M. B.
“Integrating Images and Text with Common Data and Metadata Standards in
the Archimedes Palimpsest” (2009). *Digital Humanities Abstracts 2009*,
pages 281-283.

[¶ 80](#r157 "Permalink")

[Towards a Scholarly Editing System for the Next
Decades](%20http://dx.doi.org/10.1007/978-3-642-00155-0_18) : Robinson,
P.

Robinson’s article outlines requirements for a scholarly editing system
in a digital world. He argues against “Grand Single Solutions” or
massive single purpose infrastructure and instead encourages the
creation of more projects like Interdiction and the Virtual Manuscript
Room that have focused on creating more resources online (e.g. digital
manuscript images) and more importantly are seeking to link disparate
parts (images, tools and transcriptions) that are already online
together. He also proposes that basic descriptive standards are required
as well as standard naming conventions to support better linking. [full
citation ±] Robinson, P. “Towards a Scholarly Editing System for the
Next Decades” (2009). In Huet, G., Kulkarni, A., and Scharf, P.,
editors, *Sanskrit Computational Linguistics*, volume 5402, chapter 18,
pages 346-357. Springer Berlin Heidelberg, Berlin, Heidelberg.

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

[¶ 81](#r158 "Permalink")

[Resources: Papyrology](#papyrology_standards) Collapse annotations

[Textual Analysis Using XML: Understanding Ancient Textual
Corpora](http://esad.classics.ox.ac.uk/index.php?option=com_docman&task=doc_download&gid=30&Itemid=78)
: Roued, H.

This article examines how the TEI-XML encoded editions created for the
Vindolanda Tablets Online
([http://vindolanda.csad.ox.ac.uk/](http://vindolanda.csad.ox.ac.uk/))
project might be repurposed and reused by other digital classics
projects, in particular as “a reusable word and character corpus for a
networked e-Science system and other e-Science applications.” The
TEI-XML corpus of Vindolanda has been used to create a knowledge based
of Latin words to support an Interpretation Support System (ISS) being
developed to assist scholars working with similar ancient texts. Roued
observes that the use of EpiDoc by Vindolanda had allowed them to encode
different scholarly opinions on the same text within the same XML file
since content markup (EpiDoc XML) and presentation (a variety of XSLT
sheets) have been clearly separated. The “beta” knowledge base that has
been developed is being made available as a web service. [full citation
±] Roued, H. “Textual Analysis Using XML: Understanding Ancient Textual
Corpora” (2009). In 5th IEEE conference on e-Science 2009.

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

[¶ 82](#r159 "Permalink")

[Resources: Philology](#philology_standards) Collapse annotations

[No Claims for Universal Solutions - Possible Lessons from Current
e-Humanities Practices in Germany and the
UK](http://www.clarin.eu/system/files/ClaimsUniversal-eHum2008.pdf) :
Blanke, T., Aschenbrenner, A., Küster, M., and Ludwig, C.

This article provides an explanation of TextGrid’s data integration and
interoperability strategies. While TEI was used as the basic form of
markup, partner projects used TEI at varying levels of depth, so Blanke
et al. describe how TextGrid defined a minimum “abstraction level”
necessary or a “core” encoding approach to support a basic level of
interoperability. While projects were encouraged to continue encoding
their data to the level that was appropriate for their individual
research questions, to participate in TextGrid they must also register a
mapping from their “semantically deep data” to the “TextGrid-wide core
encoding” that was described as a “reasonably expressive” subset of TEI.
[full citation ±] Blanke, T., Aschenbrenner, A., Küster, M., and Ludwig,
C. “No Claims for Universal Solutions - Possible Lessons from Current
e-Humanities Practices in Germany and the UK” (2008). “In *E-SCIENCE
'08: Proceedings of the IEEE e-Humanities Workshop.*

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

[¶ 83](#r160 "Permalink")

[§ 9](#collaborative_tools)

[Collaborative and Communication Tools](#collaborative_tools)

-   [](#) Add section comment

While a great deal of research in the humanities is often conducted by
individual scholars, one prominent feature of much digital scholarship
is that it is often quite collaborative in nature, and requires
resources that support both collaboration and scholarly communication. A
number of important resources/projects exist within the digital classics
community that promote greater collaboration and communication among
interested scholars who hope to share their work, find new colleagues,
identify best practices, among many other possibilities.

[[back to top]](#top)

[¶ 84](#p16 "Permalink")

-   [](#) Add paragraph comment

[Resources: Collaborative and Communication
Tools](#collaborative_tools_resources) Collapse annotations

[Digital Classicist
Wiki](http://www.digitalclassicist.org/wip/index.html) :

The Digital Classicist Wiki has been created to serve as a central hub
to link together the diverse digital scholarship in the various areas of
classical studies. The wiki includes a directory of over 90 digital
classics projects, an extensive FAQ with over 45 articles that provide
information on best practices, standards and technical documentation on
various topics (e.g. Sanskrit, typing and display), as well as an
annotated list of tools. In order to join the wiki, one has to apply to
one of the contributing editors, but once a member, you can then use the
wiki to post information about projects, create resource guides or
communicate with scholars working in a similar area. This resource
provides one venue where data curators could actively engage with
digital classicists in terms of developing best practices to create
preserveable data or to learn about projects that might be in need of
digital archiving services. For further details on the development of
this wiki, see the recent article by one of the Wiki creators, Simon
Mahony, of King’s College London, described briefly below. [full
citation ±] Digital Classicist Wiki

[¶ 85](#r161 "Permalink")

[Research Communities and Open Collaboration: the Example of the Digital
Classicist Wiki](http://www.digitalmedievalist.org/journal/6/mahony/) :
Mahony, S.

This article provides an overview of the Digital Classicist Wiki and its
potential role in community development, scholarship, and teaching.
[full citation ±] Mahony, S. “Research Communities and Open
Collaboration: the Example of the Digital Classicist Wiki” (2011).
*Digital Medievalist,* 6.

[¶ 86](#r162 "Permalink")

[Interedition](http://www.interedition.eu/) :

The Interedition Project (2008 to 2012) is focused on building a
“supranational networked infrastructure for digital scholarly editing
and analysis” with one major goal being to promote greater
interoperability between tools and methodology. According to the project
website, as many scholars have already created useful tools and other
resources, they hope to support greater collaboration between scholars
and to encourage resource creators to focus on greater tool
interoperability and content openness. In order to promote this,
Interedition is holding a series of workshops with interested
researchers and by project end will release a “roadmap” for this
infrastructure
([http://w3.cost.esf.org/index.php?id=233&action\_number=IS0704](http://w3.cost.esf.org/index.php?id=233&action_number=IS0704)).
The website provides access to a project wiki that provides details
about past and future workshops as well as a list of workgroups and a
draft architecture. [full citation ±] Interedition

[¶ 87](#r163 "Permalink")

[Son of Suda Online and Digital Papyrology
(SoSOL)](http://www.stoa.org/archives/1263) : Sosin, Joshua.

The Integrating Digital Papyrology project makes use of an online
editing system named SoSOL that allows authorized participants to enter
texts into the DDbDP and metadata into the HGV or APIS. This
presentation given by Joshua Sosin and posted on the Stoa website
explains both the development and purpose of this system. The SoSOL
system allows users to create editions that will only become publicly
visible when they wish. Authorized participants may also contribute new
texts, corrections to previously entered texts, variant readings,
translations or metadata, but all suggestions have to be approved by the
editorial board. An important component of this editing system is that
it records every step of this process, from vetting to final rejection
or acceptance, with prose justification required for all steps.
Additionally, rejected proposals are not deleted but are instead
retained in the digital record, in case new data or better arguments are
made to support them. All accepted proposals are also attributed to
their contributor so they can receive appropriate scholarly credit.
Sosin explains that this level of transparency is important and promotes
both collegiality and peer-review. For technical details on SoSOL, see
([http://idp.atlantides.org/trac/idp/wiki/SoSOL/Overview/](http://idp.atlantides.org/trac/idp/wiki/SoSOL/Overview/))
and access to the prototype is available at
([http://halsted.vis.uky.edu/protosite/](http://halsted.vis.uky.edu/protosite/))
[full citation ±] Sosin, Joshua. “Digital Papyrology” (2010) Paper
presented at the *Congress of the International Association of
Papyrologists*, (August 2010), Geneva, Switzerland.

[¶ 88](#r164 "Permalink")

[Stoa Consortium for Electronic Publication in the
Humanities](http://www.stoa.org/) :

The Stoa Consortium was founded by Ross Scaife in 1997 to support
dissemination of news important to classics via the gateway blog, to
promote the discussion and documentation of best practices (through
discussion groups and white papers), and most importantly, to support
“open access to networked scholarship.” Stoa is host to a number of
digital classics publications including photographic archives,
individual digital editions of classical texts, and a prominent and
collaborative digital encyclopedia (the Suda Online-
http://www.stoa.org/sol/). This project is an important model of the
diversity of digital publications created in the field of classics, each
of which present different curation challenges. [full citation ±] Stoa
Consortium for Electronic Publication in the Humanities

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

[¶ 89](#r165 "Permalink")

[§ 10](#model_digital_resources)

[Model Digital Resources](#model_digital_resources)

-   [](#) Add section comment

The following list of resources illustrates projects that model best
practices for building digital resources that can be sustained and
effectively curated for the long-term and is drawn from across the
classical disciplines. These best practices include the use of
standards, the provision of documentation, permanent and fully citable
URLs, and open access to data that can be exported in a variety of
formats.

[[back to top]](#top)

[¶ 90](#p18 "Permalink")

-   [](#) Add paragraph comment

[Resources: Epigraphy best practices models](#epigraphy_best_practices)
Collapse annotations

[Inscriptions of Aphrodisias (IAph
2007)](http://insaph.kcl.ac.uk/iaph2007/index.html) : Reynolds, J.,
Roueché, C., Bodard, G.

This website forms part of the Inscriptions of Aphrodisias corpus and
provides access to the first edition of an online corpus of inscriptions
from Aphrodisias that were recorded up to 1994. This website illustrates
a number of exemplary practices for the long-term curation of the data
it contains. All the inscriptions have been marked up in EpiDoc, and
both individual inscriptions and the entire repository can be downloaded
along with a DTD from the site, meaning that the entire corpus can be
easily stored in another location. Each inscription also has a citable
and permanent URL. In addition, in order to encourage scholars to cite
this electronic publication, all versions of inscriptions (with their
URLs) are maintained even when changes and corrections are made, in case
a scholar has cited an earlier version of an inscription. The need to
provide versioning in order to ensure that scholars have stable and
citable data that can be traced will be an important feature of any data
curation system. [full citation ±] Reynolds, J., Roueché, C., Bodard, G.
*Inscriptions of Aphrodisias* (2007).

[¶ 91](#r166 "Permalink")

[The Inscriptions of Aphrodisias as Electronic Publication: A User's
Perspective and a Proposed
Paradigm](http://www.digitalmedievalist.org/journal/4/bodard/) : Bodard,
G.

In this article, Bodard outlines six opportunities presented for
epigraphy and the humanities in general by electronic publication
(accessibility, scale, media, hypertext, updates, and iterative research
and transparency) and explains how the Inscriptions of Aphrodisias
exemplifies these opportunities. [full citation ±] Bodard, G. “The
Inscriptions of Aphrodisias as Electronic Publication: A User's
Perspective and a Proposed Paradigm” (2008). Digital Medievalist (4).

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

[¶ 92](#r167 "Permalink")

[Resources: Manuscript Studies best practices
models](#manuscript_studies_best_practices) Collapse annotations

[The Archimedes Palimpsest](http://www.archimedespalimpsest.org/) : The
Archimedes Palimpsest Project

The Archimedes Palimpsest is a 13th century prayer book that was
discovered to contain a number of erased texts, including previously
“lost” treatises by Archimedes and Hypereides. Over the last twenty
years, dozens of scholars have worked with the palimpsest, the
manuscript has been digitized, and the images created of the manuscript
pages as well as transcriptions of the text pages are freely available
for download online
([http://archimedespalimpsest.net/](http://archimedespalimpsest.net/)).
[full citation ±] The Archimedes Palimpsest Project The Archimedes
Palimpsest

[¶ 93](#r168 "Permalink")

[The Homer Multitext](http://www.homermultitext.org/) : C. Dué, M.
Ebbott, C. Blackwell, N. Smith

The The Homer Multitext (HMT) project is hosted by the Center for
Hellenic Studies (CHS) and the website provides access to a library of
text transcriptions and images of Homeric manuscripts, with the major
content being digital images of a 10th century manuscript of the Iliad
known as the Venetus A from the Marciana Library in Venice. This
manuscript has served as the basis for most modern editions of the
Iliad, and includes a large number of marginal commentaries known as
scholia that provide a wealth of historical information about the text.
The encoded transcription of this manuscript includes not just the text
of the Iliad but also the text of all the scholia, an important source
of data ignored by many digitization projects, it also encodes text
variants as well, another important source of data frequently not
included in printed editions. [full citation ±] C. Dué, M. Ebbott, C.
Blackwell, N. Smith *The Homer Multitext*

[¶ 94](#r169 "Permalink")

[Homer Multitext - Nine Year
Update](http://www.mith2.umd.edu/dh09/wp-content/uploads/dh09_conferencepreceedings_final.pdf)
: Blackwell, C. and Smith, D. N.

In order to support a more sophisticated understanding of both the
Venetus A manuscript and the Homeric tradition, the HMT project has
created a digital library model that provides access to all of the
original data needed to create critical editions, including manuscript
images, diplomatic transcriptions that can be reused, and a related body
of textual and reference material that helps to place the manuscript in
its historical context. The major focus of the HMT, Blackwell and Smith
explain, is not to build “ a single-purpose application to support a
particular theoretical approach” but instead to define “a long-term
generic digital library expressly intended to encourage reuse of its
contents, services, and tools.” [full citation ±] Blackwell, C. and
Smith, D. N. “Homer Multitext - Nine Year Update” (2009). Digital
Humanities Abstracts. 2009, pages 6-8.

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

[¶ 95](#r170 "Permalink")

[Resources: Papyrology best practices
models](#papyrology_best_practices) Collapse annotations

[Advanced Papyrological Information System
(APIS)](http://www.columbia.edu/cu/lweb/projects/digital/apis/index.html)
:

The APIS is hosted by New York University and according to its website
serves as a “collections-based repository” that hosts both information
about and images of papyrological materials from dozens of collections
based around the world. This database includes both previously published
and unpublished material and records for papyri include physical
descriptions, extensive bibliographic information, digital images (when
available), and links back to the host databases for full information
such as English or other language translations in some cases. [full
citation ±] Advanced Papyrological Information System

[¶ 96](#r171 "Permalink")

[Trismegistos](http://www.trismegistos.org/) : B. Van Beek, B. Feucht,
Y. Broux, S. Coussement, S. Waebens, M. Depauw, G. jennes, H. Verreth

The Trismegistos project based at the Katholieke Universiteit Leuven
serves both as a large “portal” for papyrological resources and as a
major papyrological aggregator from various collections with a focus on
Ancient Egypt. Its core component is the Trismegistos Texts Database
([http://www.trismegistos.org/tm/index.php](http://www.trismegistos.org/tm/index.php))
that provides federated searching across the metadata of a series of
epigraphical and papyrological databases from related projects. Two
levels of project partners participate in Trismegistos, the first group
updates their information directly into the FileMaker Database that
supports the online XML version of Trismegistos Texts, while a second
group of larger databases updates their information on an annual basis.
All of the participating projects, similar to the APIS, also maintain
individual web presences and databases online. Each papyri is given an
individual Trismegistos Number (TM number) to facilitate the finding of
records for the same papyri across all of the different databases. [full
citation ±] B. Van Beek, B. Feucht, Y. Broux, S. Coussement, S. Waebens,
M. Depauw, G. jennes, H. Verreth Trismegistos

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

[¶ 97](#r172 "Permalink")

[§ 11](#digital_preservation_lessons)

[Digital Preservation Lessons from
Classics](#digital_preservation_lessons)

-   [](#) Add section comment

As the various disciplines of classics have long dealt with both
utilizing fragmentary and fragile sources from antiquity as well as
preserving them, those working in the discipline have some useful advice
regarding larger data curation issues.

[[back to top]](#top)

[¶ 98](#p19 "Permalink")

-   [](#) Add paragraph comment

[Resources: Digital Preservation Lessons from
Classics](#digital_preservation_lessons_resources) Collapse annotations

[Ktêma es aiei: Digital Permanence from an Ancient Perspective]() :
Cayless, H. A.

Although unfortunately not available electronically, this chapter by
Hugh Cayless provides an insightful example from antiquity in terms of
the long-term sustainability of digital materials. His essential
argument is that materials that can be freely used with only limited
restrictions are most likely to survive in the long-term. He proposes
that studying how ancient texts have survived provides a useful analogy
for how digital objects may be preserved, and explains that in general
texts have typically been transmitted through accident, reuse by being
incorporated into other entities, republication or replication, and
being composed on durable materials (e.g. stone inscriptions). Cayless
also asserts that most current digital rights management schemes do not
work well with data curation goals, in that successful preservation
requires the ability to distribute and migrate copies. He suggests that
Creative Commons licenses might be one way to address this issue.
Cayless also criticizes what he views as a misguided focus by digital
preservationists on preserving the “user experience” (or in many cases
the appearance of text on the page) rather than on the intellectual
content of a work. He concludes his chapter with some useful advice for
digital archivists and preservationists: 1) since future views or uses
of an object cannot be predicted, a wide variety of digital resources
should be preserved (one method he suggests for implementing this is
releasing more objects from archival control), 2) since works have
varying cycles of interest—curators must plan for cycles of disinterest
in an object and actively promote the use of entire collections, 3) as
“self-sustaining communities of interest” may be the most important
factor in the long term survival of objects, digital archivists should
promote the growth of communities around the objects/data they curate,
4) as the more copies of an object that exist make it more likely to
survive, curators should greatly increase efforts to obtain rights to
reproduce digital resources without limitations. [full citation ±]
Cayless, H. A. “Ktêma es aiei: Digital Permanence from an Ancient
Perspective” (2010). In Bodard, G. and Mahony, S., editors, *Digital
Research in the Study of Classical Antiquity*, pages 139-150. Ashgate
Publishing, Burlington, VT.

[¶ 99](#r173 "Permalink")

[The Virtual Observatory and the Roman de la Rose: Unexpected
Relationships and the Collaborative
Imperative](http://www.academiccommons.org/commons/essay/VO-and-roman-de-la-rose-collaborative-imperative)
: Choudhury, G. S. and Stinson, T. L.

This article by Choudhury and Stinson describes manuscripts as one of
the most data rich sources available for scholars (e.g. they integrate
texts, images, annotations, intertextual allusions and references). They
also note that in their creation of the Roman de La Rose Library
([http://rose.mse.jhu.edu/](http://rose.mse.jhu.edu/)) they discovered
that there were a surprising number of commonalties between creating an
infrastructure for a manuscript digital library and for a massive
dataset in physics, the Virtual Observatory
([http://www.us-vo.org/](http://www.us-vo.org/)), demonstrating the
“parallel need for data curation and preservation in the humanities and
the sciences (for at the level of storage infrastructure, a byte is a
byte and a terabyte a terabyte).” [full citation ±] Choudhury, G. S. and
Stinson, T. L. “The Virtual Observatory and the Roman de la Rose:
Unexpected Relationships and the Collaborative Imperative” (2007).
*Academic Commons*

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

[¶ 100](#r174 "Permalink")

[§ 12](#research_practices)

[Research Practices](#research_practices)

-   [](#) Add section comment

While classical studies is an inherently interdisciplinary field with a
number of related disciplines, a number of these disciplines have
specific research practices that will require different strategies for
data curators. At the same time, many of the disciplines of classics
share the same or similar kinds of primary sources as well as a number
of research techniques that might lend themselves to common solutions.

[[back to top]](#top)

[¶ 101](#p20 "Permalink")

-   [](#) Add paragraph comment

[Archaeology](#archaeology_practices)

-   [](#) Add section comment

The field of classical archaeology has long made use of information
technology and of perhaps all of the related disciplines of classics it
has by far the most diverse and complicated types of data, both analog
legacy data and newly digitized data, all of which needs to be actively
curated. Since archaeological sites are typically destroyed during an
excavation, the need to carefully document data as it is excavated is
also very important. Archaeological research includes significant work
in the field and while extensive information is typically recorded at
the site, such as through the creation of context cards, much
information about excavated objects is ultimately entered into a
database after the site excavation is completed. This double entry is
not without its problems and the VERA project tried to address this
issue through the introduction of information technology into the field.
They discovered nonetheless that the introduction of technology did not
necessarily improve data quality, and illustrated the importance of
documenting actual research practice and critically examining how
technology may or may not assist in solving difficult issues.

[¶ 102](#p21 "Permalink")

-   [](#) Add paragraph comment

While many archaeologists actively preserve the data that they have
created, the creators of both Digital Antiquity and OpenContext noted
that much of this data is not preserved in a systematic or sustainable
fashion. Both projects are seeking to encourage archaeologists to not
only deposit their legacy data, but also to actively deposit their
current research data so that it is easier to access and can be shared
with the larger scholarly archaeology community. Fears about copyright,
intellectual property, and being “scooped” by another scholar before
formally publishing research that makes use of data they have gathered
and organized are all complicated issues that the Archaeological Data
Service, Digital Antiquity and OpenContext are trying to address through
a variety of solutions (e.g. indicating clear authorship of contributed
data, supporting embargoing of data). Similar fears about the loss of
recognition were also expressed by papyrologists in Roger Bagnall’s
discussion of attempting to get papyrologists to contribute their data
to the Integrating Digital Papyrology project. These issues will thus
need to be considered by data curators seeking to actively work with
archaeologists to preserve their data.

[¶ 103](#p22 "Permalink")

-   [](#) Add paragraph comment

A related issue that was often cited by many working in the field of
archaeological data preservation is the lack of common standards for
describing, integrating and sharing archaeological data, despite the
existence of standards such as ArchaeoML. While the existence of a
single standard for recording and sharing archaeological data is both
unlikely and impractical, the vastly varying nature of descriptive
practices has made the development of larger digital repositories for
archaeological data far more challenging, particularly in terms of
efficiently sharing data of potential interest between related
researchers. Nonetheless, there are growing calls within the field that
argue that one of the major benefits of making data available digitally
is that it allows for data to be more closely integrated and linked to
published interpretations of that data in scholarly publications and
archaeological site reports. Data curators will thus need to ensure that
archaeological data within their care can easily be linked to and cited
online in order to support the next level of digital scholarship. At the
same time, while electronic publication in archaeology, according to a
recent report by the Center for Studies in Higher Education at the
University of Berkeley (Harley et al. 2010, above), is slowly growing in
acceptance by senior scholars, the traditional and established format of
publishing for tenure in archaeology remains the monograph.

[¶ 104](#p23 "Permalink")

-   [](#) Add paragraph comment

The increasing availability of technologies to create 3d models or
digital reconstructions of archaeological sites has also led to a huge
growth in the creation of such models within the discipline of
archaeology, with two of the best known sites being Digital Karnak
([http://dlib.etc.ucla.edu/projects/Karnak/](http://dlib.etc.ucla.edu/projects/Karnak/))
and Rome Reborn
([http://www.romereborn.virginia.edu/](http://www.romereborn.virginia.edu/)).
The consequent growth in these models has also led to new challenges in
archiving not just the models, but also in finding ways to record and
preserve the levels of scholarly interpretation and uncertainty inherent
in creating them and has been addressed by the SAVE project discussed
above. Curators will need to actively work with scholars to develop
metadata models and technical solutions to address these issues.

[¶ 105](#p24 "Permalink")

-   [](#) Add paragraph comment

The need to actively curate not just digital data that scholars create
but also to preserve or at least record or store the levels of
interpretation, uncertainty and individual scholarly decision making
involved in the creation of many digital objects, such as digital
editions of Cuneiform text, inscriptions, papyrus fragments and
manuscript transcriptions, illustrates one of the common data curation
problems found across the classical disciplines including epigraphy,
papyrology and manuscript studies.

[[back to top]](#top)

[¶ 106](#p25 "Permalink")

-   [](#) Add paragraph comment

[Epigraphy](#epigraphy_practices)

-   [](#) Add section comment

Epigraphy is one of the largest related disciplines of classics and
involves the study of ancient inscriptions or epigraphs that have been
engraved into durable materials such as stone. The discipline of
epigraphy is quite advanced digitally and numerous projects exist online
including large digitized inscription collections such as the Corpus
Inscriptionum Latinarum
([http://cil.bbaw.de/cil\_en/dateien/forschung.html](http://cil.bbaw.de/cil_en/dateien/forschung.html))
or the PHI Greek Epigraphy Project
(http://epigraphy.packhum.org/inscriptions/main) and federated databases
that search various inscription collections such as EAGLE (Electronic
Archive of Greek and Latin
Epigraphy-[http://www.eagle-eagle.it/](http://www.eagle-eagle.it/)).
Although a large number of inscription collections are still published
only in print, Gabriel Bodard recently argued that digital publication
provides a more sophisticated way of managing inscriptions in that it
allows for inscriptions to be more fully treated both as texts (e.g.
through markup and subject encoding) and as archaeological objects (see
Bodard 2008, above). The digitization of large numbers of inscribed
texts thus raises a number of issues for the long-term curation of these
inscriptions and the research practices of epigraphy, the most important
of which will be to effectively curate both the encoded text/s of an
inscription and storing and linking them to the multiple images of an
inscription that are digitized or potentially to visualizations that
have been created of the archaeological object on which the inscription
was found.

[¶ 107](#p26 "Permalink")

-   [](#) Add paragraph comment

The standard practice in epigraphy has long been print publication of
inscriptions that have been transcribed using a set of publishing
protocols called the Leiden conventions, which according to Roued (2009,
above) are “a type of semantic encoding” that uses brackets, underdots
and other markings to indicate missing characters, uncertainty, addition
or other corrections made by the editor of the inscription. Many digital
epigraphy projects (largely in the form of relational databases) have
consequently directly transferred Leiden encoded inscriptions to a
digital form. Cayless et al. (2009, above) and others within the field
of epigraphy have increasingly challenged this practice by advocating
the use of the EpiDoc standard, because the use of EpiDoc allows not
just the encoding of an inscription text, but the inclusion of
information about the history of the inscription, scholarly commentary
on and descriptions of the text, as well as links to photographs and
translations. In addition, Cayless et al. argued that inscriptions that
are encoded in EpiDoC XML could be far more easily exported both as
individual inscriptions and as entire corpora, thus making it far easier
to distribute copies of a digital epigraphic corpus and preserve it.
Data curators will thus need to work with creators of digital epigraphy
projects to encourage wider adoption of standards such as EpiDoc,
encourage creators of projects to make them available for download, and
then actively download copies of digital corpora of inscriptions so that
they can be preserved in multiple locations.

[¶ 108](#p27 "Permalink")

-   [](#) Add paragraph comment

 One other significant issue identified by both Bodard (2008) and
Cayless et al. (2009) in the design of digital corpora of inscriptions
was the need to use persistent identifiers (such as DOIs) at the level
of individual digital objects (e.g. an individual inscription) so that
in a future where the same digital inscriptions may be published and
even preserved in multiple location, individual inscriptions could still
be cited independently of location. The need to support persistent
citation and linking to all types of data stored within digital
repositories will be an important feature that data curators will need
to implement in order to support digital scholarship in the future.

[[back to top]](#top)

[¶ 109](#p28 "Permalink")

-   [](#) Add paragraph comment

[Manuscript Studies and Related Classical
Disciplines](#manuscript_studies_practices)

-   [](#) Add section comment

Although manuscript studies is not a “discipline” of classics per-se,
the first standard critical editions of classical texts upon which
modern scholars frequently still rely were based off the study of large
numbers of medieval manuscripts. Ancient and medieval manuscripts are an
important data source for study across a number of classical and
historical disciplines including codicology, philology and palaeography.
Access to both the digitized images of manuscripts as well as various
levels of transcriptions (e.g. a basic text transcription, a TEI-XML
digital edition) has thus been cited as a key component of a
cyberinfrastructure for classics (see Crane et al. 2009, above).

[¶ 110](#p29 "Permalink")

-   [](#) Add paragraph comment

The large amount of data created by both libraries and scholars in the
digitization and transcription of manuscripts raises a number of
significant curation issues. Data curation and digital infrastructure
for manuscripts will require providing both long-term management of and
effective access to the wealth of data created in their digitization.
This data includes digital images of individual manuscript pages as well
as digital versions of entire manuscripts, diplomatic transcriptions of
individual pages and entire manuscripts, possibly multiple TEI editions
of the same manuscript by different scholars, and scholarly annotations
(both historical ones such as scholia and modern ones such as
philological commentaries on words).

[¶ 111](#p30 "Permalink")

-   [](#) Add paragraph comment

Data curation will also need to consider the various ways in which
different types of scholars use these data sources in order to provide
varying levels of service. For example, the discipline of philology
studies historical languages, particularly the grammar and history of
words and their variant forms, and philological scholarship within
Classics typically produces “shared primary and secondary sources about
linguistic sources” (Crane, Seales and Terras 2009, see above) with a
particular focus upon Greek and Latin. The research needs of
philologists then, especially in terms of creating digital critical
editions, are closely tied to the digitization of individual Greek and
Latin manuscripts and annotated corpora of historical manuscripts, and
typically they require access to all of the data used in their creation
(e.g. multiple manuscripts of the same classical work, diplomatic
transcriptions that include all textual variants). Teuchos and TextGrid
are thus seeking to create comprehensive environments that not only
support the creation of new philological data by scholars working with
digitized manuscripts and other sources, but also the development of
collaborative workspaces for sharing data and archives for maintaining
such data in the long-term.

[[back to top]](#top)

[¶ 112](#p31 "Permalink")

-   [](#) Add paragraph comment

[Papyrology](#papyrology_practices)

-   [](#) Add section comment

The discipline of papyrology studies documentary texts, ancient
literature, personnel correspondence and many other types of texts that
have been preserved in papyri. The publication of papyri online, such as
with inscriptions and archaeological reconstructions, involves a large
amount of scholarly editing and individual interpretation, and has been
described by many within the field as akin to the act of creating a
scholarly edition. Data curation for papyrology, as with many other
disciplines within the larger field of classics (including both
epigraphy and archaeology), will thus require preserving not just the
digital objects and databases that have been created, but the scholarly
interpretations involved in the creation of digital objects/editions of
individual ancient texts.

[¶ 113](#p32 "Permalink")

-   [](#) Add paragraph comment

There are numerous digital collections of papyri available online (two
both well-known and large full-text collections are Oxyrhynchus
([http://www.papyrology.ox.ac.uk/POxy](http://www.papyrology.ox.ac.uk/POxy))
and the Duke Data Bank of Documentary Papyri (DDbDP-
http://www.papyri.info/ddbdp/) as well as major papyri aggregators such
as the APIS and important databases of papyrological metadata such as
the Heidelberger Gesamtverzeichnis der griechischen Papyrusurkunden
Ägyptens (HGV-
[http://aquila.papy.uni-heidelberg.de/gvzFM.html](http://aquila.papy.uni-heidelberg.de/gvzFM.html)).
These resources as well as several prominent research projects, namely
e-Science and Ancient Documents (eSAD) and Integrating Digital
Papyrology (IDP), have illustrated a number of important lessons about
the practice of papyrology that will improve important to long-term for
data curation.

[¶ 114](#p33 "Permalink")

-   [](#) Add paragraph comment

To begin with, there is a significant amount of digital papyrological
data and metadata currently available online, often with differing
levels of data and metadata about the same papyri in different
collections and databases. Effective curation of this data will involve
meaningful integration and access to this data, and the Integrating
Digital Papyrology (IDP) project is seeking to provide one possible
model of data integration for papyrology. This project has also offered
important lessons (see Bagnall 2010, above) in terms of what is required
to actively solicit the participation of scholars in terms of sharing
their research data (e.g. ensuring appropriate authorship and credit)
within a long-term archive and how to build editorial models that
reassure potential contributors/users of the data quality of such
contributed data.

[¶ 115](#p34 "Permalink")

-   [](#) Add paragraph comment

Similarly, eSAD’s research offers insights into the need to curate not
just the research outputs of digital papyrology but also the research
methods used by scholars in creating digital resources. The work on an
interpretation support system by eSAD to model and store scholarly
interpretations (Roued 2009, de la Flor et al. 2010, above) during the
use of their prototype research environment for working with ancient
texts illustrates one important type of data that is only created during
the research process itself and would likely be hard to recreate later.
Data curation processes will thus need to be created that can address
the archiving of evidence and methodology of digital scholarly research
not just the “final” scholarly output (e.g. a digital edition of a
papyrus fragment).

[[back to top]](#top)

[¶ 116](#p35 "Permalink")

-   [](#) Add paragraph comment

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
Services](../../images/imls-logo.gif)](http://www.imls.gov/) [![Center
for Informatics Research in Science and
Scholarship](../../images/cirss-logo-sm.gif)](http://cirss.lis.illinois.edu)
[![Graduate School of Library and Information
Science](../../images/gslis36.gif)](http://lis.illinois.edu)
[![University of Illinois at
Urbana-Champaign](../../images/black26.gif)](http://illinois.edu)
[![Creative Commons
License](http://i.creativecommons.org/l/by-nc-nd/3.0/80x15.png)](http://creativecommons.org/licenses/by-nc-nd/3.0/)

This work is licensed under a [Creative Commons
Attribution-NonCommercial-NoDerivs 3.0 Unported
License](http://creativecommons.org/licenses/by-nc-nd/3.0/). \
 **How to cite:**Alison Babeu. "Classics, “Digital Classics” and Issues
for Data Curation", *DH Curation Guide: a community resource guide to
data curation in the digital humanities*,

.

[DH Curation Guide home](../../index.html) \
 [About this site](../../about/) [Contents](../../contents/) [FAQ about
data curation](../../faq/) [Contributing editors](../../editors/)
[Glossary](../../glossary.html) [Privacy](../../privacy/) [Contact
us](../../about#contact) [Sitemap](../../sitemap.html) \
 \

Page updated 2012-06-25

[[back to top]](#top)

a05bb59dace4487483dab0588ae04eb0
