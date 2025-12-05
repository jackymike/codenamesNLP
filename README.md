# codenamesNLP

An NLP-based "solver" for the board game Codenames.

## Default Rules for Codenames

https://officialgamerules.org/game-rules/codenames/

### Objective

Two rival spy teams compete to uncover the identities of their secret agents. Each agent is known only by a codename on the table. Spymasters give one-word clues that relate to multiple codenames, while field operatives try to guess the correct words. The first team to find all their agents wins, unless someone accidentally reveals the assassin first.

### Clue Reference Table

| Rule Type      | Allowed                                   | Not Allowed                                 |
| -------------- | ----------------------------------------- | ------------------------------------------- |
| Compound Words | If common (e.g., greenhouse)              | Made-up combos (e.g., lunar squid)          |
| Proper Names   | Yes, if common or allowed by group        | Made-up names                               |
| Acronyms       | Common ones like CIA, FBI, PhD            | Obscure or made-up acronyms                 |
| Rhyming Clues  | Only if meaningfully related              | Just rhymes with no contextual meaning      |
| Homonyms       | Yes, if different spelling (e.g., knight) | No, if same spelling but different meanings |
