# mermaid-sample
a simple sample of how the mermaid UML works


##simple diagram


```mermaid
  graph TD;
      A-->B;
      A-->C;
      B-->D;
      C-->D;
```



## A git commit diagram

```mermaid
    gitGraph
       commit tag: "v1.0.0"
       branch feat/mermaid-test
       checkout  feat/mermaid-test
       commit
       commit
       checkout main
       merge  feat/mermaid-test
       commit tag: "v1.0.1"
       commit
```

