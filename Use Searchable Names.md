# Use Searchable Names


:-1: bad
```
for (int j=0; j<34; j++) {
	s += (t[j]*4)/5;
}

```

 
:+1: good
```
int realDaysPerIdealDay = 4;
	const int WORK_DAYS_PER_WEEK = 5;
	int sum = 0;
	for (int j=0; j < NUMBER_OF_TASKS; j++) {
	int realTaskDays = taskEstimate[j] * realDaysPerIdealDay;
	int realTaskWeeks = (realdays / WORK_DAYS_PER_WEEK);
	sum += realTaskWeeks;
}

```



