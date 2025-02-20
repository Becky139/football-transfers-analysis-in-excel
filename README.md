PROJECT TITLE: FOOTBALL TRANSFERS ANALYSIS IN EXCEL 

Case Description: This Football Transfers Analysis in Excel project involves extensive data analysis of the intricacies and economic patterns within international football (‘soccer’ in the US) transfers. It delves into the movement of players from one association to another, offering an in-depth overview of the economics of international football.

Using a robust football dataset spanning two seasons (2021/2022 and 2022/2023), the analysis involves performing several key tasks in Excel—including data preprocessing and manipulation, filtering, working with Excel functions proficiently, and data visualization.

The Tasks invlove mapping transfers to and from countries across different associations, create summary tables to illustrate these transfers, compute net transfer movements, and obtain the total dollar amounts for the respective transactions.

This Excel project offers a unique opportunity to blend the passion for football with the excitement of data-driven insights, fostering a deeper understanding of the global football economy. Whether you're a football enthusiast, a data analysis student/enthusiast, or both, this Excel project promises intriguing findings and a new perspective on this captivating game. 

Instructions:
1. Database Review and Cleaning
2. Analyze the Aggregate Number of European Transfers
3. Analyze European Transfers by Country
4. Visualize Transfer Fees of Top 5 European Countries

1. Task 1: Database Review and Cleaning
Steps taken: 
> Splitted the data in the Countries sheet using Excel’s Text-to-Columns tool. Chose the Delimited file type and select 'comma' as the delimiter.
> Next, cleaned up the continent names in the list by removing any extra spaces. Started by making a copy of the list and then removing any duplicate values.
> Used Excel's Find and Replace tool to remove spaces at the start of every continent name.
> Switched to the Database sheet. Appllied a filter at the top of the table and open the filter for the Season column. Looked for entries that read 2022/2028 and replaced 2028 with 2023 using Find and Replace.
> NOTE: Selected the Season column before using Find and Replace. If you don't specify a range, Excel will make changes throughout the entire sheet, which could result in unintended changes.
> Finally, filled in the Continent columns in the Database sheet. You can use Excel’s VLOOKUP or XLOOKUP function to do this.

2. Task 2: Analyze the Aggregate Number of European Transfers
> Created transfer table and populated it using Excel’s SUMIFS function to add data based on multiple criteria. The criteria included the following:
    -The season (2021/2022 and 2022/2023)
    -The continent (Europe)
> When filling in the 'Transfers outgoing' row, I adjusted the database column to correspond with outgoing transfers and placed a minus sign in front of the SUMIFS function. This is to automatically convert outgoing transfers into negative numbers, making it easier to calculate the net movement of players.

3. Analyze European Transfers by Country
> Constructed a more comprehensive table to illustrate the quantity and the financial worth of player transfers in and out of Europe and used Excel’s SUMIFS function to fill it in.
> Included a minus sign for outgoing transfers, indicating that these transfers reduce the net inflow of players to a particular country and adjusted the column to be summed accordingly when figuring out the monetary value.
> Once calculated all the 2021/2022 season figures, I applied the exact formulas for the 2022/2023 season. 

4. Visualize Transfer Fees of Top 5 European Countries
> In the European Transfers by Country sheet, used the RANK function to identify the five countries with the most significant incoming transfer values.
> Apply the RANK formula to all cells, and found top spenders: England, Italy, France, Germany, and Spain
> Created a new sheet named Visualization Top 5 Countries. Filled in the table using Excel formulas. To get the number of incoming transfers for each country, used SUMIF function. To calculate the average transfer fee, divide dthe total value of incoming transfers by the number of transfers.
> Visualized the Data.
