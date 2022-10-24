# simbio-earm

## Installation

```
pip install simbio-earm
```

## Usage

```python
from simbio.models.earm import <model>
from simbio.simulator import Simulator

t = range(100)
Simulator(<model>).run(t).plot()
```
