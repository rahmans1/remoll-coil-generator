# remoll-coil-generator
Code for generating gdml file of spectrometer magnets.


1. python ucoilgen.py -l upstream.list -f upstreamToroid.gdml
2. Copy the generated file to remoll/geometry/upstream


1. python dcoilgen.py -l segmented.list -f hybridToroid.gdml
2. Copy the generated file to remoll/geometry/hybrid
