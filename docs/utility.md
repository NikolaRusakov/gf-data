- seed MongoDB with raw csv data

```bash
mongoimport --uri "mongodb://<<port>>:27017" --db=recipes --collection=recipes --type=csv --headerline --file=../RAW_recipes.csv
```
