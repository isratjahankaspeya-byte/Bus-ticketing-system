# Bus Ticketing System

A simple Bus Ticketing System developed in C that allows users to book, view, search, and cancel bus tickets. Ticket information is stored in text files for basic record management.

## Features

* Book a bus ticket
* View all booked tickets
* Search tickets by passenger name
* Cancel tickets
* File-based data storage
* Simple menu-driven interface

## Project Files

```text
Bus-ticketing-system/
│
├── bus_ticketing_system.txt   # C source code
├── Bus_Ticketing_System.pdf   # Project documentation/report
└── README.md
```

### Runtime Generated Files

The following files are created automatically when the program runs:

```text
tickets.txt    # Stores ticket records
counter.txt    # Stores ticket counter information
```

## How to Run

1. Rename `bus_ticketing_system.txt` to `bus_ticketing_system.c`.

2. Compile the program:

```bash
gcc bus_ticketing_system.c -o bus_ticketing_system
```

3. Run the executable:

```bash
./bus_ticketing_system
```

## Available Operations

1. Book Ticket
2. View Tickets
3. Search Ticket
4. Cancel Ticket
5. Exit

## Current Limitations

* Bus names entered by users are not validated.
* Duplicate seat numbers can be booked.
* Invalid seat numbers are not checked.
* Data is stored in plain text files only.

## Future Improvements

* Bus name validation
* Seat availability checking
* Duplicate seat prevention
* Better error handling
* Admin panel
* Database integration
* Graphical User Interface (GUI)

## Documentation

Detailed project documentation is available in:

`Bus_Ticketing_System.pdf`

## Author

Israt Jahan Kaspeya

## License

This project is intended for educational and learning purposes.
