# Access the Real-Time Intelligence Copilot and improve the accuracy 

## Task 1 - Create KQL Database

1.  On the Fabric Home page. <https://app.fabric.microsoft.com>. Login
    with the credentials if you have not logged in.

2.  Select **Real-Time Intelligence** from the Bottom left corner of the
    Microsoft Fabric Home page.

![](./media/image1.png)

3.  Select **EventHouse** under **Recommended items to create**

![](./media/image2.png)

**Note** – Make sure you are creating under a fabric capacity workspace.

4.  Enter the database name as – Database 1

![](./media/image3.png)

5.  Select three horizontal dots beside the database name. Select **Get
    Data \> Sample.**

![](./media/image4.png)

6.  Select **Stock Analysis.**

![](./media/image5.png)

7.  The table is loaded

![A screenshot of a computer Description automatically
generated](./media/image6.png)

## Task 2 - Create a KQL Query Set

1.  Select **Real-Time Intelligence** and Select **KQL QuerySet**

![A screenshot of a computer Description automatically
generated](./media/image7.png)

2.  Enter **Demo** as the name of the Query set and select **Create**

![A screenshot of a computer Description automatically
generated](./media/image8.png)

3.  Select the **Database 1** that you created in the previous task and
    select **Connect**

![](./media/image9.png)

4.  The Queryset is loaded

![A screenshot of a computer Description automatically
generated](./media/image10.png)

## Task 3 - Access the Real-Time Intelligence Copilot

1.  Select the **Copilot** button.

![A screenshot of a computer Description automatically
generated](./media/image11.png)

2.  In the Copilot pane, enter your business question in natural
    language. - **List of top 10 rows of stocks table**

3.  Press **Enter**. After a few seconds, Copilot will generate a KQL
    query based on your input. ![A screenshot of a chat Description
    automatically generated](./media/image12.png)

4.  You can copy the query to the clipboard, or **Insert** it directly
    in the KQL query editor. To run the query in the query editor, you
    must have write access to the KQL queryset. Select
    the **Run** button to execute the query.

![A screenshot of a computer Description automatically
generated](./media/image13.png)

5.  The Query runs successfully.

![A screenshot of a computer Description automatically
generated](./media/image14.png)
