## *kqlite*

**SQL database engine with high availability and automatic failover.**

***kqlite*** is a lighweight remote frontend to **SQLite** over the **PostgreSQL** wire protocol.<br>
Remote clients can connect to the same database and perform concurent reads and writes.<br>
**High availability** is easy to setup with only two nodes (cluster model is Primary->Secondary, no Raft like rqlite or dqlite).<br>

It's a solution for applications that require **High Availability**, but don't need all the features of a complete RDBMS and can perfectly fit **SQLite** in their use case.<br>
Also ***kqlite*** can be considered to be used as a storage backend for **K8s** (https://docs.k3s.io/datastore) and the **Edge**.<br>


🌈 Contribution guidelines - As this is a opensource project everyone can get involved (soon to add more details).<br>
👩‍💻 Useful resources - https://www.spectrocloud.com/blog/two-node-ha-kubernetes-for-edge-computing-cost-savings <br>


