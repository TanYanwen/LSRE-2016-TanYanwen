Q1: Read up on the Boston Matrix

The Boston Matrix is a planning enterprise product combination method, which guides the enterprise's product variety and structure to adapt to changes in market demand [1], at the same time, the limited resources of enterprise effectively assigned to a reasonable product structure, so as to ensure the profit of the enterprise, this method is the enterprise in the fierce competition to win the key.

There are four different types of matrix product types [1]: First, sales growth and market share "double high" of the product group (star products); Second, Sales growth rate is low, the market share of the high products group (cash cow products); Third, the high sales growth, market share, low product groups (problem products); Four, sales growth and market share "double low" product group (thin dog products).

________________________________________

Q2: How do you connect your requirements to your architecture?

Requirement can be divided into functional requirements and non-functional requirements, among them, the function requirement will influence architecture, architecture must adapt to the functional requirements, but functional requirements will not decide to architecture [2]. For example, whether based on interface programming or hard coded to implement function, are not functional requirements can be determined separately.

Non-functional requirements that quality attributes, etc., will fundamentally affect the architecture [2]. For example, a software which pay attention to the performance of the system may concentrate on the algorithm, and decided in the design of architecture is done to avoid the loss of performance.

At the same time, the functional requirements, non-functional requirements and architecture exists between constraints [2]. It is often a limiting conditions for architecture design, and can be transformed into functional requirements or quality attributes. For example, a customer put forward "the software must use the Windows platform" is the restrictive conditions, a customer put forward "interest rates have to be with the national unity" can be transformed into "system should rates can be configured" functional requirements, a customer put forward "the software should accept the country's financial institutions audit", is transformed into the non-functional requirements of security.

________________________________________

Q3: Can you connect all requirements directly? What do you do if you cannot?

