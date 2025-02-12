<!-- markdownlint-disable -->

<a href="../../charm/src/charm.py#L0"><img align="right" style="float:right;" src="https://img.shields.io/badge/-source-cccccc?style=flat-square"></a>

# <kbd>module</kbd> `charm.py`
Django Charm entrypoint. 

**Global Variables**
---------------
- **CRON_EVERY_5_MINUTES**
- **CRON_AT_MIDNIGHT**


---

## <kbd>class</kbd> `DjangoCharm`
Django Charm service. 

<a href="../../charm/src/charm.py#L24"><img align="right" style="float:right;" src="https://img.shields.io/badge/-source-cccccc?style=flat-square"></a>

### <kbd>function</kbd> `__init__`

```python
__init__(*args: Any) → None
```

Initialize the instance. 



**Args:**
 
 - <b>`args`</b>:  passthrough to CharmBase. 


---

#### <kbd>property</kbd> app

Application that this unit is part of. 

---

#### <kbd>property</kbd> charm_dir

Root directory of the charm as it is running. 

---

#### <kbd>property</kbd> config

A mapping containing the charm's config and current values. 

---

#### <kbd>property</kbd> meta

Metadata of this charm. 

---

#### <kbd>property</kbd> model

Shortcut for more simple access the model. 

---

#### <kbd>property</kbd> unit

Unit that this execution is responsible for. 



---

<a href="../../charm/src/charm.py#L72"><img align="right" style="float:right;" src="https://img.shields.io/badge/-source-cccccc?style=flat-square"></a>

### <kbd>function</kbd> `restart`

```python
restart() → None
```

Restart all services. 

---

<a href="../../charm/src/charm.py#L110"><img align="right" style="float:right;" src="https://img.shields.io/badge/-source-cccccc?style=flat-square"></a>

### <kbd>function</kbd> `workload`

```python
workload() → Container
```

Get workload container. 

Delete this function when it is in the paas-app-charmer project. 



**Returns:**
  Workload Container 


