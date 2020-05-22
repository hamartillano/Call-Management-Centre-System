# Call Management System - Business Report

## Project Objective
As per the request of a major travel company, our team has been given the opportunity to develop a information system which will aim to improve the daily operations of the companies in-house call management centre (CMS). Moreover, our development team's purpose is to examine the current business processes currently in place within the company and analyse what aspects of the system is to be changed as per the stakeholders request. By finding out the problems of the current processes of the business, our team will be able to brainstorm viable solutions which will improve effeciency and effectiveness of the CMS.

- Improve current business processes of the call routing system.
- Improve relationship manager to customer profile matching system.
- Create a visual interface for users to go along with phone system.
- Reduce wait times of customers.

## Problem Definition
The major travel company is looking to implement a system which will utilise a "profiling tool" to match relationship managers with the appropriate customer. Additionally, the current business processes of the major travel company does not have a means of settings up the right relationship manager with the appropriate customer which is causing the company to lose sales as customers are left dissatisfied. Furthermore, the current business processes of the travel company lacks the ability to cater to a large amount of customers at a given period which is forcing many customers to be put in queue with wait times. With many customers unsatifised with the wait times and being pair with a relationship manager with a low similarity index, customers are left unsatisfied leading to decreased sale success and effeciency. In order to improve the current business processes of the travel company, the system which handles all in-bound and out-bound calls needs to be improved to reduce customer unsatisfaction rates.

## Stakeholders
- CMC Company Manager
- Relationship Managers
- Profile specialists
- Customers
- Flight agencies
- System Administrators

## Assumptions of current business processes
- One phone number for the entire travel company
- All in-bound calls are redirected to profile specialists sector which asks the caller a set a questions regarding background, culture and preferred destination.
- All out-bound calls made have been determined by the profile specialists to match the profile of the relationship manager making the call with a customer of similar profile.
- Current customers are able to be connected directly to support relationship manager by stating their identification code.
- Information (profile and skills matrix) of registered customers and hired employees are kept in the central database of the company.
- Customer scores are recored by the corresponding relationship manager and is saved into the database.
- All in-bound calls ask the customer for their identification code, this will be used to access their sales score and be put into a priority queue (high scores) or standard queue (low scores).
- The current "Profile Tool" used only takes into account an individuals surname and residential postcode.
- All employees are required to complete 2 forms; a profile questionnaire and a skills/expertise questionnaire. This is done upon being hired by the travel company.
- A relationship managers skills/expertise may be subjected to re-evaluation if sales performance is decreasing.
- During busy periods, in-bound calls may be transferred to first available relationship manager. Relationship manager and customer pair may not have matching profiles but are skilled in destination of choice.
- Customers are able to opt out of queue during busy periods but will lose their place in queue.

## Point of View Statements
### CMC Company Manager
- Customer's working busy lives dont have time to research and plan vacations during holidays. Customers need to be directly shown what they want to reduce the stress of actually finding what they desire.
### Profile Specialists
- With numerous customers looking to consult with a travel specialist on a given destination, they need to be catered to in the quickest possible time frame so that do not need to waste time on researching their destination themselves.
### Relationship Managers
- Customer's will find it difficult to be satisfied with sales pitches because they dont trust the other person on the phone. They need to be given the opportunity to trust who theyre talking to so that they engage with the sales pitch.
### Customers
- Call centre salesmen/saleswomen make sales pitches sound boring and unenticing because the person making the call sounds like a generic, automated response. Salespeople need to clearly engaged with the customer so that I dont get the impression that the sales pitch it scripted.

