# Hackerank-Print-A-Function
The included code stub will read an integer, n, from STDIN.Without using any string methods, try to print the following:123...n
#solution
if __name__ == '__main__':
    n = int(input())
for i in range(n):
        print(i + 1 , end = "")  


