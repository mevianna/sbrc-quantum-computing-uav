# Search String
This study adopted a structured search strategy across three electronic databases to identify scientific articles on quantum-based 
approaches for collision avoidance in UAVs. A comprehensive search string was applied across all databases to capture a wide range 
of relevant terminology.

The search strategy was structured into **three conceptual blocks** combined using the Boolean operator AND.
- The **first block targeted quantum-related studies**. The generic term "quantum" was intentionally adopted, instead of more specific
expressions such as "quantum computing" or "quantum algorithms", to avoid overly restricting the search space and to capture a broader
range of potentially relevant studies.
- The **second block focused on collision-related concepts**, including collision avoidance, obstacle detection, conflict detection
and related planning.
- The **third block addressed autonomous and aerial vehicle systems**, encompassing UAVs, drones, autonomous vehicles, and
multi-vehicle systems.

```text
("quantum") AND ("anti-collision" OR "anticollision" OR "collision-free" OR "pre-crash" OR "collision avoidance" OR 
"collision-avoidance" OR "collision warning" OR "collisions" OR "collision" OR "obstacle avoidance" OR "obstacle detection" 
OR "sense and avoid" OR "trajectory prediction" OR "motion prediction" OR "path planning" OR "trajectory planning" OR 
"route planning" OR "crash avoidance" OR "conflict detection" OR "conflict resolution" OR "deconfliction" OR 
"scheduling takeoff times" OR "traffic congestion" OR "traffic prediction" OR "air traffic" OR "object detection") AND 
("UAV" OR "UAVs" OR "drone" OR "drones" OR "unmanned aerial vehicle" OR "unmanned aerial vehicles" OR "autonomous vehicle" 
OR "autonomous vehicles" OR "automated vehicle" OR "automated vehicles" OR "intelligent vehicle" OR "intelligent vehicles" OR 
"transportation system" OR "transportation systems" OR "multi-vehicle" OR "autonomous system" OR "autonomous systems" OR 
"autonomous mobile robot" OR "autonomous mobile robots" OR "vehicle" OR "vehicles")
```

# Databases
This study consulted the **IEEE Xplore**, **Web of Science**, and **ACM Digital Library**, selected for their relevance and comprehensive coverage of the research topic. These sources provide broad and up-to-date access to the literature in engineering, computer science, and emerging technologies, supporting a rigorous and systematic analysis.

## How to apply the string to the databases

### IEEE Xplore
For **IEEE Xplore**, the complete search string was applied as a single query using the standard search interface, without relying on advanced search options. All conceptual blocks were therefore considered simultaneously during retrieval.  
Access: [IEEE Xplore](https://ieeexplore.ieee.org/Xplore/home.jsp)

### ACM Digital Library
The ACM Digital Library provides two main search interfaces: the ACM Guide to Computing Literature and the ACM Full-Text Collection. In this study, searches were conducted using the **ACM Guide to Computing Literature**, as it offers broader coverage, including indexed records beyond ACM-published full texts.

The **Advanced Search** interface was employed. The search string was divided according to the Boolean AND operators, with the first field populated by quantum*. The corresponding configuration is illustrated in the figure below.

<p align="center">
  <img src="img/acm-string.jpeg" alt="ACM Advanced Search" width="700">
</p>

<p align="center">
  <strong>Figure 1.</strong> How to perform the advanced search using this string.
</p>

Additionally, the **Research Article filter** was applied to restrict the results to peer-reviewed research publications.



