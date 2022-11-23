The goal of this assessment is for you to show us your analytics experience, focusing on data modeling, querying and obtaining insights.

## Case

When a customer is booking a flight on our website, we also offer him the opportunity to buy ancillary products like insurance, airport parking etc. with the flight. Our commercial department is interested to get more insights in the sales of our ancillary products.  

In order to draw insights for the commercial department, a fictitious dataset with order data is supplied which contains information about orders, the booked flights and complementary products in 2026. Each row in the dataset represents a flight booking. The columns present some information about the booking (date, flight information, etc.) and whether some specific ancillary products (products A,B,C, and D) were also bought by the customer (ProductXSold and ProductXAmount columns).
In case of questions on the dataset you can send an email to ds@travix.com

## Assessment

### Data Modeling

The structure of the data does not seem optimal. We would like to hear your recommendation on how to improve this structure. What entities do you recognize and how would you design tables for analytical purposes? What can you tell about the techniques you’ve used?

### Querying

Write some SQL queries to explore the dataset and generate preliminary insights from this (restructured) data. Presents your insights and informative visualizations about the data.

Our commercial department is mostly interested to look at the performance of our ancillary products, in relation to the characteristics of the booked flights. One of the interesting dimensions to analyse is the lead time of the flight. This is calculated as the difference between the date of placing the order and the departure time. 
Also they are specifically interested in an experiment (A/B test) they did in the NL Market for Product A. The "ExperimentVersion” column indicates which version (A or B) was shown to this website visitor.

The results can be provided for example in a jupyter notebook, or a PDF or presentation deck. 