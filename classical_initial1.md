```mermaid
  graph TD;
    s1("X|X")--> s3("X|T") & s4("X|T") & s5("X|T");
    s1 -.-> s6("X|X");
    s2("(F)|X") --> s5 & s6 & s7("X|X");
    s2-.-> s4;
```
