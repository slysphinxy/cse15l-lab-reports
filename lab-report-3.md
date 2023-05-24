# All about ```grep```

## Interesting Option 1: ```grep -x <string>```
Source: [wikibooks](https://en.wikibooks.org/wiki/Grep)

Outputs lines that match the entire line exactly in grep.

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

Searches for matching patterns in a file.

```
ls | grep physical
```
Searching Technical Here

## Interesting Option 3: ```grep -v <string>```
Source: [wikibooks](https://en.wikibooks.org/wiki/Grep)

Searches for everything that does not match the string input to the grp command.

```
ls | grep physical
```
Searching Technical Here

## Interesting Option 4: ```grep -o <string>```
Source: [wikibooks](https://en.wikibooks.org/wiki/Grep)

Searches for and then outputs the matched parts of a matching line.

```
ls | grep physical
```
Searching Technical Here
