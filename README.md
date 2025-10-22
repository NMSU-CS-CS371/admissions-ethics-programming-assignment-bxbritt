# Part 2: Discussion & Reflection




## **Feature Selection & Design**

**What variables did you include, and why?**   

I included all of the variables because i think they all have significance.  

**Did you exclude any sensitive features? Why or why not?**   

I didn't exclude any factors, but i did consider excluding firstGen and legacy because i thought they were unfair. However, after more consideration, I realized that those two variables even out the scores especially if an individual, for example, Hannah, doesn't meet the other additional factors. 

**Should “legacy” still carry a positive weight?**  

I think legacy should carry a positive weight, maybe not a big positive weight but it **can** corelate to a student's drive/motivation. Since their parents have a background at the college, the student is **more likely** to participate in events and classes which makes them more valuable in the college's eyes. (TRUE IN SOME CASES NOT ALL)
  


**What other features (e.g., proximity, essay strength, disability) might you add or adjust?**

### **test** (weight = 0.1)
  - decreased by 2 because sometimes, standardized tests for college admissions are not an accurate form measurement to represent a student's abilities.
### **essay** (weight = 0.3)
  - increased by 2 because this encourges applicants to think critically about their application and it also provides the university with a sense of who the student is. So if a student has a good essay, that shows how much and why they want to get into the university.
### **firsttGen** (weight = 0.02)
  - decreased by 3 because while it is important for an applicant to be the first gen to go to college, i am unsure if it should be weighted so high (0.05)


## **Fairness & Outcomes**

**Between the blind and aware models, which applicants benefited or lost out?**  

The applicants benefited are low income and first gen, and the ones who lost out are high income (not intentional).

**Which applicants specifically benefited from the aware model?**

- Carlos 
- Fatima 
- George  


**Does adding income or first-generation status make the system fairer or less fair? Why?**  
Yes, I believe it makes it more fair because it gives people a chance to go and an education that they might not be able to afford.

**Which model feels more fair overall, and why?**  
Generally speaking, I think the blind score is more fair because it relies on the student's efforts rather than identity. However, some could argue that a student might not have as much effort if they feel like they are not getting the same chance. 


## Transparency & Accountability

**How transparent is your algorithm?**  
My algorithm is fairly transparent  

**Could you clearly explain a rejection to an applicant?**  
In some cases, I could explain a rejection if its clear. Like if the gpa, essay, or/and test score is low, that may be a factor. But in other cases, it harder to explain.

**Would you feel comfortable if this algorithm evaluated your application? Why or why**  
I don't know if it makes me comfortable or uncomfortable but it does remind me of the systems we have today where middle class, average-scoring students are left to fend for themselves.


## Broader Implications

**What risks might arise if such an algorithm were used in real admissions?**  
People may become angry if the university didnt let them in. One senario this could happen is if a student applies and they have a **3.0 gpa**, **high income**, legacy, but not disabled, nor first gen, nor local. They have a lower chance of getting in compared to another student who is **low income**, **2.7 gpa**, not legacy, nor disabled, but is first get and local. This may spark conflict as some will not to understand this algortihm.  

**What real-world parallels exist (e.g., hiring, policing, scholarships)?**  
Colleges and the Department of Education offer grants mainly to low income, above-average gpa. Hiring may be leinient to diverse candidates.  

**What does this exercise reveal about fairness in algorithmic decision systems?**  
It gives many people access to opportunites they might've not explored.


**Can algorithms ever be truly fair, or do they just shift where bias appears?**  
No, it's extremly hard for algorithms to be fair because the humans behind it have bias. No matter how people try to make it fair, one group is likley to be disadvantaged. 

**How should fairness and accountability be balanced in automated decisions?**  
I think accountability should be weighted more than fairness, beacuse while identity is important, the effort which an applicant yeilds should still be a priority to companies and universities. That doesn't mean that fairness should not have an impact, but i think that the ratio between accountabilty and fairness should be 60:40.








