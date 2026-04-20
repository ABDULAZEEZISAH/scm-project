### SCM RESEARCH PROJECT
**SOURCE CODE MANAGEMENT RESEARCH PROJECT**
**How does Git enhance source code management practices in modern software development, and what are its key advantages and challenges compared to other version control systems?**
Git enhances modern source code management by enabling fast, distributed, and collaborative development, which aligns perfectly with Agile and DevOps practices. Its biggest strengths—flexibility and power—are also where its main challenges lie, particularly in terms of complexity and learning curve.
**How Git enhances source code management**
At its core, Git is a distributed version control system (DVCS). Every developer has a full copy of the repository, including its entire history. That alone changes a lot:
•	Offline work: You can commit, branch, and review history without needing a network connection. 
•	Fast operations: Since most actions are local, they’re significantly quicker than centralized systems. 
•	Powerful branching & merging: Git makes it cheap and easy to create branches, which encourages workflows like feature branching, bug-fix branches, and experimentation without affecting the main codebase.
**Key advantages of Git**
1. Distributed architecture
Unlike centralized systems, Git doesn’t rely on a single server. This improves reliability and resilience—if a server goes down, developers still have full copies.
2. Efficient branching model
Branches are lightweight and fast to create/merge. This supports modern workflows like:
•	Feature-based development 
•	Gitflow or trunk-based development 
3. Data integrity
Git uses hashing (SHA-1/SHA-256) to track changes, ensuring that history cannot be easily corrupted or altered unnoticed.
4. Performance
Local commits, diffs, and logs are extremely fast compared to systems that require server communication.
5. Strong ecosystem
Tools, integrations, and community support are massive—especially with platforms like GitHub.
