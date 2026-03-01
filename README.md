# Open-sourced Off-the-Shelf Ion Exchange Membrane

**Low-Cost Homogeneous Ion Exchange Membrane Formed from Off-the-Shelf Precursors and Manufacturing Process Thereof**

## Abstract

This repository documents an experimental low-cost ion-exchange membrane (IEM) fabrication approach based on off-the-shelf precursor materials, along with supporting process concepts, demonstrations, and project context for electrochemical recovery systems. The central objective is to reduce the cost barrier associated with ion-selective membranes while preserving sufficient ionic selectivity for practical electrochemical separation, treatment, and refining applications.

The repository should be interpreted as a **research-style open documentation archive** rather than a finished industrial package. It contains process descriptions, supporting media, demonstration materials, and conceptual system documentation intended to make the underlying ideas reviewable, reproducible, and critiqueable.

## Research Objective

Commercial ion-exchange membranes are often a critical cost, sourcing, and durability constraint in electrodialysis, electrochemical treatment, and selective ion-transport systems. This project investigates whether membrane-like ion-selective behavior can be achieved using low-cost, widely available materials and fabrication methods that are accessible outside specialized membrane manufacturing supply chains.

The broader project context positions this membrane work within a larger electrochemical framework that includes:

- metal-bearing stream treatment,
- in-loop reagent regeneration,
- selective transport of ionic species,
- concentration and recovery of dissolved values,
- and reduced dependence on repeated reagent consumption.

## Scope of This Repository

This repository is primarily **document-centric** and serves four functions:

1. **Record the membrane concept** and associated fabrication/process documentation.
2. **Aggregate demonstrations** that illustrate intended membrane behavior.
3. **Provide text-first access** to key video material through curated transcript files.
4. **Preserve public technical context** around the broader Rowow / SEM TECH project.

This repository does **not** claim to provide complete validation of membrane lifetime, transport efficiency, fouling resistance, scale-up economics, or industrial readiness.

## Official Project Links

- **Project website:** <https://rowow.net/>
- **About / project background:** <https://rowow.net/about/>
- **Methods / broader process framing:** <https://rowow.net/methods/>
- **YouTube channel:** <https://www.youtube.com/@Rowow>
- **Fundraiser / current project status:** <https://www.gofundme.com/SEMTECH>

## Recommended Reading Order

### 1. Core video path

The following videos provide the most direct overview of the membrane concept and its demonstrations:

