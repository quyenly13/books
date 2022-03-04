Summary from Technical Writing Document of Google.

----------------------------------------
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
- *There is* or *There are* marry a generic nount to generic web.
- You can move the true subject and true verb from the end of the sentence to the begining.

**Example**:

*There are two disturbing facts about Perl you should know* <br>
  &rarr; You should now two disturbing facts about Perl.

In some cases, using **There is** to avoid the hassle of creating true subjects or verbs, but we can replace with a meaningful subject like this:

*There is no guarantee that the updates will be received in sequential order.* <br>
&rarr; Clients might not receive the updates in sequential order.

#### Minimize certain adjectives and adverbs
Sometimes, adjectives and adverb can make technical documentations sound dangerously like marketing material.

**Example:**
Setting this flag makes the application run **screamingly fast** &rarr; **225-250% faster**.

## Short sentences

The same rules of coding apply to writing: 
- Shorter documentation reads faster than longer documentation.
- Shorted documentation is typically easier to maintain than longer documentation.
- Extra lines of documentation introduce additional points of failure.

#### Focus each sentence on a single idea.

Just as statements in a program execute a single task, sentences should execute a single idea.

Example: 
In bash, use the if, then, and fi statements to implement a simple conditional branching block in which the if statement evaluates an expression, the then statement introduces a block of statements to run when the if expression is true, and the fi statement marks the end of the conditional branching block. <br>
&rarr; In bash, use the if, then and fi statements to implement a simple conditional branching block. The if statement evaluates an expression. The then statement introduces a block of statements to run when the if expression is true.The fi statement marks the end of the conditional branching block.

#### Convert some long sentences to lists
If the long sentence has **conjunction** (*or*/*and*,...), consider refactoring that sentence into bulleted or numbered list.

**Example:** 

- Long sentence: 

  ```
  To get started with the Frambus app, you must first find the app at a suitable store, pay for it using a valid credit or debit card, download it, configure it by assigning a value for the Foo variable in the /etc/Frambus file, and then run it by saying the magic word twice.
  ```

- Short sentence:

  ```
  Take the following steps to get started with the Frambus app:
    1. Find the app at a suitable store.
    2. Pay for the app using a valid credit or debit card.
    3. Download the app.
    4. Configure the app by assigning a value for the Foo variable in the /etc/Frambus file.
    5. Run the app by saying the magic word twice.
  ```
#### Eliminate or reduce extraneous words
A few common bloated phrases can be replaced with other word:

- at this point in time **&rarr;** now
- determine the location of **&rarr;**  find
- is able to **&rarr;** can
- causes the *production* of **&rarr;** produce
#### Reduce subordinate clauses
- Need to scrutinize subordinate clauses, consider it's role:
  - Extend the single idea
  - Bbranch off into a separate idea
- Keep the `one sentence = one idea`
#### Distinguish that from which

## Lists and tables

## Paragraphs

## Audience

## Documents

## Punctuation

## Markdown

## Self-editing

## Organizing large docs

## Illustrating

## Creating sample code



## Resource
1. https://www.chicagomanualofstyle.org/home.html
2. https://www.ox.ac.uk/sites/files/oxford/media_wysiwyg/University%20of%20Oxford%20Style%20Guide.pdf
3. https://developers.google.com/style
4. https://docs.microsoft.com/en-us/style-guide/welcome/












