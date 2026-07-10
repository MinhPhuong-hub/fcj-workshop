---
title: "Worklog week 2"
weight: 2
chapter: false
pre: " <b>1.2 </b> "
---

# Worklog Week 2: IAM, permissions, and least privilege

**Time:** 20/04/2026 - 26/04/2026

## Week 2 objectives

- Understand IAM users, groups, policies, roles, and temporary credentials.
- Practice group-based permissions, role switching, and scoped policies.
- Record common IAM permission mistakes encountered during labs.

---

## Tasks to complete this week

| Day | Task | Start date | Completion date | References |
|---|---|---|---|---|
| Mon | Study IAM concepts: principal, action, resource, and condition.<br>Compare IAM users, groups, roles, and policies. | 20/04/2026 | 20/04/2026 | [IAM Workshop](https://000002.awsstudygroup.com/)<br>[IAM User Guide](https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html) |
| Tue | Create a sample permission model: Admin, Operator, and ReadOnly.<br>Practice role switching and verify temporary permission sessions. | 21/04/2026 | 21/04/2026 | [IAM Workshop](https://000002.awsstudygroup.com/)<br>[IAM User Guide](https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html)<br>[IAM Best Practices](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html) |
| Wed | Write a policy to restrict region and instance type for lab usage.<br>Check the effect of Allow, Deny, and Condition in IAM policies. | 22/04/2026 | 22/04/2026 | [IAM Workshop](https://000002.awsstudygroup.com/)<br>[IAM User Guide](https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html)<br>[Amazon EC2 Workshop](https://000004.awsstudygroup.com/)<br>[Amazon EC2 Documentation](https://docs.aws.amazon.com/ec2/) |
| Thu | Relate IAM to the final project: the EC2 worker must use an instance profile instead of hard-coded access keys.<br>Create a minimum-permission checklist for the worker. | 23/04/2026 | 23/04/2026 | [IAM Workshop](https://000002.awsstudygroup.com/)<br>[IAM User Guide](https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html)<br>[AWS Well-Architected Security Pillar](https://docs.aws.amazon.com/wellarchitected/latest/security-pillar/welcome.html) |
| Fri-Sun | Summarize errors caused by incorrect resource scope or missing trust relationships.<br>Delete unnecessary test users, roles, and policies. | 24/04/2026 | 26/04/2026 | [IAM Best Practices](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html)<br>[AWS Free Tier Workshop](https://000001.awsstudygroup.com/)  |

---

## Week 2 outcomes

- Understood how IAM controls authentication and authorization in AWS.
- Learned to use roles instead of static access keys when services need AWS API access.
- Created a least-privilege checklist for EC2 worker, RDS, SQS, CloudWatch, and S3 evidence components.

---
