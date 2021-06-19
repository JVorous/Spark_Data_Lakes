# Spark Data Lakes
<h1>Dependencies</h1>
<ul>
    <li>configparser</li>
    <li>pyspark.sql</li>
    <li>os</li>
    <li>datetime</li>
    <li>AWS EMR Spark cluster</li>
</ul>

<h1>Project</h1>
A music streaming startup, Sparkify, has grown their user base and song database even more and want to 
move their data warehouse to a data lake. Their data resides in S3, in a directory of JSON logs on user 
activity on the app, as well as a directory with JSON metadata on the songs in their app.

As their data engineer, you are tasked with building an ETL pipeline that extracts their data from S3, 
processes them using Spark, and loads the data back into S3 as a set of dimensional tables. This will allow 
their analytics team to continue finding insights in what songs their users are listening to.

You'll be able to test your database and ETL pipeline by running queries given to you by the analytics team 
from Sparkify and compare your results with their expected results.

<h1>Steps</h1>
<ol>
    <li>Configure dl.cfg file for your specific connection parameters</li>
        <ol>
            <li>NOTE: don't change the "INPUT_BUCKET" value</li>
        </ol>
    <li>Run etl.py -- Reads data from input bucket and outputs start-schema parquet files to the 
output bucket</li>
</ol> 

<h1>Data sets</h1>
<ul>
    <li>Song data: s3://udacity-dend/song_data</li>
    <li>Log data: s3://udacity-dend/log_data</li>
</ul>
