# Member Prefixes

You also don¡¦t need to prefix member variables with m_ anymore. Your classes and functions
should be small enough that you don¡¦t need them.

:-1: bad
```
public class Part {
	private String m_dsc; // The textual description
	void setName(String name) {
		m_dsc = name;
	}
}

```
:+1: good
```
public class Part {
	String description;
	void setDescription(String description) {
		this.description = description;
	}
}
```



