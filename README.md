# Final Project: Analyzing the Impact of Gamification towards Education

## Abstract
Gamification in an educational setting has significantly increased in recent years. These platforms often rely on incorporating reward-based mechanics such as leaderboards, badges, point systems, and quizes to promote learning. With platforms such as BrainPop, IXL, Kahoot!, and Quizlet offering a fun and interactive environment, students are motivated to actively engage in the learning process.

While several studies have indicated positive impacts of gamified learning platforms, the degree of effectiveness remains contentious. Additionally, some studies discuss the ethical implications of gamified learning platforms, such as the overemphasis on competition, coersion/persuasion, and unsustainability of these platforms in the long-term.

In light of these conflicting findings, this project seeks to understand and evaluate the effectiveness of gamified learning platforms on students' academic performance.

## Data Documentation
- Dataset: 🏅Gamification in Education
- Source: Gianina-Maria Petrașcu
  
| **Variable Name**    | **Description**                                              | **Type**          | **Range**         |  
|----------------------|--------------------------------------------------------------|-------------------|-------------------|  
| `Student_ID`          | Unique numeric identifier for each student                   | Numeric           | -                 |  
| `Practice_Exam`       | Score on the practice exam                                   | Numeric           | 0–10              |  
| `Final_Exam`          | Score on the final exam                                      | Numeric           | 0–10              |  
| `User`                | Platform usage (1 = user, 0 = non-user)                      | Binary (Numeric)  | {0, 1}            |  
| `Avg_Grade_Q1-6`      | Average scores for six quizzes on the gamified platform      | Numeric           | 0–10              |  
| `No_access_Q1-6`      | Number of times each quiz was accessed                       | Numeric           | -                 |  


## License Information
MIT License

Copyright (c) 2024 Annie Pao

Permission is hereby granted, free of charge, to any person obtaining a copy of this
software and associated documentation files (the “Software”), to deal in the 
Software without restriction, including without limitation the rights to use, copy, 
modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, 
and to permit persons to whom the Software is furnished to do so, subject to the 
following conditions:

The above copyright notice and this permission notice shall be included in all 
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, 
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF 
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND 
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT 
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, 
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING 
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR 
OTHER DEALINGS IN THE SOFTWARE.

## Resources and References

### Terms of Service and Data Documentation:
- Data Source: [Kaggle Dataset](https://www.kaggle.com/datasets/gianinamariapetrascu/gamification-students-grades?resource=download&select=Students_gamification_grades.csv)

### License Documentation:
- [MIT License](https://opensource.org/license/mit)

### Academic Literature References:
[1] Christians, Gerald, "The Origins and Future of Gamification" (2018). Senior Theses. 254. 
https://scholarcommons.sc.edu/senior_theses/254 

[2]T. Staff, “A Brief History Of Gamification In Education,” TeachThought, Aug. 27, 2012. https://www.teachthought.com/education/a-brief-history-of-gamification-in-education/ 

[3] Mark Weiser. 1999. The computer for the 21st century. SIGMOBILE Mob. Comput. Commun. Rev. 3, 3 (July 1999), 3–11. https://doi.org/10.1145/329124.329126

[4] Khoshnoodifar M, Ashouri A, Taheri M. Effectiveness of Gamification in Enhancing Learning and Attitudes: A Study of Statistics Education for Health School Students. J Adv Med Educ Prof. 2023;11(4):230-239. doi:10.30476/JAMP.2023.98953.1817

[5] H. Conick, “Gamification is Manipulative. Is It Ethical?,” American Marketing Association, Jul. 30, 2019. https://www.ama.org/marketing-news/gamification-is-manipulative-is-it-ethical/ 

[6] P. Peterka, “ANOVA F Value: Mastering Signal-to-Noise Ratio for Data Analysis,” SixSigma.us, May 09, 2024. https://www.6sigma.us/six-sigma-in-focus/anova-f-value-meaning/

[7] Kent State University, “SPSS Tutorials: Pearson Correlation,” Kent.edu, 2018. https://libguides.library.kent.edu/SPSS/PearsonCorr
‌
[8] G. M. Sullivan and R. Feinn, “Using effect size—or why the p value is not enough,” Journal of Graduate Medical Education, vol. 4, no. 3, pp. 279–282, Sep. 2012, doi: https://doi.org/10.4300/JGME-D-12-00156.1.

‌[9] F. Frost, "Cohens D: Definition, Using & Example," Statistics By Jim, n.d. https://statisticsbyjim.com/basics/cohens-d/

### Analysis Tools:
- Python Libraries: [Pandas](https://pandas.pydata.org/), [Seaborn](https://seaborn.pydata.org/), [Matplotlib](https://matplotlib.org/), [Scipy](https://scipy.org/)
- Jupyter Notebook: [Documentation](https://docs.jupyter.org/en/latest/)