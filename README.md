# GitHub Diagrams Example


### Example 1

 ```mermaid
graph TD;
  Micro-Frontend-->A1[Defining Micro-Frontends];
  Micro-Frontend-->A2[Composition of Micro-frontends];
  Micro-Frontend-->A3[Micro-Frontends Communication];
```

### Example 2

```mermaid
graph TD;
  A1[Defining Micro-Frontends]-->B1[Horizontal split];
  A1[Defining Micro-Frontends]-->B2[Vertical split];
  B1--Domain Driven Design-->C1[Core Subdomains]
  B1--Domain Driven Design-->C2[Supporting Subdomains]
  B1--Domain Driven Design-->C3[Generic Subdomains]
  B2--Domain Driven Design-->C1[Core Subdomains]
  B2--Domain Driven Design-->C2[Supporting Subdomains]
  B2--Domain Driven Design-->C3[Generic Subdomains]
```
