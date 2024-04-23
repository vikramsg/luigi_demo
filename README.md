## Objective

1. We want to have a lightweight task manager. 
2. We should be able to submit 1000's of jobs to the task manager. 
3. The task manager should be capable of simultaneously running and tracking 100's of jobs. 
4. We should be able to see a UI to keep track of jobs. 


## Run

```
PYTHONPATH='.' luigi --module demo WordCount  --local-scheduler --date-interval 2012-06
```