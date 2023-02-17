# mimalloc Evaluation

This is the repository for my 2023 summer research project 'Investigating mimalloc Allocator Inefficiencies as the Number of Threads Increases', supervised by Professor Steve Blackburn.

Contained in this repository are the configuration files and raw results files from the experiments that I performed using running scripts (https://github.com/anupli/running-ng). Additionally included are my final report and pdfs of the figures used in the report, all of which are graphical visualisations of the results of my experiments.

I worked with the MMTk framework (https://github.com/mmtk/mmtk-core), using the OpenJDK binding of MMTk (https://github.com/mmtk/mmtk-openjdk). Library versions of mimalloc (https://github.com/microsoft/mimalloc) were made available through FFI bindings from mimalloc-sys (https://github.com/gnzlbg/mimallocator/tree/master/mimalloc-sys).

In the process of the project, I made some minor changes to `mmtk-core`, which were included in a pull request (https://github.com/mmtk/mmtk-core/pull/747).