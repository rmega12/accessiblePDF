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
- Found some promising npm packages on PDF:
  - https://www.npmjs.com/package/pdfkit
  

**Things Planned:**
1. Planned meeting with the project sponsor was postponed. Will have the meeting this week.
2. Research more on existing libraries/packages that could help decoding/making PDF files with accessible elements.
3. Need to discuss whether to make a web app (so we can use the existing npm packages which seems to be pretty helpful) or start with a local app programmed in C/C++/Python..
