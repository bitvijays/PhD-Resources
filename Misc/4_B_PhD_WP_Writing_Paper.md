# Writing Paper

- Reviewers (and readers) mostly will make only one pass over it. If a reviewer cannot understand the gist after one pass, the paper will likely be rejected; if a reader cannot understand the highlights of the paper after five minutes, the paper will likely never be read.
- Ensure to have coherent section and sub-section titles and to write concise and comprehensive abstracts.

The three main phases of a write-up are

- organizing materials so that the work tells a story,
- giving this story the structure of a thesis or of an academic paper, and
- actually writing.

## The Scope of a Paper

First task is to describe your aims.

- An effective exercise is to write down everything that motivated you to start the research.
- What did you want to achieve?
- What problems did you expect to address?
- What makes the problems interesting?

Next, define the scope of the work that you plan to write up.

- It is necessary to make choices about what to include, and thus it is necessary to identify what might be included.

What the core contribution of the work is going to be.

- Which results are the most surprising?
- What is the one result that other researchers might adopt in their work?
- Are the other outcomes independent enough to be published separately later on? Are they interesting enough to justify their being included?
- Does it make sense to explain the new algorithms first, followed by description of the previous algorithms in terms of how they differ from the new work? Or is the contribution of the new work more obvious if the old approaches are described first, to set the context?
- What assumptions or definitions need to be formalized before the main theorem can be presented?
- What is the key background work that has to be discussed?
- Who is the readership? For example, are you writing for specialists in your area, your examiners, or a general computer science audience?

Another element in the process of developing a paper is deciding where the work might be published. In particular, the venue partly determines the scope of a paper.

- For example, is there a page limit?
- Are there specific conventions to be observed?
- Are the other papers in that venue primarily theoretical or experimental?
- What prior knowledge or background is a reader likely to have?
- Do the editors require that your code be available online?

Once the material for a paper has been collected it has to be organized into a coherent self-contained narrative, which ultimately will form the body of the write-up. Turning this narrative into a write-up involves putting it in the form ofan academic paper: including an introduction, a bibliography, and so on.

## Telling a story

A cornerstone of good writing is identifying what the reader needs to learn.

A strong thesis or paper has a story-like flow, with a sequence of concepts building from a foundation of knowledge assumed to be common to all readers up to new ideas and results. Thus an effective paper educates its readers. It leads readers from what they already know to new knowledge you want them to learn.

For this reason, the body of a good paper - everything between the introduction and the conclusions - should have a logical flow that has the feel of a narrative.

The early parts of the paper's body typically explain hypotheses or claims; the reader expects to discover by the end whether these are justified.

There are several common ways for structuring the body of a paper. Structure by

- Chain: in which the results and the background on which they build dictate a logical order for presentation of the material. First might come, say, a problem statement, then a review of previous solutions and their drawbacks, then the new solution, and finally a demonstration that the solution improves on its predecessors.

- Specificity: an approach that is particularly appropriate for results that can be divided into several stages. The material is first outlined in general terms, then the details are progressively filled in.

- Example: in which the idea or result is initially explained by, say, applying it to some typical problem. Then the idea can be explained more formally, in a framework the example has made concrete and familiar.

- Complexity: For example, a simple case can be given first, then a more complex case can be explained as an extension, thus avoiding the difficulty of explaining foundational concepts in a complex framework. This approach is a kind of tutorial: the reader is brought by small steps to the full result.

## Organisation

Scientific papers follow a standard structure that allows readers to quickly discover the main results, and then, if interested, to examine the supporting evidence.

A well-structured write-up accommodates this behaviour by having important statements as near the beginning as possible.

- Describe the work in the context of accepted scientific knowledge.
- State the idea that is being investigated, often as a theory or hypothesis.
- Explain what is new about the idea, what is being evaluated, or what contribution the paper is making.
- Justify the theory, by methods such as proof or experiment.

A typical write-up has most of the following components:

### Title and Author

#### Title

The title should be the fewest possible words that adequately describe the content of the paper.

Titles can be long and descriptive:

- Linear-Time External Multipass Sorting with Approximation Guarantees

or short and sweet:

- Approximate External Sort

Here's a middle-of-the-road length, plus a cute name that sticks in people's minds:

- Floosh: A Linear-Time Algorithm for Approximate External Sort

Remember that

- thousands of people will read the title of the paper, every though only a few may read the whole paper.
- also that the indexing and abstracting services depend on the accuracy of the title.

#### Author

Papers begin with their title and information about authors including name, affiliation, and address.

The front matter of a paper may also include other elements.

- One is acknowledgements, which alternatively may follow the conclusions.
- Another element is a collection of search terms, keywords, or key phrases - additional terminology that can be used to describe the topic of the paper.

### Abstract

A well-prepared abstract enables readers to identify the basic content of a paper quickly and accurately, to determine its relevance to their interests, and thus to decide whether they need to read the paper in its entirety.

The abstract should

