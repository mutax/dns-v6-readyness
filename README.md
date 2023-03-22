# DNS IPv6-only readyness

This project will contain code, links to datasets and tools related to our paper

 **How Ready Is DNS for an IPv6-Only World?**

by 

  - Florian Streibelt (Max Planck Institute for Informatics),
  - Patrick Sattler (Technical University of Munich),
  - Franziska Lichtblau (Max Planck Institute for Informatics),
  - Carlos H. Gañán (Delft University of Technology),
  - Anja Feldmann (Max Planck Institute for Informatics),
  - Oliver Gasser (Max Planck Institute for Informatics),
  - Tobias Fiebig (Max Planck Institute for Informatics)

published at [PAM 2023](https://pam2023.networks.imdea.org)

The paper is available at 

- https://hdl.handle.net/21.11116/0000-000C-8817-1
- https://link.springer.com/chapter/10.1007/978-3-031-28486-1_22

Recordings of the presentation given at PAM will be linked here as soon as they are available.

# Contents of the repo

The repository will _soon_ contain the code used for our active measurements.
Due to unforeseen events, we are unable to provide the code at this point in time but will make
it available as soon as possible.

We also will publish the code of a commandline tool implementing a stripped down version of our methodology.
This allows checking for IPv6-only issues from any vantage point within e.g. an inernal network.
In contrast publicly available DNS and IPv6-checking services often are hosted on the public Internet.

# Datasets

All DNS requests made during our active measurement campaign are available as compressed json files.
We also plan to publish the collected data in the form of re-created zonefiles.

## Fileformat

The files are compressed using zstd. 

The first line is a comment containing a timestamp and linecount of the file.
Each line of the files is an individual json document, allowing filtering 
without need to deserialize the whole file at once.

The files can currently be found at: http://people.mpi-inf.mpg.de/~fstreibelt/dnsv6








