# ViSki dataset

## Overview
We introduced the ViSki dataset, which consists of occupational skills and synonym set of skills. The synonym set is a dictionary, each element in the synonym set is a dictionary as well, with value is a list of synonymous skills, and key is standard skill of thems.
*  [occupational skill](https://github.com/CaoHaiNam/Vietnamese-Ocupational-Skill-Dataset/blob/main/raw_skill_terms.txt): contain 10245 skills manually acquired from numerous Vietnamese resumes and how many times they occur in these resumes.
* [synonymset](https://github.com/CaoHaiNam/Vietnamese-Ocupational-Skill-Dataset/blob/main/synonymSet.json): consist of 740 synonym sets corresponding to 3787 skills.
* [skill2neighbor](https://github.com/CaoHaiNam/Vietnamese-Occupational-Skill-Dataset/blob/main/skill2neighbor.json): provide information about neighbors of a specific skill and how many time they co-occur in resumes. 

## Ciations
```
@inproceedings{cao2022synonym,
  title={Synonym Prediction for Vietnamese Occupational Skills},
  author={Cao, Hai-Nam and Do, Duc-Thai and Tran, Viet-Trung and Cao, Tuan-Dung and Song, Young-In},
  booktitle={International Conference on Industrial, Engineering and Other Applications of Applied Intelligent Systems},
  pages={351--362},
  year={2022},
  organization={Springer}
}
```

```
@inproceedings{tran2022practical,
  title={A practical method for occupational skills detection in Vietnamese job listings},
  author={Tran, Viet-Trung and Cao, Hai-Nam and Cao, Tuan-Dung},
  booktitle={Asian Conference on Intelligent Information and Database Systems},
  pages={571--581},
  year={2022},
  organization={Springer}
}
```
