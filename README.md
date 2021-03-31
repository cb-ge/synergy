# synergy

The two synergy master files were created in March 2021 by cb-ge using R codes and source files based on Lützen’s R codes, which includes syntax that for some reason cannot be run in RStudio. 

Workflow to produce master files from scratch are: occ.hist.cleaning, [synjem agent], merger. The occ.hist.cleaning codes prepare occupational histories for merging to synjem, the [agent] codes (e.g. Pah_yyyymmdd.Rmd) match the occ histories to synjem and assign exposure, the merger codes combine files across exposures and create the two master files. If one were only interested in learning/rerunning/updating synjem assignment for a particular substance, then the [agent] file should be sufficient. 
