# AWS Compute - EC2

## Definations
- **AWS EC2** : Amazon EC2 is a web service that provides secure, resizable compute capacity in the cloud.
- **AWS EC2 Parts** :
  - vCPU
  - Memory
  - Network
  - Storage
  - GPU
- **EC2 instance family** :

    | Family | Description  | Usage  |
    |---|---|---|
    |**General purpose**|Provides a balance of compute, memory, and networking resources, and can be used for a variety of workloads.|Scale-out workloads such as web servers, containerized microservices, caching fleets, distributed data stores, and development environments.|
    |**Compute optimized**|Ideal for compute-bound applications that benefit from high-performance processors.|High-performance web servers, scientific modeling, batch processing, distributed analytics, high-performance computing (HPC), machine/deep learning, ad serving, highly scalable multiplayer gaming.|
    |**Memory optimized**|Designed to deliver fast performance for workloads that process large data sets in memory.|Memory-intensive applications such as high-performance databases, distributed web-scale in-memory caches, mid-size in-memory databases, real-time big-data analytics, and other enterprise applications.|
    |**Accelerated computing**|Use hardware accelerators or co-processors to perform functions such as floating-point number calculations, graphics processing, or data pattern matching more efficiently than is possible with conventional CPUs.|3D visualizations, graphics-intensive remote workstations, 3D rendering, application streaming, video encoding, and other server-side graphics workloads.|
    |**Storage optimized**|Designed for workloads that require high, sequential read and write access to large data sets on local storage.|NoSQL databases, such as Cassandra, MongoDB, and Redis, in-memory databases, scale-out transactional databases, data warehousing, Elasticsearch, and analytics.|
 
- **AWS AMI (Amazon Machine Image)** : Ready and configured structure for creating an EC2 instance.
- **EC2 Lifecycle** :
  - Lunuch
  - Pending
  - Running
    - Reboot
    - Stop
      - Stoping
      - Stopped
    - Stop-Hibernate
  - Terminate
    - Shutting-down
    - Terminated
-  **EC2 Pricing options** : 
   -  `On-Demand` : Billing begins whenever the instance is running, and billing stops when the instance is in a stopped or terminated state. 
   -  `Reserved (RIs)`: RIs provide a discounted hourly rate and an optional capacity reservation for EC2 instances. RIs has these payment options :
      - **All Upfront**
      - **Partial Upfront**
      - **No Upfront**
   -  `Spot` : allow you to take advantage of unused EC2 capacity in the AWS Cloud. 
## Nice to remember
- Every EC2 instance need to exists inside a network.
- One advantage of using AMIs is that they are reusable. 
- If an EC2 instance terminated, all of data will be wiped out.
- EC2 charged your account when you are in `running` state or `stopping` state, preparing to `hibernate`
- If any resouce put in __default__ AWS VPC, it would be accessible over the internet.
- `On-Demand` and `No Upfront` is similar but they have a diffrence. by stopping an `On-Demand` instance you pay nothing, but `No Upfront` chargs your account, because it has commited to 1 to 3 year.

## Resources
- [AWS Regions and  Availability Zones](https://aws.amazon.com/about-aws/global-infrastructure/regions_az/)
- [AWS Cloud Technical Essentials | Crousera](https://www.coursera.org/learn/aws-cloud-technical-essentials)
