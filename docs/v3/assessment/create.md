# Create Assessment
This page will describe the process of creating a new assessment. Each of the options will be explained as that are reached.

## Catalogue
The assessment catalogue is accessed from the main menu 'Assessment -> Configuration -> Catalogue'
The catalogue shows all the assessments available to this instance of smart!.
If you want to use an assessment make sure you have the correct site selected, then click on the "ADD TO COMPANY" button.
That will make the assessment available to that site.

In this document we are going to focus on creating a whole new assessment.

![Image](./assets/catalogue.png)

## Create New
Start by clicking on the "ADD NEW" button.
The following screen is shown in the right panel.

* TIP: expand the panel to full screen
![Image](./assets/new1.png)

### Configuring an assessment
* Name: the assessment name and version must be unique
* Active: this is false by default when creating a new assessment. This is because you need to add a structure and verifications to the assessment before it is usable. Best practice is to create the assessment and only when you are done, set the assessment to active.
* Core Import Id: this is a unique identifier that is only used during assessment import and export. The is allows a exported version of the assessment to be imported to another instance. __NB:__ if the import finds a matching assessment it will override that assessment. So make sure you have a good naming convention
  - Example is A-XXX-01 (A: assessment, XXX: abbreviation of you standard or policy etc, 01: version of the document)
* Category: a handy label that can be used to group multiple assessments together. E.g. ESG, Standards, Policies, Meeting Checklists etc
* Show Documentation: you are able to link or upload documentation to the assessment. This is really help ful if you the assessment is based on a standard or if you want provide some training documentation that can be reviewed by users of the assessment. The documentation is available from the main submission list page.
* Version Label: as mentioned on the name field, name and version are required to be unique

### Settings
* Renew Period: some assessment need to be renewed as they have a cost associated __FUTURE FEATURE__
* Price: __FUTURE FEATURE__
* Description: description of the assessment and it's purpose
* Single User Assessment: __FUTURE FEATURE__
* Enable Standard Association: __FUTURE FEATURE__
* Use Maturity Scale: Maturity scales allow you to calculate a score using maturity. The smart! allows you the ability to create your own maturity scale, or use a score as a maturity rating. 
![Image](./assets/new_MLScale.png)
    - if you choose NONE: then you have decided that this assessment is not using a maturity levels to determine scores and an average score will be used across verifications. (only verifications that are set to be included in the scoring will be used)

#### MATURITY SCALE
This indicates that you have created a specific maturity scale in the system and you want to use that to group your verifications and perform score calculations
 ![Image](./assets/new_MLScale_ML.png)
 * Select Maturity Scale: Choose the predefined maturity level from the list
 * Display type: WIZARD or SINGLE page. The WIZARD means all verifications of a specific level will be grouped together on a page. You will then need to navigate NEXT or BACK to see the higher and lower levels of the maturity scale. WIZARD is the default view for maturity assessments. 
 SINGLE PAGE will show all the verification for the assessment on a single page ordered by maturity level.

#### SCORE SCALE
 In this case you want the score you use to reflect the maturity level. This normally takes the form of a rating.
 ![Image](./assets/new_MLScale_SS.png)
 * Max Score as Maturity: what is your max maturity score? if you had a maturity scale it would be to highest level. As many of these are based on rating type questions what is the hightest rating e.g. 4. if you use other field types they will max out at this value.

### Non Conformance Rules

### Close and Reset Configuration

### Workflow Configuration

### Assessment Structure
