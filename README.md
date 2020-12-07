# compressJSON
The function `compressJSON(json)` compresses (using *z-lib compression*) and then *Base-64 Encodes* any **JSON** string.

Before it does so, it verifies that the string it has been given to process is a **valid JSON**.

______

## compressJSON Function

### Step 1

The function `compressJSON(json)` verifies that the string passed to the function:

 - represents a valid **JSON** string

If this condition is not met, the `compressJSON(json)` function will return a verbose error detailing how the string may be fixed.

### Step 2

If the condition above is met, the `compressJSON(json)` function returns the validated JSON as a **compressed and Base-64 Encoded JSON string**.

_____

### `compressJSON(json)` (client-side) :

```

```

### `compressJSON(json)` (server-side) :

```

```
