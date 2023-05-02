----

### Cloud Computing

This course provides an introduction to the concepts, architecture, and programming techniques in high-performance cloud computing environments. An emphasis is placed on scalable web services applications, and large scale data processing and data mining applications. Topics include cloud computing, data processing in large clusters, distributed data processing, distributed storage systems, virtualization, MapReduce algorithms, and NoSQL databases. Students will study state-of-the-art solutions developed by Google, Amazon, VMWare, Yahoo, Microsoft, Sun/Oracle, and the research community. Topics may vary to reflect the current state-of-the-art and student interest. Students will apply what they learn in a series of introductory lab exercises and a final project using a cloud computing platform.

Prerequisites: CS-2852 or CS-2851.  

Course structure: 2-2-3 (class hours/week, lab hours, credits).  

Required Materials:  
- Notebook computer required. No text: see reading materials.

Upon successful completion of this course, the student will:  
- Understand the basic concepts, architecture, and programming techniques in parallel and distributed computing environments.

- Understand how to select an appropriate distributed system architecture for a given application scenario.

- Understand how to design, develop, and deploy a basic distributed application.

Grading:  
Weekly labs and final project: 60%   
Midterm: 20%   
Final: 20%   

Office DH425:    
M and Th 4-5pm 

References:  

- Video: Above the Clouds: A Berkeley View of Cloud Computing: http://www.youtube.com/watch?v=IJCxqoh5ep4 
- M. Armbrust, A. Fox, R. Griffith, A. Joseph, R. Katz, A. Konwinski, G. Lee, D. Patterson, A. Rabkin, I. Stoica, and M. Zaharia. Above the Clouds: A Berkeley View of Cloud Computing, Technical Report No. UCB/EECS-2009-28. 
- Amazon Web Services (AWS) Documentation: http://aws.amazon.com/documentation/ 
- J. Dean and S. Ghemawat, MapReduce: Simplified Data Processing in Large Clusters, Communications of the ACM, 2008. 
- Hadoop Documentation: http://hadoop.apache.org/common/docs/current/ 
- C. Olston, B. Reed, U. Srivastava, R. Kumar, and A. Tomkins, Pig Latin: A Not-So-Foreign Language for Data Processing, ACM SIGMOD 2008. 
- M. Isard, M. Budiu, Y. Yu, A. Birrell, and D. Fetterly, Dryad: Distributed Data-Parallel Programs from Sequential Building Blocks, ACM EuroSys 2007. 
- Y. Yu, M. Isard, D. Fetterly, M. Budiu, U. Erlingsson, P. K. Gunda, and J. Currey. DryadLINQ: A System for General-Purpose Distributed Data-Parallel Computing using a High-Level Language, Usenix OSDI 2008. 
- S. Ghemawat, H. Gobioff, and S-T. Leung, The Google File System, ACM SOSP 2003. 
- F. Chang, J. Dean, S. Ghemawat, W. Hsieh, D. Wallach, M. Burrows, T. Chandra, A. Fikes, and R. Gruber, Bigtable: A Distributed Storage System for Structured Data, Usenix OSDI 2006. 
- Optional: G. DeCandia, D. Hastorun, M. Jampani, G. Kakulapati, A. Lakshman, A. Pilchin, S. Sivasubramanian, P. Vosshall, amd W. Vogels,Dynamo: Amazon's Highly Available Key-value Store, ACM SOSP 2007. 
- D. Engler, D. Y. Chen, S. Hallem, A. Chou, and B. Chelf, Bugs as Deviant Behavior: A General Approach to Inferring Errors in Systems Code, ACM SOSP 2001. 
- Optional: B. Cantrill, M. Shapiro, and A. Leventhal, Dynamic Instrumentation of Production Systems, Usenix 2004. 
- J. Sugerman, G. Venkitachalam, and B-H. Lin, Virtualizing I/O Devices on VMWare Workstation's Hosted Virtual Machine Monitor, Usenix 2001. 
- Optional: P. Barham, B. Dragovic, K. Fraser, S. Hand, T, Harris, A. Ho, R. Neugebauer, I. Pratt, and A. Warfield, Xen and the Art of Virtualization, ACM SOSP 2003. 
- Optional: C. Clark, K. Fraser, S. Hand, J. G. Hansen, E. Jul, C. Limpach, I. Pratt, and A. Warfield, Live Migration of Virtual Machines, Usenix NSDI 2005. 
- X. Qie, R. Pang, and L. Peterson, Defensive Programming: Using an Annotation Toolkit to Build DoSResistant Software, Usenix OSDI 2002. • Optional: E. Shi, A. Perrig, and L. Van Doorn, BIND: A Fine-grained Attestation Service for Secure Distributed Systems, IEEE S&P 2005. 
- M. Herlihy and J. E. B. Moss, Transactional Memory: Architectural Support for Lock-Free Data Structures, ISCA 1993. 
- Optional: B. Saha, A-R. Adl-Tabatabai, R. Hudson, C. C. Minh, and B. Hertzberg, McRT-STM: A High Performance Software Transactional Memory System for a Multi-Core Runtime, ACM PPoPP 2006. 
- A. Adya, J. Dunagan, and A. Wolman, Centrifuge: Integrated Lease Management and Partitioning for Cloud Services, Usenix NSDI 2010. • Grid Engine: http://gridengine.sunsource.net/ 
- Optional: Anand Rajaraman, Jeffrey D. Ullman, Mining Massive Data Sets, 2010.

