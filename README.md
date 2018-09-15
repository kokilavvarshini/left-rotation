# left-rotation
in left rotation,the no of elements in the array that is shifted to the left is mentioned by the letter d.suppose consider  an array [1,2,3,4].If there is only one left rotation on this array,then the result will be [2,3,4,1].If,suppose ,the left rotation is 2,then the result will be [3,4,1,2].

#!/bin/python3

import math
import os
import random
import re
import sys



if __name__ == '__main__':
    nd = input().split()

    n = int(nd[0])

    d = int(nd[1])

    a = list(map(int, input().rstrip().split()))
