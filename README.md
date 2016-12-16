# CubeProblem
https://www.hackerrank.com/challenges/cube-summation

1. Clone project
2. Create a Maven configuration with command line: clean package exec:java
3. Run
  You can see the output
  And you cant test it via postman: POST http://localhost:8080/myapp/cubeproblem 
  
    With this json:
  
    {
    "numTestCases": 2,
    "iterations": [
      {"n":4,"m":5, "cubeOperations":
      [{"operation": "UPDATE 2 2 2 4"},
      {"operation": "QUERY 1 1 1 3 3 3"},
      {"operation": "UPDATE 1 1 1 23"},
      {"operation": "QUERY 2 2 2 4 4 4"},
      {"operation": "QUERY 1 1 1 3 3 3"}
      ]},
      {"n":2,"m":4, "cubeOperations":
      [{"operation": "UPDATE 2 2 2 1"},
      {"operation": "QUERY 1 1 1 1 1 1"},
      {"operation": "QUERY 1 1 1 2 2 2"},
      {"operation": "QUERY 2 2 2 2 2 2"}
      ]}]
    }

4.Done
