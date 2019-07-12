# Configuring Storage

This topic describes how application developers can create new storage configuration to support the data storage needs of applications.

## Creating Storage

Create storage configuration for your application as per the following steps:

1. In the left navigation bar, select **Container > Storage**.

2. Click the **New Storage** button and complete the detailed configuration of the storage.

3. Provide the basic information for the storage:

   - **Application**: Select an application that requires the storage.
   - **Environment**: Select the storage usage environment, for which dev, alpha, beta, ppe, and prod environments are supported currently.
   - **Cluster**: Select the cluster where the application is deployed. Note that the cluster is already pre-configured by the system.

4. Enter the storage capacity (GB) that is required by the application.

5. Enter the maximum limit on the number of stored files.

  .. image:: ../../media/storage_config.png

6. Enter the description for the storage.

7. Click the **New Storage** button to complete the configuration.

## Next Step

After the storage configuration is created, you can clone, edit and delete it as needed. The specific steps are similar to those for [Configuring Deployments](configuring_deployment).

<!--end-->
