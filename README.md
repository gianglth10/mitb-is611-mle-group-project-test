# mitb-is611-mle-group-project-test



![Architecture Diagram](./Untitled%20Diagram.drawio.svg)



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


