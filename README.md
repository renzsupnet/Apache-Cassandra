<h2>Project: Data Modeling with Postgres</h2>
<br>
<h3>Problem Statement:</h3>
<br>
<p>A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analytics team is particularly interested in understanding what songs users are listening to. Currently, they don't have an easy way to query their data, which resides in a directory of JSON logs on user activity on the app, as well as a directory with JSON metadata on the songs in their app.
<br><br>
They'd like a data engineer to create a Postgres database with tables designed to optimize queries on song play analysis, and bring you on the project. Your role is to create a database schema and ETL pipeline for this analysis. You'll be able to test your database and ETL pipeline by running queries given to you by the analytics team from Sparkify and compare your results with their expected results.</p>
<br><br>
<h3>Technology Used:</h3>
<br>
<ul>
   <li><b>Python</b></li>
      <p>Python is a popular programming language. It was created by Guido van Rossum, and released in 1991. It is used for:</p>
          <ul> <li> web development (server-side),</li>
               <li> software development,</li>
               <li> mathematics,</li>
               <li> system scripting.</li>
          </ul>
      <p>(Retrieved from : <a href="https://www.python.org/">python.org</a>)</p>
    <br>
  <li><b>PostgreSQL</b></li>
      <p>PostgreSQL is a powerful, open source object-relational database system with over 30 years of active development 
         that has earned it a strong reputation for reliability, feature robustness, and performance.</p>
      <p>(Retrieved from : <a href="https://www.postgresql.org/">postgresql.org</a>)</p>
    <br>
  <li><b>Pandas</b></li>
      <p>pandas is a fast, powerful, flexible and easy to use open source data analysis and manipulation tool,
          built on top of the Python programming language.</p> 
      <p>(Retrieved from : <a href="https://pandas.pydata.org/">pydata.org</a>)</p>
</ul>  
<h3>Installation</h3>
<ul>
    <li>1. Establish a python environment or Jupyter Notebook
    <ul><li><a href="https://www.python.org/downloads/">python installation</a></li>
        <li><a href="https://jupyter.org/install">jupyter installation</a></li>
    </ul></li>
    <li>2. Make sure the following python libraries are available/installed: glob, psycopg2, numpy, and os</li>
    <li>3. Download Files </li>
    <li>4. Instantiate database by running create_tables first</li>
    <li>5. Run etl.py</li>
    <li>6. Run queries</li>
</ul>
<h3>Database Scheme</h3>
<p>As required by Sparkify, the focus of the database is faster and simpler queries of a large data set. Star schema satisfies this requirement and has been
   implemented as part of the solution in order to avoid complex JOIN queries.</p> 
<a href="https://imgur.com/a/4SnWLIl">STAR SCHEMA (1st image)</a>
<br>
<h3>ETL PROCESS</h3> 
<p>Data is stored in a dataframe ----> Data is extracted into lists ----> Lists are inserted into their respective tables ----> Process is repeated until all files are processed</p> 
<h3>QUERY SAMPLES</h3>
<a href="https://imgur.com/a/4SnWLIl">Terminal / Jupyter Notebook Outputs</a>
<br>
<br>
<br>