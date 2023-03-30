class Solution:
    def addDigits(self, num: int) -> int:
        while num >= 10:
            sum = 0
            while num > 0:
                sum += num % 10
                num //= 10
            num = sum
        return num