- state the principal objectives and scope of the investigation,
- describe the methodology employed,
- summarize the results, and
- state the principal conclusions.
- concise summary of the paper's aims, scope, and conclusions.

Irrelevancies, such as minor details or a description of the structure of the paper, are usually inappropriate, as are acronyms, mathematics, abbreviations, or citations

It should never give any information or conclusion that is not stated in the paper. It should not exceed 250 words. In other words, the abstract should be designed to define clearly what is dealt with in the paper.

Many abstracts follow a five-element organization:

1. A general statement introducing the broad research area of the particular topic being investigated.
2. An explanation of the specific problem (difficulty, obstacle, challenge) to be solved.
3. A review of existing or standard solutions to this problem and their limitations.
4. An outline of the proposed new solution.
5. A summary of how the solution was evaluated and what the outcomes of the evaluation were.

A draft of an abstract can consist of five sentences, one for each of the points above.

Introductions should be structured in much the same way, but with a paragraph or two, not a sentence, for each component.

### Introduction

- An introduction can be regarded as an expanded version of the abstract.
- It should describe the paper's topic, the problem being studied, references to key papers, the approach to the solution, the scope and limitations of the solution, and the outcomes.
- It should include motivation: the introduction should explain why the problem is interesting, what the relevant scientific issues are, why the approach taken is a good one, and why the outcomes are significant.
- The introduction can discuss the importance or ramifications of the conclusions but should include only a brief summary of the supporting evidence, which the interested reader can find in the body of the paper.
- The reader should also understand the contribution, that is, what the discovery of the work is - the core idea that the referees or examiners need to appreciate as novel and important. This understanding requires that the reader appreciates what the properties of this contribution are, what makes it interesting and plausible, what method was used to investigate it, and why the method is appropriate.

#### Rules - Introduction

- It should present first, with all possible clarity, the nature and scope of the problem investigated.
- To orient the reader, a brief review of the pertinent literature is usually appropriate.
- The method of investigation should be stated. If deemed rep necessary, the reasons for the choice of a particular method should be outlined.
- The principal results of the investigation should be stated. Do not keep the reader in suspense; let him follow the man development of the evidence.

Introduction should consist of five paragraphs answering the following five questions:

1. What is the problem?
2. Why is it interesting and important?
3. Why is it hard? (E.g., why do naive approaches fail?)
4. Why hasn't it been solved before? (Or, what's wrong with previous proposed solutions? How does mine differ?)
5. What are the key components of my approach and results? Also include any specific limitations.

Then have a final paragraph or subsection: "Summary of Contributions". It should list the major contributions in bullet form, mentioning in which sections they can be found. This material doubles as an outline of the rest of the paper, saving space and eliminating redundancy.

### Related Work

#### Position of Related Work

Should related work be covered near the beginning of the paper or near the end?

- Beginning, if it can be short yet detailed enough, or if it's critical to take a strong defensive stance about previous work right away. In this case Related Work can be either a subsection at the end of the Introduction, or its own Section 2.
- End, if it can be summarized quickly early on (in the Introduction or Preliminaries), or if suficient comparisons require the technical content of the paper. In this case Related Work should appear just before the Conclusions, possibly in a more general section "Discussion and Related Work".

#### Why write related work section

To establish

- Need for work
  - Why previous works don’t get it done
  - The limitations of past work
- Mastery over area
  - Established bona fides
- Relationship to other scientific areas.
  - How relates to bodies of other works
- Others

#### Wrong way

Common, wrong, way to write a paper.

- Algorithms a, b, c, and d. have been done.
  - A is good because of Blah, bad because of Duh.
  - B is good because of Blah’, bad because of Duh’.
  - C is good because of Blah’’, bad because of Duh’’
- A laundry list with no introspection about field in which it exists.

#### Narrative

- Tell a story about the field in which it exists. It should try to organize the field in such a way as you can see how the work evolves from start to finish.
- Ideally, ends with the conclusion that the present work is needed.

#### Summary

- A good related work section should include works
  - If they address the central problem
  - If they address a related problem
  - If they identified the problem
  - If they use the same methodology for a similar problem
  - If your work was inspired by them
- It should be a narrative about the field, its logical relatives, the problems it faces, advances and failures, and motivating articles.
  - Show how the body of work holds together in some philosophical or technological way
  - Demonstrate mastery of subject matter to establish credentials for paper (often a fatality if done wrong)

### Body

- The body of a paper should present the results.
- This presentation should provide necessary background and terminology, explain the chain of reasoning that leads to the conclusions, provide the details of central proofs, summarize any experimental outcomes, and state in detail the conclusions outlined in the introduction.
- Since the body can be long, narrative flow and a clear logical structure are essential.
- In describing methods of the investigation, sufficient details should be given so that a competent worker could repeat the experiement.

#### Rules - Body

