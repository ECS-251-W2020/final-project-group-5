# Week 4 Summary
<strong>Activities in the past week:</strong>
1. Completed the outer implementation of Reference Committee
2. Segregated the inter shard transaction core logic from intra shard
3. Created new messages to Handle overall 2 Phase Commit for inter shard<br>
    3.1 Request_2PC<br>
    3.2 Vote_2PC<br>
    3.3 Commit_2PC<br>
    3.4 Abort_2PC<br>
4. Partially completed the Request_2PC call to other shard via 
Reference Committee

<strong>Activities planned for this week:</strong>
1. Handle Request_2PC when received by other shard
2. Sending of Vote_2PC back to Reference Committee
3. Perform Global Commit to complete inter shard transaction

<strong>Issues:</strong>
1. No blockers as of now
