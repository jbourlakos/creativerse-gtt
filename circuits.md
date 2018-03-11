# Group Therapy Land: Circuits

## Activatable Periodic Auto-turn-off 

### Purpose

This circuit automatically emits an `OFF` signal every `4` (`2`+`2`) seconds.

### Layout

```
INPUT                                           
    |                                           
    v                                           
Switch ---> Logic Gate[AND] --> Delay Gate[2]   
    |            ^                     |        
    -------------|-------------------  |        
                 |                  |  |        
                 |                  v  v        
            Delay Gate[2] <---- Logic Gate[NAND]
                 |                              
                 v                              
Inverter <-- Logic Gate[OR] <--- "true"          
    |                                           
    v
OUTPUT
```

### Parameterisation

*Activation*: if the `Switch` is `OFF` then the circuit doesn't do anything.

*Period*: can be adjusted by setting the timer in `Delay Gate`s properly.

### Use cases

Doors can be automatically closed using this circuitry.