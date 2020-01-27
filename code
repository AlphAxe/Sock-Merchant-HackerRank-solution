#!/bin/python3

import math
import os
import random
import re
import sys
import array as arr

# Complete the sockMerchant function below.
def sockMerchant(n, ar):
    c=0
    for j in ar:
        l=ar.count(j)   
        c=c+ int(l/2)
        ar=arr.array('i',[value for value in  ar if value != j])
    return c


if __name__ == '__main__':
    fptr = open(os.environ['OUTPUT_PATH'], 'w')

    n = int(input())

    ar = list(map(int, input().rstrip().split()))

    result = sockMerchant(n, ar)

    fptr.write(str(result) + '\n')

    fptr.close()
