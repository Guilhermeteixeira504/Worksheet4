This project is intentionally incomplete. Follow the worksheet in the order given.

Expected final application output:

```
FleetCheck 1.0
Vehicles loaded: 4
Vehicles requiring service: 2
Average mileage: 37000 km
```

Do not copy the solution POM. The objective is to observe how each build change alters the result.

/C:/Users/guilh/OneDrive/Desktop/Faculdade/3 ano/Qualidade de Software/FleetCheck_Starter/src/main/java/pt/upt/fleetcheck/App.java:[3,39] package com.fasterxml.jackson.core.type does not exist

APP java: fasterxml.jackson

Why is this a better failure than the one from Step 1?
    Because we sucessfully passed the compilation phase

Explain what the Shade plugin changed compared with the default JAR.
    The plugin convert the manifest in a ready-to-run apllication

Which hidden environmental assumption did the wrapper remove?
    The wrapper removed the assumption that MAven is already installed on the machine

