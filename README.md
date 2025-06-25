<h1>Testing Project for Vinted</h1>

The scope of the final project for ITF Manual Testing Course is to use all the gained knowledge through the course and apply it in practice, using a live application.

Application under test: Vinted (An online marketplace through which users can sell their new or second-hand items or purchase certain items from other users.)

Tools used: Jira, Zephyr Squad.

Functional specification of two modules:

•	Buy Module

•	Sell Module

The following 5 stories were created in Jira and describe the functional specifications of the Buy module, for which the final project is being performed.

1.	[Search and filter items](https://github.com/CheranIonut/Proiect_Final_Vinted_QA/blob/main/Story-1.png)
2.	[View images and item details](https://github.com/CheranIonut/Proiect_Final_Vinted_QA/blob/main/Story-2.png)
3.	[Save items that I like](https://github.com/CheranIonut/Proiect_Final_Vinted_QA/blob/main/Story-3.png)
4.	[Purchase items using my card](https://github.com/CheranIonut/Proiect_Final_Vinted_QA/blob/main/Story-4.png)
5.	[Receive order confirmation on email](https://github.com/CheranIonut/Proiect_Final_Vinted_QA/blob/main/Story-5.png)
   
The following 4 stories were created in Jira and describe the functional specifications of the Sell module, for which the final project is being performed.

6.	[List and sell items](https://github.com/CheranIonut/Proiect_Final_Vinted_QA/blob/main/Story-6.png)
7.	[Add information for my item and upload photos](https://github.com/CheranIonut/Proiect_Final_Vinted_QA/blob/main/Story-7.png)
8.	[Receive a confirmation after successfully listing an item](https://github.com/CheranIonut/Proiect_Final_Vinted_QA/blob/main/Story-8.png)
9. [Promote a listed item](https://github.com/CheranIonut/Proiect_Final_Vinted_QA/blob/main/Story-9.png)
    
Here you can find the release that was created for this project:

[Release](https://github.com/CheranIonut/Proiect_Final_Vinted_QA/blob/main/Release.png)

Testing process

The test process was performed based on the standard test process as described below.

1.1 Test planning
The Test Plan is designed to describe all details of testing for two major modules from the Vinted application.
The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan.

1.1.1. Roles asigned to the project and persons allocated
(numele persoanelor pot sa fie fictive, doar sa treceti numele vostru ca si tester)

•	Project manager: Alexandru Bucur

•	Product owner: Fabian Cojocaru

•	Software developer: Popescu David

•	QA Engineer: Ionuț Cheran



<h4> 1.1.2 Entry criteria defined </h4>

• Finalization and approval of the test plan

• Finalization of business requirements

• Selection of the team and assignment of roles in the project

• Budget allocation

• Preparation of the testing environment

• Preparation of test data

• Writing and validation of test cases

<h4> 1.1.3 Exit criteria defined </h4>

• All tests have been run

• All critical defects have been fixed

• The deadline has been reached

• The budget has been exhausted

• The summary report has been delivered and approved

<h4> 1.1.4 Test scope</h4>

<h5> Tests in scope: </h5>

- Functional testing; Positive and negative testing; System testing.

<h5>Tests not in scope: </h5>

-	Smoke Testing and Sanity Testing.

- Non-functional testing: Stress testing; Load testing; Volume testing; Spike testing; Scalability testing; Reliability testing; Recovery testing; Usability testing; Portability testing; Maintainability testing; Security testing; Compatibility testing; Localization testing; Compliance regulation testing.

<h4>1.1.5 Risks detected</h4>

<h5>Project risks:</h5>

Project risks are related to the need to create real accounts to publish products, to use real photos in ads, to use real bank accounts and addresses, and to ultimately make real payments.


<h5> Product risks: </h5>

Product risks are related to not publishing clothing items, not displaying photos in the appropriate quality, inaccurate filtering of products, not filtering the types of print patterns on items, displaying unavailable products, lack of clothing brands, difficulty selling published products due to high competition, the need to lower the price and promote products thus spending money.


<h4>1.1.6 Evaluating entry criteria</h4>

The entry criteria defined in the Test Planning phase have been achieved, and the test process can continue.

<h3>1.2 Test Monitoring and Control<h3>

[Test status report](https://github.com/CheranIonut/Proiect_Final_Vinted_QA/blob/main/Test-Summary.png)

[Test-metrics](https://github.com/CheranIonut/Proiect_Final_Vinted_QA/blob/main/Test-Metrics.png)


<h3> 1.3 Test Analysis </h3>
The testing process will be executed based on the application requirements.

The following test conditions were found: <br>

• Check if the user can access the sell section

• Check if the user can delete a listed item

• Check if the user can add item details

• Check if the user cannot upload more than 20 photos

• Check if the user receives a confirmation message

• Check if the user can save as a draft the item

• Check if the user can finish editing the draft

• Check if the user cannot upload an item leaving the fields blank

• Check if the user can promote (bump) an item

• Check if user can use another card to promote an item

• Check if you cannot increase the price of a bumped item

• Check if you can decrease the price of a bumped item

• Check if the user can use the sell button (+) on mobile devices

• Check if the layout of the description field doesn't break on mobile devices

• Check if you can list another item

• Check if the user can search and filter items

• Check if an invalid filter combination returns zero results

• Check if the user can clear filters

• Check if the user can click on the item image or title

• Check if the user can view the reviews and ratings on a seller's profile

• Check if the user can view his last searches

• Check if the user can save items to favourites

• Check if the user cannot save items to favourites if he's not logged in

• Check if the user can remove saved items to favourites

• Check if the user can purchase an item

• Check if the user can choose a pick-up point for delivery

• Check if the user receives a purchase receipt of his order on email

• Check if the user can zoom in and zoom out on the map of pick-up points

<h3>1.4 Test Design</h3>

Functional test cases were created in Zephyr Squad based on the analysis of the specifications.

[The test cases can be accessed here](https://github.com/CheranIonut/Proiect_Final_Vinted_QA/blob/main/Test-Cases.csv)

<h3>1.5 Test Implementation</h3>

The following elements are needed to be ready before the test execution phase begins:

• Approved test plan

• Completed and reviewed Test Cases

• Test data available

• Functional test environment

• Access to Jira

• Entry and exit criteria

• Product risks and project risks

<h3>1.6. Test Execution </h3>

Test cases are executed on the created test Cycle summary: Ad hoc

Bugs have been created based on the failed tests. [The complete bug reports can be found here](https://github.com/CheranIonut/Proiect_Final_Vinted_QA/blob/main/Bugs.doc)

The following is a summary of the bugs that have been found
**(inserati o lista cu titlurile bug-urilor identificate impreuna cu prioritatea si severitatea fiecaruia)**

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

<h3> 1.7 Test Completion</h3>
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here: **(inserati aici fie o poza cu matricea de trasabilitate din jira, fie linkul catre fiserul excel exportat din jira cu matricea de trasabilitate. Nu uitati sa faceti filtrare dupa type = story)**

Test execution chart was generated and can be found below. 

**(inserati aici raportul de executie generat din jira din sectiunea de dashboards)**

The final report shows that a number **(inserati numarul de teste)** tests have failed of a total of **(inserati numarul de teste)**

A number of **(inserati numarul de bug-uri)** total bugs were found, from which the priority is: **(inserati numarul de bug-uri)** are high and **(inserati numarul de bug-uri)** are medium.

**(inserati aici o concluzie generala a testarii care sa cuprinda cate teste au fost create si executate, ce procentaj aproximativ din cerintele in scop au fost acoperite, daca exista vreo functionalitate pe care nu ai apucat sa o testezi, daca bug-urile gasite impacteaza lansarea produsului in productie sau se pot fixa si ulterior, daca ai identificat riscuri de produs care trebuie mitigate, daca e vreo reecomandare pe care vrei sa o faci pentru lansare, daca sunt ceva lessons learned de care trebuie sa se tina cont la proiectele viitoare etc.)**
