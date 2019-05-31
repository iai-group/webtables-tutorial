# Tutorial on Web Table Extraction, Retrieval and Augmentation

Tables are a practical and useful tool in many application scenarios. Tables can be effectively utilized for collecting and organizing information from multiple sources.  With the help of additional operations, such as sorting, filtering, and joins, this information can be turned into knowledge and, ultimately, can be used to support decision-making.  Thanks to their convenience and utility, a large number of tables are being produced and are made available on the Web.  These tables represent a valuable resource and have been a focus of research for over two decades now.  In this tutorial, we provide a systematic overview of this body of research.

Tables on the web, referred to as *web tables* henceforth, differ from traditional tables (that is, tables in relational databases and tables created in spreadsheet programs) in a number of ways.  First, web tables are embedded in webpages.  There is a lot of contextual information, such as the embedding page's title and link structure, the surrounding text, etc. that can be utilized. Second, web tables are rather heterogeneous regarding their quality, organization, and content.  For example, tables on the Web are often used for layout and navigation purposes.

Among the different table types, *relational tables* (also referred to as *genuine tables*) are of special interest. These describe a set of entities (such as people, organizations, locations, etc.) along with their attributes.  Relational tables are considered to be of high-quality, because of the relational knowledge contained in them.  However, unlike from tables in relational databases, these relationships are not made explicit in web tables; uncovering them is one of the main research challenges. The uncovered semantics can be leveraged in various applications, including table search, question answering, knowledge base augmentation, and table completion.
For each of these tasks we identify seminal work, describe the key ideas behind the proposed approaches, discuss relevant resources, and point out interdependencies among the different tasks.


## Outline

   * Introduction
      -  Motivating scenarios
      -  Table types
      -  Table extraction and table corpora
   * Table interpretation
      -  Column type identification
      -  Entity linking in tables
      -  Relation extraction
   * Table search
      -  Keyword query search
      -  Search by table
   * Question answering on tables
      -  QA using a single table
      -  QA using multiple tables
   * Knowledge base augmentation
      -  Tables for knowledge exploration
      -  Knowledge base augmentation and construction
   * Table augmentation (and wrap-up)
      -  Row extension
      -  Column extension
      -  Data completion
