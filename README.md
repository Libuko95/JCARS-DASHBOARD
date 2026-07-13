# JCARS-DASHBOARD
Analysis of sales, customers and products

OBJECTIVE
To prepare clean, consistent, and analysis‑ready data for evaluating JCars Logistics’ performance across orders, customers, vehicles, and regions.

HOW TO IMPOERT DATA INTO AIVEN
Log in to your Aiven Console.

Select your PostgreSQL service (e.g., pg-2e7ff66a-jeddyondiso-7f28.b.aivencloud.com).

Download SSL Certificate

Go to Service Overview → Connection Information.

Download the SSL certificate (required for secure connections).

Connecting to DBeaver by going to new database connection then

Enter connection details:

Host: pg-2e7ff66a-jeddyondiso-7f28.b.aivencloud.com

Port: 28077

Database: defaultdb

User: your Aiven username

Password:  Aiven password

Create a schema Jcars then set the key path to jcars.
Right click on the schema to import data to dbeaver.

connect power bi to to the database by the following steps;
In power bi select get data, database, postgrsql then connect.
A window will pop up where the server inserted that is the host then full colon port pg-2e7ff66a-jeddyondiso-7f28.b.aivencloud.com:28077
Database defaultdb.

MEASURES AND CALCULATIONS CREATED

Total cars, total revenue,average ratings,calculating profit,total orders,corect delivery date,

VISUALS INCLUDED
Column charts,line charts, donut charts,tables,slicers,maps,treemaps, clustered column charts pie charst and donut charts.

KEY INSIGHTS
Corporate customers are the leading in sales.
Strong revenue growth in Q2.
Return rate increased in June

RECOMMENDATIONS
Segment customers and track satisfaction.
Align inventory and promotions with top‑selling models.
Improve logistics performance and reduce returns.
Reward top performers and provide training for reps with lower conversion rates.
Invest in underperforming regions with targeted campaigns, while reinforcing strongholds like Nairobi and Mombasa.
Increase stock and marketing for high‑demand models, phase out consistently low‑performing ones.
