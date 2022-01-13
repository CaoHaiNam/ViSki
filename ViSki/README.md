# ViSki dataset

Data to train, validate and test synonym prediction model. Detail about model can be found in paper.

Follow the code below to load data:
```python
with open(filepath) as f:
    data = []
    for line in f:
        line = line.strip('\n').lower().split('\t')
        data.append([line[0], line[1], int(line[2])])
```
