# Chapter 10 symbols and relations catalogue

This document transcribes and catalogues the readable evidence in the uploaded Chapter 10 images. Official wording is kept separate from normalized interpretation. No BPMN concepts, application schemas, renderer rules, cardinalities, or connector semantics have been added beyond the printed evidence.

## 1. Chapter 10 source inventory

| Source image reference | Printed pages visible | Readability and scope |
|---|---:|---|
| `F50FEC8D-4FA5-459E-A1D4-1183882C534A.jpeg` | 230–231 | Page 230 is blank except for the printed page number. Page 231 contains `CHAPTER 10`, `APPENDICES`, `10.1 THE BUSINESS MODELER SUITE`, the suite diagram, and opening prose. |
| `1FC0A4CD-FE9A-4D92-820A-9FAC9EDFCCD8.jpeg` | 232–233 | Continuation of Business Modeler Suite prose, extension-module list, Viewer and Doer descriptions, manufacturing/versioning discussion, and capability list. |
| `DD3BDD75-FD93-4D50-9D3E-AEC9DAD26AAF.jpeg` | 234–235 | `10.2. SYMBOLS, RELATIONSHIPS AND THEIR DEFINITIONS`, `10.2.1. SYMBOLS AND THEIR DEFINITIONS`, symbol table, and definitions for Process, Business object, Requirement, Decision, Position, and Interested Party. |
| `CE2AC3A5-10BA-49B8-BBE1-F70FE2626E6B.jpeg` | 236–237 | Definitions for Organization, Individual, Role, Project, Action, Object, Application, Layout, Notes, Time Object, Location, plus five relation definitions printed at the end of page 237. |
| `9F50DDD2-F6BA-41D9-AD72-7DA1E97E7600.jpeg` | 238–239 | `10.2.2. RELATIONSHIPS AND THEIR DEFINITIONS`, relationship overview figure, and twelve relation definitions. |

### Readable headings and printed page numbers, verbatim

- Printed page `230`
- Printed page `231`: `CHAPTER 10`; `APPENDICES`; `10.1 THE BUSINESS MODELER SUITE`
- Printed page `232`
- Printed page `233`
- Printed page `234`: `10.2. SYMBOLS, RELATIONSHIPS AND THEIR DEFINITIONS`; `10.2.1. SYMBOLS AND THEIR DEFINITIONS`
- Printed page `235`
- Printed page `236`
- Printed page `237`
- Printed page `238`: `10.2.2. RELATIONSHIPS AND THEIR DEFINITIONS`
- Printed page `239`: `We use the following types of relationships:`

### Readable content from printed pages 231–233

#### Printed page 231 — `10.1 THE BUSINESS MODELER SUITE`

> The MBM concept has a support tool called Business Modeler Suite, which offers comprehensive support for the effective development and administration of models.

> Modeler is a user-friendly modeling tool that directly supports the MBM methodology and has been designed to create graphical representations in the form of easily understandable pictures and standardized symbols (icons). This enables us to describe the business from different angles through the use of lucid diagrams and models. You gain fast access to clear, easily understandable models of your business that unambiguously describe the business’s processes, products, division of responsibility and requirements on the business. By using methodology and tools one gains a virtual playing field, where everyone involved in working either operationally or with change management can meet. The tool may be used as an interactive support in group discussions where, for example, the model can be built up on a wall using computer projection, or as a support for a process orientated working method for continual improvement.

The suite figure visibly labels `Business Modeler - Suite` and the major areas `Modeler`, `Viewer`, and `Doer`. Readable module labels include `Business Modeler`, `Business Modeler Pro`, `VMS`, `PRA`, `IT`, `NM`, `bhtml Converter`, `Enterprise Integrator`, `NavKit`, and `Document Manager`.

#### Printed pages 232–233 — suite continuation

> Models come in two versions and can be loaded with the following extension modules;
>
> • VMS (Visual Management System) that simplifies creation of Visual Management systems.
>
> • PRA (Process orientated Risk Analysis) that enables and expedites risk analyses.
>
> • IT (Information Technology) that allows a breakdown of business requirements into IT-solutions.
>
> • NM (Network Models) that enables visualization and analysis of physical networks

> Viewer can generate an easily-accessible HTML-version, so that information can be spread via the company’s intranet. Everyone involved in the work process can therefore gain access to the same information. And everyone gets the opportunity to understand the reality that is comprehensible here and now! Viewer comes in two versions and can be equipped with extra navigational support features

> Doer comprises of certain functions to increase the operational benefits in the business. Located here is a document handler called Document Manager.

