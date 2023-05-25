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
The -e option is particularly useful when the pattern contains special characters or starts with a hyphen (-), which could be mistakenly interpreted as an option by grep. By using -e, you explicitly indicate that what follows is the pattern rather than an option.

 -e pattern, --regexp=pattern
             Specify a pattern used during the search of the input: an input line is selected if it matches any of the specified patterns.  This option is
             most useful when multiple -e options are used to specify multiple patterns, or when a pattern begins with a dash (‘-’).

Searches for matching patterns in a file.

Input:
```
grep -e -year technical/biomed/1468-6708-3-1.txt
```
Output:
```
to quality-adjusted life-years, healthy year equivalents,
. That article showed that estimated 4-year YOL and YHL
primary analysis we used observed 7-year YOL and YHL when
they were available, and observed 3-year YOL and YHL plus
4-year estimated YOL and YHL when they were not (about
about 93 women per treatment arm, if 7-year YHL were the
These results are for a 7-year follow-up. The relative
```
Input:
```
grep -e climate -e biodiversity technical/plos/journal.pbio.0020001.txt
```
Output:
```
Climate change and biodiversity research, for example, urgently need the scientific input
Climate change and biodiversity research urgently need the scientific
```

## Interesting Option 3: ```grep -v <string>```
Source: [wikibooks](https://en.wikibooks.org/wiki/Grep)
Source: [chatGPT](https://openai.com/blog/chatgpt)

Searches for everything that does not match the string input to the grp command.



## Interesting Option 4: ```grep -o <string>```
Source: [wikibooks](https://en.wikibooks.org/wiki/Grep)
Source: [chatGPT](https://openai.com/blog/chatgpt)

Searches for and then outputs the matched parts of a matching line.

```
ls | grep physical
```
Searching Technical Here
