`boot repl` and then:

```clojure
(require '[clojure.java.io :as io])
(read-string (slurp (io/resource "config.edn")))
```
