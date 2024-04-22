Task 1. Created a custom bash script to monitor swype deployment restarts.
The scripts get the number of restart of the container and scaled down the replicas 
to zero after the pod restarts more that 3 times.

Task 2. Handling recurring obsolete alerts and prioritizations.

 - Handling recurring obsolete alerts
   1. Recurring obsolete tasks can be annotated with labels such that they can be 
      filtered from monitorting dashboard.
      
   2. Obsolete alerts can be classified as low-priority

- Prioritizations of alerts
  1. Classify the alerts into various serverity level based on 
      - issue, blast radius and customer impact
      - number of people or teams that are needed to assist.

  2. Integrate this classification into incident response system.