# LeetCode 242 - Valid Anagram

## Problem

Given two strings `s` and `t`, return `true` if `t` is an anagram of `s`, and `false` otherwise.

An anagram is a word or phrase formed by rearranging the letters of another word or phrase.

## Example

### Input

```text
s = "anagram"
t = "nagaram"
```

### Output

```text
true
```

### Example 2

```text
s = "rat"
t = "car"
```

### Output

```text
false
```

## Approach

Sort both strings and compare them.

If both strings contain exactly the same characters with the same frequencies, their sorted versions will be identical.

For example:

```text
anagram → aaagmnr
nagaram → aaagmnr
```

Since both are equal, they are anagrams.

## Algorithm

1. Sort string `s`.
2. Sort string `t`.
3. Compare the two sorted strings.
4. Return `true` if they are equal.
5. Otherwise, return `false`.

## Complexity

* Time Complexity: `O(n log n)`
* Space Complexity: `O(n)`

Where `n` is the length of the strings.

## Language

Python

## LeetCode

Problem: 242 - Valid Anagram

## Author

**T.Nandhini**
