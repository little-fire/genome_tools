# genome_tools
nyas - test genomics scripts

Example usage:

```
echo "name,count" >my_file.csv
for FASTA in data/*.fa.txt; do
  count =$( bash count_seq.sh $fasta )
  echo "$fasta,$count"
done >> my_file.csv
```
