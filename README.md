# Tutorial on Web Table Extraction, Retrieval and Augmentation

Tables are a practical and useful tool in many application scenarios. Tables can be effectively utilized for collecting and organizing information from multiple sources.  With the help of additional operations, such as sorting, filtering, and joins, this information can be turned into knowledge and, ultimately, can be used to support decision-making.  Thanks to their convenience and utility, a large number of tables are being produced and are made available on the Web.  These tables represent a valuable resource and have been a focus of research for over two decades now.  In this tutorial, we provide a systematic overview of this body of research.

Tables on the web, referred to as *web tables* henceforth, differ from traditional tables (that is, tables in relational databases and tables created in spreadsheet programs) in a number of ways.  First, web tables are embedded in webpages.  There is a lot of contextual information, such as the embedding page's title and link structure, the surrounding text, etc. that can be utilized. Second, web tables are rather heterogeneous regarding their quality, organization, and content.  For example, tables on the Web are often used for layout and navigation purposes.

Among the different table types, *relational tables* (also referred to as *genuine tables*) are of special interest. These describe a set of entities (such as people, organizations, locations, etc.) along with their attributes.  Relational tables are considered to be of high-quality, because of the relational knowledge contained in them.  However, unlike from tables in relational databases, these relationships are not made explicit in web tables; uncovering them is one of the main research challenges. The uncovered semantics can be leveraged in various applications, including table search, question answering, knowledge base augmentation, and table completion.
For each of these tasks we identify seminal work, describe the key ideas behind the proposed approaches, discuss relevant resources, and point out interdependencies among the different tasks.


## Outline

1. Introduction [[slides](slides/part-1.pdf)]
  - Motivating scenarios
  - Table types
  - Table extraction and table corpora
2. Table interpretation [[slides](slides/part-2.pdf)]
  - Column type identification
  - Entity linking in tables
  - Relation extraction
3. Knowledge base augmentation [[slides](slides/part-3.pdf)]
  - Tables for knowledge exploration
  - Knowledge base augmentation and construction
4. Table search [[slides](slides/part-4.pdf)]
  - Keyword query search
  - Search by table
5. Table augmentation [[slides](slides/part-5.pdf)]
  - Row extension
  - Column extension
  - Data completion
6. Question answering on tables, other tasks, and future directions [[slides](slides/part-6.pdf)]
  - QA using a single table and multiple tables
  - Other tasks (table and title generation)
  - Future directions

[Complete bibliography (BibTeX)](references.bib)


## Presenters

**Shuo Zhang** is a final-year PhD student at the University of Stavanger, under the supervision of Prof. Krisztian Balog. He is currently visiting Prof. Jamie Callan at Carnegie Mellon University, working as a short-term visiting scholar. Zhang's main research interests include information retrieval and text mining. His PhD research is concerned with developing intelligent search technology for tabular data. He has studied the problems of table retrieval and generation extensively and published about it at SIGIR'17, SIGIR'18, and WWW'18. 

**Krisztian Balog** is a full professor at the University of Stavanger, heading the Information Access and Interaction (IAI) group. He is currently on a sabbatical, working as a Staff Visiting Faculty Researcher at Google, London, UK. Balog's general research interests lie in the use and development of information retrieval, information extraction, and machine learning techniques for intelligent information access tasks. His current research concerns entity-oriented and semantic search, and novel evaluation methodologies. He has authored over 100 peer-reviewed publications and has recently published the (open access) book Entity-Oriented Search (Springer, 2018). In recognition of his significant and influential contributions to the area of semantic search and evaluation methodology, Balog was recipient of the Karen Spärck Jones Award in 2018. [[homepage](http://krisztianbalog.com/)][[Google scholar](https://scholar.google.com/citations?user=1z918TYAAAAJ&hl=en)]
