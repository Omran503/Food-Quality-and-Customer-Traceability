# Documentation

### Sprint 1 Review: Food Incident & Customer Traceability

In Sprint 1, the group worked on Food Quality Incident and Customer Traceability use case analysis, and laying the strategic basis for the project. The work covered the food safety issue, for example, allergen contamination, date labelling, and product contamination, and how the issue can be traced along the marketplace and all impacted customers can be identified and notified.

The team conducted fieldwork about the applicable standards of food traceability and regulatory guidance, such as UK FSA requirements and FDA FSMA 204 traceability structures, to guide the design of the proposed solution. The strategic analysis revealed that forward and backward traceability should connect the producer product customer order and impacted customer.

A high level BPMN process was created to model this overall process. The initial process has stakeholder lanes, incident reporting, investigation task flow, customer tracing, escalation flow, notification flow, and review process. Two key functionalities were identified: 

1. **Incident Management**
    - Reporting food quality incidents.
    - Creating and managing incident records.
    - Investigating incidents with producers.
    - Escalating or closing incidents.
    - Suspending products where required.
    - Reviewing and closing incidents.
2. **Customer Identification and Traceability**
    - Identifying affected orders and customers.
    - Tracing products back to producers.
    - Sending customer notifications.
    - Recording notification outcomes.
    - Managing failed notification follow\-up activities.


### Sprint 2 Development Work

In Sprint 2, the focus is on taking the strategic analysis of Sprint 1 and starting to model the operational side in a more detailed fashion and show the traceability between business objectives, stakeholders, and operational processes. As laid out in the Sprint 2 plan, the key outputs are: 
- i Strategic Dependency (SD) model.
- i Strategic Rationale (SR) model.
- operational BPMN models.
- Clear traceability between stakeholder requirements and process models.
- Supporting requirements, backlog items, and traceability evidence.

For this project, Sprint 2 develops the two major operational processes:

#### Operational Model 1: Incident Management

This model expands the strategic process into a detailed workflow covering:

- Incident reporting.
- Incident record creation.
- Product and producer identification.
- Producer communication.
- Risk assessment.
- Escalation handling.
- Product suspension decisions.
- Authorised review and closure activities.
- Exception scenarios such as producer non\-response and late responses.

#### Operational Model 2: Customer Traceability and Notification

This operational process focuses on:

- Identifying affected orders and customers.
- Tracing impacted products.
- Customer notification management.
- Notification result recording.
- Retry handling and escalation of failed notifications.
- Manual follow\-up where automated notification attempts fail.

The Sprint 2 work also includes socio\-technical analysis through the i\* models. The Strategic Dependency model identifies the relationships and dependencies between customers, producers, marketplace administrators, authorised representatives, and the marketplace system. The Strategic Rationale model further explores stakeholder goals, tasks, resources, soft goals, and conflicting priorities such as customer safety versus producer reputation and speed versus accuracy.

To maintain traceability, requirements have been linked to BPMN activities and stakeholder concerns. Key requirements include incident reporting, product identification, producer communication, customer tracing, notification management, audit logging, access control, and authorised incident closure.

### Sprint 2 Scope Clarification

For Sprint 2, the focus is on:

- Strategic Dependency (SD) modelling.
- Strategic Rationale (SR) modelling.
- Detailed operational BPMN models.
- Requirements and traceability documentation.

No Camunda automation, executable workflows, forms, workers, or service\-task implementation are being demonstrated, we have had 2 active memebers and just got into contact with our 3rd. We have focused Primarily on analysis to ensure that we have had any oversight and to make sure the foundations of our system are proper. 
