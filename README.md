# gaction-conditional-workflows
Mastering Workflow & Job Execution with conditional steps, job matrices, failure handling, and reusable workflows for efficient CI/CD.

This repository is a hands-on practice project for mastering Controlling Execution Flow in GitHub Actions.

Background: By default, GitHub Actions workflows execute sequentially, halting all subsequent steps and jobs if a failure occurs. However, in real-world scenarios, it's often necessary to continue execution even after a failure—for instance, to perform cleanup tasks or send failure notifications.
To address this, Conditional Execution enables greater control over workflows by allowing steps and jobs to run only under specific conditions, such as executing only on a particular branch or triggering actions exclusively on failure. Additionally, Advanced Execution Control introduces features like job matrices (executing workflows across different configurations) and reusable workflows (enhancing efficiency by avoiding redundancy).

Topics Covered in This Repository
	1. Conditional Steps & Jobs
	2. Controlling Execution via "if"
	3. Special Conditional Functions
	4. Conditional Jobs
	5. More 'if' examples
	6. Ignoring errors and failures with "continue-on-error"
	7. Using Matrix Strategies, Including and Excluding Values
	8. Reusable Workflows
	9. Adding Inputs to Reusable Workflows
	10. Secrets
	11. Reusable Workflows Outputs

This repository is a structured guide to learning these concepts with practical implementations.
