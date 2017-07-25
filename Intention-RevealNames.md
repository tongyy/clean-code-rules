# Intention-Revealing Names


:-1: bad
```
int d; // elapsed time in days
```

 
:+1: good
```
int elapsedTimeInDays;
int daysSinceCreation;
int daysSinceModification;
int fileAgeInDays;
```

------------------------------------------------


:-1: bad
```
public List<int[]> getThem() {
   List<int[]> list1 = new ArrayList<int[]>();
   for (int[] x : theList)
   if (x[0] == 4)
   list1.add(x);
   return list1;
 }
```
:+1: good
```
public List<int[]> getFlaggedCells() {
   List<int[]> flaggedCells = new ArrayList<int[]>();
   for (int[] cell : gameBoard)
   if (cell[STATUS_VALUE] == FLAGGED)
   flaggedCells.add(cell);
   return flaggedCells;
}

 public List<Cell> getFlaggedCells() {
   List<Cell> flaggedCells = new ArrayList<Cell>();
   for (Cell cell : gameBoard)
   if (cell.isFlagged())
   flaggedCells.add(cell);
   return flaggedCells;
}
 ```
