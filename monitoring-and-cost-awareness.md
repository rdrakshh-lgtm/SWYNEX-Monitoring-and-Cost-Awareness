\# Monitoring and Cost Awareness



\## 1. Overview



This document describes basic monitoring, status checks, alerting, cost awareness, and security practices for cloud deployments.



Project: SWYNEX Basic Cloud Deployment



Live Website:

https://rdrakshh-lgtm.github.io/SWYNEX-Basic-Cloud-Deployment/



GitHub Repository:

https://github.com/rdrakshh-lgtm/SWYNEX-Basic-Cloud-Deployment



\## 2. Monitoring and Status Checks



Monitoring helps identify website availability problems and deployment failures.



The following checks can be performed:



\- Open the deployed website and verify that it loads correctly.

\- Check that HTML, CSS, images, and other assets load without errors.

\- Use browser Developer Tools to identify failed requests and JavaScript errors.

\- Review the GitHub repository's Actions tab for workflow results, if workflows are configured.

\- Check the repository's deployment status and GitHub Pages settings.

\- After every update, verify that the live website reflects the latest changes.



\## 3. Logging and Deployment Status



For this static website, GitHub provides deployment information rather than application-server logs.



Useful checks include:



\- Review GitHub Actions logs when a deployment workflow runs.

\- Check deployment status and error messages in the repository.

\- Use browser Developer Tools to inspect network failures.

\- Record deployment failures and the steps taken to resolve them.



\## 4. Simple Alert Idea



A simple availability alert can help identify when the website becomes inaccessible.



Proposed approach:



1\. Check the website periodically using an uptime-monitoring service.

2\. Configure an alert when repeated checks fail.

3\. Send notifications through email or another supported notification channel.

4\. Investigate the hosting status, deployment history, and website configuration.

5\. Confirm the website is accessible after resolving the issue.



Note: This is a proposed monitoring approach and requires a monitoring service to be configured.



\## 5. Cost Awareness Checklist



\- Prefer free or low-cost hosting when appropriate.

\- Review the pricing and usage limits of cloud services before deployment.

\- Set a budget and billing alerts when using paid cloud services.

\- Remove unused cloud resources to avoid unnecessary charges.

\- Optimize images and other large assets to reduce transfer and storage usage.

\- Review usage and billing dashboards regularly.

\- Understand that free-tier limits and service pricing may change.



For this demonstration, the website is hosted using GitHub Pages, which supports static website hosting.



\## 6. Security and Access-Control Checklist



\- Enable two-factor authentication on the GitHub account.

\- Use strong, unique passwords.

\- Keep repository permissions limited to trusted contributors.

\- Never commit passwords, API keys, access tokens, or other secrets.

\- Review code changes before merging them.

\- Keep project dependencies updated when applicable.

\- Use HTTPS when accessing the deployed website.

\- Review repository settings and deployment permissions regularly.



\## 7. Recommended Monitoring Workflow



1\. Make changes to the website.

2\. Test the changes locally.

3\. Commit and push the changes to GitHub.

4\. Review the deployment status.

5\. Open the live website and verify the result.

6\. Investigate any errors and redeploy after fixing them.

7\. Periodically review security settings and hosting costs.



\## 8. Conclusion



Basic monitoring, deployment verification, cost awareness, and access control help maintain a reliable and secure website.



These practices provide a foundation for monitoring more advanced cloud deployments in future projects.

