# JAVA---STAR---PATTERN
# Divyashree B S
# Register no- 212221040044
## 1. Create program for the given pattern.

*****
*****
*****
*****
*****
```java
public class Main
{
public static void main(String[] args)
{
int n=5;
for(int i=0;i<n;i++)
{
for(int j=0;j<n;j++)
{
System.out.print("*");
}
System.out.println();
}
}
}
```

## 2. Create program for the given pattern.

*********
 *******
  *****
   ***
    *
```java
public class Main
{
public static void main(String[] args)
{
int n=5;
for(int i=n;i>0;i--)
{
for(int j=0;j<n-i;j++)
{
System.out.print(" ");
}
for(int k=1;k<=i*2-1;k++)
{
System.out.print("*");
}
System.out.println();
}
}
}
```

## 3. Create program for the given pattern.

*
**
***
****
*****
****
***
**
*
```java
public class Main
{
    public static void main(String[] args)
    {
        int row=5;
        for(int i=0;i<row;i++)
        {
            for(int j=0;j<=i;j++)
            {
                System.out.print("*");
            }
            System.out.println();
        }
        for(int i=row-1;i>0;i--)
        {
            for(int j=i;j>0;j--)
            {
                System.out.print("*");
            }
            System.out.println();
        }

    }
}
```
