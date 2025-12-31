---
Authors: [Shawn Gates]
---

## Overview
Byrthonic Language that evolved from Common Brythonic between Cornish and Breton

From an in character perspective, this document should be taken as an attempt by a scholar to document the language spoken in the Weald. Due to the nature of the area any given village will likely have fairly disparate dialects that greatly change the proncution or word choice for things. In addition, literacy is likely not high so the spellings presented here are again, only one person's version.

I am generally avoiding borrowing from other languages outside of the Byrthonic family since The Weald is not actually located in Northern Europe or the British Isles and so other languages of that area (English, French, etc.) are not present to create loan words from.

A sometimes exception to this is Latin due to The Weald generally having a late medieval feel with lots of Latin influences such as the nature of nobility and churches and heraldry, so some words can be quite hard to develop whilst ignoring Latin entirely. Though again, when possible, a Proto Indo European root is preferred, and then a new word grown using the path from PIE to Proto-Celtic to Proto-Byrthonic and on to Wealdish itself.

# Examples
```base
filters:
  and:
    - file.folder != "Templates"
    - categories.contains("examples")
views:
  - type: table
    name: Examples
    filters:
      and:
        - categories.contains("examples")
    order:
      - file.name
      - English
    sort:
      - property: file.name
        direction: ASC
  - type: table
    name: Wealdtober
    filters:
      and:
        - categories.contains("Wealdtober")
    order:
      - file.name
      - English
      - date
    sort:
      - property: date
        direction: ASC
  - type: table
    name: Phrases
    filters:
      and:
        - categories.contains("phrases")
    order:
      - file.name
      - English

```

# Grammar Rules
```base
filters:
  and:
    - file.folder != "Templates"
views:
  - type: table
    name: Grammar Rules
    filters:
      and:
        - categories.contains("Grammar")
    order:
      - file.name
      - rule

```
# Lexicon
(Select View to quickly filter)

![[Lexicon.base]]
