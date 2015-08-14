# Memory Investigations of an Rails app

- static benchmark command: <kbd>bundle exec derailed bundle:mem</kbd>
- dynamic benchmark command: <kbd>bundle exec derailed exec perf:mem</kbd>

benchmarks are under `doc/` folder with prefix like `static` and `dynamic` which
uses static benchmark and dynamic benchmark commands respectively.

- ENV

```
export SECRET_KEY_BASE="88b723b7d14f3c33e08cc5e995d04ee0355a769de91c4343c04f03dbacf877bd4501ec480394128353a131f136bfd044a148c50821b98891f4795b2a78e0c042"
```
