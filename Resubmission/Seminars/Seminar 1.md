Q1: What is GAP/CVA/IVA analysis?

1.	GAP Analysis: Gap analysis means in the process of strategy implementation, compares the customer actual performance with strategic performance expectations, then strategy evaluation and revision [1]. Actual and desired business performance compared to usually will produce gap, gap analysis is mainly to analyze the causes of the gap, and puts forward some methods to minimize or eliminate the gap.

2.	CVA Analysis: The customer value analysis is composed of many analysis methods, to understand the company's customers, competitors and market [1]. Its application process is: first, develop close relationship with customers, after make the formal customer value analysis, finally carries on the customer value strategy management

3.	IVA analysis: Internal value analysis is used to measurement of products is in line with the company's other products or policy limit of spiritual resources [1].

________________________________________

Q2: What tools are available for Continuous Integration?

A: There I find 6 open source continuous integration tools: Jenkins, Buildbot, Travis CI, Strider, Go and Integrity. I choose to further understand the Jenkins, Jenkins provides a large number of plug-ins, can help users to improve efficiency, it can manage different user permissions, such as the admin is the highest administrative rights, have all permissions, readonly only read permission, etc.[4] here we can set up multiple grouping according to specific circumstances, different permissions. And then set "Project roles," Role to add to fill in the group name, the Pattern fill in grouping rules. It also can create jobs, source code management, etc, because this is my first time know integration tools, so many functions I’m not know clear.

________________________________________

Q3: What is technical product management?

A: Product manager at the core of the work is to provide the product vision, create a roadmap, and promote its execution [2], and technical product manager is on the basis of this, has the certain development foundation, and can use technical skills to improve prioritization and planning and leverage technical skills to close the communication gap between engineering and the rest of the world.

________________________________________

Q4: What is roadmapping? How can you do it large scale?

A: Roadmap is the product manager to manage the product of a long-term planning, major have time cycle and project events and road signs of three parts [3]:

1.	Time cycle: That is, product planning time interval. Usually, the length of time cycle is product major version (such as 3.0.0-4.0.0) 3 ~ 5 times of the development cycle, if the large version of the development cycle is 3 months, then Roadmap time cycle length is between nine months to 15 months .

2.	Project events: Refers to the finished product overall plan must be to complete the work item.

3.	Sign: Refers to the time to contact the key to the completion of the work item, also known as the milestone.

In large scale, user requirements can be rapidly changing in market environment, roadmap is let people to know the future of the products, accomplish know fairly well.

________________________________________

Article 1: Requirements Abstraction Model

In market-oriented requirements engineering, software requirements have different shapes and forms to development organizations. The author provide a RAM model which is ability to handle the company requirements on multiple levels of abstraction in software requirement engineering effort. The RAM has 4 mainly benefits:

1. Requirements will compare to the product strategies to offer an assurance that requirements will not violate the overall goals set by the management. 

2. Requirements will be broken down to an abstraction level in suitable way for initiating a development effort. 

3. Work-up of requirements that they will formulated on the same level of abstraction, so that they can be set against and compared one another. 

4. All requirements give a richer understanding of each requirement which through several levels of abstraction.

The RAM has 3 main step that is specify, place and abstraction. There are four levels in RAM that are a product, feature, in specify step, author specify these four feature concreteness. Then in place step, the requirements are broke down to function level. In the abstraction step, the requirements are broke down if it is in abstract state or create some new requirements to make it abstract so it can be compared. To make it easy, the authors provided a manual as a guides to use this model when we place a requirement.

My Reflection:  I think RAM model is very necessary, because it will divided requirements into different levels such abstract level to another level. I agree with the author of this model is very important, because there is no other model in this industry is also a good way to evaluation results. It also help team to achieve requirements in an organized way. At the same time, the author mentioned RAMv2.0, requirements engineering and project will be integrated to improving the model to further extend the support and the usage of the model.

________________________________________

Article 2: A Method for Early Requirements Triage and Selection Utilizing Product Strategies

This paper presents a method that utilizes strategies for early requirements triage. Mentioned the whole process of MERT Specify, assign weights, compare the requirements, after the early requirement triage, then do the requirements Selection for Release.

Early Requirements Triage has 3 steps: 

First step is specify to explicitly state goals and objectives for the product, through answer 3 question: (1) Where we want to go? (2) How to get there? (3) What will be done? of products. 

Step 2 is assign weights, at this stage we will assign a suitable weights to the requirement of each question to judge the value of that.

Step 3 is Compare Requirements. By comparing the weight of each requirement to priority requirements. 

