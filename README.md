# SetOperationServer

SetOperationServer is an asynchronous C++ server that enables efficient set operations on data tables. This server is designed to perform operations such as set intersection and symmetric difference on two data tables, referred to as Table A and Table B.

## Features

- **Asynchronous Operations**: SetOperationServer leverages the power of asynchronous programming to efficiently handle multiple client connections concurrently.

- **Table Operations**: The server allows you to insert data into tables, truncate tables, and perform set operations on the data contained within Table A and Table B.

- **Insertion and Truncation**: Users can insert data into the tables with specified IDs and names. Duplicate entries are handled gracefully with error messages. The server also supports truncating tables to clear their contents.

- **Set Operations**: The server is capable of computing the intersection and symmetric difference of the data in Table A and Table B. The results are returned to clients in a format that includes IDs and data from both tables.

## Getting Started

To get started with SetOperationServer, you need to compile the source code and run the server on your preferred system. The server listens on a specified port and awaits incoming connections. Clients can send commands to insert data into the tables, truncate tables, and request set operations.

## Usage

Here are some sample commands that can be sent to the server:

- **INSERT A 1 example_data**: Insert data with ID 1 into Table A.

- **TRUNCATE B**: Clear the contents of Table B.

- **INTERSECTION**: Compute the intersection of data in Table A and Table B.

- **SYMMETRIC_DIFFERENCE**: Compute the symmetric difference of data in Table A and Table B.

For more details on available commands and their usage, please refer to the project's documentation.

## Requirements

SetOperationServer is written in C++ and relies on the standard library for networking. You do not need any additional libraries or dependencies.

## License

This project is open-source and released under the MIT License. Feel free to use, modify, and distribute it in your own projects.

## Contribution

We welcome contributions from the community. If you'd like to contribute, please check out our contribution guidelines.

## Feedback

We value your feedback. If you have any questions, suggestions, or issues to report, please open a GitHub issue or contact us.
