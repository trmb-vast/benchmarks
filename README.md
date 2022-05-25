# benchmarks
This is the early days of a public repo of benchmark wrapper scripts
we plan to add some screenshots and other reference numbers, but for now this is a start.

trmb_vast_fio  is a wrapper for daemon-mode fio, and also includes some VAST-cluster performance polling.
trmb_fio_parse is a simple shell script which parses the output of the above, and creates an Excel / Google spreadsheet.
               the parser was written in a couple hours, and has some hardcoded things which depend on fio output from above script.
               In my copius spare time I'll make a cleanup pass on it...
               Todo:   charts, and also A/B comparison between runs. (vdbench compare would be awesome)