> Regardless of whether you are working on the reconstruction of a business process or in normal process management, we recommend the availability and usage of IT-based tools to store information about the business and its processes. The tool is used to map the existing processes of the business, and creates a foundation for process improvement and for identifying potentials for improvements. The tool functions as a relief for over when new functions are introduced, inter alia, to visualize connections and divisions of roles and in creating an overview of the new business.

> Nothing remains static with time, everything changes. Timetables, maps, drawings, designs we need to keep them up-to-date and to archive older versions to be able to compare the old with the new. This is a classic challenge for every manufacturing industry that has their own product development. Aircraft manufacturers have to be able to pull out the drawing for the manufacture of a component that 15 years hence had been involved in a crash. In a similar fashion a pharmaceutical manufacturer has to be able to re-create the substances and test results that they have collected during many years of studies. Product responsibility legislature in different countries have ever-tougher requirements regarding traceability of eventual faults. In a similar way we shall develop, optimize, release and maintain our business models, and in time archive them – and possibly replace them with newer revisions. Accessibility and traceability are key concepts. This is made even more obvious by certification requirements (ISO, DIN, etc.).

> Business Modeler Suite can handle very highly-stated demands regarding:
>
> • Visualization capability.
>
> • Distributed accessibility.
>
> • Group-/workshop support.
>
> • Multi-user functionality.
>
> • Central and distributed databases.
>
> • Modification and linguistic handling.
>
> • Traceability.

## 2. Symbols catalogue

The machine-readable source of record is `data/chapter-10-symbols.json`. It contains **24 records**, including base symbols, explicitly shown alternatives, and both visibly distinct `Stock` triangle orientations. Alternative symbols that lack a separate prose definition are marked for cross-check rather than assigned invented semantics.

| ID | Official name | Printed page | Evidence | Review status | Normalized explanation |
|---|---|---:|---|---|---|
| `process` | Process | 234 | direct-text | reviewed | Repeatable, measurable, customer-focused activity; refinable across levels, with non-refinable processes shown as triangles. |
| `decision` | Decision | 235 | direct-text | reviewed | Process-type item representing a choice among alternatives. |
| `activity` | Activity | 234 | direct-visual | needs-cross-check | Visible Process alternative; exact semantics are not defined here. |
| `operation` | Operation | 234 | direct-visual | needs-cross-check | Visible Process alternative; exact semantics are not defined here. |
| `stock-up` | Stock | 234 | direct-text | reviewed | Upward triangle used for a non-refinable process/store; orientation distinction unresolved. |
| `stock-down` | Stock | 234 | direct-visual | needs-cross-check | Downward triangle; distinct meaning, if any, is unresolved. |
| `business-object` | Business object | 235 | direct-text | reviewed | Refinement/resource item representing a physical object, processed product, information package, or sometimes an abstract entity. |
| `document` | Document | 235 | direct-text | reviewed | Business object format with an asymmetric right corner for a described document. |
| `requirement` | Requirement | 235 | direct-text | reviewed | Specific quality defined for a process, Business object/result, or role. |
| `position` | Position | 235 | direct-text | reviewed | Organizational position relating a specific organization to one or more required roles. |
| `interested-party` | Interested Party | 235 | direct-text | reviewed | Higher-level role for relationships among general groups of organizations and/or individuals. |
| `team` | Team | 234 | direct-text | reviewed | Interested Party alternative with two individuals inside the oval. |
| `organization` | Organization | 236 | direct-text | reviewed | Abstract organizational unit with defined targets and resources. |
| `individual` | Individual | 236 | direct-text | reviewed | A specific person. |
| `role` | Role | 236 | direct-text | reviewed | Abstract competence profile required by processes. |
| `project` | Project | 236 | direct-text | reviewed | One-time undertaking with defined start, finish, target, and approved budget. |
| `action` | Action | 236 | direct-text | reviewed | Detailed subprocess-level bridge between business activities and computerized applications. |
| `object` | Object | 237 | direct-text | reviewed | IT component containing collated data/information and corresponding logic. |
| `application` | Application | 237 | direct-text | reviewed | Information system supporting a process/action. |
| `archive` | Archive | 234 | direct-text | reviewed | Application alternative used when the item is an archive. |
| `layout` | Layout | 237 | direct-text | reviewed | IT interface for roles, actors, or individuals, linked to an Action. |
| `notes` | Notes | 237 | direct-text | reviewed | Annotation for opportunities or problems not naturally specified elsewhere. |
| `time-object` | Time Object | 237 | direct-text | reviewed | Date/time item for process execution or Business object availability. |
| `location` | Location | 237 | direct-text | reviewed | Physical place. |

