# onezdtr

*I build tools that show what your machines say behind your back.*

<table width="100%">
  <tr>
    <th width="50%" align="center"><a href="https://github.com/onezdtr/3assas">3assas</a></th>
    <th width="50%" align="center"><a href="https://github.com/onezdtr/khada3">khada3</a></th>
  </tr>
  <tr>
    <td width="50%" align="center"><a href="https://github.com/onezdtr/3assas"><img src="demos/3assas.gif" width="380" alt="3assas web page: programs and where they connect, AI-judged alerts flagging a hidden binary uploading to a Russian host, live feed"></a></td>
    <td width="50%" align="center"><a href="https://github.com/onezdtr/khada3"><img src="demos/khada3.gif" width="380" alt="khada3 radar dashboard showing every device on a home network and the companies it talks to"></a></td>
  </tr>
  <tr>
    <td width="50%" align="center">See which program on your Linux machine talks to whom, from inside the kernel, and cut it off in one command. eBPF hooks name every connection from the DNS answers, an LSM hook blocks a program live, a 24/7 agent has an AI judge every new connection. Measured overhead, one-line install. (C, Rust, Python)<br><a href="https://onezdtr.github.io/3assas/">Website</a> · <a href="https://github.com/onezdtr/3assas">Code →</a></td>
    <td width="50%" align="center">A home DNS server that shows who every device on the network talks to, blocks trackers, and has an AI agent that explains the day on Telegram. Runs on an old MacBook turned server. (Python)<br><a href="https://github.com/onezdtr/khada3">Code →</a></td>
  </tr>
</table>

<table width="100%">
  <tr>
    <th align="center"><a href="https://github.com/onezdtr/chouf">chouf</a></th>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/onezdtr/chouf"><img src="demos/chouf.png" width="600" alt="chouf report: proof that a fake theme installer sent the AWS access keys and the SSH key to example.com, which programs read them, and what to do about it"></a></td>
  </tr>
  <tr>
    <td align="center">Run any program in a throwaway sandbox full of bait secrets and see what it really does: which secrets it went after and which process read them (eBPF), where it connected, proof of what left the machine, the local network kept out of reach. An AI tester drives the program, sets off what it planted for later, and judges what it says against what it does. (Rust, C, eBPF, podman)<br><a href="https://github.com/onezdtr/chouf">Code →</a></td>
  </tr>
</table>

## Stack

<p align="center"><b>Languages</b></p>
<p align="center"><img src="https://skillicons.dev/icons?i=py,rust,c,js,html,css,bash,nodejs,react&perline=15" alt="Python, Rust, C, JavaScript, HTML, CSS, Bash, Node.js, React" /></p>

<p align="center"><b>Tools &amp; infra</b></p>
<p align="center"><img src="https://skillicons.dev/icons?i=linux,fedora,git,github,sqlite&perline=15" alt="Linux, Fedora, Git, GitHub, SQLite" /></p>

<p align="center">Also: eBPF · libbpf · systemd · DNS · Tailscale · LLM agents · Gemini API · Telegram bots</p>
