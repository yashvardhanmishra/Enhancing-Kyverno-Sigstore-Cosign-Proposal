# Proposal: Enhancing Kyverno's Sigstore Cosign Module
#### Author : [@Yashvardhan mishra](https://github.com/yashvardhanmishra)

#### Upstream issue: [kyverno/kyverno#7087](https://github.com/kyverno/kyverno/issues/7087)



## Contents
[1. Background](#1-background)   
[2. Objectives](#2-objectives)    
[3. Proposal](#3-proposal)        
[4. Initial Experimentation](#4-initial-experimentation)   
[5. References](#5-references)

## 1. background
The Kyverno project currently supports image signature and attestation verification using the Sigstore Cosign tooling. This proposal aims to re-implement the Kyverno Sigstore Cosign module by leveraging OCI artifacts and references while eliminating dependencies on the Cosign CLI packages. The objective is to enable Kyverno to utilize OCI artifacts for validating container images in Cosign format.

## 2. Objectives 
The primary objective of this mentorship project is to re-implement Kyverno's Sigstore Cosign module to utilize OCI artifacts and references, while eliminating dependencies on the Cosign CLI packages. By achieving this, the project aims to accomplish the following objectives:

1. Enable Kyverno to verify container images in Cosign format using OCI artifacts, thereby enhancing the security and integrity of containerized workloads.

2. Improve the overall performance and efficiency of the Sigstore Cosign module in Kyverno.

3. Ensure compatibility and seamless integration with the existing Kyverno architecture and Kubernetes environments.
## 3. Initial Experimentation
To kickstart the project, the following experimentation plan will be executed:

1. Set up a local development environment with the latest version of Kyverno and the necessary dependencies.    

2. Familiarize myself with the current implementation of Kyverno's Sigstore Cosign module and its integration with Cosign CLI packages.  

3. Investigate and evaluate the capabilities and usage of OCI artifacts and references in image verification. 

4. Develop a proof-of-concept implementation to validate the feasibility of utilizing OCI artifacts for verifying container images in Cosign format.            

5. Perform a comparative analysis between the current implementation and the proof-of-concept to assess the potential benefits and challenges of the proposed changes.
## 4. Proposal
The proposed approach to achieve the objectives is as follows:

### Analysis and Dependencies Removal
Conduct a thorough analysis of the current implementation of Kyverno's Sigstore Cosign module and identify the dependencies on Cosign CLI packages.     
### Research and Exploration
Research and explore the usage of OCI artifacts and references for image verification within Kyverno.
### Design and Implementation
Design and implement the necessary changes in the Sigstore Cosign module to leverage OCI artifacts and references, adhering to best practices and standards.         

### Integration and Testing
Integrate the updated module into Kyverno, ensuring compatibility with existing features and workflows. 
### testing and quality assurance
Perform rigorous testing and quality assurance to validate the functionality, performance, and security of the enhanced Sigstore Cosign module.         
### Documentation and Reporting
Document the changes made, provide clear instructions, and contribute to the project's documentation for seamless adoption by the Kyverno community.
## Skills and Expertise:
To demonstrate proficiency in the required skills for this mentorship opportunity, I would like to highlight my experience and expertise in the following areas:

##### Golang:
I have a strong background in Golang programming, with hands-on experience in developing and maintaining Go-based projects. I am well-versed in Go best practices, idioms, and libraries, which will enable me to effectively implement the necessary changes in Kyverno's Sigstore Cosign module.

##### Kubernetes: 
I have acquired in-depth knowledge of Kubernetes and its associated concepts through professional experience and self-study. I have successfully deployed and managed Kubernetes clusters, implemented Kubernetes-based solutions, and have a good understanding of Kubernetes architecture and workflows. 

##### Kyverno:
agerly Learning and Applying Kyverno Concepts to Contribute to the Sigstore Cosign Module , Progressing in Learning Kyverno's Architecture and Functionality for Effective Mentorship Contributions



In addition to the above technical skills, I also possess strong problem-solving abilities, effective communication skills, and a dedication to learning and collaborating within a community-driven project like Kyverno, makes me a suitable candidate for this mentorship.




## References

1.Kyverno Documentation: https://kyverno.io/docs/            
2.Sigstore Documentation: https://sigstore.dev/      
3.OCI Artifacts Specification: https://github.com/opencontainers/artifacts
