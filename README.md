# Open Classification System (OCS)

The Open Classification System (OCS) is an open, community-driven effort to classify Internet domains by subject matter.

OCS treats the Internet as a library and domains as cataloged works. Rather than organizing websites by ownership, popularity, or search ranking, OCS organizes them according to the subjects they contain.

## Goals

* Create an open classification standard for Internet domains
* Provide a human-readable alternative to opaque categorization systems
* Enable independent catalogs, search engines, archives, and directories
* Encourage community participation in the organization of online knowledge
* Build a classification system designed specifically for the Internet

## Classification Format

OCS uses a hierarchical three-part subject code:

```text
AAA.BBB.CCC
```

Where:

| Level | Description         |
| ----- | ------------------- |
| AAA   | Primary Subject     |
| BBB   | Secondary Subject   |
| CCC   | Specialized Subject |

Example:

```text
SOC.ANT.CUL
```

Expands to:

```text
Social Sciences
└── Anthropology
    └── Cultural Anthropology
```

Another example:

```text
COM.NET.P2P
```

Expands to:

```text
Computing
└── Networking
    └── Peer-to-Peer Systems
```

## Design Principles

### Subject-Oriented

OCS classifies domains by what they contain rather than who owns them.

For example:

* A university website and a personal website may both be classified under the same subject.
* A government website discussing astronomy may be classified under astronomy.
* A corporate website publishing programming documentation may be classified under computing.

### Human Readable

Classification codes are intended to be understandable without consulting large reference tables.

```text
SOC.ANT.CUL
REL.ESO.TAR
COM.NET.P2P
```

### Open

No proprietary numbering systems.

No copyrighted decimal classifications.

No licensing requirements.

The taxonomy is intended to remain publicly available and freely implementable.

### Extensible

New subjects may be added as knowledge evolves.

The system should accommodate:

* Academic subjects
* Scientific disciplines
* Technical fields
* Cultural topics
* Historical subjects
* Emerging technologies
* Community-driven knowledge domains

## Contributing

Contributions are welcome.

Areas of interest include:

* Subject definitions
* Taxonomy design
* Classification guidelines
* Domain cataloging
* Governance and standardization

You may join the community here: https://www.reddit.com/r/OpenCatSystem/

## Status

OCS is currently under active development.

The taxonomy, governance model, and cataloging guidelines are evolving through community discussion and experimentation.
