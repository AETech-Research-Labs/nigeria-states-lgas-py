# Nigeria States & LGAs (Python Package)

A simple Python package containing all **36 Nigerian States + FCT** and their **Local Government Areas (LGAs)**.

## Installation
```bash
pip install nigeria-states-lgas
```
## Usage
```python
from nigeria_states_lgas.utils import get_states, get_lgas

print(get_states())        # List of all states
print(get_lgas("Kaduna"))  # List of LGAs in Kaduna
print(get_lgas("FCT"))      # List of LGAs in Federal Capital Territory
```