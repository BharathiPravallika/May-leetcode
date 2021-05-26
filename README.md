# May-leetcode
class Solution:<br>
    def minPartitions(self, n: str) -> int:<br>
        m = 0<br>
        for x in n:<br>
            x = int(x)<br>
            m = max(x, m)<br>
        return m
        
