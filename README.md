# Petfinder API token generator

This is a simple script to generate Petfinder API Authorization Tokens.  I wrote it to keep my sanity so I didn't have to keep copying and pasting the code to generate a new token.

## Dependencies
* Cat
* [jq](https://github.com/stedolan/jq)

## How to use
To use this script, simply clone this repo, and run the script while passing it your Api Key (Client ID), and your Secret.  Both of these should have been provided the

Pet Finder website after you request a key, to request a key visit [here](https://www.petfinder.com/developers/) to learn more about requesting an API key.

### Example
> ./gentoken -i YOUR API KEY HERE -s YOUR SECRET HERE

And thats it!  It doesn't matter what order you pass these in just make sure you pass the correct flag with the correct argument.

You should now see a prettified JSON printout with your token, this output is also written in `/home/$USER/Documents/token.json`.
    
   
