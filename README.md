# Hello wolrd docker
This action prints "Hello world" or "Hello" + the name of person to greet

## Inputs

## `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

## `time`


#Example usage
uses: action/hello-world-docker-action@v1
with:
    who-to-greer: 'Mona to Octocat'
