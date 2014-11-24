Munin Plugins
=============
Plugins for Munin.

ffmap
-----
Load `nodes.json` from a ffmap aka a Freifunk Node Map and extract
number of nodes, active gateways, mesh connections and the like.

ffmap_nodes
-----
Load `node_load.json` from an `alfred-json -r 159 -f json` output and plot information about connected clients, loadavg, traffic sum, traffic throughput and uptime.

Prerequisistes
-----
  
    sudo apt-get installbuild-essentials
    cpan install JSON
    cpan install LWP::Simple

Install Munin Client and Server, for Munin Setup on Apache or nginx use Google

    sudo apt-get install munin munin-node
