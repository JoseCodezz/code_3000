# code_3000
Collection of Assignments for CSE 3000: Contemporary Issues in Computer Science and Engineering

_Note_: Odd-numbered assignments are in HuskyCT, while even-numbered assignments are found in this repo and can be submitted to Gradescope via a Github connection.

## Outline of Assignments

### Module 02: Bot Predictor
Your goal is to build a machine learning model using given data and a Python template. You'll make changes to the GradientBoostingClassifer in mod02_build_bot_predictor.py and then test your changes in mod02_test_bot_predictor.ipynb. Can you minimize the misclassification rate on the test set?

### Module 04: Model Bias
You are given a model that was built to predict a mystery variable using zip code, income, and education level. The variable "group" represents a demographic that is prohibited and was NOT used in the model. Your goal is to use the SHAP package to review this model for bias.

### Module 06: Data De-Anonymization
Your goal is to connect anonymized data back to its source data and check the match rate. To complete this activity, write functions in the "deanonymize" script to (1) link the records in the two datasets and (2) calculate the rate at which you are successful doing so. 

### Module 08: Sustainability in Computing
You will be given a toy dataset and have the opportunity to explore the potential effects of choosing sustainable energy sources to perform computations. You'll code the energy calculation in "sustainability calculations" script, and then you can review the results of various decisions in the "check calculations" notebook. 

### HW 9: Personal Statement
I feel like a lot of companies state the same set of values, but at the same time a lot of companies do not follow these values. After reading chapter 5 of Ethical Machines the idea of a value only mattering if it changes what you actually do resonated with the way I felt. A lot of companies say they care about safety or fairnes but if these values do not prevent them from building or shipping a product that can go against these values, than the values they say they have, are of no significance. So when I think about my personal values, I want these to work the other way around where my values are what guide me from not doing something that can go against them. its important to be clear about what I do based off my values and what I will never do, especially if it means it could negativley impact another person or thing.

Recently I did a hackathon at Virginia Tech where my team built a tool that was meant to help healthcare providers with their communication to pharmacists to reduced work friction, called ScriptSync. We created AI agents for individual drugs that answer questions using only offical drug labels. The agents were able to assess whether a drug that a doctor is asking for a patient from a pharmacist is safe, for instance patient A may be on drug A, but the doctor is requesting an order for Drug B, but the Agent that holds info to Drug B and would essentially help place the order will not do it since it could put the patient at risk who is in Drug A. With healthcare, stuff like this needs to be correct and have a 100 percent confidence or else it could hurt the patient.

This bridges into the fact that we value safety and we birdged this to specific commitments. Since we value saety we will always verify our drug agents. We would ensure this agent is registered with a verfied DNS like web browers now, and ensure it has the authority to have conversation with the Health Care Professional Agent, so that both patient information does not get leaked or nor does sensitive information on drugs. There were also guard rails against the agents so they do not "hallucinate" and can only answer within the scope of information provided to it.

The main takeaway from this experience we gained from this was the fact that safety was not a value we stated we had at the end. It was something we had from the start and also used to guide us in building the tool, to prevent patients from potential occurences that could result in injury or even worse death. All this was obviously hypotehtical though since it was a hackathon, but when it comes to real companies, it is important that when they continue to scale, the value that state they have, are used to ensure certain events do not happen if it does not go along with there values, for instance if security is a big value, than do not let users information be easily leaked and so on.