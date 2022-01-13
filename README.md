# Vietnamese-Ocupational-Skill-Dataset

## Overview
We introduced the Vietnamese Occupational Skill Dataset, which consists of occupational skills and synonym sets. A synonym set is a dictionary, each element in a synonym set is a dictionary as well, which comprises a value as a list of synonymous skills, and a key representing these skills.
*  [occupational skill](https://github.com/CaoHaiNam/Vietnamese-Ocupational-Skill-Dataset/blob/main/raw_skill_terms.txt): contain 10245 skills manually acquired from numerous Vietnamese resumes and how many times they occur in these resumes.
* [synonymset](https://github.com/CaoHaiNam/Vietnamese-Ocupational-Skill-Dataset/blob/main/synonymSet.json): consist of 740 synonym sets corresponding to 3787 skills. Detail about the process of synonym set generation is presented in the paper.
* [skill2neighbor](https://github.com/CaoHaiNam/Vietnamese-Occupational-Skill-Dataset/blob/main/skill2neighbor.json): provide information about neighbors of a specific skill and how many time they co-occur in resumes. 
