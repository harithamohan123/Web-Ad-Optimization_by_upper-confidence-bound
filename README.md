# Web Ad Optimization using upper confidence bound - Reinforcement learning
________________________________________________________________________________

In this project, we find the click through rate(CTR) of certain advertisement.                                                                
Eg : Companies publish lot of Ad in Social media platforms / websites. If a Publisher post 5 different Ad , fomr that out of which has a larger click through rate is measured.                                                                                                            
                                                                                                                                  
UCB : Rather than performing exploration by simply selecting an arbitrary action, chosen with a probability that remains constant, the UCB algorithm changes its exploration-exploitation balance as it gathers more knowledge of the environment.                                                             
                                                                                                                            
Multi-armed bandit : One real-world example of a multi-armed bandit problem is when a news website has to make a decision about which articles to display to a visitor. With no information about the visitor, all click outcomes are unknown.                                                                
                                                                                                                             
Procedure:                                                                                                         
=> Analyse the problem that is need to be found.                                                                                       
=> Collect dataset of different Ads with its CTR.                                                                                
=> Load dataset and summarize detials such as number of rows and columns (total 10 Ads).                                          
=> We deal with a multi-armed bandit problem that consist of two concept Exploration and Exploitation.                                       
=> Upper Confidence bound is used. It is a deterministic algorithm.                                                                             
=> Clculate the Confidence interval and average same confidence interval for all case.                                                     
=> Based on reward confidence interval shifts. Based on current upper confidence bound one with highest is chosen to explore.                                   
=> Visualise result   .                                                      
