# ARPScan
...<i>by Jacob Collins</i>

<i>Now introducing:</i> <b>ARPScan</b>
This is a simple network mapper that uses the <b>A</b>ddress <b>R</b>esolution <b>P</b>rotocol to map out a network with a series of requests. This tool will provide you with a list of devices that return an ARP request, as well as their hardware addressed for your viewing pleasures...

<br />

### FUN FACT
If you were wondering why I made this tool, the answer is simple! <i>I couldn't get `netdiscover` to work!</i> Yes, thats right, it just wouldnt work. `nmap` (in my opinion) is too slow for a simple host scan, so I thought <b><i>HEY!</i></b> why not make my own.

<br />
<br />

## <b>WARNING:</b>
This tool is <i>very</i> noisy network wise, and can be seen and detected very easily. Infact, I dare you to run wireshark when you use this program, and see how it looks for yourself. I'm trying to figure out if there's a way to do this more subtly, but so far, to no prevail.
