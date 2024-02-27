## TOPIC 6 - Data Pipeline in Practice

#### In preparation for this week:
* read/listen/watch as much as you can from the annotated materials below

---

For this week, we are going to focus on the ins and outs of how to build a data pipeline for data products in an organization. We will reference key terms from Week 1 such as __scalability__, __reproducibility__, and __reliability__. Our conversation will begin with how data is collected from various systems and products as raw data and how it makes its way into ready data to be used by data scientists and analysts. Let's begin this week by reading this [article](https://towardsdatascience.com/data-science-for-startups-tracking-data-4087b66952a1) that goes into great depth on how data is collected into managed services such as Pub/Sub or Kinesis.

In 2006, the phrase "Data is the new Oil" by [Clive Humby](https://ana.blogs.com/maestros/2006/11/data_is_the_new.html) became one of the most common phrase during that time. Why was that the case? The comparison came about because of the volume of raw data that was being tracked by various systems and because of the various forms of insights you can gather from the data. In recent times, people are being careful with the phrase as seen in this [article](https://towardsdatascience.com/data-is-not-the-new-oil-bdb31f61bc2d). Data as we all know must be used carefully and the reality in going from raw data to refined/processed data isn't such a smooth road like Oil.

After our informative discussion on Data Collection, we will discuss how we can from our raw data to processed data by performing some __data transformation__ and __data aggregation__. As Data Scientists, you will not be able to derive valuable insights from raw datasets or make predictions from raw datasets. With that being said, the raw data has to go through some phases before it makes its way to your models. The process of going through all those phases are considered as a data pipeline. This [article](https://towardsdatascience.com/data-science-for-startups-data-pipelines-786f6746a59a) goes very in-depth on how data pipelines are used in organizations. As a workshop class, we will have the opportunity to be hands on practice how we can extract data from a data storage, perform some basic data transformations and aggregations and the store the data back into a data store.

Read more about Data Formats, Data Aggregations, Data Storage:

* [__Data Formats__](http://bigdata.black/infrastructure/storage/choose-data-format/) Choosing the right data format
* [__Data Aggregations__](https://towardsdatascience.com/aggregation-and-grouping-66396f26dd95) Implementing Data Aggregations on your raw data
* [__Data Storage__](https://aws.amazon.com/blogs/startups/picking-the-right-data-store-for-your-workload/) What to think about when picking a data storage for your data
