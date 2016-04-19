---

This work is licensed under the Creative Commons CC0 License

---

# MASL Import/Export Documentation Design Note
### xtUML Project Analysis Note


1. Abstract
-----------
BridgePoint shall provide import/convert and export utilities for MASL models. Along with the 
implementation of these utilities, documentation will be packaged in a build of 
BridgePoint to be delivered to the user. Following initial release, revisions to
the documentation are needed based on feedback from customers and the developer community.

2. Document References
----------------------
<a id="2.1"></a>2.1 [8298 Parent task for documentation (phase 1)](https://support.onefact.net/issues/8298)  
This is the parent task for all phase 1 documentation activities.

<a id="2.2"></a>2.2 [8339 Prepare Analysis Note] Task )](https://support.onefact.net/issues/8339)  
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
  
<a id="2.8"></a>2.8 [MASL infused BridgePoint release](https://s3.amazonaws.com/xtuml-releases/internal-build/v5.3.2/BridgePoint_v5.3.2_linux.zip)  
This is the release of BridgePoint that includes MASL enhancements. 

<a id="2.9"></a>2.9 [8298 Analysis Note](bridgepoint/8298_raven_phase1_documentation/8298_Analysis_Note.md)  
This is the requirements and analysis of the Raven documentation project. 
  
3. Background
-------------
For relevant background regarding MASL methodology and conventions see [[2.7]](#2.7).

For relevant background on the implementation of the MASL import/export utilities, see both the 
analysis note [[2.5]](#2.5) and the design note[[2.6]](#2.6) for issue #8019.

For relevant background on the MASL documentation currently supplied with BridgePoint, see the Help contents 
provided in [[2.8]](#2.8) BridgePoint release 5.3.2 

4. Requirements
---------------

See section 4 of analysis note [[2.9]](#2.9) for issue #8298


5. Analysis
-----------

As part of the release of BridgePoint 5.3.2, the initial BridgePoint support for MASL was included. Along with 
the functional support of MASL import/export, this release included an initial version of the MASL conversion
guide and tutorial. The guide and reference pages provide a good summary of each tool, however a high-level 
overview and detailed mappings of MASL to MASL-infused xtUML are missing. Included as part of the overview will
need to be a diagram summarizing the workflow and common usage patterns. 

6. Work Required
----------------
To remidy the shortcomings identified in the analysis above, supplementary documentation in the 
areas noted below is needed.

6.1 Preparation of a high-level overview that summarizes the expected MASL project flow using BridgePoint xtUML.
This overiew must include a summary diagram and describe the expected import-modify-export workflow. 

6.2 Enhancement of the discussion of MASL type resolution and type reference mappings to MASL-infused model representations

6.3 Enhancement of the discussion of mapping MASL public services and Terminator services to activities inside the 
MASL-infused bridge component.

6.4 Enhancement of the discussion of importing MASL Pragmas and markings, editing/adding new markings and pragmas in the
MASL-infused model and the mapping used during export.

6.5 Correct tutorial steps to match the operation of BridgePoint 5.3.2
 

7. Acceptance Test
------------------
See section 7 of analysis note [[2.9]](#2.9) for issue #8298.

End
---

