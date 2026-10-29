# Periodic Table Database

A PostgreSQL database project for storing chemical element information.

## Usage

Run the element lookup script with an element name or atomic number:

    ./element.sh oxygen
    ./element.sh 8

## Database Tables

- elements: Element names, symbols, and atomic numbers.
- properties: Atomic masses, melting points, boiling points, and type references.
- types: Element classifications.
