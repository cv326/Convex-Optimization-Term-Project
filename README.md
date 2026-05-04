# Convex-Optimization-Term-Project
Repository for Phase II – Report Development of Term Project

# Running Instructions
Our project was created in a Google Colab Notebook and so all the packages, libraries, environments, and data dependencies should be self contained in that notebook. One should be able to just click the 'run' button to replicate the results in the report.
In our report we also used several images not currently in the codebase. There is a comment with the different image numbers that you can use and replace the number in the img_path_1 variable. (Other images were cut out of final codebase to ensure it remained concise). 

# LLM Disclosure: 
**Notebook LLM:** 

**URL:** https: //notebooklm.google.com/notebook/71b300cd-7459-4514-a576-5b9620dc9d38 

**Dates Used:** April 18, 19, 20, and May 3

**Where used:** Used to better comprehend the algorithm and its individual components. This information was used to inform the report part of the project. Prompts and answers can be seen the chat link given. To verify the information, the papers cited in the report were checked to ensure that information was correct and being clearly understood. The outputs were not directly put in the report but rather used as another source of information for better understanding. 


**ChatGPT:**

**URL:** https://chatgpt.com/share/69f8004b-408c-83ea-900e-a048e135631d

**Dates used:** May 2 and 3

**Where used:** Used to help with the code implementation for the first update (u-update in code). Because the implementation of ADMM is being applied to 2D matrices, the operational complexity balloons. This piece of code requires some more advanced matrix manipulation, which I was having difficulty translating from the theoretical knowledge in the papers to code. This code was used to help implement this section of the algorithm to ensure the step was implemented consciously with respect to space complexity. The output indicated 2 linear algebra functions (LinearOperator and conjugate gradient) from a library that could be used to solve the linear operator. The steps taken to verify the validity of this code were referencing the papers listed in the citations to trace whether the functions implemented in the code could be directly mapped to functions presented in the papers. Additionally, the documentation on the two new functions was looked up to validate how they were supposed to be used. This LLM was also used to help generate a several lambda and rho values for testing to create a spread of different values to sample from. All prompts and answers visible in link. 

  
