# Common Monadic Forms

:-1: bad
```
	void includeSetupPageInto(StringBuffer pageText)
 ```

:+1: good
```
	StringBuffer includeSetupPageInto(StringBuffer in)
	void includeSetupPageInto(StringBuffer out)
}
```



