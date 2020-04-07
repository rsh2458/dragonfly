# CSV Files

These files come from ...  The CSV output from this is not great, and the lines are arbitarily split up.  The following code will maybe fix them.

```bash
 file=0-1.csv
 perl -i.bak -p -e '/[ \]]$/ && chomp' $file
```
