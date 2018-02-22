# How to usee the DoDAF meta-model \(DM2\)

## DoDAF glossary and model files

* The DM2 provides a **standard glossary** of terms and definitions for architecture work within the Department of Defense. These terms may be used across the **six** major processes of the DoD.
* The DM2 itself is available as a **Sparx Enterprise** Architect model file.

## DoDAF diagrams and UML as an ontology diagramming notation

* The **IDEAS model** is represented using **UML notation** provided by the **SparxEA** tool and tailored by the IDEAS add-in.
* The **stereotype of an element** in an IDEAS UML model is shorthand for the element being an **instance of the type** referred to by the stereotype, through the type must be one defined in the **root package** of the foundation.
  > These stereotype, _**color**_-coded class symbols are used in the model
* An IDEAS diagram with **color**-codinge:
  ![](/assets/IDEAS-with-color-coding.png)
* Naming conventions for type and relationships:
  1. Names are formed by concatenating words. The initial letter of each word in a multi-word name is **capitalized**.
  2. Names of types begin with an **uppercase** letter. Names of types are **nouns** or noun phrases.
  3. Names of relationship begin with a **lowercase** letter. Names of relationships are **verbs** or verb phrases.
* The **size** of graphical elements does **not** signify importance.
  * reducing the visual clutter of crossing lines.
  * removing unnecessary bends in connecting lines.
* **IDEAS foundational types** are generally **not shown** in data group diagrams.

## Support for DoD key processes through DoDAF viewpoints

* The DoDAF groups meta-model concepts that are semantically **related**.
  * Principle data groups are building **blocks** for descriptions behavior and structure.
  * Supporting data groups provide **properties and attributes** for the principle data groups.
* These DoDAF 2.0 data groups **support** both DoDAF **viewpoints** and the DoD key **processes**.
  ![](/assets/data-groups.png)
* The principle data groups are:
  * Performers 
  * Resource Flows
  * Information and Data
  * Rules
  * Capabilities
  * Services
  * Projects
  * Organizational Structures
* The supporting data groups are:
  * Measures
  * Locations
  * Pedigrees



