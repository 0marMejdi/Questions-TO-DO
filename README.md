# Challenge-TO-DO

##  Challenge 1 -> Create a Local Storage with expiry such that it takes a Key, a value and Time such that the key will be available in local Storage till that specified time and after that it would be deleted.

Example: 

Setting key and value with time 1000 seconds 
window.localStorageWithExpiery.setItem("key1", "value", 1000);

Query within 1000 seconds 
window.localStorageWithExpiery.getItem("key1"); 
Answer -> "value"

Query after 1000 seconds 
window.localStorageWithExpiery.getItem("key1"); 
Answer -> "undefined"



# Send the Pull Request for this challenge test 
