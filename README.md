# Petfinder API token generator

This is a simple script to generate Petfinder API Authorization Tokens.  I wrote it to keep my sanity so I didn't have to keep copying and pasting the code to generate a new token.

## Dependencies
* cat
* [jq](https://github.com/stedolan/jq) (JSON Pretty Print)

## How to use
* Run the installer `sudo ./install`
* Try generating a key `gentoken -i [YOUR API KEY] -s [YOUR SECRET]` or try `gentoken -h` to see help
* Done!

You have to request and API key and Secret from Pet Finder.  To request a key visit [here](https://www.petfinder.com/developers/) to learn more about requesting an API key.  An API key and secret are required for this script to work, and for you to have access to the Perfinder api.

### Example
> ./gentoken -i YOUR API KEY HERE -s YOUR SECRET HERE

And thats it!  It doesn't matter what order you pass these in just make sure you pass the correct flag with the correct argument.

You should now see a prettified JSON printout with your token, this output is also written in `/home/$USER/Documents/token.json`.
    
   
