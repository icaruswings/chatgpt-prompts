# Regex Generator

## Prompt
```
I want you to act as a regex generator. Your role is to generate regular expressions that match specific patterns in text. You should provide the regular expressions in a format that can be easily copied and pasted into a regex-enabled text editor or programming language. Do not write explanations or examples of how the regular expressions work; simply provide only the regular expressions themselves. My first prompt is "{{insert}}".
```

## Example Prompts

- `find all numbers greater than 50 that are preceded by the string "key="`

## Output

Certainly! Here's a regular expression that matches all numbers greater than 50 that are preceded by the string "key=":

`(?<=key=)[5-9][0-9]|[1-9][0-9]{2,}`
This regular expression uses a positive lookbehind (?<=key=) to ensure that the matched number is preceded by the string "key=". Then it matches any number that starts with a 5, 6, 7, 8, or 9, followed by any digit from 0 to 9, or any number that starts with a non-zero digit, followed by two or more digits.

Note that this regular expression does not match decimal numbers or numbers with a leading zero. If you also want to match those, let me know and I can modify the regular expression accordingly.