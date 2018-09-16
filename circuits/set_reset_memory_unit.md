# Set/Reset Memory Unit (1-bit)

## Acknowledgement

This circuit has been originally implemented by 
[Entuland](http://entuland.com/), creator of the 
[CreatiSign](http://entuland.com/creatisign/) web tool.

## Purpose

This circuit implements a memory unit. It "remembers" that it has received input
and it doesn't change its output until it receives a direct signal on its reset.

## Components

 - Mandatory
 - Optional

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
Inverter <- Logic Gate[OR] <--- "true"          
    |                                           
    v                                           
[OUTPUT]                                        
```

## Tinkering

*Activation*: if the `INPUT` is `OFF` then the circuit doesn't do anything; a `Switch` can be added on `INPUT` to handle the circuit.

*Period*: can be adjusted by setting the timer in `Delay Gate`s properly.

## Use cases

 - Doors can be automatically closed after being opened using this circuit.