# Storage in the Cloud

## Cloud Storage

1. Your Cloud Storage objects live in buckets. Which of these characteristics do you define on a per-bucket basis? Choose all that are correct (3 correct answers).

- [X] A globally-unique name
- [ ] An encryption-at-rest setting (on or off)
- [X] A geographic location
- [ ] A default file type for the objects in the bucket
- [X] A default storage class

2. True or false: Cloud Storage is well suited to providing the root file system of a Linux virtual machine.

- [ ] True
- [X] False

3. Why would a customer consider the Coldline storage class?

- [ ] To improve security.
- [ ] To save money on storing infrequently accessed data.
- [X] To save money on storing infrequently accessed data.
- [ ] TO use coldline Storage API.

## Cloud Bigtable

1. True or false: Each table in NoSQL databases such as Cloud Bigtable has a single schema that is enforced by the database engine itself.

- [ ] True
- [X] False

2. Some developers think of Cloud Bigtable as a persistent hashtable. What does that mean?

- [ ] Each item in the database consists of the exact same field, and can be looked up based on a variety of keys.
- [X] Each item in the database can be sparsely populated, and is looked up with a single key.

## Google Cloud SQL and Cloud Spanner

1. Which database service can scale to higher database sizes?

- [ ] Cloud SQL
- [X] Cloud Spanner

2. Which database service presents a MySQL or PostgreSQL interface to clients?

- [X] Cloud SQL
- [ ] Cloud Spanner

3. Which database service offers transactional consistency at global scale?

- [ ] Cloud SQL
- [X] Cloud Spanner

## Google Cloud Datastore

1. How are Cloud Datastore and Cloud Bigtable alike? Choose all that are correct (2 correct answers)

- [X] They are both NoSQL databases.
- [ ] The both have a free daily quota.
- [X] They are both highly scalable.
- [ ] They both offer SQL-like queries.

2. True or false: Cloud Datastore databases can span App Engine and Compute Engine applications.

- [X] True
- [ ] False

## Google Cloud Platform Storage Options

1. You are developing an application that transcodes large video files. Which storage option is the best choice for your application?

- [X] Cloud Storage
- [ ] Google Drive
- [ ] Cloud Spanner
- [ ] Cloud Datastore

2. You manufacture devices with sensors and need to stream huge amounts of data from these devices to a storage option in the cloud. Which Google Cloud Platform storage option is the best choice for your application?

- [ ] BigQuery
- [X] Cloud Bigtable
- [ ] Cloud Spanner
- [ ] Cloud Datastore

3. Which statement is true about objects in Cloud Storage?

- [X] They are immutable, and new versions oerwrite old unless you turn on versioning.
- [ ] They can be edited in place.
- [ ] The are immutable, and versioned by default.
- [ ] They are immutable unless you turn on versioning.

4. You are building a small application. If possible, you'd like this application's data storage to be at no additional charge. Which service has a free daily quota, separate from any free trials?

- [ ] Bigtable
- [ ] Cloud Spanner
- [ ] Cloud SQL
- [X] Cloud Datastore

5. How do the Nearline and Coldline storage classes differ from Multi-regional and Regional? Choose all that are correct (2 responses).

- [ ] Nearline and Coldline use a differently-architected API.
- [ ] Data in Nearline and Coldline is not retrievable immediatly.
- [X] Nearline and Coldline asses lower storage fees.
- [X] Nearline and Coldline assess aditional retrieval fees.
- [ ] Nearline and Coldline have lower durability.

6. Your application needs a relational database, and it expects to talk to MySQL. Which storage option is the best choice for your application?

- [ ] Cloud Spanner
- [ ] Cloud Storage
- [ ] Bigtable
- [X] Cloud SQL

7. Your application needs to store data with strong transactional consistency, and you want seamless scaling up. Which storage option is the best choice for your application?

- [ ] Cloud Storage
- [X] Cloud Spanner
- [ ] Cloud Datastore
- [ ] Cloud SQL

8. Which GCP storage service  is often the ingestion point for data being moved into the cloud, and is frequently the long-term storage location for data?

- [X] Cloud Storage
- [ ] Cloud Datastore
- [ ] Cloud Spanner
- [ ] Local SSD
