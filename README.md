# mitb-is611-mle-group-project-test


## System Architecture

```mermaid
flowchart LR
DB["Data"]
Train["Model Training"]
Registry["Model Registry"]
Deploy["Model Deployment"]
Monitor["Monitoring"]

DB --> Train --> Registry --> Deploy --> Monitor
```



![Architecture Diagram](./MLE.svg)