1. A clear new important technical contribution should have been articulated by the time the reader inishes page 3 (i.e., a quarter of the way through the paper).
2. Every section of the paper should tell a story. (Don't, however, fall into the common trap of telling the entire story of how you arrived at your results. Just tell the story of the results themselves.) The story should be linear, keeping the reader engaged at every step and looking forward to the next step. There should be no signiicant interruptions -- those can go in the Appendix;

#### Important components

- Running Example: When possible, use a running example throughout the paper. It can be introduced either as a subsection at the end of the Introduction, or its own Section 2 or 3
(depending on Related Work).
- Preliminaries: This section, which follows the Introduction and possibly Related Work and/or Running Example, sets up notation and terminology that is not part of the technical
contribution. One important function of this section is to delineate material that's not original but is needed for the paper.
- Content: The meat of the paper includes algorithms, system descriptions, new language constructs, analyses, etc. Whenever possible use a "top-down" description: readers should be
able to see where the material is going, and they should be able to skip ahead and still get the idea.

### Performance Experiements

- What should performance experiments measure? Possiblities:
  - Pure running time
  - Sensitivity to important parameters
  - Scalability in various aspects: data size, problem complexity,
  - Others?

- What should performance experiments show? Possibilities:
  - Absolute performance (i.e., it's acceptable/usable)
  - Relative performance to naive approaches
  - Relative performance to previous approaches
  - Relative performance among different proposed approaches
  - Others?

### Conclusions

- The conclusions section, or summary, is used to draw together the topics discussed in the paper.
- Include a concise statement of the paper's important results and an explanation of their significance.
- Appropriate place to state (or restate) any limitations of the work: shortcomings in the experiments, problems that the theory does not address, and so on.
- The conclusions are an appropriate place to look beyond the current context to other problems that were not addressed, to questions that were not answered, to variations that could be explored. They may include speculation, such as discussion of possible consequences of the results. A conclusion is that which concludes, or the end.
- Conclusions are the inferences drawn from a collection of information.
- Write “Conclusions”, not “Conclusion”.
- If you have no conclusions to draw, write “Summary”, which is often the appropriate way to end a thesis chapter.

In general a short summarizing paragraph will do, and under no circumstances should the paragraph simply repeat material from the Abstract or Introduction. In some cases it's possible to now make the original claims more concrete, e.g., by referring to quantitative performance results.

### Future Work

This material is important part of the value of a paper is showing how the work sets new research directions.

### Acknowledgement

- Acknowledge any significant help received from any individual.
- Acknowledge any outside financial assistance such as grants, contracts or fellowships.

### Bibliography

A paper's bibliography, or its set of references, is a complete list of theses, papers, books, and reports cited in the text. No other items should be included.

#### Rules - Bibliography

- First, only primary references should be listed. References to unpublished data, papers in press, abstracts, theses, and other secondary materials should not clutter up the Literature Cited. If such a reference seems absolutely essential, it may be added parenthetically in the text.
- Second, check all parts of every reference against the original publication, before the manuscript is submitted, and perhaps again at the galley-proof stage.

There are far more mistakes in the Literature Cited section of a paper than anywhere else.

### Appendices

- Some papers have appendices giving detail of proofs or experimental results, and, where appropriate,material such as listings of computer programs.
- Appendices are only occasionally necessary for a paper, in cases where there is material such as a proof whose length would interrupt the flow.

## Writing Up Checklist

### Regarding the scope of the work

- In what forum, or kind of forum, do you plan to publish?
- Is the scope of the work well defined?
- Is there a single, clearly articulated research question or goal? Have you identified which aspect of the work is of greatest impact, or of greatest interest?
- What would success in the project look like? What would failure look like? Can you anticipate the form of the outcomes in either case?
- Who is the readership? How deep or thorough will the background need to be to ensure that the readers fully appreciate the work?
- Do you and your co-authors have an agreed methodology for sharing the work of completing the write-up?
- Are the roles of the participants clear? What are your responsibilities? What activities will the others undertake?

### Regarding how the write-up is organized and presented

- What form will your write-up take? What other paper or thesis should your write-up resemble?
- Are you writing to awell-defined structure and organization? What are the sections, and how do they relate to each other?
- Do the title, abstract, and introduction appropriately set the context for the work?
- Have you identified a structure for the argument? A format for the results?
- Have you established a connection between the question, background, methods, and results? That is, have you identified the shape that the narrative will take?
- Is there anything unusual about the organization of the write-up, and, if so, is there a reason for this organization and how will it be explained to the reader?
- If you are writing a paper, are you working to defined length limits or a specified format?
- If you are writing a thesis, are there formatting requirements?

### Regarding your approach to the work

- Are you maintaining a log and notebook?
- Do you work to an explicit schedule with dates and targets?
- Do the deadlines leave enough time for your advisor to provide feedback on your drafts, or for your colleagues to contribute to the material?
- Do you have an effective approach to writing that lets you quickly generate text?
- How are results being selected for presentation? How do these results relate to your original aims? How do the selected results relate to the complete body of evidence you are gathering?
- Have the results been critically analyzed?
- In a thesis with multiple contributions, are they explicitly linked by an overarching goal?
- For a thesis, do you knowhow it will be examined? How is that knowledge shaping your writing.
