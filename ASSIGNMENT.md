# 4.6 Assignment: Knowledge Representation System

## Full Assignment Brief
## Module 4
 4.6 Assignment: Knowledge Representation System

### Overview

You will design, implement, and evaluate a knowledge representation system for a domain of your choosing. This assignment integrates the theoretical concepts of knowledge representation, ontologies, and reasoning covered in Modules 3 and 4, requiring you to apply predicate logic, develop formal ontologies, and implement rule-based reasoning systems.

Note that this discussion is required/graded.

This assignment should demonstrate that you can:

- Apply predicate logic to formally represent domain knowledge
- Design and implement ontologies using appropriate tools and methodologies
- Develop rule-based reasoning systems with forward and backward chaining
- Evaluate the expressiveness and limitations of different knowledge representation approaches
- Demonstrate competency in ontology development tools and/or semantic reasoning libraries

###  Instructions

#### Assignment brief

Select each title to view information on the assignment requirements. Open all sections simultaneously by selecting the Expand All Panels button     .  

#### 1. Domain selection and scope definition

Select a specific domain area that interests you (e.g., healthcare diagnostics, financial risk assessment, cybersecurity threat analysis, supply chain management, environmental monitoring, etc.).

Your chosen domain should be:

- Sufficiently complex to demonstrate meaningful knowledge representation concepts (i.e., not too simple a domain)
- Well-bounded to allow comprehensive coverage within the scope of this assignment (i.e., not too complex a domain)
- Rich in relationships between entities, properties, and rules
- Amenable to rule-based reasoning with clear inference patterns

#### 2. Technical implementation

Choose one of the following implementation approaches:

- 
**Option A: Protégé-based implementation**

Develop your ontology using Protégé 5.x
- Define classes, properties, individuals, and axioms
- Implement SWRL rules for reasoning
- Use a reasoner (HermiT, Pellet, or FaCT++) for inference
- Demonstrate query answering using SPARQL or DL queries

- 
**Option B: Python with pykg2vec**

Implement knowledge graph embeddings for your domain
- Create entity and relation embeddings
- Demonstrate link prediction or knowledge completion tasks
- Evaluate embedding quality using appropriate metrics

- 
**Option C: Python with semantic libraries**

owlready2: Manipulate OWL ontologies programmatically
- pronto: Work with OBO format ontologies
- OAK: Use the Ontology Access Kit for ontology operations

#### Note

- Alternative tools or libraries require instructor approval. Check with your instructor prior to using a tool not listed above.
- 
If you wish to gain experience and get instructor feedback on multiple approaches, you may choose multiple options above. 

You should specify one to be your primary implementation, which will be used to determine the bulk of your grade. 
- The secondary implementation will be mainly for additional feedback for you.

#### 3. System components

Your implementation must include:

3.1 Formal ontology structure

- Classes and hierarchies: Organize domain concepts using subsumption relationships
- Properties: Define object properties (relationships) and data properties (attributes)
- Axioms and constraints: Specify domain and range restrictions, cardinality constraints, and disjointness
- Individuals: Populate your ontology with representative instances

3.2 Rule-based reasoning system

- Production rules: Implement at least five meaningful inference rules using your chosen framework.
- Reasoning strategy: Demonstrate both forward chaining (data-driven) and backward chaining (goal-driven) inference where applicable.
- Consistency checking: Ensure your ontology is logically consistent.

3.3 Query and inference capabilities

- Competency questions: Define and answer at least eight domain-specific queries that demonstrate your system's capabilities.
- Reasoning examples: Show how new knowledge is inferred from existing facts and rules.
- Classification: Demonstrate automatic classification of new instances.

#### 4. System demonstration

Provide a comprehensive demonstration that includes:

- Knowledge base population: Show how domain knowledge is represented.
- Rule execution: Demonstrate inference processes with step-by-step reasoning traces.
- Query processing: Execute various types of queries (simple lookup, complex reasoning, classification).
- Edge cases: Show how your system handles incomplete information or conflicting data.

#### Deliverables

Select each title to view information on the assignment deliverables. Open all sections simultaneously by selecting the Expand All Panels button     .  

#### 1. Technical artifacts

- For **Protégé implementation**, submit the following:

.owl ontology file(s)
- .swrl rules file (if separate)
- Screenshots of key ontology views (class hierarchy, property definitions, individuals)
- Query results and reasoning traces

- 
For **Python implementation**, submit the following:

Complete Python code with clear documentation
- Requirements file (requirements.txt or equivalent)
- Sample data files
- Output demonstrations (visualizations, query results, reasoning traces)

#### 2. Technical report (APA Style)

Submit a report (2,500-3,500 words) structured following APA style:

- 
**Abstract (150-200 words)**

Provide a concise summary of your domain, approach, key findings, and contributions.

