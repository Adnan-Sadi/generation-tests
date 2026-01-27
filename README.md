# generation-tests
Testing different generation methods with the cloud GPU hosted LLM instance. 

* `test_structured.sh`: Uses Pydantic wrapper to enforce structured generation.
* `test_loose.sh`: Trusts the model and prompt to get the given structure. Should be faster...


### To run:
* SSH into one of our CPU instances
* Remove any existing copies of `test_structured.sh` or `test_loose.sh`
* Upload the modified version and run it
* The script cleans up after itself when done

