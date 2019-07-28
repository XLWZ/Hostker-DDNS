# Hostker-DDNS

Hostker/Zhujike DDNS script for asuswrt-merlin.

You'll need a Hostker API key and configure the script in the header.

The script depends on [JSON.sh](https://github.com/dominictarr/JSON.sh), and will download a copy into the current directory  if it doesn't exist. If your deploy won't have write access, download it and give it executable permissions in the same directory.

## Usage

Put `ddns-start` in `/jffs/scripts`

Remember

`chrom +x /jffs/scripts/ddns-start`

Then in router setting enable DDNS, choose Custom.
