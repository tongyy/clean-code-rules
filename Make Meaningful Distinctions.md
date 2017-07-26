Make Meaningful Distinctions


:-1: bad
```
public static void copyChars(char charArray1[], char charArray2[]) {
	for (int i = 0; i < charArray1.length; i++) {
	charArray2[i] = charArray1[i];
}
```

 
:+1: good
```
public static void copyChars(char source[], char target[]) {
	for (int i = 0; i < source.length; i++) {
	target[i] = source[i];
}
```



