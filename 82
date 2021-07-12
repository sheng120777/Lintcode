class Solution:
    def singleNumber(self, A):
        A=sorted(A)
        if len(A)==1:
            return int(A[0])
        else:
            for i in range(len(A)):
                if int(A[i-1])!=int(A[i-2]) and int(A[i])!=int(A[i-1]):
                    return int(A[i-1])
