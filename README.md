# shellscript

## Create a shell script that automates system monitoring and log processing.
Requirements:

### Create a shell script named system_monitor.sh that:

Collects and displays current CPU usage, memory usage, and disk space
Identifies the top 5 processes consuming the most CPU and memory
Searches for ERROR and WARNING messages in a specified log file
Archives logs older than 7 days into a compressed format
Accepts command-line arguments to customize behavior (e.g., log file path, archive directory)


### The script should:

Include proper error handling
Be well-documented with comments
Work on a standard Linux/Unix environment
Output results in a structured, readable format

# Perl
## Create a Perl script for text processing and data extraction.

### Requirements:

Create a Perl script named log_analyzer.pl that:

Parses a complex log file with mixed format entries
Extracts relevant information using regular expressions
Generates a summary report of events, errors, and statistics
Identifies patterns or anomalies in the log data
Converts the extracted data to a structured format (JSON or XML)


### The script should:

Use efficient Perl idioms and best practices
Include proper error handling
Be configurable through command-line arguments
Process large files efficiently

# Java 
Objective: Implement a multi-threaded data processing application.
Requirements:

## Create a Java application that:

Reads data from a CSV file containing sample time-series data
Processes the data using multiple threads to calculate statistics (min, max, average, standard deviation)
Implements a producer-consumer pattern for efficient data processing
Writes the results to an output file
Provides progress updates during processing


## Your solution should:

Use proper Java concurrency mechanisms (ExecutorService, Future, etc.)
Handle exceptions appropriately
Be well-organized with appropriate class structure
Include JUnit tests for core functionality


## File structure:

Main class: DataProcessor.java
Other classes as needed
Test classes for unit testing
