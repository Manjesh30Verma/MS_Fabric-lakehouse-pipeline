"Building Your First Lakehouse on Microsoft Fabric Using PySpark: A Step-by-Step Guide"

Step 1: Set up Microsoft Fabric Environment
Before you begin, ensure you have access to Microsoft Fabric. This platform integrates analytics, data engineering, and machine learning, enabling easy use of PySpark for large-scale data operations.

Create a Workspace:

Navigate to Microsoft Fabric and create a new workspace.
This workspace will host your Lakehouse and support the data and analytics workload.
Create a Lakehouse in the Workspace:

Once your workspace is set up, click on New -> Lakehouse.
Name your Lakehouse and configure the settings, including the storage account or location in the cloud.

Step 2: Set up PySpark Environment in Fabric
Microsoft Fabric allows you to use Spark environments for data engineering and machine learning.

Create a Notebook:

From the workspace, create a Notebook where you’ll write and execute PySpark code.
Choose PySpark as your language environment in the notebook settings.
Connect to the Lakehouse:

Load your Lakehouse data into the notebook by connecting PySpark to the Lakehouse storage.
Use Spark’s built-in data access libraries to connect to your Lakehouse.
Example code to connect and explore the data:


![Screenshot from 2024-10-04 15-03-29](https://github.com/user-attachments/assets/2c618c00-3a04-4874-84a3-81a79c084995)

![Screenshot from 2024-10-04 15-03-43](https://github.com/user-attachments/assets/610d01ad-7eb5-4a95-82fd-103d9db3035c)

![image](https://github.com/user-attachments/assets/2b2662d7-1212-4d14-bf54-3e05b7d5f7b0)

![image](https://github.com/user-attachments/assets/c047cc52-53f5-4a2a-963c-ac839db7c3e0)

