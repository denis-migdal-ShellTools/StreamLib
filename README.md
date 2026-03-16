# StreamLib

Several Shell functions to manage streams and watch files

## Read

- `readline $OUTPUT [--p $PROMPT --i $DEFAULT]`
- `read_secret $OUTPUT [--p $PROMPT]`
- `readchar $OUTPUT [--p $PROMPT]`
- `read_args $OUTPUT [--p $PROMPT]`

## JSON

- `read_jsonline $VAR[...]`
- `json_extract $JSON $VAR[...]`

## Others

- `import $NAME`: import the functions
- `watchfiles $FILES[...]`: write a JSON entry upon each changes 
- `quote $STR` : escape $STR.

## Possible improvments

- more options for watchfiles (exclude/include)
- quote: enable to use it from input instead of args.
- json: from indexed/associated array.