- ** Introduction**

- Explain your problem motivation and domain significance
- Define the scope and boundaries of your knowledge representation system
- Outline the research questions or competency requirements you addressed

- ** Background and literature review**

- If any previous models of this domain exist, provide a brief review of those approaches
- Justify your chosen representation methodology

- ** Methodology and system design**

- Domain analysis: Provide a detailed description of your chosen domain
- Conceptual model: Present a high-level overview of key concepts and relationships
- Knowledge representation framework: Justify your chosen tools/libraries
- Ontology design patterns: Describe the patterns and principles you applied

- ** Implementation**

- Ontology structure: Provide a detailed description of your classes, properties, and axioms with rationale
- Rule design: Explain your inference rules with logical formulations
- Technical architecture: Describe your system components and their interactions
- Include UML diagrams, ontology visualizations, or system architecture diagrams

- ** Evaluation and results**

- Reasoning performance: Present examples of successful inferences with explanations
- Consistency and completeness: Analyze the logical consistency and coverage of your system
- Limitations identified: Discuss what your system cannot represent or infer

- ** Critical analysis**

- Expressiveness vs. computational complexity: Analyze your representation choices
- Alternative approaches: Briefly discuss other possible representations you considered, discuss how those alternatives might have changed your results.
- Scalability considerations: Discuss performance implications with larger knowledge bases

- ** Conclusion**

- Summarize your results, highlight key takeaways
- Reflect on what your system reveals or suggests about your domain (did you discover any new knowledge about your domain)
- Suggest future work and potential extensions
- Your conclusions should be written as a report to a superior at a place of employment. You want to highlight what was learned about the domain that would help them. The conclusions should not be about what you learned about python, protégé, or any of the libraries.

- 
**References**

Cite any sources in APA format, this includes where you got information about your domain, such as Wikipedia. If you consulted Claude or Copilot to aid in any portion of your work, cite the AI as well. If Gemini aided you in debugging code, include that in your references. Also include any relevant papers on knowledge representation, ontologies, and domain-specific applications that you consulted.

- 
**Code documentation and comments**

All code must be thoroughly documented with:

Clear function/method documentation
- Inline comments explaining complex logic
- README file with setup and execution instructions
- Example usage demonstrations

#### Evaluation

Select each tab to learn how your assignment will be evaluated.

### Technical implementation

Technical implementation (40 points) criteria:

- Correctness: System functions as designed without errors
- Completeness: All required components are implemented
- Code quality: Clean, well-structured, and documented code
- Tool proficiency: Effective use of chosen development tools

Select the next tab to learn more.

### Knowledge representation quality

Knowledge representation quality (25 points) criteria:

- Domain modeling: Accurate and comprehensive representation of domain concepts
- Ontology design: Proper use of classes, properties, axioms, and design patterns
- Rule formulation: Logically sound and meaningful inference rules
- Expressiveness: Ability to represent complex domain relationships

Select the next tab to learn more.

### Reasoning and inference

Reasoning and inference (20 points) criteria:

- Rule execution: Correct implementation of forward/backward chaining
- Query answering: Successful resolution of competency questions
- Consistency: Logically consistent knowledge base
- Explanation: Clear demonstration of reasoning processes

Select the next tab to learn more.

### Report quality

Report quality (15 points) criteria:

- Technical writing: Clear, professional, and well-structured presentation
- Analysis depth: Thoughtful discussion of design choices and limitations
- APA compliance: Proper formatting, citations, and references
- Visual documentation: Effective use of diagrams and figures

#### Submission guidelines

- Report: PDF format, APA style, 12pt Times New Roman, double-spaced
- Code: Python 3.8+ with virtual environment specifications (if Python was used)
- Ontologies: OWL format compatible with Protégé 5 (if Protégé was used)

#### Additional resources

Recommended tools and libraries:

- [Protégé](https://protege.stanford.edu/)
- [owlready2](https://pypi.org/project/Owlready2/)
- [pronto](https://pypi.org/project/pronto/)
- [pykg2vec](https://pypi.org/project/pykg2vec/)
- [OAK](https://incatools.github.io/ontology-access-kit/)

Ontology design resources:

- [OBO Foundry Principles](http://obofoundry.org/principles/)
- [Ontology Design 101](https://protege.stanford.edu/publications/ontology_development/ontology101.pdf)
- [FAIR Data Principles](https://www.nature.com/articles/sdata201618) 

#### Academic integrity

This is an individual assignment. While you may discuss general concepts with classmates, all implementation work and written analysis must be your own. Proper attribution is required for any external resources, datasets, or code libraries used; this includes generative AI and large language models. See the course syllabus for clarification.

Once you have completed this assignment, select Next to explore the module summary.

Icon Progress Bar (browser only)

## Due Date
None
