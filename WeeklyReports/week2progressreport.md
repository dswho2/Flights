# Week 2 Progress Report

## Progress
This week we have finished the data acquisition process and are working on filtering/cleaning and merging our datasets.

We have settled on using:
1. [USDOT DB1B Flight Market Dataset](https://www.transtats.bts.gov/Tables.asp?QO_VQ=EFI&QO_anzr=Nv4yv0r%FDb4vtv0%FDn0q%FDQr56v0n6v10%FDf748rB%FD%FLQOEO%FM&QO_fu146_anzr=b4vtv0%FDn0q%FDQr56v0n6v10%FDf748rB)
2. [USDOT Domestic Airline Consumer Airfare Report Dataset (Quarterly)](https://catalog.data.gov/dataset/domestic-airline-consumer-airfare-report-detailed-fare-information-for-selected-city-pair--118f7)

Additionally, we are developing our BFS traversal algorithm. So far we have decided to use nodes with adjancency lists of pointers to other airport nodes. 

### WW2 → WW3 Rollover Goals
1. We are still waiting on erikrj2 to finalize the Node class details; dsho2 is on standby to continue working on the BFS design integrated with our airport Node code.

1. erikrj2 to work on dataset filtering/cleaning and merging; will likely be done via scripting after re-exporting datasets. Afterwards, erikrj2 will adapt data to BFS node system to finish BFS stop-optimized flight portion of program.

## Issues
We are having trouble reaching one of our groupmates, who has not responded to email nor Discord messages.

## Plan for the Next Week
1. Finish Node class for BFS traversal

1. Finish BFS algorithm

1. Begin development of file I/O for storage of processed data.

1. Load price data into graph for preparation of A* heuristic with Euclidean distance for the cost metric.
