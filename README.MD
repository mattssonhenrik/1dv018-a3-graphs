# Programmeringsuppgift 3
## Bygg
./gradlew build
## Kör
./gradlew run

### Modifiera tester
I App.java kan ni ändra på rad 15 och 16 för att öka storleken på våra grafer och lägga till kopplingar (edges) mellan noderna på rad 19-24.


```java
        DirectedGraph directedGraph = new DirectedGraph(5);  
        UnDirectedGraph unDirectedGraph = new UnDirectedGraph(5);```
```

```java
        directedGraph.addEdge(0, 1);
        directedGraph.addEdge(1, 2, 2.5);
        directedGraph.addEdge(2, 0);
        directedGraph.addEdge(3, 4);
        directedGraph.addEdge(0, 1);
        directedGraph.addEdge(0, 4);
