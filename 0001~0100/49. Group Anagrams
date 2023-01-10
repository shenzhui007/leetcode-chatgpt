class Solution:
    def groupAnagrams(self, strs: List[str]) -> List[List[str]]:
        d = {}
        for s in strs:
            key = ''.join(sorted(s))
            if key in d:
                d[key].append(s)
            else:
                d[key] = [s]
        return list(d.values())
