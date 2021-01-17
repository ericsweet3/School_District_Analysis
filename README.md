## School District Analysis


## Project Overview
- For this project, we initially ran an analysis and report about the school grade percentages of various high schools, charter and public, based on different aspects such as size, budget, etc. We were notified that some grades showed evidence of academic dishonesty, specifically the 9th grade at Thomas High School. We went back in and re-factored the code to reflect the initial report, but without the 9th grade levels.
  
## Results

- How is the district summary affected?
	- Surprisingly not by much, there's the obvious slight change that you'll see when removing an entire grade level, but as for the district summary, you don't see any changes with regards to the holistic view of the district. 
	![District_Summary_1](https://user-images.githubusercontent.com/75768098/104851309-db843200-58b9-11eb-8372-91f9f5f4fa5c.png)
	- And here is the updated summary:
	![District_Summary_2](https://user-images.githubusercontent.com/75768098/104851328-fa82c400-58b9-11eb-841b-b0fd64b1d11c.png)
	
	-As you can see, there is not much change since we are just removing around 1% of the total data


----


- How is the school summary affected? 
	- The school summary is only slightly affected (as expected when removing a large set of data). The percentages fell very slightly along with the overall percentage. 
	
	![school_summary](https://user-images.githubusercontent.com/75768098/104851484-d8d60c80-58ba-11eb-879a-22bdaa91cf78.png)

	- The total percentages changed marginally compared to the original dataset
---

- How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?
	-  Again, it changed practically nothing. Thomas High School is still one of the top performing schools in the district, even without factoring in the 9th grade scores. From the district summary you can see that their overall % passing grades still places them at 2nd compared to the other schools, and removing the 9th grade scores did nothing to move them from that spot. The new overall % being 90.63 would still place them higher than Griffin High School who have a 90.6%. 
	
	![school_ranking](https://user-images.githubusercontent.com/75768098/104851539-2b172d80-58bb-11eb-98a5-a99b3b203710.png)

	
---

- You can also take into account math/reading scores, spending, school size, and the type of school (district or charter) which I will show below.  

- Reading scores by grade:

	![reading_score_grade](https://user-images.githubusercontent.com/75768098/104852066-2a33cb00-58be-11eb-959e-818a3d88d4ce.png)

	- Only changes that we see from removing the 9th grades scores is that it no longer appears on the chart, the rest of the grades are unchanged
	
- Spending:
	
	![spending_range_1](https://user-images.githubusercontent.com/75768098/104852120-77b03800-58be-11eb-9dde-eecb899b3728.png)
	
	![spending_range_2](https://user-images.githubusercontent.com/75768098/104852121-7a129200-58be-11eb-8fad-e4763dd09f9c.png)
	
	- The first picture is the original, followed by the updated. We see no changes in this respect since we aren't alterating the cost per student.
- School Size:

	![school_size_1](https://user-images.githubusercontent.com/75768098/104852150-b0e8a800-58be-11eb-89e1-3cdeabe55be9.png)
	
	![school_size_2](https://user-images.githubusercontent.com/75768098/104852152-b2b26b80-58be-11eb-9fc9-c2cffb25f070.png)
	
	- Since Thomas High School was already performing at the top, nullifying the data from a small group from within it only changes the numbers slightly, and for this 	instance, they fall.
	
- School Type:

	![school_type_1](https://user-images.githubusercontent.com/75768098/104852193-09b84080-58bf-11eb-8336-6d983eae1411.png)
	
	![school_type_2](https://user-images.githubusercontent.com/75768098/104852194-0ae96d80-58bf-11eb-836c-20d5aaa129f9.png)
	
	- The change when grouping them by type of school is still incredibly negligible, changing only in the hundreths digit place. Since its placing didnt change much at all when we were analyzing the grades, this won't really affect that much at all.


## Challenge Summary
  - So for the analysis, I found that there are mostly negligible changes that are shown after going in and refactoring the code. For starters, the average math score only fell 0.6% and the percentage of passing reading scores only fell 0.3%. With regards to school sizes, the "Medium" category only fell marignally and for the totality of it all, the ranking of Thomas High School remained the same, only change is with Griffin High School getting slightly closer to that #2 spot. 
