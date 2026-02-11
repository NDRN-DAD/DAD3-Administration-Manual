[Home](../../index.md) / [Configuration Reference](../index.md) / [Section: Local Data](index.md) / Local Data Fields

# Local Data Fields

**Page Type:** Table with Collapsible Filters section (URL: [https://dad3.ndrn.org/admin/admindisplayuserdefinedfields](https://dad3.ndrn.org/admin/admindisplayuserdefinedfields)) <!--style: Subtitle -->

**Associated Record Types:** [Funding Sources](../section-funds/funding-sources.md), [Service Request Types](../section-service-requests/service-request-types.md) (Service Requests), [Project Types](../section-service-requests/project-types.md), [Problem/Subproblem](../section-funds/problems-subproblems.md)

![Local Data Fields admin page screenshot](../../images/Local%20Data-Local%20Data%20Fields.png)

## Local Data Fields Form

### Basic Info Tab

![Screenshot of Local Data Local Data Fields Form Basic Info tab](../../images/Local%20Data-Local%20Data%20Fields-Form-Basic%20Info.png)

- **Name** (Short Text - required)
    Name of the Local Data Field (as seen in the Report Generator)

- **Label Text** (Short Text - required)
    Name of the Local Data Field (as seen in records / by end users)

- **Help Text** (Long Text - optional)

     Agencies can add Help text to this field that displays as a tip when hovering over or navigating to the Local Data Field. 

- **Field Type** (Dropdown selection)
    Checkbox List
    Date Dropdown
    Dropdown List
    Numeric Box
    Text Box - Multi-Line
    Text Box - Single-Line
    Yes/No Radio Buttons

- **Display Type** (Dropdown selection)
    - **Opening**: Field displays at all times
    - *Closing**: Field displays only on **Prepare for Closing**

- **Client Association** (Dropdown selection)
    - **On Creation**: Field displays on the New Client Creation form; optional to answer
    - **On Creation - Required at SR Closing**: Field displays on the New Client Creation form; Service Requests for the Client cannot be closed until it is completed (similar to reportable Client fields like Gender, Race and Ethnicity)
    - **On Edit**: Field does *not* display on New Client Creation form, but appears on edit.
    - **On Edit - Required at SR Closing**: Field does *not* display on New Client Creation form, but appears on edit. Service Requests for the Client cannot be closed until it is completed.


- **SR Association** (Dropdown selection)
    - **Required**: Field is required to close the service request
    - **Optional - On Creation**: Field is optional and displays on the New Service Request form
    - **Optional - On Edit**: Field is optional and does *not* display on New Service Request form, but appears on edit.
    - **Optional with Warnings - On Creation**: Field is optional and displays on the New Service Request form; Validation Warning displays on record if unanswered.
    - **Optional with Warnings - On Edit**: Field is optional and does *not* display on New Service Request form, but appears on edit; Validation Warning displays on record if unanswered.

- **Project Association** (Dropdown selection)
    - **Required**: Field is required to close the project
    - **Optional - On Creation**: Field is optional and displays on the New Project form
    - **Optional - On Edit**: Field is optional and does *not* display on New Project  form, but appears on edit.
    - **Optional with Warnings - On Creation**: Field is optional and displays on the New Project form; Validation Warning displays on record if unanswered.
    - **Optional with Warnings - On Edit**: Field is optional and does *not* display on New Project form, but appears on edit; Validation Warning displays on record if unanswered.

- **Active Date** and **Inactive Date**: Field will display in records with a Reference Date greater than or equal to the Active Date, and less than the Inactive Date (if entered).


### Options Tab

This tab appears if Field Type is Checkbox list or Dropdown list. Each option appears based on Active and Inactive dates. Options are **Requires Further Explanation** and **Is the Default Option**.

![Screenshot of Local Data Local Data Fields Form Options tab](../../images/Local%20Data-Local%20Data%20Fields-Form-Options.png)

### Funds Tab

Select the Funding Sources for which this field should display. To display for all funding sources, use **Not Funding Specific** option.

![Screenshot of Local Data Local Data Fields Form Funds tab](../../images/Local%20Data-Local%20Data%20Fields-Form-Funds.png)

### Service Request Types Tab

If associated with Service Requests, select the SR Types for which this field should display. To display for all SR Types, use **Not Service Request Type Specific** option.

![Screenshot of Local Data Local Data Fields Form Service Request Types tab](../../images/Local%20Data-Local%20Data%20Fields-Form-Service%20Request%20Types.png)

### Project Types Tab

If associated with Projects, select the Project Types for which this field should display. To display for all Project Types, use **Not Project Type Specific** option.

![Screenshot of Local Data Local Data Fields Form Project Types tab](../../images/Local%20Data-Local%20Data%20Fields-Form-Project%20Types.png)

### Problems / Subproblems Tab

If desired, select Problem/Subproblem combinations: the field will only display if Problem and Subproblem for the record match. To display for all Problem/Subproblem selections, use **Not Problem / Subproblem Specific** option.

![Screenshot of Local Data Local Data Fields Form Problems & Subproblems tab](../../images/Local%20Data-Local%20Data%20Fields-Form-Problems%20&%20Subproblems.png)

[← Previous: Section: Local Data](index.md) | [Next: Out of Date Client Local Data Fields →](out-of-date-client-local-data-fields.md)
