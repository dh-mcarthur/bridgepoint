---

This work is licensed under the Creative Commons CC0 License

---

# MASL import/export documentation analysis
### xtUML Project Analysis Note


1. Abstract
-----------
BridgePoint shall provide import/convert and export utilities for MASL models. Along with the 
implementation of these utilities, documentation will be packaged in a build of 
BridgePoint to be delivered to the user.

2. Document References
----------------------
<a id="2.1"></a>2.1 [8019 Analysis note](https://github.com/cortlandstarrett/mc/blob/8019_progen3/doc/notes/8019_masl/8019_masl_ant.md)  
This is a high level analysis of the MASL project.  

<a id="2.2"></a>2.2 [8019 Design note](https://github.com/cortlandstarrett/mc/blob/8019_progen3/doc/notes/8019_masl/8019_masl_dnt.md)  
This is the corresponding design note for [[2.1]](#2.1).  

<a id="2.3"></a>2.3 [MASL Reference Manual](https://github.com/leviathan747/mc/blob/8320_packaging/doc/notes/8073_masl_parser/8073_masl_parser.dnt.md)  
MASL Reference.  
  

3. Background
-------------
For relevant background regarding MASL methodology and conventions see [[2.3]](#2.3).

For relevant background on the implementation of the MASL import/export utilities, see both the 
analysis note [[2.1]](#2.1) and the design note[[2.2]](#2.2) for issue #8019.

4. Requirements
---------------

A review of the BridgePoint utilities implementing the MASL import and export functionality as described in [[2.3]](#2.3) derived the following documentation requirements

1. The conversion of MASL projects and domains into xtUML model files is to be summarized in a concise prescriptive document. 

2. The exporting of a xtUMLA package or component into an equivalent MASL domain is to be summarized in a concise, prescriptive document. 

3. The recommendations and practices associated with the preferred operation of the MASL import and export implementation is to be summarized in a 
concise, prescriptive document.

4. The step-by-step instructions for the import of a MASL domain, modification inside BridgePoint and export to a MASL domain is to be presented in 
a tutorial-style document.

5. All documents are to be largely text with few screenshots, expect where essential.

6. All documents are to be delivered as a single HTML file with subfolder of referenced artifacts (images, linked docs, etc.) if necessary

7. All documents are to be paginated as a single continuous page.

8. Primary page formatting is to be consistent with existing content displayed on the online website xtUML.org.  



5. Analysis
-----------

The MASL import/conversion and export flows are a mixture of existing BridgePoint functionality and new technology. Consequently, the documentation
of this new flow must comprehensively cover the high level principles and usage, while leveraging the existing BridgePoint documentation where available.
For the new technology contained within MASL2xtuml and xtUML2masl command line script, detailed function-specific documents are required that fully describes
all setting and usage options. For consistency with existing BridgePoint documentation, these two documents must be paginated as a single command per page, and contents
of the page will begin with a head line, followed by single sentence description of the utility provided by the command, comprehensive description of all parameters 
and examples of expected usage. Complementing these individual commands is a need set out in requirements [4.3] and [4.4] for a description of the overall MASL - xtUML model 
exchange. this overview document must describe the steps of the exchange process, provide guidance in the form of recommendations (ie filesystem organization, workspace organization,
naming conventions, etc.) and summarize the process using generic steps. A separate document will extend the description of the steps by demonstrating the process 
using an example that originates in the MASL model representation is exported into xtUML where it is modified before being exported back into an equivalent MASL model. 


6. Work Required
----------------
To implement the documentation package for the MASL import and export utilities a process involving three steps will be followed.
Preparation for each document will begin with interviews where data on the specific area is collected. Each interview will
cover topics of expected usage, methods for invocation, and recommendations for users. Step 2 involves compiling the facts obtained during the interviews into 
HTML documents according to 3 document structures. Requirements [4.1] and [4.2] to have a single page structure, requirement [4.3] to have a narrative structure, 
and requirement [4.4] to have a tutorial/instruction structure. The final step involves formatting the document contents such that requirements [4.5] through [4.8] 
are satisfied.
 

7. Acceptance Test
------------------
The same acceptance procedure is to be employed for each document. The steps of the acceptance procedure for each document identified in section 4 are
1. Place the implementation containing an HTML file and associated subfolder, if present,is to be placed in an empty directory.
2. Open the HTML page using the Google Chrome browser
3. The rendered page will be visually inspected and compared against the requirements noted in section 4. 
4. Acceptance will be granted if all identified deviations are shown to not detract from the accuracy or interfere with the comprehension of the meaning contained 
in the passage.

End
---

