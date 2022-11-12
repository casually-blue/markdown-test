```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

```mermaid
    gitGraph
       commit
       commit
       branch develop
       commit
       commit
       commit
       checkout main
       commit
       commit
```

```mermaid
gantt
dateFormat  YYYY-MM-DD
title Adding GANTT diagram to mermaid
excludes weekdays 2014-01-10

section A section
Completed task            :done,    des1, 2014-01-06,2014-01-08
Active task               :active,  des2, 2014-01-09, 3d
Future task               :         des3, after des2, 5d
Future task2               :         des4, after des3, 5d
```

```stl
solid cube-ascii
    facet normal  0.000000e+00  0.000000e+00  1.000000e+00
        outer loop
            vertex  0.000000e+00  0.000000e+00  1.000000e+01
            vertex  1.000000e+01  0.000000e+00  1.000000e+01
            vertex  0.000000e+00  1.000000e+01  1.000000e+01
        endloop
    endfacet
    facet normal  0.000000e+00  0.000000e+00  1.000000e+00
        outer loop
            vertex  1.000000e+01  1.000000e+01  1.000000e+01
            vertex  0.000000e+00  1.000000e+01  1.000000e+01
            vertex  1.000000e+01  0.000000e+00  1.000000e+01
        endloop
    endfacet
    facet normal  1.000000e+00  0.000000e+00  0.000000e+00
        outer loop
            vertex  1.000000e+01  0.000000e+00  1.000000e+01
            vertex  1.000000e+01  0.000000e+00  0.000000e+00
            vertex  1.000000e+01  1.000000e+01  1.000000e+01
        endloop
    endfacet
    facet normal  1.000000e+00  0.000000e+00  0.000000e+00
        outer loop
            vertex  1.000000e+01  1.000000e+01  0.000000e+00
            vertex  1.000000e+01  1.000000e+01  1.000000e+01
            vertex  1.000000e+01  0.000000e+00  0.000000e+00
        endloop
    endfacet
    facet normal  0.000000e+00  0.000000e+00 -1.000000e+00
        outer loop
            vertex  1.000000e+01  0.000000e+00  0.000000e+00
            vertex  0.000000e+00  0.000000e+00  0.000000e+00
            vertex  1.000000e+01  1.000000e+01  0.000000e+00
        endloop
    endfacet
    facet normal  0.000000e+00  0.000000e+00 -1.000000e+00
        outer loop
            vertex  0.000000e+00  1.000000e+01  0.000000e+00
            vertex  1.000000e+01  1.000000e+01  0.000000e+00
            vertex  0.000000e+00  0.000000e+00  0.000000e+00
        endloop
    endfacet
    facet normal -1.000000e+00  0.000000e+00  0.000000e+00
        outer loop
            vertex  0.000000e+00  0.000000e+00  0.000000e+00
            vertex  0.000000e+00  0.000000e+00  1.000000e+01
            vertex  0.000000e+00  1.000000e+01  0.000000e+00
        endloop
    endfacet
    facet normal -1.000000e+00  0.000000e+00  0.000000e+00
        outer loop
            vertex  0.000000e+00  1.000000e+01  1.000000e+01
            vertex  0.000000e+00  1.000000e+01  0.000000e+00
            vertex  0.000000e+00  0.000000e+00  1.000000e+01
        endloop
    endfacet
    facet normal  0.000000e+00  1.000000e+00  0.000000e+00
        outer loop
            vertex  0.000000e+00  1.000000e+01  1.000000e+01
            vertex  1.000000e+01  1.000000e+01  1.000000e+01
            vertex  0.000000e+00  1.000000e+01  0.000000e+00
        endloop
    endfacet
    facet normal  0.000000e+00  1.000000e+00  0.000000e+00
        outer loop
            vertex  1.000000e+01  1.000000e+01  0.000000e+00
            vertex  0.000000e+00  1.000000e+01  0.000000e+00
            vertex  1.000000e+01  1.000000e+01  1.000000e+01
        endloop
    endfacet
    facet normal  0.000000e+00 -1.000000e+00  0.000000e+00
        outer loop
            vertex  1.000000e+01  0.000000e+00  1.000000e+01
            vertex  0.000000e+00  0.000000e+00  1.000000e+01
            vertex  1.000000e+01  0.000000e+00  0.000000e+00
        endloop
    endfacet
    facet normal  0.000000e+00 -1.000000e+00  0.000000e+00
        outer loop
            vertex  0.000000e+00  0.000000e+00  0.000000e+00
            vertex  1.000000e+01  0.000000e+00  0.000000e+00
            vertex  0.000000e+00  0.000000e+00  1.000000e+01
        endloop
    endfacet
endsolid
```
