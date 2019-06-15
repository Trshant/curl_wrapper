## 14JUN2019 ##
Added a method GET/POST/PUT/DELETE dropdown so we can change the method for curl 
Added a update commend button so we can see the updated command

## TODO ##
Add a panel to see the output
Make the UI more intuitive

## ADVANCED TODO ( wishlist ) ##
Add a SQLITE db so that we can save the command under separate collections! 

# -------------ORIGINAL RESCRIPTION from 5 years ago-----------#
# cURL Wrapper #

![image](doc/images/screen_shot.png)

## reason ##
for some reason people I work with don't know how to use curl on the command line, so I through this project together. Assumes you have a modern version of curl which supports `--data-urlencode`

## Usage ##
    >git clone https://github.com/jceaser/curl_wrapper.git
    >python curl.py
    
Any combo box values added in the script are stored in the local directory as files:

* ./url.values
* ./head.names
* ./head.values

## License ##
I (thomas cherry) wrote most of this in an afternoon. It would not have been possible without the help of others (as found by google). I place the code in the public domain since it's all from the public anyways. If you find this helpful and are so inclined, you can give me credit or simply link back to this project.
