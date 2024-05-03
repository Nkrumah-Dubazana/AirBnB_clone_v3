
```
# AirBnB Clone V3 - The Console

## Overview
The Console is the initial phase of the AirBnB Clone project at Holberton School, introducing fundamental concepts of higher-level programming. The project's ambition is to build a simple version of the AirBnB website, termed HBnB. This segment involves creating a command interpreter to manage AirBnB-like objects.

## Functionalities
- **Create**: Initiate a new object (e.g., a User or a Place).
- **Retrieve**: Fetch an object from various sources like files or databases.
- **Update**: Modify attributes of an object.
- **Destroy**: Remove an object.
- **Miscellaneous**: Perform operations like counting or computing statistics on objects.

## Contents
- [Environment](#environment)
- [Installation](#installation)
- [File Descriptions](#file-descriptions)
- [Usage](#usage)
- [Examples](#examples)
- [Bugs](#bugs)
- [Authors](#authors)
- [License](#license)

## Environment
Developed and tested within Ubuntu 14.04 LTS, utilizing Python 3.4.3.

## Installation
```bash
git clone "https://github.com/alexaorrico/AirBnB_clone.git"
cd AirBnB_clone
./console # For interactive mode
echo "<command>" | ./console.py # For non-interactive mode
```

## File Descriptions
- **[console.py](console.py)**: Entry point of the command interpreter.
- **`models/`**: Contains classes like `BaseModel`, `User`, `Place`, `State`, `City`, `Amenity`, and `Review`.
- **`models/engine`**: Includes the `FileStorage` class for JSON serialization and deserialization.

## Usage
The console supports various commands such as:
```bash
./console.py
(hbnb) help
(hbnb) quit
(hbnb) create BaseModel
(hbnb) show BaseModel <id>
(hbnb) destroy BaseModel <id>
(hbnb) all BaseModel
(hbnb) update BaseModel <id> <attribute name> "<attribute value>"
```

## Examples
```bash
./console.py
(hbnb) create BaseModel
(hbnb) all BaseModel
(hbnb) show BaseModel 1234-1234-1234
(hbnb) update BaseModel 1234-1234-1234 email "a@b.com"
(hbnb) destroy BaseModel 1234-1234-1234
(hbnb) quit
```

## Bugs
Currently, no known bugs.

## Authors
- Alexa Orrico - [Github](https://github.com/alexaorrico) / [Twitter](https://twitter.com/alexa_orrico)
- Jennifer Huang - [Github](https://github.com/jhuang10123) / [Twitter](https://twitter.com/earthtojhuang)
- Joann Vuong
- **Nkrumah Dubazana** - [Github](https://github.com/Nkrumah-Dubazana)

## License
Public Domain. No copyright protection.
```


