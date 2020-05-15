# Best practices in research data management and stewardship

The course is made up of seven sessions covering:

* Data management planning
* Data protection in research, requirements and responsibilities originating from GDPR
* Practicalities of data handling
* Reproducible computational analyses
* Exploratory analyses, reproducible manuscripts
* FAIR data principles
* Data publishing and archival

**Teaching Objectives:**

* To remember the research data lifecycle, to reveal data management planning as a form of decision making. Listing key factors that shape data management decisions.
* To learn about software tools that assist data management planning.
* To learn how the GDPR affects research and to reveal researchers' responsibilities when working with human-subject data.
* To learn about the record keeping requirements of the GDPR, and the tools that can be used for record keeping during the course of research.
* To learn about various data transfer channels, their advantages and disadvantages
* To learn how to properly name files and organize research data
* To learn about data integrity and its role in research data management
* To learn how to make computational processing and analysis reproducible.
* ...
* To learn about FAIR data principles and their rationale, to reveal key indicators for FAIR'ness for a dataset.
* To learn how FAIR principles can be applied in data and results publishing on the example of data publishing at FAIRDOMHub.

**Learning Outcomes:**

* Learners can list key decision areas that underlie data management.
* Learners can use the Data Stewardship Wizard to record data management decisions for prospective projects.
* Learners can list requirements for accountable use of human data in research
* Learners can use the Data Information System to keep record of research projects and sensitive human-subject data.
* Learners can setup their own safe working environment
* Learners are able to ingest research data and perform key operations increasing the data integrity
* Learners can use snakemake and conda to structure their computational workflows and make them reproducible.
* ...
* Learners can tell whether or not their current practices on data handling results in FAIR data.
* Learners can publish their data and their results in accordance to FAIR principles
* Learners can use FAIRDOMHub and similar platforms for their future work

## Materials to be explored before attending the course

* Running example for course practicals ([PDF](resources/DM-DP_RunningExample.pdf)), and the paper by [Gérard et.al.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6380961/) which is the actual study that inspired our running example

## Course Programme

### Session 1 Data management planning

* Data Management planning as an intervention
* Research data lifecycle
* Areas of consideration in data management planning
* Data management planning tools
* Practical with the Data Stewardship Wizard (DSW)

### Session 2 Data protection in research

* Brief overview of the GDPR
* Impact of the GDPR on bio-medical research, ethical and legal requirements
* Organisational and technical measures for data protection:
  * policies, training, data protection impact assessments,
  * data classification, encryption, pseudonymisation,
  * record keeping/accountability,
* Practical with the Data Information System (DAISY)

### Session 3 Practicalities of data handling

* Research data transfer
* Optimal file naming and organization
* Management of data integrity
  * README files
  * Checksums
  * Encryption
  * Read-only permission
* Data retention
* Practical on data ingestion

### Session 4 Reproducible computational analyses

* Brief overview of ChIP-seq protocol and analysis
* Introduction to snakemake and conda
* Installation of conda and snakemake in a Linux Virtual Box
* Create snakemake workflow for ChIP-seq analysis:
  * Mapping
  * Peak Calling
  * Generate bigWig files for visualisation
  * Summary rule
* Inspect workflow results
* Exercises and discussion

### Session 5 Exploratory analyses, reproducible manuscripts
* Data and project organization for analysis
* Literate programming 
* Writing manuscripts using RMarkdown
  * Introduction
  * Worked example from Chip-Seq
  * Lessons learned


### Session 6 FAIR data principles

* Understanding FAIR principles
* Incentives for FAIR data
* Achieving FAIR'ness, possible paths
* Group discussions

### Session 7 Data publishing and archival

* Recalling FAIR principles in publishing data and results
* Introduction to FAIRDOMhub as a resource for FAIR data and results publishing
* Practical using FAIRDOMHub for FAIR data and results publishing
