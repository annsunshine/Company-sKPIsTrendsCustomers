# Power BI Project
I created this project to enable the managers to track KPIs, compare global performance, analyze trends and identify high-value customers in a quick and effective way.
```power BI
Data is divided into four main sheets;  Dashboard, Map, Product details and Customer details. Thanks to that the managers have bigger clarity of data.
I started from adding necessary tables to the project using Get data option and modifying them for a work purpose. 
```
![image](https://github.com/user-attachments/assets/2aa24599-bc14-4798-be9c-f241de5deda6)
```power BI
The next step was to create a model so connect tables via relationships based on a common field (Product Key), which would help analyze data then.
```
![image](https://github.com/user-attachments/assets/8e1968fc-450d-4e22-a4c2-b3602ccf735f)
```power BI
Later, I moved on to DAX section and created a special new table, directly inside the project, and called it a Measure table. I also used here explicit measures so wrote DAX formula and defined a new measures. It enabled aggregation so generation of a new calculated values.  Thanks to that I could analyze relational data models.
```
![image](https://github.com/user-attachments/assets/ef1aa51b-41e1-460a-af76-8f9e0e9705bb)
```power BI
In the first sheet, I made visualization of below. I will divide it into the pieces and describe one by one.
```
![image](https://github.com/user-attachments/assets/98eea8a7-7eb2-4ebf-8d53-721ff4856d6d)
```power BI
I started from adding the brand so Adventure works rectangle on the left and Revenue, Profit, Orders, Return rate, using a Card option, on the top.
```
![image](https://github.com/user-attachments/assets/e0e21817-6706-49c9-a504-56c71dadfb8d)
```power BI
Then, I decided to check how orders by category look like. I chose Clustered bar chart here.
```
![image](https://github.com/user-attachments/assets/114978c7-104d-4e12-b895-acb57c69c40c) 
```power BI
Next, I created a diagram, using a Line chart, and added tooltips, trend, anomalies. I wanted to check how the revevue looks like in the beginning of each month and how it is changing.
```
![image](https://github.com/user-attachments/assets/027fb1e9-32e5-42a1-a4eb-10f8162b2134) 
```power BI
I also built Matrix to check Orders, Revenue, Return rate for Top 10 products (I set it thanks to Filter option Top N). Additionally, in Cell elements, for Orders I clicked Data bar, while for Return rate, Background colour.
```
![image](https://github.com/user-attachments/assets/30aae11f-26a7-4b1d-8223-40605826abb4) 
```power BI
What’s more, I chose Drillthrough Page type for Product detail sheet, in Page information. Due to that after clicking one of the Top 10 products on the Dashboard, we are moved to Product details sheet, where all necessary pieces of information regarding selected product are displayed.
```
![image](https://github.com/user-attachments/assets/ad4b711d-99d2-4fe7-ba63-05ff5911b579)
![image](https://github.com/user-attachments/assets/1e531b93-64b6-44d5-9cf5-66f3d7923ff8)
```power BI
Furthermore, Card, Clustered bar chart, Line chart, Matrix are connected to each other and provide data connected to the product or time that was chosen by me. Please see below.
```
![image](https://github.com/user-attachments/assets/c099a5fd-e54d-4b7c-ab6b-0ccff40f8bfd)
![image](https://github.com/user-attachments/assets/dbbe9006-fecd-414b-8552-2d587cf081dd)
![image](https://github.com/user-attachments/assets/a6ad20ae-4169-41be-bdea-9cf6427475a2)
```power BI
Moreover, I used two Cards to create the most ordered and returned product type. Here again Filter type Top N was useful.
```
![image](https://github.com/user-attachments/assets/bf9799f5-08b9-4f29-9777-ad64c186b7e2)
```power BI
The last but not least items, which I decided to add are Monthly revenue, orders and returns. I used here KPI option.
```
![image](https://github.com/user-attachments/assets/ca8b7ec1-e0a3-4076-8c1c-89ee609dbb1b)
```power BI
Let’s move on to the next sheet, Map one. I added Map and Slicer, so the managers can check orders by continent. Additionally, I managed roles so assigned particular people to see only one continent.
```
![image](https://github.com/user-attachments/assets/910cb6f6-863f-4ec9-a7be-25214dfccb3b)
```power BI
Now it is time for Product detail’s sheet. Firstly, I added a new Card and modified filters, so after selecting a product from Top 10 ones, it will appear on the Card as well.
```
![image](https://github.com/user-attachments/assets/a12fd6c9-a19f-45b1-bc07-7d86362c2bcc)
```power BI
Then, I created three Gauge diagrams. Here I wanted to check how Total orders look like in a comparison to Order target so was is exceeded or not. The same with revenue and profit.
```
![image](https://github.com/user-attachments/assets/b9b47d06-648f-4127-908e-364e0387c7f4)
```power BI
Next, I added a Line chart to present how total profit and adjusted profit are changing in the beginning of each week, month and year. I used a Date hierarchy option to enable the managers check dates in which they are interested in effectively and quickly.
```
![image](https://github.com/user-attachments/assets/9c0ee6e9-d0cc-4d0f-94c5-e65539fb6b85)
```power BI
What’s more, I created Slicer. Thanks to it, the manager may scroll on any price adjustment them is interested in and data will be mirrored on the Line chart. However, to make it work, I had to add a new numeric parameter first and then add a new measure called Adjusted profit.
```
![image](https://github.com/user-attachments/assets/d44315e8-7282-41e4-9a67-dfe3fdb3ca87)
```power BI
Another step was the creation of Area chart that would show selected Top 10 product’ Orders, Profit, Returns, Revenue and Return rate in a weekly, monthly and yearly period of time. Here Date hierarchy was used as well. I decided to build another slicer which could help reflect on the chart only data that managers would like to check quickly. To achieve it, I created a new field parameter called Product metric selection.
```
![image](https://github.com/user-attachments/assets/da8c87a7-5da5-4c42-81f1-168cbcff54dc)
![image](https://github.com/user-attachments/assets/5e0d1250-6075-4d18-89e5-810547c3c54b)
```power BI
The last element on this sheet is a Text box. Thanks to that after selecting particular Top 10 product, in the text box appear name of the product, its Orders, period of time in which the trend is visible on the Area chart and the percentage of Orders’ increase.
```
![image](https://github.com/user-attachments/assets/2e8fada7-235d-4a3b-b890-4b33bead4c42)
```power BI
In the Customer detail’s sheet I started from adding two Cards which would reflect Unique customers and Revenue per customer.
```
![image](https://github.com/user-attachments/assets/e2258816-1a33-489b-a00d-e0d2db3a4819)
```power BI
Secondly, I created a Line chart which aim was to illustrate Total customers and Revenue per customer, using Date hierarchy (start of week, month, year).  I also added Slicer so the diagram might show either Total customers or Revenue per customer outcome. To achieve that I created a new field parameter called Customer metric selection and included there Total customers and Average revenue per customer.
```
![image](https://github.com/user-attachments/assets/e9381b22-0724-4a0d-9c95-a9dbc9911c9a)
```power BI
Then, I created two Donut charts since I wanted to illustrate Orders by income level and Orders by occupation. It is possible to click on any Income level or Occupation type to know how Orders and Revenue look like for that group.
```
![image](https://github.com/user-attachments/assets/b7c774f9-a11e-4d22-8b07-c7eab9a51b33)
```power BI
Moreover, I decided to introduce Top 100 customers, when it comes to the quantity of orders and the revenue. I used here a Table option and added Data bars plus Background colour. There is also opportunity to click on one of the clients, to quickly find out how the revenue and orders look like for them.
```
![image](https://github.com/user-attachments/assets/39a89758-3baf-42a4-8fc7-b54a951360d5)
```power BI
Moreover, I created three Cards, which show Top customer by revenue, them order’s quantity and revenue.
```
![image](https://github.com/user-attachments/assets/3c3dec3d-4358-4071-9527-51a9b4408296)
```power BI
Furthermore, I added free text and gave there information about the customer who drove the highest revenue and provided there the number. In addition, I added there a sign which after clicking reflect the revenue on the Line chart. I used here Bookmark option and turned on Action in Format button, to let it work properly.
```
![image](https://github.com/user-attachments/assets/fc3ba06d-7079-4886-92ef-a2ad3936f6db)
![image](https://github.com/user-attachments/assets/e20b703f-6484-4ba4-8b38-62be7feeb093)
```power BI
The last but not least visualization that I chose, was a Slicer. After changing the year, other visual tools like Donut chart, Line chart, Cards are reflecting the latest numbers.
```
![image](https://github.com/user-attachments/assets/a5912b02-c27f-43f9-871f-9bf0be14162b)
```power BI
I also used Category tooltip to illustrate total revenue, profit, return, orders and return rate by category, when we “touch” particular category using a mouse.
```
![image](https://github.com/user-attachments/assets/0c624ae3-27df-4e4c-8ec7-689293e47d61)
```power BI
Finally, I decided to add signs, which would enable moving between sheets and filter/filter out some options. Firstly, I added all necessary signs and updated Icon and Action options. Then, I created already mentioned by me Bookmarks.
```
![foto_powerBI](https://github.com/user-attachments/assets/3da35df4-6571-42ae-bbb3-8e2f149a99b7)
```power BI
At the end, I decided to use some AI tools like Decompensation tree, Key influencers, Visual calculations, to quickly check some correlations or numbers. The outcomes are visible in a separate sheets.
```
![image](https://github.com/user-attachments/assets/ffb3356e-37db-4b3f-a918-0dc532be8083)
![image](https://github.com/user-attachments/assets/45734184-37c8-4850-a8e9-9d2fc8448f3e)
![image](https://github.com/user-attachments/assets/dbc47025-1817-4ebb-ace3-19267666a67a)


    


























