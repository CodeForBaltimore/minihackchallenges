# Main Challenge

Add functionality to a minimal server, set up in CH1, to add a route that accepts a post request. The post should be a json object with the structure of:

```
{
  word:valueString
}


```

The function should test that the object is of the correct format then determine if the valuestring passed in is a palindrome (a word, phrase, or sequence that reads the same backward as forward, e.g., madam or nurses run). The response should be of the format:

'''
{
  word:valueString,
  palindrome:[true|false]

}

'''




### Reccomend using:
* Node.js https://nodejs.org/en/
* Express https://expressjs.com/

### References
* http://www.codingdefined.com/2016/06/how-to-parse-json-in-nodejs.html



# Additional challenge:
write and additional route and function that determines if a number is a prime, even, odd, integer, etc based on a passed iin parameter like:

'''
{
  number:value,
  test:[prime|odd|even|integer|<other>]
}

'''

# Submission for review/feedback

Create a subfolder in this directory named with your github name. Place all relevant code needed in the folder and submit a pull request to this project's submissions branch.
