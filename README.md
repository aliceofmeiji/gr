# gr
simple ascii graphs for esc/pos printers

gr WIDTH MIN MAX \[CHAR\]

gr takes in numbers from stdin and plots them according to the arguments:

- WIDTH width of the graph in characters (amount of characters per line)
- MIN lowest value of the graph (anything below it will not be plotted)
- MAX maximum value of the graph (anything above it will not be plotted)
- CHAR optional character to be drawn instead of '|'
