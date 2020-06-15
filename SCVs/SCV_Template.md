# Use this template for communicating Swarm Council Votes

## Instructions:

* The title of the SCV should follow the format SCV_(EPOCHtime)_(TITLE).md where EPOCHtime is equivalent to the current Unix Epoch and can be calculated using https://www.unixtimestamp.com/index.php
* Edit in "Raw" so that you can see all content;
  * The text between the tags `<hash-start>` and `</hash-end>` should be hashed using the SHA256 algorithm and evidenced below the text, for future reference.

<hash-start>
---
Title: (TITLE, e.g. Decision regarding April Voting Period) |
Sponsor: Swarm Council | 
Created: (DATE, EPOC)
---

# Advancement of GAP to GAB

## Description of the decisions taken

These GAPs advance to GAB (pursuant to Sec VII.B.1 of the SNC-2019.02):
(Title, GitHubURL, Action (Advances to GAB, Does not advance to GAB), reason (optional), other actions (e.g. modified voting interval)...)

(optional)
These GAPs do not advance to GAB (pursuant to Sec VII.B.1 of the SNC-2019.02):
(Title, GitHubURL, Action (Advances to GAB, Does not advance to GAB), reason (optional), other actions (e.g. modified voting interval)...)

(optional)
These GAPs/GABs are canceled (pursuant to Section VIII.E.(b) of the SNC-2019.02):
(Title, GitHubURL, reason (optional),...)

(optional)
These GAPs/GABs have a modified Enactment Period (pursuant to Section VIII.E.(c) of the SNC-2019.02):
(Title, GitHubURL, reason (optional),...)
</hash-end>

## Hash
0x(HASH)
Based on sha256-32, e.g. using [Hash Calculator](https://www.pelock.com/products/hash-calculator)

## VerifiedExistence
(TxHASH) via [VerifiedExistence](https://github.com/swarmfund/swarm-open-tools/blob/master/VerifiedExistence/Readme.md)

## License
Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
