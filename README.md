# pwospf-dissector-wireshark
wireshark dissector for pwospf packets

This repository contains NetFPGA wireshark dissector from https://github.com/NetFPGA/netfpga for pwospf packets.

See LICENSE file for information about NetFPGA's license agreement.

For more information about pwospf packets, see http://yuba.stanford.edu/cs344/admin/pwospf/.

The following packages are required: libglib2.0-dev and libwireshark-dev

tshark: `tshark -V -r "foo.pcap" frame.number==1`

To avoid compilation, just copy 'packet-pwospf.so' file to your machine (/home/user/.wireshark/plugins).
