# 12.1

● Explain the need of Flume


Flume lets Hadoop users ingest high-volume streaming data into HDFS for storage. Specifically, Flume allows users to:

1.Stream data:
  Ingest streaming data from multiple sources into Hadoop for storage and analysis
  
2.Insulate systems:
  Buffer storage platform from transient spikes, when the rate of incoming data exceeds the rate at which data can be written to the destination
  
3.Guarantee data delivery:
  Flume NG uses channel-based transactions to guarantee reliable message delivery. When a message moves from one agent to another, two transactions are started, one on the agent that delivers the event and the other on the agent that receives the event. This ensures guaranteed delivery semantics
  
4.Scale horizontally:
  To ingest new data streams and additional volume as needed
