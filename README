Title: Hadoop Examples
Author: Marek
Date: Marh 21, 2015
Keywords: java,hadoop

Compile using
% mvn install

Run your job using
%	hadoop jar ./target/wordcount.jar -r <count> -m <count> dataset1.txt $(date +%s)

To make this a little easier create a shell script called setmeup that will execute the command.

	#!/bin/bash
	#/usr/local/Cellar/hadoop/1.2.1/bin/hadoop jar ./target/bdp-1.0.jar 	dataSet1.txt $(date +%s)

After you create the script, do a chmod +x ./setmeup to make it executable. Then run  ./setmeup which should execute the job.

