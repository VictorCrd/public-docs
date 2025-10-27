# Example Documentation

This document contains examples of Python code.

## Creating a DataFrame

Here is a simple way to create a pandas DataFrame:

```python
import pandas as pd

data = {'col1': [1, 2], 'col2': [3, 4]}
df = pd.DataFrame(data)
print(df)
```

## A More Complex Example

This snippet demonstrates creating a DataFrame with various data types.

```python
import pandas as pd
import numpy as np

data = {
    'Name': ['Tom', 'Nick', 'Krish', 'Jack'],
    'Age': [20, 21, 19, 18],
    'Score': [np.nan, 85, 90, 95]
}

df_users = pd.DataFrame(data)
print(df_users.info())
```

This file ends here.
