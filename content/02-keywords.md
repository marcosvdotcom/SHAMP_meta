---
title: Working with Keywords
nav: Keywords
topics: Keywords, search strings, MeSH
description: How to go from a topic to a locked-in set of keywords and a search string your whole team can use.
---

## Getting started with keywords

- Identifying the keywords or subjects for your topic is the first step in standardizing your search process.
- Once you have your search string locked in, you can (and should!) use the same search across databases.
- To help coordinate searching across teams of researchers, it is important to get this locked in early. Do not plan to update as you go unless meaningful gaps or issues are identified.

## Keyword strategies

- Use a tool like the [MeSH on Demand](https://meshb.nlm.nih.gov/MeSHonDemand) search tool.
- Brainstorm with AI:
  - [Primo Research Assistant](https://alliance-uidaho.primo.exlibrisgroup.com/discovery/researchAssistant?vid=01ALLIANCE_UID:UID)
  - Chatbots: ask for MeSH (medical subject headings) or similar
- Browse keywords on target articles:
  - Search MeSH terms at the [National Library of Medicine](https://www.ncbi.nlm.nih.gov/mesh/)

## Drilling down and leveling up with keywords

"Patient transfer" is a useful example. Look it up in MeSH to see how the term sits within a broader hierarchy and what narrower terms nest beneath it:

- [MeSH search for "patient transfer"](https://www.ncbi.nlm.nih.gov/mesh/?term=patient+transfer)


## Keywords versus strings

If you check out the "patient transfer" entry, you'll notice that it includes a long list of related terms:

	Patient Transfers
	Transfer, Patient
	Transfers, Patient
	Patient Dumping
	Dumping, Patient
	Patient Turfing
	Patient Turfings
	Turfing, Patient
	Turfings, Patient....

To name just a few! When searching in databases that use MeSH terms, PubMed will automatically build all those snyonoms into the search. This is sometimes an advantage, but can also introduce issues if it brings in too many unlrelated articles.

Adding search strings allows you to ask pubmed to search for a specific phrase. You do this as follows:
- ("informational sessions"[All Fields])

This example would search for the exact phrase "informational sessions" across all available text fields. 

> You can use strings to specify by including a specific target you're interested, or by asking for an irrelevant string to be filtered out
<br> - To filter out a result you can use NOT or the hyphen (-) to exclude results with that string

<!-- TODO: The original slide includes a screenshot of the nested MeSH hierarchy for Patient Transfer.
     Save it to the "images" folder and uncomment the line below.
{% include figure.html img="mesh-patient-transfer.png" alt="Nested MeSH hierarchy for Patient Transfer" caption="Nested example of Patient Transfer" width="75%" %}
-->
