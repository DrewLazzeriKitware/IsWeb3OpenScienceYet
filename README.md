# Is Web3 Open Science Yet?
This repo aspires to track the progress of the Web3 community as it utilizes p2p networks, incentive engineering, and p2p networks to solve problems in Open Science. Inspired by https://www.arewewebyet.org/.

This is work in progress and we need your contributions! Open an issue to start a conversation about a problem, a project, or a way forward. 

The obstacles to Open Science listed below are tagged with these status emojis:

🔧 There are established communities surrounding tooling for this problem.

🌵 People are working on this! But expect thorns 

💀 To our knowledge, nobody is working on this

# Storage
<table>
<tr> <th> Problem </th> <th> Details </th> <th> State </th> <th> Projects </th> </tr>
<tr> 
  <td> 🔧 Archival </td>
  <td>
    How do we preserve research papers AND data? As universities and libraries are threatened with closures, how do we help research outlast the institutions that have been their stewards so far? 
  </td>
  <td> 
    Several projects are incentivizing long term content hosting.
  </td>
  <td>
    <a href="https://www.arweave.org/">Arweave</a> is pay-once-store-forever storage for smaller datasets.
    <a href="https://filecoin.io/">Filecoin</a> is pay as you go storage for large datasets.
  </td>
</tr>
<tr><td> 🌵 Access control </td>
  <td> 
    How do we ease sharing of data between researchers who should have access without leaking data to people who shouldn't have access?
  </td>
  <td>
    Access control is harder in p2p networks, but some projects are working on this.
  </td>
  <td>
    <a href="https://oceanprotocol.com/" >Ocean Protocol</a> uses "data wallets" to control data access. 
    <a href="https://docs.ipfs.io/concepts/privacy-and-encryption/#enhancing-your-privacy"> IPFS </a> can share encrypted files.
  </td>
</tr>
<tr> <td>💀 Extremely large datasets</td></tr>
<tr> 
  <td>💀 Exchange with formats following open standards</td>
  <td></td>
  <td></td>
  <td>Maybe <a href="https://ipld.io/">IPLD</a> is useful here? Or <a href="https://ceramic.network/">Ceramic?</a></td>  
</tr>
<tr> 
  <td>💀 Provenance information</td>
  <td></td>
  <td></td>
  <td>Maybe <a href="https://ipld.io/">IPLD</a> is useful here? Or <a href="https://ceramic.network/">Ceramic?</a></td>    
</tr>
<tr> 
  <td>💀 Metadata preservation</td>
  <td></td>
  <td></td>  
  <td>Maybe <a href="https://ipld.io/">IPLD</a> is useful here? Or <a href="https://ceramic.network/">Ceramic?</a></td>    
</tr>
<tr> 
  <td>💀 Annotating datasets / Linking associated datasets </td>
  <td> A medical dataset may have multiple researchers annotating or segment it. How can we preserve that relationship?</td>
  <td></td>  
  <td>Maybe <a href="https://ipld.io/">IPLD</a> is useful here? Or <a href="https://ceramic.network/">Ceramic?</a></td>    
</tr>
<tr> <td>💀 Search for related datasets</td></tr>
</table>


# Ecosystem
<table>
<tr> <th> Problem </th> <th> Details </th> <th> State </th> <th> Projects </th> </tr>
<tr> <td>💀Attribution</td> </tr>
<tr> 
  <td>🔧 Funding</td>
  <td> How can we steer funding towards research?</td> 
  <td> There are solid projects around founding research, primarily in research tools and software. </td> 
  <td> <a href="https://gitcoin.co/">Gitcoin</a> has routed millions of dollars towards "public goods," largely software. <a href="https://showcase.ethglobal.com/"> EthGlobal </a> has regular hackathons rewarding product implementations and ideas. Many <a href="https://en.wikipedia.org/wiki/The_DAO_(organization)"> DAOs </a> are rallying around organizing funding for science.  </td>
</tr>
</table>

# Computation
<table>
<tr> <th> Problem </th> <th> Details </th> <th> State </th> <th> Projects </th> </tr>
<tr> <td>💀 High thoughput</td></tr>
<tr>
  <td>🌵 Reproducible</td> 
  <td> How can we verify computatinoal research claims? </td> 
  <td> As web3 storage matures, frameworks that take advantage of them are appearing. </td> 
  <td> <a href="https://docs.holium.org/"> Holium </a> provides a framework for describing data pipelines, including their histories. </td> 
</tr>
<tr> <td>💀 Multi-threading, GPU accelerated</td>
  <td></td>
  <td></td>
  <td><a href="https://www.golem.network/"> Golem </a> is a Ethereum based marketplace for computation which has recently added GPU support. </td>
  
</tr>
</table>
