

# PyChain Ledger


This is a blockchain-based application with a user friendly interface using Streamlit, complete with ability to check validation of transactions, adjust block difficulty, select from the block history via drop-down menu, and view transaction history via user friendly dataframe. 

---

## Technologies

This prodject uses Python 3.7 with the following packages:
* ### **Streamlit** - A  is an open-source app framework that uses blockchain technology and machine learning
* ### **pandas** - A package of intuitive data analysis tools
* ### **hashlib** - A single interface for different hash algorithms 


---

## Installation Guide

First, install the following in the dev environment:
    
    pip install streamlit
    
    
Import the following libraries and extensions: :  
    
    import streamlit as st
    from dataclasses import dataclass
    from typing import Any, List
    import datetime as datetime
    import pandas as pd
    import hashlib
    
---

## Usage


* ### Adjust difficulty slide in left side bar
* ### Input sender and reciever data and click Add Block button
* ### Repeat to build up a history 
* ### Note updated history in dataframe below and drop down menu in left side bar


![SampleCode](https://github.com/nssensalo/Challenge_18/blob/main/Screenshot%20(182).png)


---

## Contributors

A.Nansamba Ssensalo
[LinkedIn](www.linkedin.com/in/a-nansamba-ssensalo)

---

## License

[![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt)
