% A Change Data Capture Architecture with Debezium and Kafka
% *[Rodrigo C. Moraes](https://github.com/rodrigocmoraes)*
% February 13, 2021


# What is Debezium?

## 

!["dee-BEE-zee-uhm"](img/debezium.png)

##

Debezium is a **set of distributed services** that capture **row-level changes** in your 
databases so that your applications can see and respond to those changes. Debezium 
records in a transaction **log** all row-level changes committed to **each database table**.

<font size="5">Source:</font> <font size="5">[Debezium FAQ](https://debezium.io/documentation/faq/#what_is_debezium)</font>

::: notes

This is my note.

- It can contain Markdown

::: 

## What is Change Data Capture?

**C**hange **D**ata **C**apture, or CDC, is an older term for a **system that monitors and captures the 
changes in data so that other software can respond to those changes**. Data warehouses often 
had built-in CDC support, since data warehouses need to stay up-to-date as the data changed 
in the upstream OLTP databases.

<font size="5">Source:</font> <font size="5">[Debezium FAQ](https://debezium.io/documentation/faq/#what_is_change_data_capture)</font>

## What databases can Debezium monitor?
