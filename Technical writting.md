Summary from Technical Writing Document of Google.
## Grammer (optional)
1. Noun
    - Nouns represent people, places, or things.
    - In programming, noun maybe is classes, variables,...

2. Pronoun
    - A noun that substitutes for another noun or sentences.

3. Verb
    - A verb is an action word or phrase.

4. Adjective and adverb
    - Adverb is a word or phrase that modifies a verb, an adjective, or another adverb.
    - Adjective	a word or phrase that modifies a noun.

5. Conjunction and transition
    - Conjunctions connect phrases or nouns within a sentence. The most important conjunctions are **and**, **or**, **but**.
    - Transitions connect sentences themselves. The most important transitions in technical writting are **however**, **therefore**, **for example**


## Word

#### Define new or unfamiliar terms
Take one of the following to tactics:
- The term already exists &rarr; link to good existing explanation (Don't reinvent the wheel)
- The document is introducing &rarr; define the term. 
- In case introducing many terms &rarr; collect the definitions into a glossary.

#### Use term consistently
- Apply the same unambiguous word or term consistently throughout the document.
- When introducing a long winded concept name or product name, you can specify a shortened version of that name and use it throughout the document.

*Example*:  **Protocol Buffers** (or **protobufs** for short) provide their own definition language. Blah, blah, blah. And that's why protobufs have won so many county fairs.

#### Use acronym properly
- Put unfamiliar acronym in parentheses, both the spelled-out version and the acronym in boldface.
Example: 
This document is for engineers who are new to the **Telekinetic Tactile Network (TTN)** or need to understand how to order TTN replacement parts through finger motions.

- Don't cycle back-and-forth between the acronym and the expanded version in the same document.

#### Whe use the acronym ?
- Don't use the acronym that would only be use a few times.
- Do define acronyms that meet both of the following criteria:
 + The acronym is significantly shorter than the full term
 + The acronym appears many times in the document.

 #### Disambiguate pronouns
- Only use a pronoun after the noun have been introduced.
- Place the pronoun as close as possible to the referring noun. If more than five words separate the noun from the pronoun, considering repeating the noun instead of using the pronoun.
- If introducing a second noun between first noun and it's pronoun, reuse first noun instead of using a pronoun.

###### It and they
- These pronouns cause the most confusion in document

**Example:** 

Python is interpreted, while C++ is compiled. It has an almost cult-like following. 

   &rarr; What does *It* refer to, Python or C++.

###### This and that
- Replace **this** and **that** with the appropriate noun.
- Place a noun immediately after **this** or **that**.

## Active voice
- Active voice is usually clearer than passive voice.
- Passive voice reports action indirectly.
- Sentences that start with an imperative verbs are typically in active voice.

&rarr; Be bold-be active.

## Clear sentences

#### Choose strong verb
- **Choose** precise, strong specific verb to engage and educate readers.
- **Reduce** imprecise, weak or generic verbs such as: forms of be (is, are, am, was, were, etc), occur, happen.

*Example:*

The error **occurs** when clicking the Submit button

   &rarr; Clicking the Submit button **triggers** the error.

This error message **happens** when ... 

   &rarr; The system **generate** this error message when ...

We **are very careful to** ensure..

   &rarr; We **carefully** ensure....

**Pratice:**

1. When a variable declaration **doesn't have** a datatype, a compiler error **happens**.

    &rarr; When a variable declaration **doesn't specify** a datatype, the compiler **generates** an error message.

    &rarr; If you declare a variable but **don't specify** a datatype, the compiler **generates** an error message.

2. Compiler errors **occur** when you **leave off** a semicolon at the end of a statement.

    &rarr; Compilers **issue** errors when you **omit** a semicolon at the end of a statement.

    &rarr; A missing semicolon at the end of a statement **triggers** compiler errors.


#### Reduce there is / there are
- There is or There are marry a generic nount to generic web.








