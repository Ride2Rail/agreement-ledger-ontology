

### Agreement Ledger Ontology

The definition of an ontology to represent contracts defined through the Ride2Rail Agreement Ledger component enables the possiibility of having a machine-readable and interoperable representation of the agreements. On one hand, the underlying blockchain ensures the trust about the execution of the contracts, on the other hand, their ontological representation facilitates the retrieval of information within the Shift2Rail IP4 ecosystem.

### Ontological requirements

#### Use Cases

**QUESTION**: Who will be the actors interested in querying the ontological data? What are the use cases for that?

Use the following template to investigate what are the relevant data that can be represented using the ontology to be accessed:

##### UCX - New use case Title

*Description:* provide a description of the use case including a justification of its usefulness or relevance to this domain

*Stakeholders:* indicate who is involved in the use case

*Workflow:* provide details of the use case, stakeholder interactions and results obtained

#### User Stories

This section collects User Stories generated from the identified Use Cases.

| Id   | Use Case | User Story                                               |
| ---- | :------: | -------------------------------------------------------- |
| US1  |   UC1    | As (_actor_) I want (_something_) to obtain (_benefit_). |

### Agreement Ledger Ontology: Ontological requirements

#### UC1 – Dispute Resolution about Ridesharing

*Description*: In case of a dispute between a driver and a traveller regarding a booked ride, the authority/operator wants to access trusted data to resolve it. 

*Stakeholders*: Driver, Traveller, Authority/Operator

*Workflow*: The authority/operator analyses the details of the booking agreement between the driver and the traveller obtaining trusted information that can help in solving the dispute.

##### User Stories

| *Id* | *Use  case* | *User  Story*                                                |
| ---- | ----------- | ------------------------------------------------------------ |
| US1  | UC1         | As Authority I want to check the planned origin/destination of a booked ride to solve a dispute on the itinerary performed by a driver. |
| US2  | UC1         | As Authority I want to check the price agreed for the ride to solve a dispute between a driver and a traveller. |

#### UC2 - Incentives to promote Ridesharing

*Description*: Travellers (both drivers and passengers) are given incentives to involve ride-sharing in their multimodal rides.

*Stakeholders*: Traveller, Travel Service Provider

*Workflow*: Incentives are represented as ontological smart contracts and can be queried to get information about incentive conditions and mechanisms about active incentives within IP4.

##### User Stories

| *Id* | *Use  case* | *User  Story*                                                |
| ---- | ----------- | ------------------------------------------------------------ |
| US1  | UC2         | As a Travel Service Provider I want to check incentives defined by other TSPs throught the ledger to understand how to incentivise my services. |
| US2  | UC2         | As a Traveller I want to check the conditions of incentives defined by  a TSP to check if I am entitled to receive an incentive. |

#### Facts and Competency Questions

Facts and Competency Questions defined in the shared document: https://docs.google.com/spreadsheets/d/1rTRvpwsC0_AdPDcg5ng6kYwB4pdYM6s7GAZMlDUezXQ/edit?usp=sharing
