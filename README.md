# fitness-codechef-probelm

Problem
Chef wants to become fit for which he decided to walk to the office and return home by walking. It is known that Chef's office is X km away from his home.
If his office is open on 5 days in a week, find the number of kilometers Chef travels through office trips in a week.

Input Format
First line will contain T, number of test cases. Then the test cases follow.
Each test case contains of a single line consisting of single integer X.

Output Format
For each test case, output the number of kilometers Chef travels through office trips in a week.

Constraints

    1≤T≤10

    1≤X≤10
    
Sample 1:
    
    Input
        4
        1
        3
        7
        10

    Output
        10
        30
        70
        100

solution

      # cook your dish here
      t=int(input())
      for i in range(t):
          x=int(input())
          k=2*x
          print(k*5)
