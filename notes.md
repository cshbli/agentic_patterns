
## Some Setups

### Install Groq
```
pip install grop
```
You can apply a free Groq API Key. If you don't want to put API key in `.env` file. You can set it in the Jupyter Notebook:
```
os.environ["GROQ_API_KEY"] = "you API KEY"
```

### Others
- Install dotenv
```
pip install python-dotenv
```

- Install colorama
```
pip install colorama
```

### Python Path of agentic_patterns

In order to properly import `ReflectionAgent` from `agentic_patterns` source directory, you can append the source directory path in the Jupyter Notebook.

```
import sys
import os

# Add the path to the directory containing agentic_patterns
sys.path.append(os.path.abspath('../src'))

from agentic_patterns import ReflectionAgent
```
