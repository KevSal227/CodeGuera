# 💻 CodeGuera — JavaScript Practice

## About This Repository

This repository is where I've started saving JavaScript coding challenges as I work on improving my problem-solving skills.

My goal is to get more comfortable with JavaScript fundamentals, understand how different methods work, and become better at breaking down coding problems.

## Challenges

### Sort and Star — Codewars (8 kyu)

**The Problem**

Given an array of strings, sort them alphabetically, take the first string, and return it with `***` between each letter.

**My Solution**

```javascript
function twoSort(s) {
  return s.sort()[0].split('').join('***');
}
```

**How It Works**

1. `.sort()` puts the strings in alphabetical order.
2. `[0]` selects the first string.
3. `.split('')` separates that string into individual characters.
4. `.join('***')` combines the characters with three asterisks between them.

**Example**

Input: `["banana", "apple", "cherry"]`

Output: `"a***p***p***l***e"`

## What I Learned

This challenge helped me practice chaining JavaScript methods together to solve a problem without writing unnecessary code.

I also got more comfortable working with arrays, strings, and understanding what each method returns.

One thing worth remembering is that `.sort()` modifies the original array.

## Tech Stack

- JavaScript

## Future Goals

I plan to keep practicing coding challenges and improving my understanding of JavaScript fundamentals, algorithms, and problem-solving.

## Author

[Kevin Salazar on GitHub](https://github.com/KevSal227)
