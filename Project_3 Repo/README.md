# Predicting Regulatory Approvals of European Mergers & Acquisitons
Prepared by Rahul D. Raju

# Abstract 
The landscape of corporate mergers and acquisitions is a high stakes game, with nearly 790,000 deals since 2000 valued at over 57 trillion.  There are numerous obstacles to any deal, however, from shareholder approval to combative board directors.  The greatest of these obstacles is approval from government regulators.  Once a merger or acquisition is approved by both companies, any adverse rulings by governing authorities can result in significant cost to the acquiring company.  These costs include wasted time, loss of focus from normal business operations, legal fees, repercussions from shareholders and damage to the reputations of management.  Also, if a merger is denied, the acquirer will typically have a to pay a “break-up” fee to the target company.  These fees can be extremely expensive, typically ranging from 100 million to 1 billion dollars.  Being able to better predict regulatory decisions and the factors employed in making them would enable acquiring companies the opportunity to prescreen potential target takeovers and therefore avoid the cost associated with choosing poorly.  


# Data
The Directorate-General of Competition’s of the European Commission maintains a data set of all mergers and acquisitions decisions in Europe from 1990-2014.  The set contains a total of 5,196 merger decisions, with 31,451 observations. 
Website:  https://www.diw.de/en/diw_01.c.670982.en/pages/research_data_center_for_business_and_organizational_data__rdc-bo.html#c_809915


# Methodology/Algorithms
A Classification algorithm is considered appropriate for this type of assessment as it provides the ability to predict qualititative outcomes.  There are multiple algorithms that can be used for classification, however, logistic regression was chosen for this purpose. Logistic regression would provide a scale from 0 to 1 that implies the likelihood a decision would fall into the approval or disapproval category.  Since the regulatory process is mult-faceted, mulitiple regression models would be used at each stage of the process.  Certain features of all past regulatory m&a decisions could be used to determine what factors have had the greatest impact on their respective decisions.  Changes in coefficients at each stage of the process could also be assessed to measure the changing correlations at each stage of the process.  



# Tools

1.  Data Acquisition/Cleaning/EDA
    - Google Sheets
    
2.  Data Visualization
    - Tableau    


# Results Summary

The biggest factor affecting regulatory decision making is the impact proposed mergers 
have on competition.  A focus was placed on features that attempt to quantify competiton.  
This included:

- Combined market share of merged entities
- Number of Competitors
- Competitive Concern
- The Herfindahl-Hirschman Index(HHI), representing market concentration
- Barriers to entry
- Complexity of underlying industry

