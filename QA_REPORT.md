Viduli Deployment QA Assessment – Brief Report

Name: Nalin Trivedi

Bugs

404 After Successful Deployment
The application returned a 404 Not Found response even after a successful deployment and green status indicator. There was no clear indication that configuring the Run Command was mandatory.

Logs Not Visible When Pod Fails
When the application failed to start, the Logs section appeared empty until a running pod was manually selected, with no explanatory message shown to the user.

Paid Tier Payment Failure
Attempts to deploy using the Paid Tier were blocked due to payment method rejection. The platform did not provide clear error messages or guidance to resolve the issue.

Usability Issues

Run Command Terminology Is Confusing
The use of “Run Command” instead of “Start Command” caused confusion during application setup.

Secrets Configuration Lacks Guidance
No examples or hints are provided in the Secrets section, making it unclear what values should be entered.

Logs Discovery Is Not Intuitive
Accessing logs requires navigating to a separate tab and manually selecting a pod, which is not obvious for first-time users.

Documentation Quality

Missing Minimal Deployment Example
Documentation lacks a complete minimal Node.js example showing required run commands and port binding.

CI/CD Behavior Not Clearly Explained
GitHub auto-rebuild behavior and deployment triggers are not clearly documented.

No Troubleshooting for Common Errors
Common issues such as 404 responses, missing run commands, and logging behavior are not covered in a troubleshooting section.

