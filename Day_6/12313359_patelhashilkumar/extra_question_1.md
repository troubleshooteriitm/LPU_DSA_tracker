# Valid Anagram

Link - https://neetcode.io/problems/is-anagram/question?list=neetcode150

```python
class Solution:
    def isAnagram(self, s: str, t: str) -> bool:
         if len(s) != len(t):
            return False
         return Counter(s) == Counter(t)
```