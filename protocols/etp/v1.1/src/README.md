The src directory contains both the original avro schemas for ETP (in the Schemas directory) and generated proxy class implementations for common languages and development platforms. Some things to keep in mind:

1. These generated implementations are very minimalist, just enough to serialize and de-serialize the messages.
2. Each of the folders contains its own README with further information on compiling and using the classes. In some cases, there will be a secondary distribution method, such as NuGet or npm, which can be used to directly install the compiled classes as a package for your development environment. This is also documented in the README.
3. There is a separate git repository for more complete sample implementations of ETP clients and servers, based on these classes. It is located at [https://bitbucket.org/energistics/etpsamples](https://bitbucket.org/energistics/etpsamples).
4. These are all works-in-progress. For users of the community technology preview (CTP), check back often at the git repository for updates.

Please forward questions, bug reports and suggestions to the [ETP Development Team](mailto:etpteam@list.energistics.org)