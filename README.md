# Hydrolix Data Science Examples

Examples for data science use cases with the [Hydrolix Spark Connector] (https://docs.hydrolix.io/docs/hydrolix-spark-connector)

## Video Piracy

The video piracy folder contains a sample python notebook that can be used as a
starting point for detecting piracy based on CDN log data. It relies on specific
column names that might need to be adapted based on the CDN table schema, including:

* `timestamp`: timestamp of the log line
* `client_ip`: ip address of the client
* `user_agent`: user agent of the client
* `cmcd_session_id`: CMCD session id
* `extension`: file extension for the requested object
* `bytes_out`: number of bytes requested, in kilobytes
* `cmcd_streaming_format`: CMCD streaming format
