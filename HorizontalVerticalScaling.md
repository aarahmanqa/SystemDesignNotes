# Horizontal and Vertical Scaling
## Link
https://youtu.be/xpDnVSmNFX0?si=mRjwgRxtfhNh7UA6
## Horizontal Scaling:
Increase the number of servers
## Vertical Scaling:
Increase the configuration of system
## Differences:
<img width="843" alt="image" src="https://github.com/aarahmanqa/SystemDesignNotes/assets/6194278/e3827938-9ad0-4a9b-8735-726ef432698f">

## One of the issues with the Vertical Scaling is `Data Inconsistency`. To overcome the same, these are the techniques used:
## Distributed Locking:
Implementing distributed locking ensures that only one node modifies a piece of data at a time, reducing conflicts and maintaining data integrity
## Optimized Transaction Processing:
Implement robust transaction management systems to handle concurrent data operations effectively
## Consensus Algorithms:
Utilize algorithms like Paxos or Raft for coordinated decision-making across distributed systems
## Eventual Consistency Models:
In scenarios where immediate consistency is not critical, adopt eventual consistency to improve performance while ensuring data accuracy over time