## How, Might, We (HMW) Statements
### CMC Company Manager
1. How might we improve sales by 15% next period?
2. What might we do to help relationship managers achieve higher sales pitch success?
3. What might be holding customers back when coming into contact with our company?
4. How might we find new techniques to improve overall customer satisfaction and response rate?
### Relationship Managers
- How might we improve sales pitch success to our customers so that they are not left unsatisfied?
- What can we change about our sales tactic to get a better impression on customers?
- What makes customers uninterested in the sales pitch being given?
- What is stopping us from increasing sales pitch success?
- In what ways could we improve customers responses so we can get an idea of what should be done?
### Customers
1. How might we improve sale pitch success to our customers so that they are not left unsatisfied?
2. What can we change about our sales tactic to get a better impression on customers?
3. What makes customers uninterested in the sales pitch being given?
4. What is stopping us from increasing sales pitch success?
5. In what ways could we improve customers responses so we can get an idea of what should be done?

## Empathy Maps
### Customers
Emotion | Description
:---: | ---
Think and Feel | Feel like they want to go sometwhere. Think that they don't know where to go.
Hear | Friends and colleagues discussing places they have visited.
See | Potential holiday destinations.
Do and Say | Call up to buy packages and tell their friends about them.
Pain | Fear of not getting the holiday they want.
Gain | Hopes to get a product they need.

### Company Manager
Emotion | Description
:---: | ---
Think and Feel | Think that their system needs improvement, they feel like it could be more efficient.
Hear | That their customers are not fully satisfied from their system.
See | Customers buying travel packages using their service.
Do and Say | Manage the company and relay it to their shareholders.
Pain | Afraid of getting less profit and losing investors.
Gain | Hopes that with an increase of efficiency their profits will go up.

### Relationship Manager
Emotion | Description
:---: | ---
Think and Feel | Think about how they can be more effective, feel like the current system has flaws.
Hear | Their work colleagues complain about the system.
See | Customers buying packages they tell them about.
Do and Say | Reply to the customers calls and advertise their products.
Pain | Afraid of not meeting the sales quota.
Gain | Hopes that with a new system it will be easier to get sales.

### System Administrator
Emotion | Description
:---: | ---
Think and Feel | Think that the system can be built better. Feel like they have to put too much effort to maintain the current system.
Hear | The users complaining about the system.
See | The users struggle with the current system.
Do and Say | Work on upkeeing the current system and talk to the managers about it.
Pain | Fear an issue can arise that they cannot fix.
Gain | Hopes the new system will fix the current issues.

## Product Backlog
User Story | Priority | Estimation | Acceptance Criteria
--- | :---: | :---: | ---
As a relationship manager, I want to be paired up with a customer of similar "Profile", so that I can bettter relate with the customer. | High | 9 | Relationship manager will be connected to a user with a similar "Profile" based on age, sex, culture, language proficiency, experience and product knowledge
As a customer, I want my call to be taken quickly with little waiting time in order to save time. | High | 9 | The average waiting time in que for a customer is decreased significantly compared to the previous system.
As a flight agency manager, I want my flights to fill up with customers so that my resources are used efficiently. | High | 8 | The sales rates of flights goes up and the flights have more people flying on average.
As a customer, I want to be connected to a relationship manager with extensive knowledge regarding the travel destination I wish to go to, so that I am well informed and given proper guidance and knowledge. | High | 7 | Customer is connected to a relationship manager who has been acknowledged as highly informative regarding the chosen travel destination. 
As a relationship manager, I want to complete a "Profile" questionnaire, so that my "Profile" can be acknowledged within the system. | High | 6 | Relationship managers are able to complete a questionnaire which asks for their age, sex, culture, language proficiency, experience and product knowledge forming the foundation for a "Profile" and "Skill Matrix".
As a relationship manager, I wish to have a stable system where I can take calls with no issues. | Medium | 7 | The system has very little downtime and does not crash frequently.
As a CMC Company Manager, I want to check each relationship managers sales performance, so that I can evaluate whether the relationship manager effectively and effeciently performing sales. | Medium | 6 | CMC Company Manager's can display all relationship managers sales performance in a table and can click on a specific employee to display sales information and performance.
As a relationship manager, I want to check my sales performance and information, so that I can evaluate my own performance and improve on aspects which are showing low effectiveness. | Medium | 5 | Relationship managers will be able to check their sales performance as a pop up window, displaying their success rate, total sale opportunities (number of customers), dates of sales and line graph showing daily customers.
