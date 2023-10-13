# TableOpsServer

TableOpsServer is an asynchronous C++ server designed for performing set operations on data tables. It provides efficient handling of operations such as set intersection and symmetric difference on two data tables, referred to as Table A and Table B.

## Features

- **Asynchronous Operations**: TableOpsServer utilizes asynchronous programming to handle multiple client connections concurrently, ensuring high performance and responsiveness.

- **Table Operations**: This server allows users to insert data into tables, truncate tables, and execute set operations on the data within Table A and Table B.

- **Insertion and Truncation**: You can insert data with specified IDs and names into the tables. Duplicate entries are gracefully handled with error messages. The server also supports truncating tables to clear their contents.

- **Set Operations**: TableOpsServer is capable of computing the intersection and symmetric difference of the data in Table A and Table B. The results are returned in a format that includes IDs and data from both tables.

## Getting Started

To get started with TableOpsServer, you need to compile the source code and run the server on your preferred system. The server listens on a specified port and awaits incoming connections. Clients can send commands to insert data into the tables, truncate tables, and request set operations.

## Usage

Here are some sample commands that can be sent to the server:

- **INSERT A 1 example_data**: Insert data with ID 1 into Table A.

- **TRUNCATE B**: Clear the contents of Table B.

- **INTERSECTION**: Compute the intersection of data in Table A and Table B.

- **SYMMETRIC_DIFFERENCE**: Compute the symmetric difference of data in Table A and Table B.

For a more detailed explanation of available commands and their usage, please refer to the project's documentation.

## Requirements

TableOpsServer is written in C++ and relies on the standard library for networking. You do not need any additional libraries or dependencies to run this server.

## License

This project is open-source and released under the MIT License. You are welcome to use, modify, and distribute it in your own projects.

## Contribution

We appreciate contributions from the community. If you would like to contribute, please check out our contribution guidelines.

## Feedback

Your feedback is valuable to us. If you have questions, suggestions, or issues to report, please open a GitHub issue or contact us.

