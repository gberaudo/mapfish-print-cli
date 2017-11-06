# mapfish-print-cli
A small tool to help debug a mapfish print v3 specification

## Get the print URL
Trigger a print from your browser and `copy as curl` the print request.

## Get the specification printed
Paste the curl command and change `curl` by this program.
The resulting pdf will be stored in `last_print.pdf`.

## Tricks
You can replace `--data-binary $'{...}'` with `--data-binary $'@a_filename_with_the_spec.json'` Then you can change that file and quickly see the result.
