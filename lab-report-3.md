# All about ```grep```

## Interesting Option 1: ```grep -x <string>```
Source: [wikibooks](https://en.wikibooks.org/wiki/Grep)
Source: [chatGPT](https://openai.com/blog/chatgpt)

The grep -x command is used to search for an exact match of the entire line in a given input. It matches lines that completely match the specified pattern or regular expression.

Outputs lines in a file that exactly match the entire line input in grep.

```
grep -x 
```
Searching Technical Here

Input:
```grep -x "INSIDE THE FOUR FLIGHTS" technical/911report/chapter-1.txt```
Output:
```INSIDE THE FOUR FLIGHTS```

Input:
```grep -x "LEGAL SERVICES CORPORATION" technical/government/About_LSC/commission_report.txt```
Output:
```LEGAL SERVICES CORPORATION```

## Interesting Option 2: ```grep -e <string>```
Source: [wikibooks](https://en.wikibooks.org/wiki/Grep)
Source: [chatGPT](https://openai.com/blog/chatgpt)

The grep -e command is used to search for a pattern or regular expression in a given input. The -e option allows you to specify the pattern or regular expression directly on the command line.

The pattern is the text or regular expression you want to search for, and file(s) represents the file(s) in which you want to search for the pattern.

Searches for matching patterns in a file.

```
ls | grep physical
```
Searching Technical Here

## Interesting Option 3: ```grep -v <string>```
Source: [wikibooks](https://en.wikibooks.org/wiki/Grep)
Source: [chatGPT](https://openai.com/blog/chatgpt)

Searches for everything that does not match the string input to the grp command.

```
ls | grep physical
```
Searching Technical Here

## Interesting Option 4: ```grep -o <string>```
Source: [wikibooks](https://en.wikibooks.org/wiki/Grep)
Source: [chatGPT](https://openai.com/blog/chatgpt)

Searches for and then outputs the matched parts of a matching line.

```
ls | grep physical
```
Searching Technical Here
