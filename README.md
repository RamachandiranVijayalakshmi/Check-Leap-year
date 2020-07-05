# Check Leap year
- **We add a Leap Day on February 29**
- **Almost every four years.**
- **The leap day is an extra, or intercalary day and we add it to the shortest month of the year, February.**
- **Get the Year into the User and also Check that year is Leap Year Or Not.**
### Many Condition To Caluculate The Leap Year There are:
- **The year can be evenly divided by 4, is a leap year, unless**
- **The year can be evenly divided by 100, it is NOT a leap year, unless**
- **The year is also evenly divisible by 400. Then it is a leap year.**
## Sample Code For Check Leap Year
```
if year%4==0:
   if year%100==0:
      if year%400==0:
         print(year,'is a Leap Year')
      else:
          print(year, "is not a Leap Year")
   else:
      print(year,'is a Leap Year')
else:
   print(year, "is not a Leap Year")
```
## Exaple Output
```
Enter year:1992
1992 is a Leap Year
```
