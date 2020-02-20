# HandheldGammaRayPlotter
Personal edit to Zane Jobe's HandheldGammaRayPlotter
https://github.com/zanejobe/HandheldGammaRayPlotter

Notes:
1. All files should be saved in your Jupyter Notebook Directory
2. The CSV must be formatted just like mine.
3. Edit the HandheldGammaRayPlotter.ipynb file datapath and filename to match your csv perfectly.
4. In Jupyter, run each cell individually in order ('Cell - Run All' tends to skip some cells).

Known Errors:
1. After running the cell that starts with,
plt.plot(df.Kprc, df.id, label='K')
plt.plot(df.Uppm, df.id, label='U')...
I get:
KeyError					Traceback (most recent call last)
.
.
and
.
.
KeyError: 0

Not sure what impact these make - it seems like all the plots look fine. 

2. The cell after "Export to LAS (to be done later)" currently produces two blank plots.