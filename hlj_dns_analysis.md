###HLJ_DNS analysis
----------------

#####File contains
* runDns.sh
* dnsAnalysis
* runDay.sh


the `runDns.sh` is a crontable script,it can deal the data file that created in current hour. 

The `dnsAnalysis.scala` is the main program,it's a spark-script.

The `runDay.sh` is copyed from `runDns.sh`, but some place is not the same. This shell's job is to check the history data which not be analysised in time.