### Verbatim symbol definitions

#### Process — printed page 234

> A Process is a repetitive activity that may be cross-functional and measurable and that may perform a task with customer focus. The processes are used for many levels of complexity from high, general levels down to lower, more detailed levels. There are certain processes that are not refinable, for example stores, which are visualized as a triangle. The process is named with a verb and a noun that describe what happens, e.g. build cars, bake bread, print document and so on.

#### Business object — printed page 235

> Business object is a refinement or resource object in the form of a physical object or a processed product, or an information package. (It may even sometimes be an abstract entity (see: Need for Adjustment) related to a process). If you need to demonstrate that a document that is described, then there is a new format in the business object that has an asymmetric right corner. The business object is given a noun and often has the addition of an adjective or participle before the name (Frozen meatballs, vegetables delivered, document template).

#### Requirement — printed page 235

> A Requirement in terms of Business Modeler is a specific quality defined for a process, business object (result) or role described by an interested party or organization or process. A requirement is named by indicating its direction (increase / decrease) or level of a specific quality for example improved regularity, reduced waste.

#### Decision — printed page 235

> A Decision is a type of process with a special symbol that shows that a decision of choice has to be made where different alternatives can be described. A decision can be named under a process but one ought to be able to respond with different alternatives such as for example Buy Car: Yes/No, Product is faulty: Stop production/Let it go, Purchase plant: alternative a/b/c.

#### Position — printed page 235

> A Position is a position in an organizational department. A position may comprise one or more roles. The position is the relation between a specific organization and the roles required in that organization. The position is titled with the comprehensive organizational prefix, for example Purchasing manager, Logistics supervisor.

#### Interested Party — printed page 235

> An Interested Party is a higher level of role. The interested party is used to show relationships between general groups of organizations and/or individuals are perceived. If one wants to demonstrate that an individual is an interested party, there is an alternative symbol that resembles an ‘Interested party’ but has two individuals inside it, for example customers. When naming an interested party the central part of the model should be used, for example MBM customers, XXX owner(s).

#### Organization — printed page 236

> An Organization is an abstract unit used to specify a specific organization department with defined targets and resources. The naming of organizations is most often done in accordance with the most important process, for example engine development (avoid numerals).

#### Individual — printed page 236

> An Individual is a person – a specific individual. There are icons for men and women. When naming individuals use real names, not codes!

#### Role — printed page 236

> A Role is an abstract composition of competence profile as required by the different processes. Roles may be collected to cover a position. A role is named in conjunction with the competency profile as defined by the process, for example system development, project manager, IT expert, catalyst.

#### Project — printed page 236

> A Project is an abstract object to show and describe a specific project. A project is something one does once only and that has a defined start and a defined finish and a measurable target and an approved budget. The project is named as per the organization, often with a verb and a noun, for example Project XXX, Recovery of waste-heat.

#### Action — printed page 236

> An Action is a detailed level of a sub-process that describes the common denominator between the business activities and computerized applications, i.e. the utilization of objects and methods, or the use of pre-existing IT methods through messaging. Actions are described in both process models and IT-models. The name must reflect the required action. Use a verb plus the object that is involved in the action. A strict standard is recommended as the actions name will probably appear as menu choices in later implemented application such as order, new user, update customer.

#### Object — printed page 237

> An Object is an IT component that contains a collection of independent, well-defined collated data and corresponding logic, or ‘information’. The logic is divided into methods. A method is also a well-defined logical share and an object. The logic will indicate working with the stored information. A method may also call in other methods through objects or can communicate through ‘messaging’. An object is activated by the issue of an order which addresses requirements. An order can be made from an action or an object. When naming an object it must be the same as the agreed name of the business object. An object shall have the same conventions as for actions, for example New XXX, update XXX, Remove XXX.

#### Application — printed page 237

> An Application is an information system that supports a process/action. Most often used in process and IT-models. There is an extra symbol here that shows if it is an archive that one is talking about. Naming in accordance with traditional usage within the organization.

#### Layout — printed page 237

> A Layout is an IT-interface designed for specific roles, actors or individuals. The layout describes the content of logical and navigational patterns. The layout is then linked to the desired action. The layout may be created or serve as a template once it has been implemented in the desired IT environment. (Graphical User Interface or GUI, telephony with synthetic voices, WEB/Internet, etc.) Naming: A Layout specifies a GUI window. Use a name suited to the user’s interactive formula.

#### Notes — printed page 237

