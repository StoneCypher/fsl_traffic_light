# fsl_traffic_light
FSL 4-state Traffic Light.  Used as a model for translation

```fsl
machine_name     : "Traffic light";
machine_author   : "John Haugeland / @stoncypher";
machine_comment  : "4-state traffic light; translation model";
machine_license  : MIT;
machine_language : en;
machine_version  : 1.0.1;
fsl_version      : 1.0.0;





Off 'Enable' -> Red;

Red 'Proceed' -> Green 'Proceed' -> Yellow 'Proceed' -> Red;

[Green Yellow Red] 'Disable' ~> Off;
```

![](traffic%20light.png)
