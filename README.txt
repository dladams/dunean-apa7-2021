github:dladams/dunean-apa7-2021

To use package:

- Build and set up duneproc.
- Check out this packagepull in a local directory.
- Cd there and run and of the following:

Make dataset
> ./makeDataset RUN EVT1

DQM plots (display, metric vs.channel):
./doDqm RUN EVT

DQM2 plots (FEMB counts)
./doDqm2 RUN EVT1

Raw waveforms
./doWfRaw RUN EVT

Pedestal distributions
./doPedestalDist RUN EVT