> Notes is/are an abstract object(s) for noting general or specific opportunities or problems that are of interest and that are not naturally specified elsewhere. Named after the title of the identified opportunity or problem.

#### Time Object — printed page 237

> Time Object is used to show date/time when processes and activities are to be executed, or when business objects are to be accessible/available.

#### Location — printed page 237

> Location is a physical place.

The visual-only or variant records `Activity`, `Operation`, the two `Stock` orientations, `Document`, `Team`, and `Archive` are catalogued in the JSON file with direct page and image provenance. No separate prose definition was invented where none was printed.

## 3. Relations catalogue

The machine-readable source of record is `data/chapter-10-relations.json`. It contains **17 relations**. Connector meaning is recorded as dependent on connected item types and context. Cardinality is `unresolved` for every relation because no explicit cardinality rules are printed in the uploaded pages.

| ID | Official name | Printed page | Source model-item type → target model-item type | Evidence |
|---|---|---:|---|---|
| `addresses` | Addresses | 239 | Requirement/Notes/Time → Process or result | direct-text |
| `consists-of` | Consists of | 239 | Whole → constituent part | direct-text |
| `controls` | Controls | 239 | Prerequisite Business Object → Process | direct-text |
| `corresponds-with` | Corresponds with | 239 | Model item → similar/mirrored model item | direct-text |
| `defines` | Defines | 239 | Definer → Requirement or problem | direct-text |
| `flow` | Flow | 239 | Prerequisite → Process → refinement result | direct-text |
| `handles` | Handles | 239 | Organization → product | direct-text |
| `interrelates-with` | Interrelates with | 239 | Model item ↔ model item | direct-text |
| `is-a-part-of` | Is a part of | 239 | Part → whole | direct-text |
| `is-a-kind-of` | Is a kind of | 239 | Specialized kind → general category | direct-text |
| `is-specialized-in` | Is specialized in | 239 | General category → specialized kind | direct-text |
| `is-used-by` | Is used by | 239 | Supporting prerequisite Business Object → Process | direct-text |
| `is-situated-at` | Is situated at | 237 | Object/model item → Location | direct-text |
| `is-followed-by` | Is followed by | 237 | Process → Process | direct-text |
| `performs` | Performs | 237 | Machine/resource/competence → Process task | direct-text |
| `secondary-flow` | Secondary flow | 237 | Process task → side-effect Business Object result | direct-text |
| `verification-flow` | Verification Flow | 237 | Process context → verifying-documentation Business Object result | direct-text |

### Verbatim relation definitions

#### Printed page 237

> Is situated at used to describe that an object is located in a specific place (Location).

> Is followed by used when we – by way of exception – describe how processes are laid in sequence without any intermediate result (Business Objects).

> Performs used to describe how a machine, resource or competence performs tasks in a process.

> Secondary flow used in our flows where a result (Business Object) is a side effect of a task in the process in question.

> Verification Flow used in our flows where a result (Business Object) creates verifying documentation for the process in question.

#### Printed page 239 — `We use the following types of relationships:`

> Addresses used when a requirement is defined and is to be pointed to a process or a result. This relation may also be valid for example in a defined problem (Notes) or a point in time (Time).

> Consists of used when we need to describe an organizational structure, product, process etc. (Inverse is ‘Is a part of’).

> Controls used in our flows when a prerequisite (Business Object) is directional for the process in question.

> Corresponds with used when we have two similar symbols that in fact are mirror image of each other (a result can correspond with a Class in a Class diagram).

> Defines used to describe, for example, who defines a requirement or problem.

> Flow used to describe the refinement flow and is drawn from prerequisites to the process and onwards to the process’s refinement result.

> Handles used for example to describe that a given Organization ‘Handles’ a certain product.

> Interrelates with used to describe an unspecified collaboration between two parts of our objects. This can be valid between two different interested parties or between two different processes, for example.

> Is a part of used to describe ‘Is a part of’ structure (see the inverse, ‘Consists of’).

> Is a kind of used to describe category or relationship. A car is for example a type of vehicle. A fast order is a type of order. (Refer to the inverse ‘Is specialized in’).

> Is specialized in used for describing categories or relationships. A vehicle can be specialized in a car. An order has its specialization in a fast order. (Compare the inverse ‘Is a kind of’).

> Is used by used in our flows when a prerequisite (Business Object) has a supporting role for the process in question.

## 4. Explicit modeling rules

