```sh
$ sbt '+ compile'
$ srcclr scan --debug | grep 'Building graph' | sed -n 's/.*\(Building graph.*\)/\1/p'
Building graph using Scala 2.10.6, sbt 0.13.16
```
test1
