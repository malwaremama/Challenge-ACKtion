# Challenge-ACKtion Skillet

#### Purpose of this Skillet:
This skillet will make the firewall aware of the Challenge-ACK mechanism allowing it to work unhindered. This is to be used in a specific use case where a server is configured to mitigate "Blind Reset Attack Using SYN Bit" and sends a Challenge-ACK. The firewall does not understand this mechanism by default.

Detailed information on this configuration can be found [HERE](https://knowledgebase.paloaltonetworks.com/KCSArticleDetail?id=kA10g000000boBJCAY)

#### Walkthrough:
Import this into Panhandler and you just SEND IT! Panhandler will push this configuration to the specified host(s).

### Support Policy
The code and templates in the repo are released under an as-is, best effort,
support policy. These scripts should be seen as community supported and
Palo Alto Networks will contribute our expertise as and when possible.
We do not provide technical support or help in using or troubleshooting the
components of the project through our normal support options such as
Palo Alto Networks support teams, or ASC (Authorized Support Centers)
partners and backline support options. The underlying product used
(the VM-Series firewall) by the scripts or templates are still supported,
but the support is only for the product functionality and not for help in
deploying or using the template or script itself. Unless explicitly tagged,
all projects or work posted in our GitHub repository
(at https://github.com/PaloAltoNetworks) or sites other than our official
Downloads page on https://support.paloaltonetworks.com are provided under
the best effort policy.