1. A Process is named with a verb and a noun.
2. Processes may be modeled at multiple levels, from high/general to lower/more detailed.
3. A process that is not refinable, for example a store, is visualized as a triangle.
4. A Business object is named with a noun and often has an adjective or participle before the name.
5. The asymmetric-right-corner Business object format is used for a described document.
6. A Requirement is named by direction or level of a quality, such as increase/decrease or improved/reduced.
7. An Organization is most often named according to its most important process; numerals are to be avoided.
8. An Individual is named with a real name, not a code.
9. A Role is named in conjunction with the competency profile defined by the process.
10. A Project is one-time and has a defined start, defined finish, measurable target, and approved budget.
11. An Action name uses a verb plus the object involved.
12. An Object uses the agreed Business object name and the same conventions as Actions.
13. A Position may comprise one or more Roles and connects a specific Organization with required Roles.
14. `Is followed by` is exceptional and is used only for direct Process sequence without an intermediate Business Object.
15. `Flow` runs from prerequisites to a Process and onward to the Process’s refinement result.
16. `Controls` and `Is used by` both concern prerequisite Business Objects, but distinguish directional and supporting roles respectively.
17. `Secondary flow` concerns a result that is a side effect.
18. `Verification Flow` concerns a result that creates verifying documentation.
19. `Consists of` / `Is a part of` and `Is specialized in` / `Is a kind of` are explicitly identified as inverse pairs.

## 5. Context-dependent meanings

- A Business Object changes role by context: prerequisite, refinement result, supporting prerequisite, directional prerequisite, side-effect result, or verifying-documentation result.
- A connector cannot be assigned one universal meaning solely from its line. The printed definitions tie meaning to connected item types and to whether the relation occurs in a flow, organizational structure, categorization, collaboration, or location context.
- `Addresses` may originate from a Requirement, and the text also allows examples involving Notes or Time.
- `Interrelates with` intentionally leaves the collaboration unspecified.
- `Corresponds with` concerns mirrored or similar representations, including the worked example of a result corresponding with a Class in a Class diagram.
- `Performs` can originate from a machine, resource, or competence.

## 6. Ambiguities and unresolved items

- The exact line-end shapes, arrowheads, and visual differences among all relation connectors in the printed page 238 overview are too small to transcribe with full confidence from the uploaded photograph. The relation names and prose definitions are readable; visual forms are therefore conservatively described and marked for visual cross-check.
- No explicit cardinality is printed for any relation.
- The precise distinction between the upward and downward `Stock` triangles is not stated.
- `Activity` and `Operation` are visible alternatives in the symbol table but have no separate readable prose definitions in these images.
- `Team` and `Archive` are visible table labels; their semantics are taken only from the adjacent Interested Party and Application prose, respectively.
- The Object paragraph uses both an agreed Business object name and action-style examples (`New XXX`, `update XXX`, `Remove XXX`); no attempt has been made to resolve or rewrite this tension.
- The phrase in the Viewer/Doer prose on printed page 232, “The tool functions as a relief for over when new functions are introduced,” appears grammatically irregular in print and is retained rather than silently corrected.
- The page 238 overview contains small labels and connector details that are not all independently legible at the photograph’s resolution; no guessed labels were added.

## 7. Cross-check targets for Chapters 6–9

- Confirm whether Chapters 6–9 define distinct meanings for the two `Stock` triangle orientations.
- Confirm whether `Activity` and `Operation` receive formal definitions or restrictions.
- Cross-check flow-line visual styles for `Flow`, `Secondary flow`, and `Verification Flow`.
- Cross-check direction and endpoint forms for inverse relation pairs.
- Confirm whether Position, Team, Document, and Archive are formal subtypes, visual variants, or context-specific alternatives.
- Confirm naming conventions and examples for Object versus Action.
- Cross-check whether any chapter states cardinality or validation rules; none are present in the uploaded Chapter 10 evidence.

## 8. Completeness and review checklist

- [x] All six uploaded Chapter 10 images were reviewed.
- [x] Printed pages 230–239 visible in the uploads were inventoried.
- [x] Every readable heading was preserved verbatim.
- [x] Every visible symbol in the 10.2.1 table and readable prose was captured.
- [x] Every readable relation definition on pages 237 and 239 was captured.
- [x] Every record contains printed-page and source-image provenance.
- [x] Direct evidence and interpretation are stored separately.
- [x] Only the permitted evidence classifications are used.
- [x] No BPMN terminology or external modeling assumptions were introduced.
- [x] No application schemas or renderer rules were created.
- [ ] Page 238 connector endpoint forms should be checked against a higher-resolution scan.
- [ ] Alternative-symbol semantics should be cross-checked against Chapters 6–9.
