# Mitigating duplicity of questions using ensemble learning: A quora questions case study.ipynb
Multiple questions with the same intent can cause seekers to spend more time finding the best answer to their question, and make writers feel they need to answer multiple versions of the same question. Quora values canonical questions because they provide a better experience to active seekers and writers, and offer more value to both of these groups in the long term.

1. Problem Statement 

* Identify which questions asked on Quora are duplicates of questions that have already been asked.
* This could be useful to instantly provide answers to questions that have already been answered.
* We are tasked with predicting whether a pair of questions are duplicates or not.

2. Real world/Business Objectives and Constraints 
 * The cost of a mis-classification(error) can be very high.
 * Thus we would want the probability threshhold of a pair of questions to be  duplicates high.
 * No strict latency concerns.
 * Interpretability is partially important.
