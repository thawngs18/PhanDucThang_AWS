---
title: "Week 1 - Getting familiar with AWS and basic AWS services"
weight: 1
---

## Objective

- Learn company regulations and culture, complete internship procedures with the supervisor, and establish a shared workflow with the FCJ team.
- Understand AWS Free Tier 2025 policies, identify high-cost-risk services, and build a safe budget control plan.
- Build a secure IAM system, apply the Least Privilege principle, and minimize Root account usage.
- Master cloud networking fundamentals (VPC, Subnet, IGW, NAT Gateway) and network security layers (Security Group, Network ACLs).
- Practice building an independent virtual network (VPC) and deploying an EC2 server on AWS.

## Tasks Completed

### Date 17/04/2026

- Meet, get acquainted, and build relationships with team members.
- Review company regulations, culture, and internship workplace rules in detail.
- Reference: [https://rules.fcjuni.com/1-regulations/](https://rules.fcjuni.com/1-regulations/)

### Date 20/04/2026

- Contact and officially confirm internship information with the academic supervisor.
- Proactively connect, form the team, and assign roles with FCJ members.
- Standardize communication channels and task management tools.

### Date 21/04/2026

- Study updated AWS Free Tier 2025 documentation.
- List and note services with high cost-overrun risk to avoid unexpected charges.
- Register an AWS account and complete five basic tasks to receive $200 credits.
- Configure billing alerts for safe budget control.
- Reference: [https://000001.awsstudygroup.com/](https://000001.awsstudygroup.com/)

### Date 22/04/2026

- Set up the IAM trio: User, Group, and Role.
- Use policies to define allowed and denied actions based on the Least Privilege principle.
- Avoid daily Root account usage and enforce MFA for the Admin account.
- Implement Switch Role so OperatorUser can temporarily assume Admin privileges when required.
- Successfully create AdminGroup, AdminUser, OperatorUser, and assign AllowSwitchAdminPolicy to complete the lab.
- Reference: [https://000002.awsstudygroup.com/](https://000002.awsstudygroup.com/)

### Date 23/04/2026

- Learn about Subnets, Route Tables, Internet Gateway, and NAT Gateway.
- Understand how Security Groups, Network ACLs, and VPC Resource Map work.
- Reference: [https://000003.awsstudygroup.com/](https://000003.awsstudygroup.com/)

### Date 24/04/2026

- Created VPC, Subnet, Internet Gateway, Route Table, Security Group, and enabled VPC Flow Logs monitoring.
- Deployed EC2: Created the server and verified successful VSCode-to-server connection.
- Reference: [https://000003.awsstudygroup.com/](https://000003.awsstudygroup.com/)

## Labs completed

<div class="row g-3">
  <div class="col-md-4">
    <div class="card h-100 shadow-sm">
      <div class="card-body">
        <h5 class="card-title">Lab 001 - AWS Free Tier</h5>
        <p class="card-text">Activated the AWS account, completed five starter tasks for credits, configured AWS Budgets alerts, and terminated resources after practice.</p>
      </div>
    </div>
  </div>

  <div class="col-md-4">
    <div class="card h-100 shadow-sm">
      <div class="card-body">
        <h5 class="card-title">Lab 002 - AWS IAM</h5>
        <p class="card-text">Created User/Group/Role, applied least-privilege policies, enabled MFA, validated Switch Role, and confirmed the Deny &gt; Allow rule.</p>
      </div>
    </div>
  </div>

  <div class="col-md-4">
    <div class="card h-100 shadow-sm">
      <div class="card-body">
        <h5 class="card-title">Lab 003 - Amazon VPC</h5>
        <p class="card-text">Built a VPC with public/private subnets, configured IGW/NAT Gateway, route tables, security group, network ACL, and verified EC2 connectivity.</p>
      </div>
    </div>
  </div>
</div>

## Outcome

- Internship information was confirmed, FCJ team structure was completed, roles were clarified, and communication/management tools were aligned.
- Successfully registered AWS account, completed five starter tasks for $200 credits, and configured billing alarms.
- Successfully configured IAM entities (AdminGroup, AdminUser, OperatorUser), enabled MFA for Admin, and set up Switch Role (AllowSwitchAdminPolicy).
- Deployed network infrastructure including VPC, Subnet, Internet Gateway, Route Table, Security Group, and enabled VPC Flow Logs.
- Successfully launched an EC2 server and validated connection from VSCode.
