# <img src="https://pro32connect.ru/res/common/i/favicon-ts1ru1728292327.ico" width="50" height="50"> Pro32-parser

Pro32-parser is a python script that runs a REST API GET request on PRO32connect clients database using a custom API-KEY given for each of their customers.

To run the code you must first rename the file 
`config_clear.py` > `config.py`
and fill the `config.py` with your key

***Keep in mind that for now i dont have implemented a for cycle to extract a list of IDs from a GET/list request. I do it manually with EMEditor using a macro command***