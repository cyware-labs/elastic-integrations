# Intel Exchange

The Intel Exchange integration allows you to monitor indicator. Intel Exchange is an any-to-any threat intelligence platform (TIP) that is built as a unique solution for the collection, processing, and dissemination of threat intelligence data in various formats. Intel Exchange allows you to receive and share threat intelligence in the form of human and machine-readable packages. By utilizing the Structured Threat Information eXpression (STIX) format and the Trusted Automated Exchange of Intelligence Information (TAXII) mechanism, Intel Exchange achieves threat data enrichment and threat intelligence exchange.

Use the Intel Exchange integration to fetch intel exchange data to elastic. Then visualize that data in Kibana, create alerts to notify you if something goes wrong, and reference indicator when troubleshooting an issue.

## Data streams

The Intel Exchange integration collects one type of data streams: -->
- **`indicator`** Indicators retrieved from the Intel Exchange API's save result set endpoint.


## Requirements
You need Elasticsearch for storing and searching your data and Kibana for visualizing and managing it.
You can use our hosted Elasticsearch Service on Elastic Cloud, which is recommended, or self-manage the Elastic Stack on your own hardware.
You need valid API credentials for intel exchange.
Make sure you have save result set rule is created.

## Setup

<!-- Any prerequisite instructions -->

For step-by-step instructions on how to set up an integration, see the
[Getting started](https://www.elastic.co/guide/en/welcome-to-elastic/current/getting-started-observability.html) guide.

<!-- Additional set up instructions -->

<!-- If applicable -->
<!-- ## Logs reference -->

<!-- Repeat for each data stream of the current type -->
<!-- ### {Data stream name}

The `{data stream name}` data stream provides events from {source} of the following types: {list types}. -->

<!-- Optional -->
<!-- #### Example

An example event for `{data stream name}` looks as following:

{code block with example} -->

<!-- #### Exported fields

{insert table} -->

<!-- If applicable -->
<!-- ## Metrics reference -->

<!-- Repeat for each data stream of the current type -->
<!-- ### {Data stream name}

The `{data stream name}` data stream provides events from {source} of the following types: {list types}. -->

<!-- Optional -->
<!-- #### Example

An example event for `{data stream name}` looks as following:

{code block with example} -->

<!-- #### Exported fields

{insert table} -->
