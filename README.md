# Accessible PDF Maker
## Weekly Status
### Week of 09/27/2020
**Things Done:**
- Had the first meeting with the sponsor.
  - Obtained some info about current process to make accessible PDF :
    - https://chi2021.acm.org/for-authors/presenting/papers/guide-to-an-accessible-submission
    - https://assets19.sigaccess.org/creating_accessible_pdfs.html
    - https://webaim.org/techniques/acrobat/converting
    - https://github.com/petergramaglia/access_sigchi
  - Expected priority of development:
    1. Less manual work on generating accessible PDFs
    2. Avoid Adobe Acrobat Pro to reduce accessibility cost for users
    3. Batch processing capability
- Some research about PDF format:
  - https://web.archive.org/web/20141010035745/http://gnupdf.org/Introduction_to_PDF#General_structure
- Engineering Diagram
     
     
  ![Engineering Diagram](/engineeringDiagram.png "Engineering Diagram")
       
      
- User Consideration
  1. Deliverable goals are listed in "Expected priority of development" section above.
  2. The app should protect user’s data and privacy. If the app is stealing the user's PDF when they upload it, that user will not want to use the app. Because of this, this project will not use a database for our web application, and no information about a user will be stored in any way.
  3. The app itself should be fully accessible. While this should be true of all products, since this project is specifically for adding accessibility, it would be diappointing if itself fails to meet common accessibility requirements.
  

**Things Planned:**
1. Will have the second meeting with the sponsor next Friday.
2. Research more on existing libraries/packages that could help decoding/making PDF files with accessible elements. If certain language/framework has some powerful packages already, this project will incline to use that in order to avoid re-inventing the wheel.
3. Think about tech stack.

### Week of 10/04/2020
**Things Done:**
- Finally got into CS Slack. -_-#
- Did more research about PDF format:
  - https://web.archive.org/web/20141010035745/http://gnupdf.org/Introduction_to_PDF#General_structure
- Found a promising npm packages on PDF:
  - https://www.npmjs.com/package/pdfkit
  
** Difficulties and Failures:**
- Team wasn't productive in this week. Communication wasn't smooth as members are having their midterms.
- Meeting with the sponsor was cancelled but rescheduling hasn't been done since she was on vacation.
- Team weighing on tech stacks. Web frameworks seem easy to pick up and use but Python seems good, too. During the summer, Code for Good had already made a Ruby on Rails app that provides a web interface for this project. Although there wasn't mcuh achinevement on the PDF side, we could still continue from there.  

**Things Planned:**
1. Planned meeting with the sponsor was postponed. Will have the meeting this week.
2. Research more on existing libraries/packages that could help decoding/making PDF files with accessible elements.
3. Need to discuss whether to make a web app (so we can use the existing npm packages which seems to be pretty helpful) or start with a local app programmed in C/C++/Python.


### Week of 10/11/2020
**Things Done:**
- Had the second meeting with Dr. Short. Scheduled next meeting on two weeks from today.
- Read some articles that contain helpful informations on the PDF accessibiltiy topic:
  - https://www.pdfa.org/wp-content/uploads/2013/08/PDFUA-in-a-Nutshell-PDFUA.pdf
  - https://helpx.adobe.com/acrobat/using/creating-accessible-pdfs.html#:~:text=%20Workflow%20for%20creating%20accessible%20PDFs%20%201,In%20Acrobat%20Pro%2C%20this%20stage%20includes...%20More%20
- Found more libraries on PDF:
  - https://www.pdflib.com/
  - https://pdf-lib.js.org/docs/api/index#const-beginmarkedcontent
  - https://hexapdf.gettalong.org/ (Ruby)
  - https://pypi.org/project/PyPDF2/ (Python)
** Difficulties and Failures:**
- Found this post when looking for some libraries to tag PDFs (for accessibility labels): https://tex.stackexchange.com/questions/579/how-can-tagged-pdfs-be-created-that-support-universal-accessibility-and-reflowin. It seems that many people tried the same thing but eventually gave up. Their previous work is disconitnued. 

**Things Planned:**
1. Try those different libraries found to see if any of them is helpful. 
2. Get the Ruby on Rail project from Tufts Code for Good up and running to see if there is anything we can build up upon.
3. Begin research on if LaTeX source files will be needed in order to make an accessible PDF, and how to parse LaTeX if needed
