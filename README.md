# Olivia ![License: MIT](https://img.shields.io/github/license/KaitlynEthylia/Olivia)
*Logo TBD*

---
[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)[![forthebadge](https://forthebadge.com/images/badges/powered-by-black-magic.svg)](https://forthebadge.com)

> **⚠️ NOTE**
>
> This project is extremely new and currently contains very few questions. It serves currently as a place to store trivia questions from contributors until it is a reasonable enough size to be used. This warning will be removed once each topic and difficulty has at least 5 questions, or until the project reaches 400 questions.


## About
---
Olivia is an organised collection of trivia questions about various topics organised so that they can easily be searched through. The project uses Markdown so that the questions can easily be read from anywhere but it is recommended to use the Obsidian editor as the questions make use of some specific features of Obsidian's flavour of markdown, such as foldable cards to be able to hide the answer, whilst still keeping it in the same card as the question, and comments for the reader only visible in edit mode.

If you are reading these trivia questions yourself, it is recommended that you use obsidian and set it to open new tabs in reader mode, this will hide the answer and any comments that may include spoilers for the answer. But if you have an extra person available to read out the questions, they can easily be read as plain text.

## Organisation
---
### Topics
Questions are organised primarily based on the topic they are most related to. At this time there are 9 main topics, but that is subject to change. These 9 topics are:
 1. Arts & Music
 2. Business
 3. History
 4. Language
 5. Literature
 6. Maths
 7. Politics
 8. Pop Culture
 9. Technology

(The numbers are not significant but the list is left ordered as the topics are referred to using these numbers in both filenames and tags.)

### Difficulties
These topics are then further subdivides into 7 difficulties, named via roman numerals: I, II, III, IV, V, VI, and VII. Difficulty is subjective so there is no strict guideline as to where a question should go, but in general, difficulty I should be used for questions that the majority of children 8+ should be able to work out just from the context of the question, up to difficulty VII which should be used for questions that certainly require obscure background knowledge and are unlikely to be guessed correctly at all by a moderate sized group

### Keywords
Within these folders, questions are organised by the filename format `9X-999-KEYWORD`. The 9X refers to the number of the category followed by the roman numeral of the difficulty. the 999 then refers to the number of the question, this simply increments as new questions are added, and must always be 3 digits. Finally followed by a keyword relating to the question. These do not have to be unique but serve as a way for someone looking for a specific question to be able to locate it more easily by looking for a relevant keyword.

### Tags
Finally, each question ends in a list of tags relating to the question. tags that apply to questions from any topic will be listed first, a complete list of which can be found in [Taglist.md][taglist]. Tags specific to the topic of the question will be prepended with `<topic number>/` with lists being available in the relevant folder's taglist file.
> **Note**
>
> The tag list does not serve to list all the tags that may be used, but instead as a list of all tags that have been used. It is HIGHLY subject to change.

## Questions
---
Questions are formatted first by providing a title that relates to the subject of the question. and then a breif form of the question. This may be enough but if it is not there is also provided extra context and a more detailed explanation of the question, removing any ambiguity. Below this is the answer, and, if neccessary, an explanation of why that answer is correct. More information may then be provided below.

For a full example of how a question may look, see [The Full Template][full-template], or for a simplifies view of how most questions will look see [The Simple Template][simple-template]

---
# Contributing

There are very few rules for contributing in order to encourage as many people as possible to submit questions. SImply:
- All contributed questions should roughly follow the structure shown in the templates.
- Secondly, This project uses Obsidian's flavour of markdown, with this file being the only exception (Using GitHub's markdown for obvious reasons), so all contributions should also follow that style
- Lastly, any tags that you add to a question you should also ensure are in the relevent taglist file. There are no rules on what can and cannot be a tag so you may edit the taglist as necessary, just be reasonable and make sure your tag is not a duplicate of an existing one with the same meaning.

For the sake of consistency, I suggest writing in British English with the inclusion of the Oxford Comma, but this will not be enforced and is simply an aesthetic preference.

---
Relative links used in this document, using Obsidian's formatting:
[[Taglist]]
[[Full-Template]]
[[Simple-Template]]

---
License: [MIT][mit license]

[taglist]:         ./Taglist.md
[full template]:   ./Templates/Full-Template.md
[simple template]: ./Templates/Simple-Template.md
[mit license]:     https://choosealicense.com/licenses/mit/ "MIT License"