

|  SCHOOL OF INFORMATION AND TECHNOLOGY |  |  |
| ----- | :---- | :---: |
| NAME: **Villena**, Aeron Jeff A. | **Laraya**, Althea Joy Y. | DATE PERFORMED: Nov. 28, 2024 | /50  |
| Section: IDC2 | DATE SUBMITTED: Nov, 28, 2024 |  |

1. # **SYSADM1 – Capacity Management & Planning**

## **Part 1\. A Simulated Dataset for Capacity Planning Exercise**

**Scenario:** A mid-sized e-commerce website is expecting a significant surge in traffic due to an upcoming holiday sale.

### Projected Traffic Increase

* **Expected Peak Traffic:** 5x the normal peak traffic  
* **Peak Time:** 12:00 PM \- 3:00 PM on the sale day

  ### System Specifications

* **Server Count:** 5  
* **CPU Cores per Server:** 8  
* **RAM per Server:** 32GB  
* **Network Bandwidth per Server:** 1Gbps

  ### Additional Considerations

* **New Product Launch:** A highly anticipated product will be released during the sale.  
* **Marketing Campaign:** A major marketing campaign will be launched to promote the sale.  
* **Potential Cyber Threats:** Increased traffic can attract malicious actors.

Tasks:

1. Review the provided server performance data and identify potential bottlenecks

Based on the server performance data provided, we identified that there could be potential bottlenecks in the following:

| Key Metric | Potential Bottleneck |
| ----- | ----- |
| **CPU Utilization/Cores** | During the peak hours of 12:00\~3:00 PM with the expected heavy traffic, the 8 Core might not be able to handle requests that will result in **slower response time** and might **go beyond the limits of CPU capacity**. |
| **Network Bandwidth** | There will be a limited network bandwidth across all servers as it will increase 5x than the usual during the peak hour, which causes **congestion**, **slow data transfers**, leading to **packet drops**, and **disrupting user sessions**. |
| **Response Time** | In the current peak hour, the response time is already high but bearable but if the traffic will increase 5x, it will also increase alongside with it which leads to **user dissatisfaction** because of how slow the platform will be. |
| **Memory Allocation/Utilization** | The existing RAM might suffice for the usual traffic but it might cause the server to **freeze, lag, slower load times, and might render unable to process additional requests** due to the high processing during the heavy peak hour. |

2. Brainstorm possible solutions to address the identified bottlenecks. Propose potential solutions considering hardware and software-based solutions. 

   * **Add More Servers:** Increase the total number of servers in the system to handle the surge in traffic by distributing the workload more effectively.

   * **Upgrade Server Specifications:** Enhance the existing servers with higher-capacity CPUs, more RAM, or faster storage for better performance.

   * **Upgrade Network Bandwidth:** Increase the per-server or overall network bandwidth to reduce congestion and improve data transfer rates.

   * **Deploy Web Application Firewall (WAF):** Protect against malicious traffic, like DDoS attacks, by filtering harmful requests and reducing unnecessary server strain.

   * **Deploy Content Delivery Network (CDN):** To cache and deliver static content from edge servers closer to users, reducing server load and improving response times.

   * **Using Cloud Services:** Offer dynamic, scalable infrastructure that adapts to traffic demands, ensuring optimal resource usage, improved performance, and reduced downtime. 

3. Discuss the pros and cons of each proposed solution by filling out the table below. 

| Proposed Solution | Pros | Cons | Cost | Complexity | Potential impact on system performance |
| ----- | ----- | ----- | :---: | ----- | ----- |
| Add Additional servers | Increases overall capacity; distributes workload to handle traffic surges effectively.	 | Expensive; requires configuring new servers and updating the load balancer. | **High (PHP 112,000–280,000 per server)** | **Medium\-** It Requires hardware installation and configuration; also needs integration with load balancing. | **High** \- Significantly boosts capacity to handle 5x traffic. |
| Upgrade Server Specifications | Improves server performance without needing additional machines; can address CPU and RAM issues. | Costly; downtime is required to install upgrades, and it has limited scalability. | **High  (PHP 56,000–168,000 per server)** | **Low to Medium**\-Straightforward upgrades but may require temporary downtime. | **Moderate** \- Improves performance for single servers but not scalable for major surges. |
| Increase Network Bandwidth | Solves congestion issues by allowing faster data transfers. | High monthly cost; requires working with internet service providers (ISPs). | **High  (PHP 28,000–84,000/month per server)** | **Medium** \- Needs ISP coordination and network reconfiguration. | **High** \- Prevents data bottlenecks and improves overall system speed. |
| Deploy Content Delivery Network (CDN) | Reduces server load and improves response times by caching content closer to users. | Monthly fees apply; it doesn’t help much with dynamic or live data. | **Medium (PHP 2,800–28,000/month)** | **Low to Medium** \- Easy setup but requires integration into your application. | **High** \- Offloads traffic to the CDN, speeding up user experiences significantly. |
| Deploy Web Application Firewall (WAF) | Protects against attacks like DDoS and reduces unnecessary server load. | Requires technical expertise to set up and maintain; adding more operational cost. | **Medium (PHP 11,200–56,000/month)** | **Medium** \- Setting up security rules and maintaining them requires skill. | **Moderate to High** \- Prevents malicious traffic from disrupting the system. |
| Use Cloud Services | Provides dynamic scalability and ensures performance during traffic surges. | Recurring cost; requires significant time to migrate and configure. | **Medium to High (PHP 28,000–280,000/month depending on usage)** | **Medium to High**  \- Initial setup and integration with existing systems are challenging. | **Very High** \- Dynamically adjusts resources to handle traffic spikes effortlessly. |

Grading Rubric:

| Criteria | Excellent | 10pts | Good | 7pts | Needs Improvement | 4pts |
| ----- | :---- | :---- | :---- |
| **Problem Identification**  | Accurately identifies the primary problem and provides a detailed explanation. | Identifies the main problem and provides a basic explanation. | Identifies a problem but lacks clarity or accuracy. |
| **Solution Proposal**  | Proposes multiple relevant solutions and provides detailed explanations, including potential drawbacks and benefits. | Proposes one or two relevant solutions but lacks detailed explanation. | Proposes a solution but lacks feasibility or relevance. |
| **Evaluation of Solutions**  | Provides a thorough evaluation of the proposed solutions, considering factors like cost, complexity, and potential impact. | Provides a basic evaluation of the proposed solutions, but lacks depth. | Does not evaluate the proposed solutions or provides a superficial evaluation. |
| Score: |  |  |      /30 |

