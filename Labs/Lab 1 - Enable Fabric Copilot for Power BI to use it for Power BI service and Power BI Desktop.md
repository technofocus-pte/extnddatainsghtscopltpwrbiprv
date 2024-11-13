# Enable Fabric Copilot for Power BI to use it for Power BI service and Power BI Desktop

## Task 1 - Enable Fabric Trial License

1.  Open a browser and paste the [Fabric
    Trial](https://www.microsoft.com/en-us/microsoft-fabric/getting-started)
    URL

2.  Click on **Try for Free.**

![A screenshot of a computer Description automatically
generated](./media/image1.png)

3.  Enter your credentials.

![A screenshot of a login screen Description automatically
generated](./media/image2.png)

4.  Once you enter your credentials and selected Next. You will be
    navigated to Microsoft Fabric Home page.

![A screenshot of a computer Description automatically
generated](./media/image3.png)

5.  You must make sure that the Trial licence is enabled by selecting
    the account on top-right corner of the Fabric home page. Select
    **Free Trial.**

![A screenshot of a computer Description automatically
generated](./media/image4.png)

6.  Select **Free Trial.**

![A screenshot of a computer Description automatically
generated](./media/image5.png)

7.  Once it is enabled, select **Fabric Home Page.** You will be
    navigated to Fabric Home Page.

![A screenshot of a computer Description automatically
generated](./media/image6.png)

![A screenshot of a computer Description automatically
generated](./media/image7.png)

## Task 2 - Create Fabric Capacity using Azure portal

Microsoft Fabric is deployed to an Azure Active Directory tenant. Within
each Fabric tenant, Fabric capacities can be created to group resources
for various purposes -- this might be done organizationally (sales,
marketing, development), geographically, or other logical grouping.

If a Fabric Trial is available, we recommend taking advantage of that
opportunity to try Microsoft Fabric for a period of time (currently 60
days) with no commitment. To see if you are in a trial or eligible for a
trial, visit the [Fabric portal](https://app.fabric.microsoft.com/). If
you are able to log in or presented the option to start a trial, you
should be all set!

To create a Fabric capacity outside of a trial environment, create a new
resource from the Azure portal, and search for Fabric.

1.  Login to Azure Portal – <https://portal.azure.com> with the
    credentials provided to you to execute the lab.

2.  From the Azure portal home page, click on **Azure portal menu**
    represented by three horizontal bars on the left side of the
    Microsoft Azure command bar as shown in the below image.

> ![A screenshot of a computer Description automatically
> generated](./media/image8.png)

3.  Navigate and click on **+ Create a resource**.

> ![A screenshot of a computer Description automatically
> generated](./media/image9.png)

4.  On **Create a resource** page, in the **Search services and
    marketplace** search bar, type!!**Fabric!!**, then select
    **Microsoft fabric**.

> ![A screenshot of a computer Description automatically
> generated](./media/image10.png)

5.  In the **Marketplace** page, navigate to the **Microsoft Fabric**
    section, click on the **Create** button dropdown, then select
    **Microsoft Fabric** as shown in the image.

> ![A screenshot of a computer Description automatically
> generated](./media/image11.png)

6.  In the **Create Fabric capacity** window, under the **Basics** tab,
    enter the following details and click on the **Review+create**
    button.

[TABLE]

> ![](./media/image12.png)

7.  Once the Validation is succeeded, click on the **Create** button.

> ![A screenshot of a computer Description automatically
> generated](./media/image13.png)

8.  After the deployment is completed, click on the **Go to resource**
    button.

![](./media/image14.png)

## Task 3 - Using Copilot for Power BI in the service

To use Copilot in the Power BI service, you need to ensure that reports
are in a workspace at the right capacity. The workspace must be in
either Premium Power BI (P1 and above) or paid Fabric (F64 and
above) capacity.

### Step 1 - Create a Fabric Workspace

1.  Switch back to Fabric Home page.

2.  Go back to **Power BI** window. Select Power BI from the left bottom
    navigation pane.

![A screenshot of a computer Description automatically
generated](./media/image15.png)

3.  On the left side navigation menu of **Power BI** Home page, navigate
    and click on **Workspaces**.

![](./media/image16.png)

4.  In the Workspaces pane, click on **+** **New workspace button.**

> ![A screenshot of a computer Description automatically
> generated](./media/image17.png)

5.  In the **Create a workspace** pane that appears on the right side,
    enter the following details, and click on the **Apply** button.

[TABLE]

> ![](./media/image18.png)
>
> ![](./media/image19.png)

6.  Wait for the deployment to complete. It takes 2-3 minutes to
    complete.

![](./media/image20.png)

7.  Select **Workspace settings.**

![A screenshot of a computer Description automatically
generated](./media/image21.png)

8.  Select **License info** and check that workspace is created under
    **Fabric Capacity**

![A screenshot of a computer Description automatically
generated](./media/image22.png)

## Task 4 - Using Copilot in Power BI Desktop

1.  Launch the Power BI application from the desktop in the VM

2.  Sign in with the credentials that is provided to execute the lab

3.  Once you are logged in, select **Copilot.**

![A screenshot of a computer Description automatically
generated](./media/image23.png)

4.  Enter the credentials provided to you to execute the lab.

5.  Once you are logged in, you can access apps and services.

![](./media/image24.png)

6.  Select **Select Workspace.**

7.  Click on drop-down to select your workspace that you created.

![](./media/image25.png)

8.  Select **OK**

![](./media/image26.png)

9.  Select **Get Started**

![](./media/image27.png)

![A screenshot of a phone Description automatically
generated](./media/image28.png)
