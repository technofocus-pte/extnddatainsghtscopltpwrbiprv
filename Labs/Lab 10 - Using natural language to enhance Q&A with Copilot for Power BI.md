# Using natural language to enhance Q&A with Copilot for Power BI

## Exercise 1 - Use Power BI Q&A to explore your data and create visuals on a dashboard

### Task 1 – Import a Sales and Marketing Sample file.

1.  Launch the **Power BI Desktop** app on the Desktop

2.  Sign in if you are not signed in with the credentials provided you
    to execute the lab

3.  Select **Open**

![A screenshot of a computer Description automatically
generated](./media/media10/image1.png)

4.  Select **Browse this device and** navigate to **C:\LabFiles.**
    Select **Sales and Marketing Sample.pbix** file.

5.  The Power BI file will launch.

6.  Open a new page by selecting **+**(plus).

![](./media/media10/image2.png)

7.  Start on a blank report page and select the **Q&A visual** icon on
    the **Visualizations** \> **Build visual** pane.

![A screenshot of a computer Description automatically
generated](./media/media10/image3.png)

8.  The Q&A window is visible.

![](./media/media10/image4.png)

9.  To customize your visual, select a suggested question or enter text
    in the Q&A question field, where it says *Ask a question about your
    data –* Enter - **top geo states by sum of revenue**.

Power BI determines the appropriate visual type based on the selected
suggestion or entered text. In our example, Power BI determines that a
map visual is best suited to display the data.

![](./media/media10/image5.png)

10. You can also instruct Power BI to use a specific visual type by
    adding the type to the text you enter in the **Q&A question field**.
    For example, the data in our example isn't meaningful when presented
    on a scatter chart, but it's helpful when shown as a filled map.

11. Enter - **top geo states by sum of revenue** **filled map**

![](./media/media10/image6.png)

### Task 2 - Create a Q&A visual with a natural language query

1.  As you enter text, Power BI adds a red double underline to words it
    doesn't recognize. When possible, Power BI helps define unrecognized
    words. – **Enter revenue for VanA**

2.  The following example shows suggestions from Power BI for an
    unrecognized term. The two suggestions can satisfy our intended
    question.

![](./media/media10/image7.png)

3.  Let's choose the last suggestion in the list. Enter more text for
    the current question. Enter - **Total sum of revenue for Vanarsdel
    (product manufacturer)**. As you enter more text for the question,
    Power BI lets you know when it doesn't understand the question and
    tries to help. In this example, Power BI suggests a different way to
    word the question by using terminology from the semantic model. The
    suggested terms are underlined in blue.

![A screenshot of a computer Description automatically
generated](./media/media10/image8.png)

4.  With Power BI's help, we're able to ask a question with all
    recognizable terms. Power BI displays the results accordingly.

![A graph on a white background Description automatically
generated](./media/media10/image9.png)

5.  Instruct the Q&A visual to show the data in columns by adjusting
    your question. At the end of your current query, enter the text "as
    a column chart."

![A graph with blue lines Description automatically generated with
medium confidence](./media/media10/image10.png)

### Task 3 - Enhancing Q&A with Copilot for Power BI

1.  One a new page in the report, in the Q&A window. Enter – **Show
    available manufacturers by region** and run the query.

![](./media/media10/image11.png)

2.  The available word is not identified. Hence, we can assign synonym
    to **available manufacturers** to **Manufacturers**

3.  Select the gear icon on the Q&A window.

![A screenshot of a computer Description automatically
generated](./media/media10/image12.png)

4.  Select **Synonyms**.

![A screenshot of a computer screen Description automatically
generated](./media/media10/image13.png)

5.  Expand **Manufacturers.**

![](./media/media10/image14.png)

6.  **Add available manufacturers for manufacturers (First one).**

![A screenshot of a computer Description automatically
generated](./media/media10/image15.png)

![](./media/media10/image16.png)

7.  Now it recognises the word

![A screenshot of a computer Description automatically
generated](./media/media10/image17.png)

8.  If we want to refer to a name with other name, we can teach Q&A. If
    we want to teach **Region** as **Location**. Select the gear icon.

![A screenshot of a computer Description automatically
generated](./media/media10/image18.png)

9.  Select **Region** an alternative for **Location** and select
    **Save**

![A screenshot of a computer Description automatically
generated](./media/media10/image19.png)

10. The result is displayed

![](./media/media10/image20.png)
