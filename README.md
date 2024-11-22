Example

Given the following JSON file example.json:
{
 "key1": 10,
 "key2": {
 "key3": "value3",
 "destination": "finalValue"
 },
 "key4": [1, 2, {"destination": "anotherValue"}]
}

Running the application with:
Java -jar DestinationHashGenerator.jar 12345 example.json

Output:
c719733517bfbdad3b8504213a7f3c96;5f4dcc3b
