# From the Deep

In this problem, you'll write freeform responses to the questions provided in the specification.

## Random Partitioning
Adopting this type of approach can lead to greater insight with large amounts
of data being collected. This approach is capable of handling large amounts
of data because of the data distribution to multiple locations making it more
scalable. However, one disadvantage of this approach is the overconsumption of
power due to the need to query multiple partitions simultaneously to retrieve
complete datasets.


## Partitioning by Hour
Partitioning by hour has a disadvantage because the data will not be evenly
distributed because most of the data collected will be within a specific time
frame and could lead to storage and processing imbalances. However, one
advantage to partitioning by hour is that the researcher will only need to query
some boats in order to collect the majority of the data, making it efficient
for smaller projects.


## Partitioning by Hash Value
A particular advantage of partitioning by hash value is the even distribution of
data so that no database is overwhelmed and supports storage and processing
loads. However, a disadvantage of partitioning by hash value would be the
complex queries when researchers are querying for data in a certain range, which
would require the need to run the query on all databases.
