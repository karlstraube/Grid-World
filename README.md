# Grid-World

Deep-sarsa is the program with dynamic obstacles in which we are trying to extract q-value / weight updates.  The default program deploys an untrained agent.  To deploy a a trained agent, swtich "False" to "True" for self.load_model in line 20 of the deep_sarsa_agent.py file.  For comparison, I included the regualar sarsa program that successfully utilizes weight visualization.  However, the obstacles in sarsa are stationary.  
