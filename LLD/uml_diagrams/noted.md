uml diagrams: diagrams to show how the aplllicatin behave , component / object iterations, complete apllication worlflow etc.

1)Structural (Static uml diag)--- total 7, imp class diagrams
2)Behavorial (Dynamic uml diag)-- total 7, imp sequential diagrams

# in calss diagram:

┌──────────────────────────────────────┐
│                 Car                  │
├──────────────────────────────────────┤
│ - model : String                     │
│ # speed : int                        │
│ + brand : String                     │
│ ~ color : String                     │
├──────────────────────────────────────┤
│ + Car()                              │
│ + start() : void                     │
│ - calculateMileage() : void          │
│ # accelerate() : void                │
│ ~ stop() : void                      │
└──────────────────────────────────────┘

public---(+)
protected--(#)
private--(-);
