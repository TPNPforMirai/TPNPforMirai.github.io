# Latency Record

## Overview

```flow
st=>start: Original Website
op1=>operation: RSSHub@Oracle Cloud
cond1=>condition: Blocked or NotBlocked?
e1=>operation: TPNP
e11=>operation: Trojan Proxy
st->op1->cond1
cond1(Blocked)->e11->e1
cond1(NotBlocked)->e1
```
