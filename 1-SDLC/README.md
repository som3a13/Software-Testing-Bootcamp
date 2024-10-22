# How software is Developed SDLC

## Sequential Development

1. Analysis
2. Design
3. Implementation
4. Deploying & Testing

### Waterfall model:  User will interact with app at end of DLC 

Very appropraite when you have already known requirments , very simple for small teams

1. Requriments
2. Design
3. Development
4. Testing
5. Deployment
6. Maintenance

Defects:

* Testing will come late.
* we cant go back to previous step we should start from beginning.

### V-Model

1. Business Requirements [BRD] :  Client/Customer features
2. System Requirements/Specifications [SRS] : what technologies will be used to create these features
3. Architectural design / high level : interactions between the system components
4. Detailed Design / low level : Design of modules  /components
5. Implementation / coding
6. Every level has corrosponding testing level

   * Unit testing : for Detailed design
   * Integration testing : for high level      -------> Developer responsibility
   * System Testing : for System Requirments ------> Software tester responsibility
   * Acceptance testing : for Business Requirments -----> Software tester / beta users / Business  owner responsibility / Client


### System Testing Process

1. **Test Planning:**
   * Define the scope, objectives, and resources for system testing.
   * Develop a test strategy and identify the required tools and environments.
2. **Test Design:**
   * Create test cases based on requirements and use cases.
   * Design test data and define the expected results.
3. **Test Execution:**
   * Execute test cases and document the results.
   * Report any defects or issues identified during testing.


## Agile Software Development [short notes]

1. Not sequential
2. In agile  : we get continous feedback from user
3. Writing user stories
4. Deliver continuos feedbac from customer

### Incremental

Product  is divides to alot of pieces  . each phase will depend on the other  and at end it'll have a meaning

### Iterative 

Features will be updated / improved in each iterate and take feedback from customer/product owner

### Scrum Process [Methdology to apply Agile Philosophy]

1. **Product backlog** - features  written as User stories  by Product owner
2. **Sprint backlog** - Project will be divided to sprints , specific feature / sprinit will be timed 1-4 weeks
3. **Sprint  will have a Scrum Master [Leader]** , master for team [Developers / testers ]
4. **Daily Scrum  /Stand up meeting** : A short daily meeting (usually 15 minutes) where team members discuss what they did yesterday, what they will do today, and any blockers they are facing.
5. **Sprint Review:** A meeting at the end of the Sprint to showcase the work completed and gather feedback from stakeholders.
6. **Sprint Retrospective:** A meeting following the Sprint Review where the team reflects on the past Sprint to identify improvements for the next Sprint.

### Agile vs Sequential

* **For agile** : Fixed time & Effort   But  Requirments will be estimated the mainly reqs. and can be incremented
* **For sequential**  : Fixed Requirments But Estimated time & Effort
