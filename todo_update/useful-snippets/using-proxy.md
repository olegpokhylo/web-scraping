---
sidebar_position: 9.5
---

# Using Proxy

The following example demonstrates how to use a proxy:

```python 
class Task(BaseTask):
    browser_config = BrowserConfig(
        proxy = "http://lum-customer-hl_1b230841-zone-MYZONE:MYPW@zproxy.lum-superproxy.io:22225"
    )
```
