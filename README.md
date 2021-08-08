## penguins-testdata

This repository contains a bunch of NMR data which are used for tests and documentation of the Python 3 [penguins](https://github.com/yongrenjie/penguins) package.

They are kept in a separate repository because the files are big and I don't want to clutter the main repository with the actual files.

There is also a `nmrdata.zip` file which is provided as "sample data" for people to use when following the tutorial in the documentation.

In practice, the main repository contains this one as a submodule.

------------------

## Description of the data

| Expno | Description |
| ----- | ----------- |
| 1 | 1D proton |
| 2 | 2D CLIP-COSY |
| 3 | Raw data from 2D PSYCHE (technically from NOAH-3 MSP) |
| 4 | Processed data from expno 3 |
| 5 | 2D dataset that wasn't run |
| 6 | 2D HSQC with TD2 not equal to a multiple of 1024 |
| 7 | 1D proton with dtypa=2 |
| 8 | 2D HMBC with dtypa=2 (from NOAH-2 BS) |
| 9 | 2D HSQC with 25% NUS |
| 22 | NOAH-4 MSCN on gramicidin (used for the README) |
| 22001 | 15N HMQC from 22 |
| 22002 | 13C HSQC from 22 |
| 22003 | COSY from 22 |
| 22004 | NOESY from 22 |
