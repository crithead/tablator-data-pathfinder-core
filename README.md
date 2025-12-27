# Pathfinder Core Tables

These tables are from the __Pathfinder Core Rulebook__ and are formatted for the
[tablator](https://github.com/crithead/tablator) table library.

## Tablator Examples

    tablator -d pathfinder-core -l
    tablator -d pathfinder-core -p spells-paladin-1
    tablator -d pathfinder-core -n 3 spells-wizard-1

Setting the enviromnt variable `TABLATOR_DATA_DIR` elimintaes the need to
include the DATA_DIR on the command line.

Print all tables

    find $TABLATOR_DATA_DIR -name \*.json -exec basename {} .json \; | xargs tablator -p