After early requirement triage, the author shows how to select requirements for release. The author also shows specify product-technology roadmap and estimate resources way can be implemented through a variety of tools.

My reflection: The author through literature to support a series of requirement for early planning, and that it can be used in different size of the company. His specific requirements analysis process description is very fuzzy, mostly by answering some questions like "where to go", "how we get there," and so on, but there is no clear demand for a specific standard, this is me a bit more confused. At the same time, the article also mentioned at the end, the author did not verify in the interview, brainstorming whether it is feasible to early requirement mining approaches.
________________________________________

Article 3: Requirements engineering: In search of the dependent variables

In this paper, the authors think that the quality of using SRS as the dependent variable is flawed, so this paper proposes a framework as the dependent variable requirements engineering quality evaluation as an alternative method. The author the dependent variable is divided into five different levels, respectively is the requirement phase, project, product, company and society, their relationship is linked together. 

At the same time, the article mentions of the same tools, e.g., GAP, CVA, and IVA, can be used to help us choose products way to keep a balance between high risk, high return and low risk, low return.

My Reflection: Based on dependent variables analysis, this article tells us in the positioning of products, we need a multi-angle thinking, want to realize the necessity of strategy forward, at the same time we define product strategy should reflect the long-term goals, and these goals must be consistent with the current market and technology. But overall, the article gives a conceptual analysis, not combined with a lot of practical experience, so whether this can be applied to the company's real needs more research is needed in the analysis (requires an instance).

________________________________________

Article 4: Quality Requirements in Industrial Practice—An Extended Interview Study at Eleven Companies

This article through the way of practice, hope to find a different company, between different categories of products, the balance of their functional requirements and quality requirements.

This paper answers the answer the four research question:

1.	The first question is to find which quality requirement is most important according to different company. According to The results, B2B and B2C have different priority to understand, but usability get most points.

2.	The second question is the study of the quality requirements and functional requirements and common interdependent relationship. We can see that B2B and B2C has a different choice.

3.	The third question is about cost estimations. The study found that the quality requirements and functional requirements of estimation didn't distinguish, at the same time, there are no difference between B2B and B2C of cost estimation of quality requirements.

4.	The last question is the study of dismissal and the connection between quality requirements. From the result we can find, for B2C, performance requirements are more often dismissed due to the difficulties in proper estimation. For B2B, QR that are not visible to the customer, such as maintainability and testability, are dismissed more often than other QR. The result reveals three main reasons for dismissal of QR: Poor cost estimations, lack of resources, and QR have lower priority than FR.

Through 11 software company's data collection and analysis, the author found that the B2C, usability is considered to be the most important QR, for B2B, safety is the most important aspect. 

My reflection: This article gives a good idea to let us to know the quality of the balance between quality requirement and function requirement, but in some actual projects, there may have some software are both 2B and 2C, at the same time for quality and functional requirements of the control may need more discussion and analysis. The previous article (Requirements engineering: In search of the dependent variables) has in the search of the dependent variables mentioned five level of quality may be as an analysis and reference, and can applied to practice.

________________________________________

Article 5: A cost-value approach for prioritizing requirements

Software application development goal is to meet the needs of the masses, and meet the all customers’ requirements during developing is impossible, so there is necessary to find a way to select valuable requirements from a lot of requirements. This article analysis tool is used for priority development requirement of the cost value method, and it successful application in two companies.

This analytical tool considers three factors: quality, time, and cost. The cost-value approach consists of five steps as follow: 

1. Requirements engineers review the candidate requirements to ensure that are stated in an unambiguous way.

2. Users apply AHP’s pairwise comparison method to make an assessment of the relative value of candidate requirements.

3. Use AHP’s pairwise comparison to estimate the cost of implementing each requirement.

4. Build the cost-value diagram based on the data.

5 .Stakeholders use the cost-value diagram to discuss and select the candidate requirements for release planning.

My reflection: I think the author proposed this method can help us to prioritize the requirements by analyzing them through cost and value. But at the same time, this method also ignore the dependency relationship between the requirements, in fact we need to consider not only the cost, but more need to consider the strategies as well as the requirements’ impact.

________________________________________

Reference

[1] Gorschek T, Davis A M. Requirements engineering: In search of the dependent variables[J]. Information and Software Technology, 2008, 50(1): 67-75.

[2]” What is a Technical Product Manager, Anyway?” http://www.mindtheproduct.com/2014/05/technical-product-manager-anyway/

[3] “Roadmap：Product blueprint for how to design”, http://www.woshipm.com/pd/144905.html

[4] “JENKINS summaries” http://www.cnblogs.com/ceshisanren/p/5639869.html
