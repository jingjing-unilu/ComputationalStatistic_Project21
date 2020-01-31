#### This project could be found at https://github.com/BraveJean/ComputationalStatistic_Project21
# ComputationalStatistic-project
ComputationalStatistic-project@UNI_LU
# Project 21 : Compairing two given random requences
- Author: Jingjing XU  /  Student ID: 0180092002  / University of Luxembourg
- Advisor: Prof. Raymond Bisdorff

- Description: This project concerns the validation or not of the claim that two given random sequences, X1 and X2, each of length 10000 : see http://sma.uni.lu/bisdorff/CompStatDec18/project-21Data.csv have been obtained from the same RNG.

- Tasks:
    1. Compare statistically and graphically the two given random sequences X1 and X2.
    2. Are the given sequences X1 and X2 potentially drawn from the same RNG ?
    3. Motivate your answer with arguments taken from the Computational Statistics Course.

- Content:
    1. get data

   - Content:
    1. get data
        1.1 Correlation Test
        
    2. Distribution Test
       - 2.1 Equidistribution Test (Frequecy Test)
            - 2.1.1 Chi-squared Test（chisq.test）
                - 1）Test if 'X1' , 'X2' is uniform distribution.
                - 2）Test if 'X1' and 'X2' is from same uniform distribution.
            - 2.1.2 Kolmogorov–Smirnov test (ks.test)
            
        - 2.2 Gap Test (gap.test)
            - 1) From 0-0.5
            - 2) From 0.5-1.0
            
        - 2.3 Serial Test (serial.test)
        
        - 2.4 Equidistribution Test (Use Frequence Test-freq.test)

    3. Conclusion
    4. Acknowledgement
    5. Reference
