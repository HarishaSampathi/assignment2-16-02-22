# assignment2-16-02-22
hacker rank function program
def is_leap(year):
    if year%4==0 and year%100!=0 or year%400==0:
        return True
    else:
        return False
year = int(input())
print(is_leap(year))
output:
1995
false