1. [DIY Low-Cost Ion Exchange Membrane: Full Build Guide & Open Source Dedication](https://www.youtube.com/watch?v=c3tNXDlgE2M)
2. [Ion exchange membranes and their potential](https://www.youtube.com/watch?v=HX8M6vGijfg)
3. [Diy open source Cation exchange membrane test proof](https://www.youtube.com/watch?v=X2MjqFa_ry4)
4. [Diy open source ANION exchange membrane test proof](https://www.youtube.com/watch?v=z5NOLVb5-s0)

### 2. Text-first review path

To support reproducible review and easier citation, the repository includes local markdown mirrors of the most relevant videos:

- [`video_data/readme.md`](video_data/readme.md)
- [`video_data/c3tNXDlgE2M.md`](video_data/c3tNXDlgE2M.md)
- [`video_data/HX8M6vGijfg.md`](video_data/HX8M6vGijfg.md)
- [`video_data/X2MjqFa_ry4.md`](video_data/X2MjqFa_ry4.md)
- [`video_data/z5NOLVb5-s0.md`](video_data/z5NOLVb5-s0.md)

These files are intended to make the project easier to inspect without relying exclusively on the YouTube interface. Each file contains structured metadata, the original description, and a cleaned transcript.

## Repository Contents

### Primary technical documents

Current top-level repository documents include:

- [`Diagram.pdf`](Diagram.pdf)
- [`Flow Chart.docx`](Flow%20Chart.docx)
- [`Patent.docx`](Patent.docx)
- [`patent.pdf`](patent.pdf)
- [`REDACTED RowowLLC_TechnicalVolume.pdf`](REDACTED%20RowowLLC_TechnicalVolume.pdf)
- [`SEM TECH.pdf`](SEM%20TECH.pdf)
- [`SEM TECH PRESENTATION.pdf`](SEM%20TECH%20PRESENTATION.pdf)

### Video-derived technical notes

The `video_data/` directory functions as a lightweight literature/observation layer for the project’s public media. It provides stable, searchable text references for the videos most relevant to the membrane concept.

## Technical Framing

### Central hypothesis

The working hypothesis of this repository is that a low-cost membrane fabricated from commonly available materials can exhibit ion-selective behavior sufficient to support electrochemical transport and separation functions that are traditionally associated with more expensive commercial membranes.

### Project-described membrane concept

Across the project’s public materials, the membrane is described as a low-cost ion-exchange membrane formed from off-the-shelf precursors. The video materials in this repository present a fabrication narrative based on accessible ingredients and non-specialized preparation methods, with the stated goal of making membrane experimentation more available to independent builders and smaller-scale researchers.

### Intended application domain

The broader project context presented on the Rowow site places the membrane within a larger electrochemical system architecture for:

- continuous treatment of contaminated or value-bearing solutions,
- continuous leaching with in-loop chemistry regeneration,
- and continuous refining through selective electrochemical transport and deposition.

In practical terms, the intended application domain includes metal-bearing waste streams, mining and tailings-related contexts, e-waste-associated chemistry, and other dissolved-ion systems where reagent reuse and selective transport matter.

## Evidence Types in This Repository

The materials in this repository should be interpreted according to evidence class rather than treated as a single validation tier.

### 1. Process and concept documents

The PDFs and DOCX files provide project documentation, process framing, diagrams, and supporting technical narrative.

### 2. Build-level media

The full build guide video and its corresponding `video_data` file provide the most direct public-facing explanation of the membrane concept, fabrication path, and project intent.

### 3. Demonstration-level evidence

The cation and anion proof videos present simple demonstrations intended to show ion-selective behavior. These are useful as **behavioral demonstrations**, but they are not equivalent to a full transport-characterization study.

### 4. Conceptual / systems-level framing

The overview video and the Rowow site frame the membrane as part of a larger systems concept. These sources are best read as project positioning, intended use, and design direction rather than as standalone validation.

## What Is Demonstrated vs. What Is Not Yet Established

### Demonstrated at a basic level

Based on the material curated here, the repository documents:

- a publicly described low-cost membrane fabrication concept,
- a set of demonstration videos intended to show cation and anion selectivity,
- a broader electrochemical process narrative linking membrane transport to recovery/treatment applications,
- and an open-publication approach intended to make the project reviewable and reproducible.

### Not established by this repository alone

This repository does not, by itself, establish:

- long-term membrane lifetime,
- quantified ion-transport efficiency,
- selectivity under multi-ion industrial feed conditions,
- fouling resistance,
- oxidative/acid stability across extended operating periods,
- crossover under continuous duty,
- current-efficiency benchmarks,
- energy-per-unit-recovery metrics,
- or commercial-scale process economics.

Readers interested in research, replication, or deployment should treat these as open technical questions unless independently validated.

## Broader Project Context (Rowow / SEM TECH)

The membrane concept is presented as a subsystem within a broader electrochemical platform. The Rowow site describes three major process categories:

- **Continuous Treatment** — electrochemical treatment of contaminated or metal-bearing liquids to reduce environmental burden while recovering value where possible.
- **Continuous Leaching** — regeneration of active solution chemistry in-loop while maintaining dissolution and concentration pathways.
- **Continuous Refining** — selective transfer and deposition to upgrade or separate target metals from mixed feeds or intermediate products.

Within that framework, low-cost membranes are positioned as enabling components that may reduce cost barriers for wider experimentation and deployment.

## Intended Audience

This repository is most useful for:

- independent electrochemistry experimenters,
- applied researchers exploring low-cost membrane alternatives,
- process developers interested in closed-loop recovery concepts,
- critics evaluating the plausibility of the membrane/process claims,
- and collaborators who want a text-accessible entry point into the project.

## Experimental Status

This project should be regarded as **active, public, and experimental**.

The repository documents a concept, supporting materials, and demonstrations, but it should not be interpreted as a completed validation package. The linked fundraiser further indicates that scale-up testing and prototype validation remain ongoing goals.

## Safety and Research Use Disclaimer

Electrochemical and chemical process work can involve:

- corrosive acids and bases,
- oxidizers and reactive intermediates,
- hazardous dissolved metals,
- gas generation,
- thermal events,
- electrical hazards,
- and waste-handling obligations.

Before replicating any process or experiment described here:

- verify chemical compatibility of all construction materials,
- confirm containment, ventilation, and PPE,
- account for gas evolution and electrical fault conditions,
- evaluate local legal, environmental, and disposal requirements,
- and assume that scaling changes system behavior.

Nothing in this repository constitutes certified engineering guidance, environmental compliance guidance, legal advice, or process safety certification.

## Open Documentation / License

This repository is published under the **CC0-1.0** license.

The project is presented as an open-publication effort intended to place the membrane concept and related documentation into the public domain for review, experimentation, criticism, and possible extension by others.

## Suggested Next Steps for Reviewers

If you are evaluating this repository technically, a useful review sequence is:

1. Read the `video_data` index and the full build-guide transcript mirror.
2. Compare the build-guide claims to the cation/anion demonstration scope.
3. Review the Methods page for the larger process architecture.
4. Inspect the patent/process documents for explicit construction and system details.
5. Separate demonstration-level evidence from durability and scale claims.
6. Document unresolved questions before attempting replication.

---

Contributions, replications, critique, and independent measurements are likely to be most valuable when they clearly distinguish between:

- **observed behavior**,
- **inferred mechanism**,
- **project-stated goals**, and
- **unresolved technical assumptions**.
