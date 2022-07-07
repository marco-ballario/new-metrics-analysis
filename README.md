# metrics-analysis

## Usage

To generate json data files:
```
./produce-data.sh
```
To generate static analysis graphs:
```
python3 static-analysis.py
```

## Graphs

### Weighted Methods per Class (WMC)
Sum, minimum, maximum and average over a set of repository files.
<div align="center"><img src="./graphs/static-analysis/wmc-static-analysis.png" width="100%"></div>

### Magnitude (ABC)
Sum, minimum, maximum and average over a set of repository files.
<div align="center"><img src="./graphs/static-analysis/abc-static-analysis.png" width="100%"></div>

### Number of Public Methods (NPM)
Sum, minimum, maximum and average over a set of repository files.
<div align="center"><img src="./graphs/static-analysis/npm-static-analysis.png" width="100%"></div>

### Number of Public Attributes (NPA)
Sum, minimum, maximum and average over a set of repository files.
<div align="center"><img src="./graphs/static-analysis/npa-static-analysis.png" width="100%"></div>

### Size metrics comparison
Compare ABC magnitude, Halstead estimated program length, PLOC and Cyclomatic Complexity metrics for a set of repositories.
<div align="center"><img src="./graphs/static-analysis/size-metrics-comparison.png" width="100%"></div>
