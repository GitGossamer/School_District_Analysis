# School_District_Analysis
Module 4 - Pandas
# Overview of the school district analysis: Explain the purpose of this analysis.
Due to suspicion of academic dishonesty, I was tasked with replacing the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. This analysis report describes how these changes affected the overall analysis.
## Results: Using bulleted lists and images of DataFrames as support, address the following questions.
*	How is the district summary affected?
o	There doesn’t seem to be a significant change in overall scores between the before (with 9th graders) and after (without 9th graders) scores.
 ![District Summary](https://user-images.githubusercontent.com/96449605/151862672-86211a45-b2cc-4f96-a765-3f522cb6885d.png)

*	How is the school summary affected?
-	The impact on the school summary seemed favorable. Taking THS as a sample school…
	Passing math % improved by 26.3%, moving from 66.9% up to 93.2%.
	Passing reading % improved by 20.9%, moving from 69.7% up to 90.6%.
	Of note: overall passing % remained the same. This is something that may require further investigation since both math and reading % increased.
Before:
 
![School Summary 1](https://user-images.githubusercontent.com/96449605/151862954-81d9cef7-a2d1-4975-a8b1-6ec9d26d311e.png)


After:
![School Summary 2](https://user-images.githubusercontent.com/96449605/151863017-b0a48439-bce4-4267-b341-954254c42152.png)

*	How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
THS sits right in the middle in terms of school rankings. Replacing the scores didn’t seem to have an impact on changing the average scores for both reading and math. Overall, they remained the unchanged. That said, as noted above in the previous question’s response, the passing scores for both math and reading did see significant improvement from replacing the 9th graders scores.            
![School Ranking](https://user-images.githubusercontent.com/96449605/151863119-afc46c0b-1137-4469-90c2-952b84bc0a1b.png)

 
*	How does replacing the ninth-grade scores affect the following:
-	Math and reading scores by grade: The affect was negligible because the only impacts would be to 9th grade. Otherwise, it was a very small population with relatively low impact.
-	Scores by school spending: School spending was also a marginal change, with relatively few students impacting the overall spending ranges per student.
-	Scores by school size: Again, the impacts to school size – particularly the larger schools – were negligible. 
 ![School Categories](https://user-images.githubusercontent.com/96449605/151863202-f449e189-11f8-4347-a03c-46fae122df34.png)

-	Scores by school type: Replacing the 9th grader scores had little to no impact on school type. 
 ![School Type](https://user-images.githubusercontent.com/96449605/151863234-cb9ee7a2-4171-4e9d-9bd0-e80f82c28bdb.png)

### Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
1.	Because we removed THS 9th graders from the overall analysis, there was minimal impact on their scores, which remained largely unchanged.
2.	Passing math % improved by 26.3%, moving from 66.9% up to 93.2%.
3.	Passing reading % improved by 20.9%, moving from 69.7% up to 90.6%.
4.	There was a negligible impact on the overall analysis in the areas of school spending, school size, and school type.
