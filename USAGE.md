<!-- Start SDK Example Usage -->
```python
import tom

s = tom.Tom()


res = s.pets.create_pets()

if res.status_code == 200:
    # handle response
    pass
```
<!-- End SDK Example Usage -->