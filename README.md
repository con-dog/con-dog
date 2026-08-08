# Me

I build weird, small, fast projects.

> [!NOTE]
> If it has already been done before, I'm (probably) not interested.
>
> If you tell me it can't be done, I will try to find a way to do it.

<table>
<tr>
<td width="50%">
  <a href="https://github.com/con-dog/tiny-neural-network">
    <img src="https://github.com/con-dog/tiny-neural-network/blob/0394b2ac5ad294de34de6aabf0a0178340d82ce7/media/maze-solver-fast-small-loop.png" width="100%">
  </a>
</td>
 <td width="50%">
  <a href="https://github.com/con-dog/snibble">
    <img src="https://github.com/con-dog/snibble/blob/6c9ac71ac51988b272f2d602777e082b283c80e7/media/snibble-fast-small-loop-3.png" width="100%" />
  </a>
</td>
</tr>
 <tr>
 <td width="50%">
  <a href="https://github.com/con-dog/chunked-z-level-raycaster/blob/master/README.md">
    <img src="https://github.com/con-dog/chunked-z-level-raycaster/blob/75acf3fb3f56c42ebaec1726f834c10b839fb6dc/_media/chunked-raycaster-fast-small-loop.png" width="100%" />
  </a>
</td>
<td width="50%">
  <a href="https://github.com/con-dog/snibble-bench-demo">
    <img src="https://github.com/con-dog/snibble-bench-demo/blob/d58209572b00a88d7391b1bdf6ebcbcdae949877/media/snibble-bench-fast-small-loop.png" width="100%">
  </a>
</td>
</tr>
  <tr>
 <td width="50%">
  <a href="https://github.com/con-dog/tiny-neural-network">
    <img src="https://github.com/con-dog/tiny-neural-network/blob/d63f6506df6b312fdcc4a93309c7d23ac528b35f/media/microlex-streaming-small-fast-loop.png" width="100%" />
  </a>
</td>
<td width="50%">
  <a href="https://github.com/con-dog/chunked-z-level-raycaster/blob/master/README.md">
    <img src="https://github.com/con-dog/chunked-z-level-raycaster/blob/c6938be737d391198486f63293125aaf36d9a0c0/_media/textured-raycaster-small-fast-loop.png" width="100%">
  </a>
</td>
</tr>
</table>

## Stats for Nerds 

> [!NOTE]
> All benchmarks performed on a 2021 MacBook Pro with 16GB RAM

> [!WARNING]
> This is an active work in progress. Some benchmarks and claims change as I continue to revisit and expand / compress projects

<table>
  <tr>
    <th colspan="3" align="left">Compression</th>
  </tr>
  <tr>
    <th align="left">Metric</th>
    <th align="left">Description</th>
    <th align="left">Project</th>
  </tr>
  <tr>
    <td>1 byte</td>
    <td>Snibble's custom event protocol size</td>
    <td>snibble / snibble-bench</td>
  </tr>
  <tr>
    <td>14 bytes</td>
    <td>Maze-solving Neural Network solving 96.5% of unseen mazes</td>
    <td>maze-solver</td>
  </tr>
  <tr>
    <td>20MB</td>
    <td>Total size for a 100×100×10 chunk ray-casted world with O(1) lookup performance</td>
    <td>chunked-z-level-raycaster</td>
  </tr>
  <tr>
    <td>100 bytes</td>
    <td>Typical Snibble replay size for a 5 minute game (entire state)</td>
    <td>snibble / snibble-bench</td>
  </tr>

  <tr>
    <th colspan="3" align="left">Performance</th>
  </tr>
  <tr>
    <th align="left">Metric</th>
    <th align="left">Description</th>
    <th align="left">Project</th>
  </tr>
  <tr>
    <td>2ms</td>
    <td>Snibble's average total frame time with 256 simultaneous players (logic AND rendering)</td>
    <td>snibble</td>
  </tr>
  <tr>
    <td>30x</td>
    <td>Speed of Microlex JavaScript lexical classifier vs PrismJS under equivalent benchmark</td>
    <td>microlex</td>
  </tr>
  <tr>
    <td>2048</td>
    <td>Simultaneous agents performing complex spatial/lexical/adversarial tasks at 60FPS</td>
    <td>snibble / snibble-bench</td>
  </tr>

  <tr>
    <th colspan="3" align="left">Accuracy</th>
  </tr>
  <tr>
    <th align="left">Metric</th>
    <th align="left">Description</th>
    <th align="left">Project</th>
  </tr>
  <tr>
    <td>97.3%</td>
    <td>Blink link navigation prediction accuracy with a 10 byte Neural Network</td>
    <td>blink</td>
  </tr>
  <tr>
    <td>100%</td>
    <td>Exact replay accuracy for Snibble replays</td>
    <td>snibble / snibble-bench</td>
  </tr>
</table>


## How

- Focusing on performance (highest speeds, tiniest sizes)
- Removing conventional layers (servers, databases)
- Under heavy self-inflicted constraints (e.g. "can this fit in a QR Code?")

> [!WARNING]
> I’ve used LLMs heavily since 2026 to speed up experimentation.
> 
> Old problem: My idea generation outpaced my execution.
>
> New problem: My execution can now outpace understanding.
>
> I'm learning to navigate this problem in newer projects.


