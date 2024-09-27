## how to use this keyboard decoder


* you can use the **decode_keylogger.py** like this: 
````bash
python decode_keylogger.py input_file output_file keyboard_type

#input_file: it's your keyboard logs in binary form 
#output_file: it's the place where you want to save your decoded logs
#keyboard_type: choose between azerty or qwerty 

````

* you can **test** the **decode_keylogger.py** thanks the test file:

````bash
python decode_keylogger.py test decoded_test azerty
````
* you should identify towards the decoded logs this message: 
````bash
thiiiiiiiiiis ttesst is a successssssssssssssssss !!!!!!!!!!!!!^C
````
