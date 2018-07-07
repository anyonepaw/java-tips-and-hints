**'Optional.get()' without 'isPresent()' check** 

```
...findFirst().orElse(null);
Returns the value if present, otherwise returns null. 
The documentation says that the passed parameter may be null (what is forbidden for orElseGet and orElseThrow).
```
https://stackoverflow.com/questions/38725445/optional-get-without-ispresent-check
