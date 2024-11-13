# Use Copilot to create measure descriptions

## Task 1 - Enable the preview feature

1.  Launch the Power BI Desktop that is available on the desktop.

2.  Navigate to **File** \> **Options and settings** \> **Options**.

3.  Select **Preview features**, select **Measure descriptions with
    Copilot**.

![](./media/media9/image1.png)

4.  Check if the option is enabled, if it is not, check the option and
    select **OK.**

## Task 2 – Create a new Measure

1.  In the **Fields** pane on the right side of the page, right-click
    the **Sheet1** table, or hover over the table and select **More
    options** (**...**).

![A screenshot of a computer Description automatically
generated](./media/media9/image2.png)

2.  From the menu that appears, choose **New measure**.

> ![A screenshot of a search bar Description automatically
> generated](./media/media9/image3.png)

3.  This action saves your new measure in the **Sheet1** table, where
    it's easy to find.

4.  You can also create a new measure by selecting **New Measure** in
    the **Calculations** group on the **Home** tab of the Power BI
    Desktop ribbon.

> ![Screenshot of new measure from the ribbon.](./media/media9/image4.png)

**Tip -** When you create a measure from the ribbon, you can create it
in any of your tables, but it's easier to find if you create it where
you plan to use it. In this case, select the **Sheet 1** table first to
make it active, and then choose **New measure**.

5.  The formula bar appears along the top of the report canvas, where
    you can rename your measure and enter a DAX formula.

![](./media/media9/image5.png)

6.  By default, each new measure is named *Measure*. If you don’t rename
    it, new measures are named *Measure 2*, *Measure 3*, and so on.
    Because we want this measure to be more identifiable,
    highlight *Measure* in the formula bar, and then change it to **Sum
    of Sales**.

7.  Begin entering your formula. After the equals sign, start to
    type *Sum*. As you type, a drop-down suggestion list appears,
    showing all the DAX functions, beginning with the letters you type.
    Scroll down, if necessary, to select **SUM** from the list, and then
    press **Enter**.

![A screenshot of a computer Description automatically
generated](./media/media9/image6.png)

8.  An opening parenthesis appears, along with a drop-down suggestion
    list of the available columns you can pass to the SUM function.

9.  Expressions always appear between opening and closing parentheses.
    For this example, your expression contains a single argument to pass
    to the SUM function: the **Sales** column.

10. Begin typing ***Sheet 1***.

11. The column name preceded by the table name is called the fully
    qualified name of the column. Fully qualified column names make your
    formulas easier to read.

12. Select **Sheet 1\[Sales\]** from the list, and then enter a closing
    parenthesis.

![](./media/media9/image7.png)

![](./media/media9/image8.png)

**Tip -** Syntax errors are most often caused by a missing or misplaced
closing parenthesis.

13. The measure is created.

![](./media/media9/image9.png)

14. Now uncheck all the columns except **Country** and **Sum of Sales**

![A screenshot of a checklist Description automatically
generated](./media/media9/image10.png)

15. The chart now uses one measure that you created manually **Sum of
    Sales** and Country which Power BI summed automatically.

![](./media/media9/image11.png)

## Task 3 – Create a measure description

1.  In the existing model , we select manually created measure in the
    Data pane of Model view to see the measure properties.

2.  Select Model view from the left navigation pane

> ![A screenshot of a computer Description automatically
> generated](./media/media9/image12.png)

3.  Select **Model** tab and then manually created measure – **Sum of
    Sales.**

![A screenshot of a search box Description automatically
generated](./media/media9/image13.png)

4.  Select the **Create with Copilot** (preview) button under
    the **Description** textbox.

![](./media/media9/image14.png)

![A blue line with black text Description automatically
generated](./media/media9/image15.png)

5.  Review the measure description from Copilot, then select **Keep
    it**.

![](./media/media9/image16.png)

6.  Now the measure description is in the **Description** box. You can
    edit the description, if you need to.

![](./media/media9/image17.png)
