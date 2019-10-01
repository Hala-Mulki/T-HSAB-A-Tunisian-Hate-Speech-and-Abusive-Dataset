# T-HSAB-A Tunisian Hate Speech and Abusive Dataset
 The first Tunisian Hate Speech and Abusive Dataset

#T-HSAB Dataset: Context and Topics
The Tunisian Hate Speech and ABusive (T-HSAB) is the first Arabic Tunisian Hate Speech and Abusive Language Dataset proposed in the The 7th International Conference on Arabic Language Processing October 16-17, 2019 (Nancy, France).

Since the \Jasmine Revolution" at 2011, Tunisia has entered a new era of ultimate freedom of expression with a full access into social media. This has been associated with an unrestricted spread of toxic contents such as Abusive and Hate speech.
T-HSAB combines 6,024 Tunisian comments labeled as normal, abusive or hate. The collected tweets were posted between October 2018 and March 2019.

#Data Collection & Resources
T-HSAB was constructed out of Tunisian comments scraped from facebook and youtube. We collected the comments based on multiple queries formulated from the potential entities that are usually targeted by abusive/hate speech such as “اليهود” (Jews), "الأفارقة" (Africans), “المساواة في الميراث” (gender equality in inheritance), etc.



#Data Annotation Guidelines
Our annotation process was conducted by 3 Tunisian-speaking annotators. The annotation instructions defined the 3 label categories as:

• Normal tweets are those instances with no offensive, aggressive, insulting and profanity content.

• Abusive tweets are those instances that combine offensive, aggressive, insulting or profanity content.

• Hate tweets are those instances that: (a) contain an abusive language, (b) dedicate the abusive language towards a specific person or a group of people and (c) demean or dehumanize that person or that group of people based on their descriptive identity (race, gender, religion, disability, skin color, belief).

• The annotators were provided by the nicknames usually used, within hate/abusive contexts, to refer to certain political parties, minorities and ethnic/religion groups. For example, “كحلوش” (of a dark skin), which represents the African ethnic group, is usually used within hate speech contexts.

#Annotation Evaluation: Methods & Results
The annotation credibility was evaluated using several evaluation measures:

1- Pairwise Percent Agreement Measure (PRAM): best value between annotator 1 & annotator 2 = 97.9%

2- Cohen's Kappa (K): best value between annotator 1 & annotator 2 = 96.1%

3- Krippendorff’s Alpha (α)= 75%

#T-HSAB: Classification Experiments
1- Binary Classification (Normal, Abusive):

Best performance by Naive Bayes with an F-measure of 92.3%

2- Multi-Class Classification (Normal, Abusive, Hate):

Best performance by Naive Bayes with an F-measure of 83.6%

#Paper Citation
@inproceedings{mulki2019hsab, title={T-HSAB: A Tunisian Hate Speech and Abusive Dataset},

author={Haddad, Hatem and Mulki, Hala and Oueslati, Asma},

booktitle={Arabic Language Processing: From Theory to Practice},

year={2019}

}