A: No. Requirement is hierarchical which divided into three categories: business requirements, user requirements and development requirements. User requirements may come from business requirements, and development requirements may from the user requirements. To connect these requirements, we can be derived by way of two-dimensional matrix of requirements to find the legacy requirements [3]. Two-dimensional matrix concrete as shown in figure (because I don't know how to upload pictures directly, so the images are presented in the link: http://pan.baidu.com/s/1o7SnPMU) by two-dimensional matrix to analyze the demand and function, quality, the relationship between the constraints, in order to determine the relationship between each other.

________________________________________

Article 1: Towards a Reference Framework for Software Product Management

This article provide a framework for a body of knowledge for software product management, the structure can divide into 4 parts: Portfolio management are aim to look market trends and product development strategy, Product roadmapping are used to plan purpose of software products, Requirements management are contains the activities of gathering, identifying, revising and organizing incoming requirements from the various stakeholders and Release planning are make a prioritization and selected the implemented to give to stakeholders.

My reflection: This article systematically introduces the complete process of requirement analysis, concrete process, but the real analysis is not every step of the analysis report, but to think about what our behavior to satisfy the people's interests, the logic is correct. When we are using these tools, accurate requirement analysis is on the business model and profit model of the process of the correct understanding.

________________________________________

Article 2: Market-Driven Requirements Engineering for Software Products

This paper taking the market as the guidance of requirements engineering. The author points out that the software product has two dimensions: one is a degree of customization, another is the content of the hardware and software. The degree of customization is generic products, customized products, and customer specific products. In hardware and software there includes three classes, one is the pure fixed in the specific hardware architecture hardware products, products include embedded system hardware and embedded software, pure software independent hardware products. In some cases, MDRE and customer specific development does not contain so many different software development mass market that can be customized to specific customer and sales.

In MDRE, the main goal is to deliver the right product at the right time, and have to face the competition, and the success of a product is based on sales and comments. Software product development is based on customer needs, and predict the future product and competition. So in MDRE more custom products of evolution is necessary. Creating new requirement elicit to innovation requirements and analysis of market requirement of the products. Product development organization under the background of MDRE main consideration release plan, cost estimation, and priority. Product validation in MDRE can do in the final stages of development.

My reflection: The author explain MDRE in the process of software products, and these challenges in MDRE process which need to take care of during the manager. The technology and method provided by the author but MDRE need more methods and techniques, as requirement will arrive in continuous flow, time should be used in an optimized way. Also in the process of MDRE, requirement flow between the two companies is not the same so they need to adjust, choose to suit their situation of methods and techniques. The authors describe MDRE process and its complexity in good way, it is easy to understand.

________________________________________

Article 3: Scaled Agile Framework: http://www.scaledagileframework.com/

Richard Dolman and Steve Spearman set up a website, where they made a comparison matrix is used to view the different large-scale agile methods. They say the goal of contrast is:

1. Try to use objective criteria for one of the most popular agile framework were compared.

2. A model can be used to compare analysis.

3. A large number of reference to the author, industry leaders and others review as agile framework contrast "opinion".

The model can be used when an organization has more than three or four agile teams need to work together, no matter how will face some special challenges. Most large-scale agile framework attempts to provide the corresponding ideas or technology, the organizational level to help large agile teams work together, the less cooperation team to four, much to the hundreds, and the team may be distributed in various places. The definition of other large-scale agile may be beyond the category of IT, such as in business operations or other aspects of the pursuit of agile organization. The requirements are not in the current popular methods for effective support.

My Reflection: I think, this is a agile methods contrast model, it is not applicable to all large enterprises, so must do a lot of research before use, so as to find the most suitable for their experience and demand model. What is the best way to do large-scale agile and what is suitable for large-scale framework, there are too many different perspective, and also need more analysis and research in this aspect.

________________________________________

Article 4: Are you biting off more than you can chew? A case study on causes and effects of overscoping in large-scale software engineering

This article use a case study to find overscoping in large-scale, market-driven software development projects how agile requirements engineering affect these situation. The studies company use milestones to manage the project. And there are some agile RE practices considered in the company:

1.	Cross-functional development teams are the teams which consists of all working filed members.

2.	Integrated requirements engineering in the RE tasks are integrated with other tasks in project.

3.	User stories and acceptance criteria need to be developed. 

Through the conducted case study the authors list the causes for over scoping are:

1.	Continuous requirements inflow from multiple channels

2.	Low development team involvement in early phases

3.	Requirements not agreed with development team

4.	Detailed requirements specification produced upfront

5.	Unclear vision of overall goal

6.	Weak process adherence

My reflection: The author analyzes the causes and effects of overscoping, these can help the company to screen their project whether these problems. The results indicate that overscoping is mainly under caused by the fast - moving market - driven domain in which the case company operates, and how this inflow of requirements is managed. The author after study should be expanded to more areas, in response to different methods of software engineering and market to know how overscoping effected.

________________________________________

Article 5: Exploring factors affecting decision outcome and lead time in large scale requirements engineering

Decision making is an important part of the process at the same time choose whether be included or rejected. Several characteristics that make this decision and we need to consider the relation between them. In this article, the author conducted a case study of two-stage Company, follow the stage door model management requirements.

According to the study of this article, the sooner the company has more features, will be later than the version release it takes more time. In addition, another finding is that the relationship between the two to make a decision at the time is same for all releases. Then the relationship between the types of customer, their influence in the decision of the replacement is that small businesses have the opportunity to give the important customer types, but in the process of large-scale MDRE, don't have much importance to the customer. The decision of the product and some influence decision-making, most will be rejected and large industry, which had little effect on the result of the number of project decisions.

In addition, this is a case study company only a log data are insufficient to generalize the results with the results in this paper. Then release quantity and decision-making results have the same problem, generalized the result is not as investigation object, the author mainly provides from custom project research firm market driven and release number, the relationship between the final decision result is not the same, so we can't say that we get the answer. And the type of customer and decision outcome relation will be more acceptance of issues when the customer is more important and less acceptance for the customer with less importance.

My reflection: I think this paper provides the difference decision making strategy in large scale and small scale industries. But the survey most are with small-scale industry respondent and the authors can be more in-depth study.

________________________________________

Article 6: An industrial survey of requirements interdependencies in software product release planning

Identify requirements mutual dependency is a complex task, only 20% of the requirement is responsible for the interdependent relationship. In this article, the author's purpose is to know the nature of the interdependence and classification support release plan. With a survey of five different companies, by small, medium and large companies. Requirements in each company manager (here requires a manager can be a product manager, project manager, engineer) asked to choose the requirements of the top 20 is a higher priority, from these dependencies between each pair of requirements is necessary.

Some type of interdependence relationship need time, ICOST CVALUE. RM shall have the right requirement to add a new relationship but in this study there did not determine the relationship between the new requirements. Results show that the most common type is a value by ICOST and CVALUE. These requirements may affect the cost or value of another requirement. Then type that is associated with other two companies, which is the most interesting aspect of products for the market or under the condition of the interdependence, between the valuable related is more common and custom development projects related functions mutually dependent relationship is the most common.

My reflection: I think the interdependent relationship between requirements helps to distinguish and choose to release plan for each release program, so there will be a working software to achieve. At the same time, the author said it is necessary to further study as test the interdependent relationship between the results, the survey also should improve visual requirements. I think through improving these can work in a large-scale industry.

________________________________________

Reference

1.	Boston matrix analysis for Procter & gamble, http://wenku.baidu.com/link?url=uFqL_exTBjkiCWOxwpXJODYU_fYBasAyrINjwl-UgOo0R_7A20uLQWK3JtOteG47uUpG5gButNySC0bCk9TPF-HD8X6NGcFsmYyXpi6tLqW

2.	Software architecture of the non-functional requirements, http://www.docin.com/p-225137298.html

3.	How to develop the requirements analysis of software architecture, http://www.tuicool.com/articles/b2uymy

