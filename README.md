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

![help](https://raw.githubusercontent.com/IamJony/semi-nord-theme-bluefish/main/Screenshot_2024-07-21-09-03-25_1366x768.png)

#### Search directly
By default, book-scraping-fzf prompts the user for the book name to search. However, you can perform a direct search by passing the argument using echo.

To bypass the interactive prompt and provide the book name directly from the command line, you can use redirection as follows: 

`echo "linux" | ./book-scraping-fzf --en --pdf --lib`


#### Prioritize book searches on libgen (**Automatic download support**)

`book-scraping-fzf --lib`

#### Search by author
`./book-scraping-fzf --en --author "gabriel garcia"`

#### Search pdf in spanish

`book-scraping-fzf --pdf --es` 

#### Search epub

`book-scraping-fzf --epub`

#### Search multiple books
To search for multiple books using `csv-search` script, first, edit the `books.csv` file in a text editor or spreadsheet application to make any necessary changes, such as adding, removing, or adjusting book information. After saving the file, run the csv-search command in your terminal or command lin



## Example:
![book-scraping-fzf](https://raw.githubusercontent.com/IamJony/semi-nord-theme-bluefish/main/a-2024-07-21_20.17.07%20(online-video-cutter.com)(1).gif)

