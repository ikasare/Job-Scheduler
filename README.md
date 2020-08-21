# Job-Scheduler
A project that makes use of the Binary Search Tree data structure to allow users to create a job schedule.

This project is implemented using Python3.

Companies and people always have a list of jobs or tasks that they aspire to complete in a day.

This program maintains the scheduling of these daily jobs. 

The program is also dynamic: New jobs can be scheduled and completed ones can be removed.

There are a basic number of jobs that are fed to the program when it starts. These jobs are added in the `dataa.txt` file.

The program is able to load these jobs and create a starter schedule from the load file when it starts.

The program is dynamic: Jobs can be added and removed and the order of scheduled jobs still remains intact.

Jobs only run one at a time. There is no overlap during the duration of a job.

The load file, `dataa.txt`, is dynamically updated as jobs are being added or removed. This is to ensure that the modified daily schedule are not lost when the user exits.

Binary Search Tree is used to implement this.

The key for the nodes is time. Since time is continuous and we can only have one job run at a time the BST will not allow for duplicate jobs. Also, scheduling becomes easy.

The BST structure ensures that we are able to always provide an in-order form of the jobs and e can easily insert and remove jons all the while ensuring there is no overlap.

