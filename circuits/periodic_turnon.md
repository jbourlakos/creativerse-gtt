# Periodic Turn-on

## Purpose

This circuit automatically emits an `ON` signal every `X` (`X/2`+`X/2`) seconds.

## Components

 - Mandatory
   - `Logic Gate` x 3
   - `Delay Gate` x 2
 - Optional
   - `Switch` x 1 (as `INPUT`)

## Layout

```
[INPUT] --> Logic Gate[AND] --> Delay Gate[X/2] 
    |            ^                     |        
    -------------|-------------------  |        
                 |                  |  |        
                 |                  v  v        
          Delay Gate[X/2] <---- Logic Gate[NAND]
                 |                              
                 v                              
            Logic Gate[OR] <--- "true"          
                 |                              
                 v                              
             [OUTPUT]                           
```

## Tinkering

*Activation*: if the `INPUT` is `OFF` then the circuit doesn't do anything; a `Switch` can be added on `INPUT` to handle the circuit.

*Period*: can be adjusted by setting the timer in `Delay Gate`s properly.

## Use cases

 - Lights can be automatically reactivated after turning them off.