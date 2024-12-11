# IBM FileNet Content Manager

## Overview

IBM FileNet Content Services is a flexible, full-featured content management solution that is part of the foundation for IBM Cloud Pak for Business Automation. In three labs you will get introduced to important core concepts of FileNet Content Platform Engine, Content Services GraphQL, and IBM Content Navigator. This will enable you to use FileNet Content Platform Engine to build the information architecture for automation projects realized with Cloud Pak for Business Automation. 

## Labs

**Track 2 - Developer Role / Solution Implementation**

- **<a href="CONTENT%20Lab%201%20-%20CPE.pdf" target="_blank">Setting up FileNet Content Manager for Automation Projects on Cloud Pak for Business Automation</a>:**
  In this lab, you will create a small hierarchy of Document classes to
  capture different kinds of documents together with custom metadata,
  and will learn about the most important security concepts. You will
  explore Document storage and learn to migrate documents between
  different Storage Areas.  Further you will determine how to trigger
  custom actions for example when new documents have arrived, and how to
  configure and test functionality of content based retrieval,
  i.e. searches for documents based on information contained in the
  documents themselves, not (only) on their metadata.

    In this lab, for triggering the custom actions, a custom JavaScript is
    used to file a newly uploaded document into a folder, those identity
    is derived from a search. The script is available in the <a href="https://github.com/IBM/cp4ba-labs/tree/main/23.0.2/Content/Lab%20Data" target="_blank">Lab Data</a> folder. Be aware that in the script, some
    replacements need to be made, to make it refer to the right
    properties. The username prefix is denoted by usrxxx in the script,
    and the xxx part needs to be updated.

    **Approximate Duration**: 4 - 5 hours

- **<a href="CONTENT%20Lab%202%20-%20GraphQL.pdf" target="_blank">Interfacing FileNet Content Platform Engine with GraphQL on Cloud Pak for Business Automation</a>:**
  The second lab on GraphQL builds on top of the first one, as the
  searches performed using GraphQL use the documents and document
  classes defined in the first lab.  Here you learn by a series of
  example, how to build the most important queries using GraphQL.  The
  examples also show how to download documents using GraphQL, how to
  create folders, and modify security settings.

    **Approximate Duration**: 1.5 - 2 hours

- **<a href="CONTENT%20Lab%203%20-%20ICN.pdf" target="_blank">Content Navigator on Cloud Pak for Business Automation</a>:**
  The third lab on IBM Content Navigator builds on top of the first, but not the second one.
  In it you can learn important concepts which allow you to configure IBM Content Navigator for a business application.
  The administration parts of the lab can only be performed in environments with administrative access. For other cases walkthroughs are provided in the lab guide.
  
    **Approximate Duration**: 1.5 - 2 hours