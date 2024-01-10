<!-- Start SDK Example Usage [usage] -->
```python
import tom
from tom.models import shared

s = tom.Tom()

req = shared.Pet(
    id=596804,
    name='string',
)

res = s.pets.create_pets(req)

if res.status_code == 200:
    # handle response
    pass
```
<!-- End SDK Example Usage [usage] -->