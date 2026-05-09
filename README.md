# mitb-is611-mle-group-project-test

## System Architecture (drawio)

![Architecture Diagram](./MLE.drawio.svg)


## System Architecture (mermaid)

```mermaid
flowchart LR
DB["Data"]
Train["Model Training"]
Registry["Model Registry"]
Deploy["Model Deployment"]
Monitor["Monitoring"]

DB --> Train --> Registry --> Deploy --> Monitor
```


