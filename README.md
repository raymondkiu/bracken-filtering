# bracken-filtering
Filter Bracken outputs (metagenomics)
```
Usage: ./bracken_extract_data3.sh [-f | -n] -o <output_file> -i <input_file> [-a] [-b <percentage>]

Options:
  -f    Extract columns ending with '_frac' and multiply by 100 (4 decimal places)
  -n    Extract columns ending with '_num'
  -o    Output filename
  -i    Input filename
  -a    Show author name (Raymond Kiu)
  -b    Filter threshold (only for -f mode)

Example Usage:
  ./extract_columns.sh -f -o frac_filtered.tsv -i input.tsv -b 5 -a
  ./extract_columns.sh -n -o num_output.tsv -i input.tsv
```
