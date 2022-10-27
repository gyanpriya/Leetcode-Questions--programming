# Leetcode-Questions--programming

Count Odd Numbers in an Interval Range

def countOdds(self, low: int, high: int) -> int:
        if high%2 != 0:
            count =high//2 - low//2 + 1
        else:
            count = high//2 - low//2
        return count