---

### Week 1: Intro to Cloud Computing

<!--
[1. Intro to Cloud Computing](http://jayurbain.com/msoe/cs4230/slides/Cloud%20Briefing/cloud_briefing_x2.pdf) 
-->

[1. Intro to Cloud Computing](slides/cloud_briefing_x2.pdf) 

[Lab 1: Introduction to Cloud Computing using AWS](https://docs.google.com/document/d/1umFyMuCpuccp9mrPfZk4ygAGBxkZIVNvUsSXPyjq8h8/edit?usp=sharing)
<!--
[Lab 1: Introduction to Amazon Web Services - Launching an EC2 Machine Instance](http://jayurbain.com/msoe/cs4230/cs4230-lab1-aws.pdf)  

[Awesome Lab 2: Creating an Amazon Machine Image (AMI)](http://jayurbain.com/msoe/cs4230/cs4230-lab2-aws.pdf)  
-->
Reading:    
[M. Armbrust, A. Fox, R. Griffith, A. Joseph, R. Katz, A. Konwinski, G. Lee, D. Patterson, A. Rabkin, I. Stoica, and M. Zaharia. Above the Clouds: A Berkeley View of Cloud Computing, Technical Report No. UCB/EECS-2009-28.](http://jayurbain.com/msoe/cs4230/Readings/Above%20the%20Clouds%20-%20A%20Berkeley%20View%20of%20Cloud%20Computing.pdf)

References:  
[vi cheat sheet](http://www.lagmonster.org/docs/vi.html)    - link not working  
[Ubuntu Guides](https://help.ubuntu.com/community/ExternalGuides)     
[Ubuntu/Linux command Line cheat sheet](http://files.fosswire.com/2007/08/fwunixref.pdf)    
  
### Week 2: Virtual Machines

[3. Virtual Machines](slides/l2_VMM.pdf) 

[Lab 2: Most Excellent Flask EC2 Web App on AWS](https://docs.google.com/document/d/1SeYCrRIlKWzPCu04Jx4rJGFggfuHj2FbDh7IVQAO0LY/edit?usp=sharing)

[Lab 2: Flask Elastic Beanstalk Web App on AWS](https://docs.google.com/document/d/1KA7DlPtYOd4JO3J8fygLDxEtw36hgIoeduiac0XIPIY/edit?usp=sharing)

[4. Auto Scaling Computing Clusters](http://jayurbain.com/msoe/cs4230/slides/cs4230-autoscaling-4.pdf)

Reading:   
[Virtual Machine Monitors](http://pages.cs.wisc.edu/~remzi/OSTEP/vmm-intro.pdf)  
[Xen and the Art of Virtualization](http://jayurbain.com/msoe/cs4230/Readings/Xen%20and%20the%20Art%20of%20Virtualization.pdf)  
[Amazon Web Services (AWS) Documentation](http://aws.amazon.com/documentation/)   

<!--
[Lab 3: EBS](http://jayurbain.com/msoe/cs4230/cs4230-lab3-ebs.pdf)
-->

### Week 3: Containers, Composing and Orchestrating Applications 

[5. Intro to Docker and Containers](slides/Docker.pdf)

[Lab 4: Docker](https://docs.google.com/document/d/1O2coHp9cKl_PWLVcEVvlgebWFlIZXLntHSH0Hffa5K0/edit?usp=sharing)

[6. Container Orchestration](slides/Container Orchestration.pdf)

Reference:  
Install Python, pip, and the EB CLI on Linux (Thanks Harry Kubiak!)     
https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/eb-cli3-install-linux.html    

<!--
Developing and Deploying Web Applications on AWS
1) Instructions for setting up Eclipse for Web Development, development of Web command pattern with Servlet
2) Developing a Model-View-Controller with Command Servlet, JSP View
3) Java JDBC sample project with MySQL: Database2.jar
4) Lab 5: Deploying a Web App to an AWS EC2 Instance
A Servlet and JSP Tutorial
Servlet and JSP development with Eclipse WTP
Miksu Vojtech - PHP Intallation Instructions

Reading:
[S. Ghemawat, H. Gobioff, and S-T. Leung, The Google File System, ACM SOSP 2003.](http://jayurbain.com/msoe/cs4230/Readings/The%20Google%20File%20System.pdf)

[WEBSEARCH FOR A PLANET: THE GOOGLECLUSTER ARCHITECTURE](http://jayurbain.com/msoe/cs4230/googlecluster-ieee.pdf)

[Lab 4. Elastic Load Balancing and Auto-Scaling Clusters with VPC](http://jayurbain.com/msoe/cs4230/cs4230-lab4-autoscaling-web-VPC.pdf)

-->

### Week 4: Container Orchestration with Docker Compose and Kubernetes, CAP Theorem

[Lab 5: Composing a Flask-MySQL app with docker and docker-compose](https://docs.google.com/document/d/19ehdRBdGwGS2LC5-WNqttChIFvu-iDW_HOIaU23Nw8E/edit?usp=sharing)

[Lab 6: Deploy a Flask API Service on Kubernetes](https://docs.google.com/document/d/1z6fkpfDdjuaPl9_zOaI7Hk-yhioZoXKSsg-jwJt1ZNE/edit?usp=sharing)

[7. CAP Theorem](slides/CAP-theorem.pdf)    

References:  

[Docker Compose](https://docs.docker.com/compose/overview/)  
[Kubernetes Concepts](https://kubernetes.io/docs/concepts/overview/)

### Week 5: Distributed Storage Systems, Map Reduce Application Examples

[8. Technologies for Scalable Distribution, AWS Dynamo](slides/dynamo-5.pdf)

[lab 17: DynamoDB Web App](https://docs.google.com/document/d/1crUDhpT3c5uzKunTMMiwFSU2IPuiN0YJKNvMcrSeTKs/edit?usp=sharing)


<!--
[Lab 4. Elastic Load Balancing and Auto-Scaling Clusters with VPC - Continued](http://jayurbain.com/msoe/cs4230/cs4230-lab4-autoscaling-web-VPC.pdf)
-->

### Week 6: MIDTERM, Distributed Database  

[MIDTERM - study guide](https://docs.google.com/document/d/1iC41RVYHphK4a7dhmrgEp9VGwJsjNEg6l7KtbMDY0EU/edit?usp=sharing) 

[Map Reduce](slides/map_reduce_algo.pdf)

Extra content:    
[Data-Intensive Text Processing with MapReduce.pdf (Ch. 2, 3)](http://jayurbain.com/msoe/cs4230/Data-Intensive%20Text%20Processing%20with%20MapReduce.pdf)  
[MapReduce and DFS Applications](http://jayurbain.com/msoe/cs4230/slides/map_reduce_applications.pdf)  
[MapReduce Application Examples](http://jayurbain.com/msoe/cs4230/slides/map_reduce_examples.pdf)
[Big Data Storage in Modern Databases](http://jayurbain.com/msoe/cs4230/slides/Big%20Data%20Storage%20in%20Modern%20Databases.pdf)
[High Performance Database Systems](http://jayurbain.com/msoe/cs4230/slides/HighPerformanceDatabaseSystems.pdf)
[Distributed Storage Systems. Google File System (GFS)](http://jayurbain.com/msoe/cs4230/slides/cs4230-google-file-system-3.pdf[])
[MapReduce Algoirthms](http://jayurbain.com/msoe/cs4230/slides/map_reduce_algo2.pdf)   
[Hadoop Commands](https://hadoop.apache.org/docs/r2.7.1/hadoop-project-dist/hadoop-common/CommandsManual.html)
[Hadoop Documentation](http://hadoop.apache.org)
[C. Olston, B. Reed, U. Srivastava, R. Kumar, and A. Tomkins, Pig Latin: A Not-So-Foreign Language for Data Processing, ACM SIGMOD 2008.](http://jayurbain.com/msoe/cs4230/Readings/Pig%20Latin%20-%20A%20NotSoForeign.pdf)

<!--
[Lab 6:]()  
[Lab 6 Part 1: Hadoop Download and Install](http://jayurbain.com/msoe/cs4230/Hadoop/cs4230-download%20and%20install%20hadoop.pdf)   
[Lab 6 Part 2: Hadoop Query](http://jayurbain.com/msoe/cs4230/Hadoop/hadoop%20query%20lab.pdf)  
[Lab 6 Part 3: Hadoop MapReduce](http://jayurbain.com/msoe/cs4230/Hadoop/hadoop%20mapreduce%20lab.pdf)
-->

[Example: Hadoop WordCount with Eclipse on Cloudera QuickStart VM](http://jayurbain.com/msoe/cs4230/HadoopWordCount.zip)

### Week 7: Data Platforms, Spark

[Data Platforms](https://docs.google.com/presentation/d/1wCImXY9Q3KWbhLS0q-s5ndKnrPaC9zbq4hdFOW8xK1I/edit?usp=sharing)

[Lab 7 Part 1 & 2](https://docs.google.com/document/d/1mnORjsRg634MG5JCOO6dU3wGlIyBHqQPEqzJ1yOlroQ/edit?usp=sharing)

References:    

[Resilient Distributed Datasets: A Fault-Tolerant Abstraction for In-Memory Cluster Computing](https://www.usenix.org/conference/nsdi12/technical-sessions/presentation/zaharia)

[Google's BigTable](http://jayurbain.com/msoe/cs4230/slides/cs4230-googleBigTable.pdf)

### Week 8: Machine Learning on Large Distributed Datasets   

[Scalable Machine Learning](https://docs.google.com/presentation/d/1XIHAxrk4uE2CMW2d3rFkXdAY9w1lDTSLwrsW-dwAPr0/edit?usp=sharing)

[Machine Learning Intro](https://docs.google.com/presentation/d/1R6A_0nqWS7H_6AVnm0L1K8zPy6aReFBFMT0auo5l7Dc/edit?usp=sharing)

[Lab 8 Scalable Linear Regression using PySpark](labs/PySpark/Tutorial%206%20-%20Pyspark%20-%20Machine%20Learning%20.ipynb)  

References:    
[Introduction to MLOps - Databricks](introduction-to-mlops-aws.pdf)

[The Big Book of MLOps - Databricks](The-Big-Book-of-MLOps-v6-082322.pdf)

<!--
Reading:   
[F. Chang, J. Dean, S. Ghemawat, W. Hsieh, D. Wallach, M. Burrows, T. Chandra, A. Fikes, and R. Gruber, Bigtable: A Distributed Storage System for Structured Data, Usenix OSDI 2006.](http://jayurbain.com/msoe/cs4230/Readings/Bigtable%20-%20A%20Distributed%20Storage%20System%20for%20Structured%20Data.pdf)

[Dynamo: Amazon's Highly Available Key-value Store](http://jayurbain.com/msoe/cs4230/slides/dynamo-5.pdf)

[Optional: G. DeCandia, D. Hastorun, M. Jampani, G. Kakulapati, A. Lakshman, A. Pilchin, S. Sivasubramanian, P. Vosshall, amd W. Vogels,Dynamo: Amazon's Highly Available Key-value Store, ACM SOSP 2007.](http://jayurbain.com/msoe/cs4230/Readings/Bigtable%20-%20A%20Distributed%20Storage%20System%20for%20Structured%20Data.pdf)

### Week 9: Data Mining: Finding Similar Sets at Scale, Minhashing  

[Finding Similar Sets: Jaccard, Shingling, MinHash, and LSH](http://jayurbain.com/msoe/cs4230/slides/FindingSimilarSets.pdf)

[Lab 8: Finding similar sets](http://jayurbain.com/msoe/cs4230/cs4230-lab8-finding_similar_sets.pdf)

-->

### Week 9: Data Mining: Frequent Item Sets

[Scalable Mining of Frequent Itemsets](http://jayurbain.com/msoe/cs4230/slides/dm06FPBasic.pdf)

[Final Exam Review](http://jayurbain.com/msoe/cs4230/CS4230-final-exam-study-guide.pdf)

### Week 10: Search, Review

### Week 11: Final Exam 

CS 4230-011, Urbain, Wednesday 2:00PM-4:00, DH338

