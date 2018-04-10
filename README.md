# DataScience_session11_assn
Consider a DataFrame df where there is an integer column 'X': df = pd.DataFrame({'X': [7, 2, 0, 3, 4, 2, 5, 0, 3, 4]}) For each value, count the difference back to the previous zero (or the start of the Series,whichever is closer). These values should therefore be [1, 2, 0, 1, 2, 3, 4, 0, 1, 2]. Make this a new column 'Y'. 
