### napalm
---
https://github.com/napalm-automation/napalm

```py
// napalm/nxos/__init__.py
import pkg_resources

from napalm.nxos.nxos import NXOSDriver
from napalm.nxos.nxos import NXOSDriverBase

try:
  __version__ = pkg_resources.get_distribution("napalm-nxos").version
except pkg_resources.DistributionNotFound:
  __version__ = "Not installed"

__all__ = ("NXOSDriver", "NXOSDriverBase")
```

```
```

```
```

