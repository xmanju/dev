## Software Architecture 

### Best Practices

- Instead of being built to last, it is built to CHANGe
- Before any components can be designed, the software architect must clearly understand the needs of the user and the domain
- The software architect must identify the subsystems in the product after which he should consider components and layers and abstract them so as to identify every key interface therein
- Using an iterative and incremental approach to designing the software architecture is a great idea
- Use lessons learned from history, record every decision you make and conclusively mitigate major risks.
- Under investing in software architecture is not an option

Source : https://dzone.com/articles/an-introduction-to-software-architecture-what-you

### 4 Stages of Maturity of a Product

- Survival
- Quality
- Convenience
- Customization

Source: http://sourcesofinsight.com/4-stages-of-market-maturity/

### Stone Soup Programming

- Components must be additively commutative
- The components should be idempotent, e.g. redundancy as choice or fallback
- The components must provide integration hooks
- The components do not directly identify one another
- Robust and stable; nothing volatile, toxic, explosive
- Some notion of `seed` components

Source: https://awelonblue.wordpress.com/2012/09/12/stone-soup-programming/