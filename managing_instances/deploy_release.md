# Deploy Release
some text

## Who can perform this function?
Any of the roles below:
* Solution Center Administrator
* Solution Center Company Administrator
* Solution Center Solution Administrator
* Solution Center Instance Administrator

## Deploy a specified portal release to an instance and configure portal runtime nodes for an instance
### Steps:
1. On the left panel, click **Solutions**. A list of all the solutions for your company that have access to the solution center will be displayed.
2. Select your solution by clicking on the solution name.
3. Click the **Instances** tab. A list of all the instances for the selected solution will be displayed.
4. Select an instance by clicking on the instance name to retrieve an instance.
5. Click the **Deployments** tab.
6. Click **Deploy Release**. A list of active releases will be displayed.
7. Click **Add Release**.
8. Provide a friendly release name in the field **Release Name**.
9. Provide a release description in the field **Release Description**.
10. Attach a YAML file for the release, and click the **Add Release** button. At thi stage, your release is ready for deployment.
11. Run the release by clicking on the action button next to the desired release.
12. Release will be deployed, and will be available once the nodes have started.
    * The number of portal runtime nodes for a development instance is 1.
    * The number of portal runtime nodes for a pre-production instance is 2.
    * By default, the number of portal runtime nodes for a production instance is 2. However, you're allowed to increase the number of portal runtime nodes for a production instance upto 10.
12. You can view the status of all the portal runtime nodes under the **Active Nodes** section.
13. You can scale up your nodes for an instance by clicking on the up arrow next to the **Scale** field under the **Scales Nodes** column. Also, you can increase the node memory by clicking on the up arrow next to the **Scale** field under the **Memory per Node** column. The maximum amount of memory allowed per node is 4GB.