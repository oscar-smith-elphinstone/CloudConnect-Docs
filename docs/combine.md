# Combine
The combine step is used to combine two datasets by matching timeseries data point between them. The combine function is able to match over a custom time interval ensuring data that is not synced can still be combined together accurately.

Single column data sets can be added, subtracted, divided or multiplied by each other. This if you want to perform a calculation which involves two or more signals. Keep in mind that the combine function can be chained like the other steps. This means you can combine as many tables as you need into a single column table.

There are 5 combine types currently available throught the combine step with more options set to come soon.

## Multiply

```
COMBINE (Name) Data_1 Data_2 MULTIPLY(time_interval)
```

## Divide
```
COMBINE (Name) Data_1 Data_2 DIVIDE(time_interval)
```

## Add
```
COMBINE (Name) Data_1 Data_2 ADD(time_interval)
```

## Subtract
```
COMBINE (Name) Data_1 Data_2 SUBTRACT(time_interval)
```

## Merge
```
COMBINE (Name) Data_1 Data_2 MERGE(time_interval)
```