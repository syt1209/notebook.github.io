### Best Practices for Biomedical Research Data Management

[Harvard Medical School Course](https://www.canvas.net/browse/harvard-medical/courses/biomed-research-data-mgmt) | [Home](./index.md)

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
    * _Who_   | Who collected the data? Who/what were the subjects under study?
    * _What_  | What data was collected, and for what purpose? What is the content and structure of the data?
    * _Where_ | Where was this data collected? What were the experimental conditions that produced it?
    * _When_  | When was the data collected? Is the data part of a series, or ongoing experiment?
    * _Why_   | Why was this experiment performed? How does it relate to your question?

##### Research Workflow

* **Data workflow**: Creating Data --> Processing Data --> Preserving Data --> Sharing Data --> Reusing Data
    
    **1. Creating Data**
    * Design expriment
        * Methods
        * Sample login
    * Collect raw data
        * Experiment
        * Observation
        * Measurements
    * Capture metadata

    **2. Processing Data**
    * Interpret data
        * Tables
        * Charts
        * Graphs
        * Drawings
        * Pictures
    * Review data
        * PI
        * Collaborators
        * Regulators
    * Prepare manuscript
    
    **3. Preserving Data**
    * Migrate data
        * Format
    * Backup/store data
        * Local
        * Network
        * Repository
    * Create metadata, documentation
    * File/folder organizational scheme
        * Concise, meaningful
        * Consistent
        * Versioning
    * Sharing Data
        * Share w/ collaborators
        * Promote data
        * Control access
            * Secure method
            * DOI
    * Reusing Data
        * New research
        * Teach/learn
        * Follow-up research

##### Tips on folder/file organization

 * **Organize folders by meaningful hierarchical categories** such as primary/secondary/tertiary or subject/collection method/time

 * **Project or experiment name or acronym**: use meaningful abbreviations

 * **Researcher name/initials**: using a last name is the standard reference for retrieving records and ensures that files are sorted in proper alphabetical order

 * **Type of data**: text, images, sound files, etc

 * **Version number of file**: a “V” helps denote that the element pertains to a version number

 * **Including the three-letter file extension for application-specific files** aids in setting up calling or associated programs with your operating system

 * **Use a sequential numbering system** leading with zeros for clarity and to make sure files sort in sequential order. For example, use "001, 002, ...010, 011 ... 100, 101, etc." instead of "1, 2, ...10, 11 ... 100, 101, etc"

 * **Include date or date range of experiment** using consistent date recording: best practice for date designations is YYYYMMDD or YYMMDD. This format makes sure all of your files stay in chronological order, even over the span of many years

 * **Try not to make file names too long**, since long file names do not work well with all types of software

 * **Avoid proprietary formats**: DOC and DOCX Word documents are in proprietary formats and should be stored in another location as well and should have back up revisions as TXT or RTF files

 * **Understand image file formats**: JPG files are okay but TIF files are preferred for reuse. TIF is a lossless file format, so nothing is lost when the file is saved and compressed, and they have the capacity to support layers

 * **Do not use spaces, periods or other special characters**. Other options include: Underscores (file_name.xxx), Dashes (file-name.xxx), No separation (filename.xxx); Camel case (FileName.xxx)

 * **Include in the directory a readme.txt file** that explains your naming format along with any abbreviations or codes you have used.

#### Metadata - Contextual details

* **What is metadata?**

    _Structured information that describes, explains, locates, or otherwise makes it easier to retrieve, use, or manage an information resource._

* **Why is metadata important?**

    _Find data, use the data, help others to find and use data, future use..._

* **Types of metadata**

    _**Descriptive metadata** describes the object or data and gives the basic facts_

    _**Structural metadata** describes the structure of an object including its components and how they are related_

    _**Administrative metadata** includes information about the management of the project_

* **Metadata standards**

    [List of Metadata Standards](https://www.dcc.ac.uk/guidance/standards/metadata/list)

* **Best practices for metadata creation**

    * Identify formats, terminologies and guidelines
        
        * Conceptual model: define the structure and interrelation of information and transmission format
        * Controlled vocabularies: lists of predefined terms that ensure consistency of use. A list of predefined terms specific to a single discipline
        * Technical standards: ensure that units such as date and time, etc. are entered in consistent formats
        * Minimum information reporting: report the same essential information
    * Identify data elements (dates, funders, methodologies, files)

    **_Metadata_** includes:
        - Types/formats of measures  
        - Data Dictionary with file naming conventions  
        - File formats and size  
        - Statistical programs used for analysis  
        - Names and models of instrumentation  
        - Conditions under which data were collected  
        - Descriptive data associated with ID of participant  
        - Sharing and reuse policy  
        - Access and rights policy  

    **_Possible standards_**:  
    - **Dublin Core**: A basic, domain-agnostic standard which can be easily understood and implemented, and as such is one of the best known and most widely used metadata standards.  
    - **Darwin Core**: The Darwin Core is a metadata specification for information about the geographic occurrence of species and the existence of specimens in collections.
    - **Observ-OM**: Used to integrate and compare observation data across experimental projects, disease databases, and clinical biobanks.

    ##### Key concepts
    - **Ontology**: A set of concepts and categories in a subject area that shows their properties and the relations between them.  
    - **Taxonomy**: A hierarchy that uses the “is a” relation  
    - **Controlled Vocabulary**: An enumeration of terms defined to be shared and reused
    - **Glossary**: List of terms with definitions and explanations in natural language
    - **Classification**: A set of categories in which objects are grouped into
    - **Folksonomy**: A collection of terms (tags) to enhance categorization
    - **FAIR**
        - **Findable**: metadata should be uniquely and persistently identifiable  
        - **Accessible**: identifiers should provide a mechanism for metadata access (license, authentication)  
        - **Interoperable**: metadata should be machine-accessible & use standard vocabulary  
        - **Reusable**: there should be sufficient metadata to integrate like with like and allow component data objects to be cited post-integration  

#### Data Storage and Security


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
* [Data Management Rubric for Video Data in Organismal Biology](https://academic.oup.com/icb/article/57/1/33/3964476)
* [Lurking in the Lab: Analysis of Data from Molecular Biology Laboratory Instruments](https://escholarship.umassmed.edu/jeslib/vol1/iss3/5/)
* [The Importance of Metadata Standards](https://uop.whoi.edu/techdocs/presentations/MMI_Guides.pdf)
* [Version control and authenticity](https://ukdataservice.ac.uk/learning-hub/research-data-management/format-your-data/versioning/)
* [Data Documentation Initiative: Toward a Standard for the Social Sciences](http://www.ijdc.net/article/view/66)
* [Big data, little data, no data: Scholarship in the networked world](https://mitpress.mit.edu/books/big-data-little-data-no-data)