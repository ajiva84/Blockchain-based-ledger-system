# Blockchain Based Ledger System

------------------

<img src="https://github.com/ajiva84/Blockchain-based-ledger-system/blob/main/application.png" width="1000" height="500">


# Overview

A blockchain-based ledger system to illustrate and learn the records and stores transactions across in immutable blocks. It has a friendly web user interface. It allows the user to transfer money between senders and receivers and verifies the integrity of the data in the ledger. 



# Technologies

Python is the primary language used to code this application. Streamlit library is utilized to provide a web interface. Dataclass and Typing libraries are used to create dataclass and input manipulations. Finally, Hashlib is used to construct the SHA256 hash of the transaction and blocks to showcase the integrity of the data. 



This project leverages python 3.7 with the following packages:

* [Streamlit](https://docs.streamlit.io/library/get-started) - Streamlit turns data scripts into shareable web apps
* [DataClasses](https://docs.python.org/3/library/dataclasses.html) - It provides a decorator and functions for automatically adding generated special methods 
* [Typing](https://docs.python.org/3/library/typing.html) -  This module provides runtime support for type hints
* [Hashlib](https://docs.python.org/3/library/pathlib.html) - This module implements a common interface to many different secure hash and message digest algorithms (e.g., SHA256)


## Installation Guide


Before running the application first install the following dependencies.

```python
  pip install streamlit
  
```

## Usage

Use the following command to run the app

```git to the directory and type
 Streamlit run pychain.py
```

---
## Screenshots
Input fields and the block display
<img src="https://github.com/ajiva84/Blockchain-based-ledger-system/blob/main/Record-blocks.png" width="1000" height="500">



----
Transaction and block hashes with timestamp
<img src="https://github.com/ajiva84/Blockchain-based-ledger-system/blob/main/Transaction-hashesh-timestamp.png" width="1000" height="200">



----
Difficulty adjustor and block inspector

<img src="https://github.com/ajiva84/Blockchain-based-ledger-system/blob/main/Block-inspector-difficulty.png">



----

## Contributors

Azam Jiva

---

## License

MIT
