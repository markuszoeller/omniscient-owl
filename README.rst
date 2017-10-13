======
README
======

This project contains all the logic for the lifecycle of software.
Each folder has a detailed description what its specific focus is.
The flow of things should be this iterative approach::

                 +--------+
         +------>| source +-------+
         |       +--------+       v
    +----+---+                +-------+
    | change |                | build |
    +--------+                +-------+
         ^                        |
         |                        v
    +---------+              +---------+
    | operate |              | release |
    +---------+              +---------+
           ^                    |
           |                    v
         +---------+    +--------+
         | upgrade |<---| deploy |
         +---------+    +--------+


