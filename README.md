# book-scraping
A Bash script to search and download books using shadows libraries
## Dependencies
1. fzf
2. wget
3. curl
4. jq
## How it works 
The script downloads Anna's page and through the use of regular expressions, manages to extract information from the books and in turn extracts the URLs from the different download servers

## Update script 
`book-scraping-fzf --update`

## Parameters
Parameters can be combined to refer to a list of parameters `--help` or `-h`.


#### Prioritize book searches on libgen (**Automatic download support**)

`book-scraping-fzf --lib`

#### Search pdf in spanish

`book-scraping-fzf --pdf --es` 

#### Search epub in all lenguaje 

`book-scraping-fzf --epub`



## Example:
![ecampl](https://raw.githubusercontent.com/IamJony/semi-nord-theme-bluefish/main/Screenshot_2023-05-09-03-06-23_1366x768.png)
![example](https://raw.githubusercontent.com/IamJony/semi-nord-theme-bluefish/db8ea9eaca408fc5625b27db9f03375516472198/Screenshot_2023-05-09-03-06-29_1366x768.png)
![GitHub Logo](https://raw.githubusercontent.com/IamJony/semi-nord-theme-bluefish/main/Screenshot_2023-05-09-03-07-07_1366x768.png) 

