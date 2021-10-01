# Kubernetes Schemas

This project contains PlantUML diagrams for a better understanding of Kubernetes.

The resulting schemas can be seen on the [Github Project Page](https://soframel.github.io/k8s-schemas/).

## Kubernetes For Developers Simplified Class Diagram

This class diagram contains the main concepts needed from a developer perspective.

Warning: this class diagram is far from exhaustive !

In addition, it sometimes contains some adaptations for a better readability, like regrouping concepts in a parent class, event if not done in Kubernetes reference.

Finally, it mixes the concepts of specifications and objects: specifications are reproduced as class attributes or relations directly on the same class representing the runtime objects. Note that main concept classes inherit the `K8SObject` class.

To generate SVG image: 
```bash
java -jar <path-to-plantuml> k8s-for-devs-simplified.plantuml.puml -tsvg
```