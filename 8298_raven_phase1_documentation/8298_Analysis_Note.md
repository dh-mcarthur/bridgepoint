---

This work is licensed under the Creative Commons CC0 License

---

# MASL Import/Export Documentation Analysis
### xtUML Project Analysis Note


1. Abstract
-----------
BridgePoint shall provide import/convert and export utilities for MASL models. Along with the 
implementation of these utilities, documentation will be packaged in a build of 
BridgePoint to be delivered to the user.

2. Document References
----------------------
<a id="2.1"></a>2.1 [8298 Parent task for documentation (phase 1)](https://support.onefact.net/issues/8298)  
This is the parent task for all phase 1 documentation activities.

<a id="2.2"></a>2.2 [8339 Prepare Analysis Note](https://support.onefact.net/issues/8339)  
This is the parent task for the preparation of the documentation Analysis Note.

<a id="2.3"></a>2.3 [8340 Conduct interviews to capture workflow details)](https://support.onefact.net/issues/8340)  
This is the parent task for all phase 1 documentation activities.

<a id="2.4"></a>2.4 [8341 Preparation of guide dodcuments and initial documentation materials](https://support.onefact.net/issues/8341)  
This is the parent task for all phase 1 documentation activities.


<a id="2.5"></a>2.5 [8019 Analysis note](https://github.com/cortlandstarrett/mc/blob/8019_progen3/doc/notes/8019_masl/8019_masl_ant.md)  
This is a high level analysis of the MASL project.  

<a id="2.6"></a>2.6 [8019 Design note](https://github.com/cortlandstarrett/mc/blob/8019_progen3/doc/notes/8019_masl/8019_masl_dnt.md)  
This is the corresponding design note for [[2.1]](#2.1).  

<a id="2.7"></a>2.7 [MASL Reference Manual](https://drive.google.com/folderview?id=0B834tggB4vylb0tNT2xYdm1SOGs)  
This is the MASL language reference.  
  

3. Background
-------------
For relevant background regarding MASL methodology and conventions see [[2.7]](#2.7).

For relevant background on the implementation of the MASL import/export utilities, see both the 
analysis note [[2.5]](#2.5) and the design note[[2.6]](#2.6) for issue #8019.

4. Requirements
---------------

A review of the BridgePoint utilities implementing the MASL import and export functionality as described in [[2.6]](#2.6) led to the following derived 
documentation requirements

<a id="4.1"></a>4.1. The conversion of MASL projects and domains into xtUML model files is to be summarized in a concise prescriptive document. 

<a id="4.2">4.2. The exporting of a xtUMLA package or component into an equivalent MASL domain is to be summarized in a concise, prescriptive document. 

<a id="4.3">4.3. The recommendations and practices associated with the preferred operation of the MASL import and export implementation is to be summarized in a 
concise, prescriptive document.

<a id="4.4">4.4. The step-by-step instructions for the import of a MASL domain, modification inside BridgePoint and export to a MASL domain is to be presented in 
a tutorial-style document.

<a id="4.5">4.5. All documents are to be largely text with few screenshots, expect where essential.

<a id="4.6">4.6. All documents are to be delivered as a single HTML file with a single subfolder of referenced artifacts (images, linked docs, etc.) if necessary

<a id="4.7">4.7. All documents are to be paginated as a single continuous page.

<a id="4.8">4.8. Primary page formatting is to be consistent with existing content displayed on the online website xtUML.org.  

<a id="4.9">4.9. While preparing these documents, if the existing BridgePoint documentation is found to be lacking, issue(s) shall be raised to 
describe the need for improvements



5. Analysis
-----------

The MASL import/conversion and export flows are a mixture of existing BridgePoint functionality and new technology. Consequently, the documentation as required by 
[[2.1]](#2.1)[2.1] of this new flow must comprehensively cover the high-level principles and usage, while leveraging the existing BridgePoint documentation where available.
For the new technology contained within MASL2xtuml and xtUML2masl [[4.5]](#4.5) and [[4.6]](#4.6)) command line scripts, detailed function-specific documents are required 
that fully describes all setting and usage options. These documents will satisfy requirements [[4.1]](#4.1) and [[4.2]](#4.2). For consistency with existing BridgePoint 
documentation, these two documents must be paginated as a single command per page [satisfies [[4.6]](#4.6) and [[4.7]](#4.7)], and contents of the page will begin with a head line, 
followed by single sentence description of the utility provided by the command,comprehensive syntax description of all parameters and examples of expected usage. 
Complementing these individual commands is a pair of methodology documents as set out in requirements [[4.3]](#4.3) and [[4.4]](#4.4) which describe the overall MASL - xtUML 
model exchange. This overview document must describe the steps of the model exchange process, provide guidance in the form of recommendations 
(ie filesystem organization, workspace organization, naming conventions, etc.) and summarize the process using generic steps. A separate document 
will extend the description of the steps by demonstrating the process using an example that originates in the MASL model representation, is exported 
into xtUML where it is modified, and is then exported back into an equivalent MASL model. This document will satisfy [[4.4]](#4.4).


6. Work Required
----------------
To implement the documentation package for the MASL import and export utilities, a process involving three steps will be followed. The steps are described in 6.1 through 6.3.

6.1 Preparation for each document will begin with interviews where data on the specific area is collected. Each interview will
cover topics of expected usage, methods for invocation, and recommendations for users. 

6.2 Next the facts obtained during the interviews are compiled into HTML documents according to the 3 document structures identified in 
Requirements [[4.1]](#4.1) through [[4.4]](#4.4). Requirements [[4.1]](#4.1) and [[4.2]](#4.2) to have a single page structure, requirement [[4.3]](#4.3) to have a narrative structure, 
and requirement [[4.4]](#4.4) to have a tutorial/instruction structure. 

6.3 The final step involves formatting the document contents such that requirements [[4.5]](#4.5) through [[4.8]](#4.8) are satisfied.
 

7. Acceptance Test
------------------
The same acceptance procedure is to be employed for each document. The steps of the acceptance procedure for each document identified in section [[4.1]](#4.1) 
through [[4.4]](#4.4) are detailed in 7.1 through 7.4. 

7.1 Place the implementation containing an HTML file and associated subfolder, if present, in an empty directory.

7.2 Open the HTML page using the Google Chrome browser.

7.3 The rendered page will be visually inspected and compared against the requirements noted in section 4. 

7.4 Acceptance will be granted if all identified deviations are shown to not detract from the accuracy or interfere with the comprehension of the meaning contained 
in the passage.

End
---

