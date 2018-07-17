# Insurance-Claims-EDA-and-ML

##                                        Predictive analytics in health insurance

Insurance industry is using advanced analytical techniques to better understand customers. Managing the member experience by gaining analytical insights is critical for payers as the health insurance marketplace becomes more competitive every year. Adding value with personalization helps insurance providers create meaningful relationships with members, fostering an environment where customer loyalty can thrive. As a win/win for members and insurance providers, it pays to be proactive with wellness programs spurring long-term health, informed by better insight into member health across a number of corresponding factors.

### Cost Bucketing : 
Let’s break down the business impact of chronic disease on insurance payers today: according to Centers for Disease Control, chronic diseases account for 84% of the nation’s health care costs i.e, 80% of the overall cost of the nation’s healthcare cost originates from only 20% of the most expensive members.
To reduce noise in the data and at the same time reduce the effects of extremely expensive members (who can be considered outliers), members’ costs are partitioned into five different bands or cost buckets. It is partitioned in such a way that the sum of all members’ costs is approximately the same in each bucket, i.e., the total dollar amount in each bucket is the same.

### Claims Financial Analytics :
It is all about analyzing all your claims data and gaining new knowledge to solve your most pressing health care issues. It can help payers reduce costs and access critical insights as they transition to value-based care.
The data here is the claim data for two years(2008 & 2009).

Attribute Information:

                 Name		         Description
	              -------		       -------------
	           age                         age of member
               alzheimers                  binary(0&1)
               arthritis                   binary(0&1)
               cancer                      binary(0&1)
               copd                        binary(0&1)
               depression                  binary(0&1)
               diabetes                    binary(0&1)
               heart.failure               binary(0&1)
               ihd                         binary(0&1)
               kidney                      binary(0&1)
               osteoporosis                binary(0&1)
               stroke                      binary(0&1)
               reimbursement2008           reimbursement amount for member in year 2008
               bucket2008                  Cost bucket to which member belongs in year 2008
               reimbursement2009           reimbursement amount for member in year 2009
               bucket2009                  Cost bucket to which member belongs in year 2009




Objective of project is to determine the bucket to which individual belongs based on what diseases he/she has.
