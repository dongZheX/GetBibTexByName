
## Requestments:
* BeautifulSoup
* requests
* urllib
* openyxl
* tqdm
* pypinyin
* re
* selenium

## How to use
1. Create dir results and data in the root.
2. run 'python bibtex.py --names xxx xxx xxx --u --m 1' in terminal.

Then the results will be generated in dir results.

## The args
* if you want to update your results and don't want to use pickle data, use --u
* if the name is ambiguity, you can get the exact author page in dblp, and use --person_url --names --m 2
