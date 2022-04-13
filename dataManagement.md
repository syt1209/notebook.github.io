### Best Practices for Biomedical Research Data Management

[Harvard Medical School Course](https://www.canvas.net/browse/harvard-medical/courses/biomed-research-data-mgmt)

**Main takeways**
- Types of research data.
- The research lifecycle.
- The data lifecycle.
- Common data formats and file types that facilitate long-term access to data.
- Significance of observing file naming conventions and version control.
- Documentation needed to facilitate accessibility and reproducibility of findings.
- The documentation needed to facilitate accessibility and reproducibility of research findings.
- The intent of data policies
- Major government funding agencies currently requiring data management plans.
- Basic principles that govern both human subject research and use of animals for research.
- Tools available to foster collaboration and sharing of resources.
- Importance of managing and sharing research data.
- Characteristics of long-term storage, curation, and preservation of research data.

#### Research Data Management

* **Research data**– the recorded factual material commonly accepted in the scientific community as necessary to validate research findings.
* **Research data management** – storage, access, and preservation of data produced from a given investigation.
* **Data** **for reproducibility**= **appraising data** (underlying published results) + **metadata/documentation** (contextual details about the data sets) + **code/scripts** (associated with analyses and results)
* **Lifecycle: <span style="text-decoration:underline;">Plan  → Collect → Assure → Describe → Preserve → Discover → Integrate → Analyze → Plan</span>**
    * **Plan**
        * File naming convention
        * Standard way for structuring folder directories
        * Community standard for naming and describing data elements
        * Reporting standards and minimum information standards to record sufficient contextual information
        * Optimal file formats for storage and archiving, and formats optimal for dissemination, access, use, and reuse
        * Explore data sharing repositories early 
    * **Describe**
        * Controlled vocabulary for naming data elements
        * Standards for defining values
        * Data dictionaries
        * Readme files
        * Codebooks
        * Minimum information and reporting standards
    * **Preserve access (repositories and data centers)**
        * Disciplinary repositories
        * Repositories built around methods
        * Federally-funded repositories and data centers
        * Institutional repositories
        * Open repositories
        * Data enclave options for sensitive data sets
    * **Discover (publishing and citing data)**
        * Obtaining digital object identifiers (DOIs) for data sets
        * Other identifiers: accession number (NCBI), clinical trial registry numbers (NCT)
        * Citing data sets and their location in publications and presentations along with funding source, grant proposals, etc.
        * Assigning a license defining terms of use
        * Ensuring sensitive data sets meet IRB standards for consent and de-identification
        * Deposit after appropriate embargoing for publication, intellectual property, or security
* **Data policies**
    * Data ownership and intellectual property
    * Data management and stewardship responsibilities
    * Public access, data sharing, and dissemination
    * Retention

    [Browse Data Sharing Requirements by Federal Agency](https://datasharing.sparcopen.org)
* **Data types**
    * **_Raw data_**: What is being measured or observed? This is the data that is being generated during the research project. 
    * **_Processed data_**: How can the raw data be made useful/manipulable?
    * **_Analyzed data_**: What does the data tell us? Is it significant? How so?
    * **_Finalized/published data_**: How does the data support your research question?
    * **_Derived or compiled data_** is reproducible but expensive. Examples include 'Data mining', 'Compiled databases', and '3D models'.
    * **_Observational data_** is captured in real time, usually irreplaceable (sensor readings, telescope images, sample data)
    * **_Experimental data_** is obtained from lab equipment, often reproducible but can be expensive (gene sequences, chromatograms)
    * **_Simulation data_** is generated from test models where models and metadata are more important than output data (climate models)

* **Trade secrets** are not considered research data because they must be held confidential by a researcher until they are published, and are protected under law.

* **Medical information** or other information that could be used to identify a particular person in a research study are not considered research data because if disclosed, it would constitute a clearly unwarranted invasion of personal privacy.

* **Data Management Plans (DMPs)** cover all stages of the data life cycle.

* **Spreadsheets and databases** relate to data discovery, collection and organization.

* **Data types and laboratory methods** should be documented for data quality assurance and control.

* **Policies** should be consulted when addressing data preservation and dissemination plans for data sharing.

\
&nbsp;

#### The Research Lifecycle

* **Preferred data formats**
    * _non-proprietary (open)_
    * _unencrypted and uncompressed_

* **Data/file types better for long-term preservation**
    * _Tabular data: CSV_
    * _Moving images: MOV, MPEG_
    * _Audio: WAVE, MP3_
    * _Images: TIFF, JEPG2000 (.jp2)_
    * _Text: PDF/A, ASCII_

* **ISO standards for dates**: yyyymmdd

* **Metadata**: 
    * _Who_ | Who collected the data? Who/what were the subjects under study?
    * _What_ | What data was collected, and for what purpose? What is the content and structure of the data?
    * _Where_ | Where was this data collected? What were the experimental conditions that produced it?
    * _When_ | When was the data collected? Is the data part of a series, or ongoing experiment?
    * _Why_ | Why was this experiment performed? How does it relate to your question?

##### Research Workflow

##### Research Data Files

---------------------------------------
###### Readings & Resources
* [Ten Simple Rules for Creating a Good Data Management Plan](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004525)
* [Research Data Management: A Primer Publication of the National Information Standards Organization](https://groups.niso.org/higherlogic/ws/public/download/15375/PrimerRDM-2015-0727.pdf)
* [Data Management Best Practices](https://old.dataone.org/best-practices)
* [Primer on Data Management: What you always wanted to know but were afraid to ask](https://old.dataone.org/sites/all/documents/DataONE_BP_Primer_020212.pdf)
* [Nine simple ways to make it easier to (re)use your data](https://ojs.library.queensu.ca/index.php/IEE/article/view/4608)
* [Crowdsourced spreadsheet detailing features of agency public access and data sharing policies](https://docs.google.com/spreadsheets/d/1PYOhBh6bglh6BkQFlpvNLOwlpzvQyguWAG8AkQMtU0s/edit#gid=985495879)
* [Best Practice Data Life Cycle Approaches for the Life Sciences](https://www.biorxiv.org/content/10.1101/167619v1)
* [Open Data Handbook. File Formats](http://opendatahandbook.org/guide/en/appendices/file-formats/)
* [UK Data Service. Format your data](https://ukdataservice.ac.uk/learning-hub/research-data-management/#format-your-data)
* [A Quick Introduction to Version Control with Git and GitHub](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004668)
* [Review of Data Management Lifecycle Models](https://researchportal.bath.ac.uk/en/publications/review-of-data-management-lifecycle-models)
* [OME. Bio-formats](https://www.openmicroscopy.org/bio-formats/)
* [PRONOM. Online Registry of Technical Information](http://www.nationalarchives.gov.uk/pronom/)