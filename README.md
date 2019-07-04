# home-assistant-configs-cfs
Home Assistant configurations for my home automation system


# network diagram
```

                                 +-------------+
                                 |     NBN     |
                                 +------+------+
                                        |
                                        |
                             +----------+-------------+
                             |      CISCO GATEWAY     |
                             +----------+-------------+
                                        |
                                        |
 +-----------+                    +------+------+                  +-------------------+
 | Study PC  +----------------+---+  USG|8|150W +------------------+  Unifi|AP|AC|PRO  |
 +-----------+                |   +------+------+                  +-------------------+
                              |          |
 +-----------+                |          |
 |   Ubuntu  +----------------+          |
 +-----------+                       +---+---+                     +-------------------+
                                     | USG|8 +----+----------------+       TUNER       |
                                     +---+---+    |                +-------------------+
                                         |        |
                                         |        |                +-------------------+
                                         |        +----------------+        NUC        |
                                         |                         +-------------------+
                                         |
                               +---------+---------+
                               |  Unifi|AP|AC|PRO  |
                               +-------------------+
```
