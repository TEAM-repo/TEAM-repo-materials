# Architecture 

The goal of this assignment is to document the architecture of your app. You will be revising this document to include as a chapter in your final writeup submitted at the end of the semester.
Architecture

Each team must submit a project architecture, which is a professional document that should provide a complete view of the architecture of your application. The purpose of this document is to capture the significant architectural decisions you have made and explain why you have chosen those particular solutions. Consider this document as a complement to the UML diagrams that you have been submitting. The document shouldn't focus on what the user is able to do but rather describe what your system uses to provide the functionality and those back-end components' interaction with the interface.

*   Expand upon the benefits and limitations of your current architectural design.
*   Explain your architecture with the aid of diagrams (bullet points are fine). Feel free to reuse any text or diagrams that you have previously created.

For example, you might...

*   Provide bullet point descriptions of each of the run-time components (see explanation below): what it does, and the requirements it must meet.
*   Provide bullet point descriptions of the major persistent data objects: what kind of information they contain, how/where they are stored, and (where appropriate) supporting middle-ware (e.g., MySQL).
*   Provide diagrams illustrating the major components, their responsibilities, and their interactions.
*   Discuss the key issues that arose in the development of this architecture and the rationale that drove the selection of the chosen approach.
*    Discuss major issues still outstanding (anything that causes you to doubt that it will be possible to successfully build this system on a predictable schedule): what the problem is, what options have been considered, and how those options fall short.


Think of a **component** as a part of the system that contributes to the system's functionality. For example, user data input is a functionality that is accomplished using components such as, for example, data collection interface and database storage.

Microsoft Developer Network defines a component as a "an encapsulated piece of code that performs some function for an application."
https://msdn.microsoft.com/en-us/library/bb727121.aspx (Links to an external site.)Links to an external site.

Here's an example of OpenEdge Application Server components and their dependencies:
https://documentation.progress.com/output/ua/OpenEdge_latest/index.html#page/asadm/run-time-components-and-operation.html (Links to an external site.)Links to an external site.
and the Rockwell Automation components (slide 28):
https://www.rockwellautomation.com/resources/downloads/rockwellautomation/pdf/events/automation-fair/2011/psug/afpsug11_ed16.pdf (Links to an external site.)Links to an external site.

    
    Here's an example of past project's architecture: ActiveTransportAndroid_Architecture.pdfPreview the document
Template (ProjectName_Architecture.pdf)

[There is no page limit, but aim for conciseness.]

Project: <name of project under development>

Client: <name(s)>

Development Team: <name> (PM), <name>, …



<Description of your app architecture>
Rubric

An approximate breakdown is as follows.

    [15 pts] Architecture
*       [3 pts] Conceptual roles of each component (run-time and data objects) are clear
*       [3 pts] Interactions and how components cooperate to provide the required services are clear
*       [3 pt] Benefits of current design, including rationale are listed and are sound
*       [3 pt] Major concerns and limitations of current design (e.g., Is it MVC? What can it not handle?)
*       [2 pt] Document is accessible to an external developer (e.g., someone not on the project team could read the document and use it to extend on your design)
*       [3 pt] Quality of visuals (figures are labeled and captioned, free of typos, well-formatted and readable when printed, and referenced within text)
*       [3 pt] Overall quality (document complements existing diagrams, nothing obvious is missing, well-formatted, readable, free of typos, etc.)

Additionally, be sure that your document satisfies the following criteria:

*   Timeliness - The document was submitted before the deadline.
*   Readability - The content presented in the document should be well-formatted, clear, and readable.
*   Completion - The document is complete, and clearly written.
*   Accessibility - This document should be written such that someone not on your project can understand the content.
*   Depth - This document should include details that are specific to your project and help document the architecture of your project. For example, even if you are using the same framework as another team, the write-up should include your project-specific details, which are different than other teams.

