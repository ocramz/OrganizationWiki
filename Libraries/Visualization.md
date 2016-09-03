# Visualization libraries #

Caution : some libraries might be bitrotten (as of Sept. 2016)

## Native libraries ##
* [Chart](http://hackage.haskell.org/package/Chart) is the most known haskell graphing library. It has various backends and support for IHaskell.
* [haskell-plot](http://hackage.haskell.org/package/haskell-plot-0.1.0.0): a library that tries to simplify the API of Chart.
* [barchart](http://hackage.haskell.org/package/barchart-0.1.1.1) a program that generates bar charts from CSV file

## Binding to other plotting libraries ##
### Bindings to [plot.ly](https://plot.ly/)
* [QuickPlot](https://hackage.haskell.org/package/QuickPlot-0.1.0.1). If you build it with Stack, be sure to use the `stack.yaml` in the github repo, otherwise the installation will fail.

### Bindings to [Google Charts](https://developers.google.com/chart/)
* [hs-gchart](http://hackage.haskell.org/package/hs-gchart)
* [GoogleChart](http://hackage.haskell.org/package/GoogleChart)

### Bindings to [d3js](https://d3js.org/) 
* [d3js](http://hackage.haskell.org/package/d3js): declarative visualization on a web browser with DSL approach.

### Bindings to [gnuplot](http://www.gnuplot.info/) 
* [gnuplot](http://hackage.haskell.org/package/gnuplot): 2D and 3D plots using gnuplot
