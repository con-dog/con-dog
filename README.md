# Me

I build 山乇丨尺ᗪ <sub>small</sub> <em>fast</em> projects.

<table>
<tr>
<td width="50%">
  <a href="https://github.com/con-dog/dwarves-and-dice/blob/master/README.md">
    <img src="https://github.com/con-dog/dwarves-and-dice/blob/95357e1ee9abe1194c2e4b40d9c84f0ac634d0d6/media/gifs/prettier-final.gif.png" width="100%">
  </a>
</td>
<td width="50%">
  <a href="https://github.com/con-dog/clingon/blob/master/README.md">
    <img src="https://github.com/con-dog/clingon/blob/8becb09bd06ee80a979c26e90c65506e93885c8a/media/clingon.gif.png" width="100%">
  </a>
</td>
</tr>
<tr>
<td width="50%">
  <a href="https://github.com/con-dog/tiny-neural-network/blob/master/README.md">
    <img src="https://github.com/con-dog/tiny-neural-network/blob/0394b2ac5ad294de34de6aabf0a0178340d82ce7/media/maze-solver-fast-small-loop.png" width="100%">
  </a>
</td>
 <td width="50%">
  <a href="https://github.com/con-dog/snibble/blob/master/README.md">
    <img src="https://github.com/con-dog/snibble/blob/e89a7bc3c6a0349a0df5b606baf1b8e881d8bfb6/media/snibble-small-fast-with-qr.png" width="100%" />
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
  <a href="https://github.com/con-dog/slices-demo/blob/main/README.md">
    <img src="https://github.com/con-dog/slices-demo/blob/f4ab8cf30217e235841b5f577fd490c93c545459/media/slices-short-small-silo-pool.png" width="100%">
  </a>
</td>

</tr>
 <tr>
 <td width="50%">
  <a href="https://github.com/con-dog/tiny-neural-network/blob/master/README.md">
    <img src="https://github.com/con-dog/tiny-neural-network/blob/d63f6506df6b312fdcc4a93309c7d23ac528b35f/media/microlex-streaming-small-fast-loop.png" width="100%" />
  </a>
<td width="50%">
  <a href="https://github.com/con-dog/chunked-z-level-raycaster/blob/master/README.md">
    <img src="https://github.com/con-dog/chunked-z-level-raycaster/blob/c6938be737d391198486f63293125aaf36d9a0c0/_media/textured-raycaster-small-fast-loop.png" width="100%">
  </a>
</td>
</tr>
</table>

## Stats

> [!WARNING]
> All benchmarks performed on a 2021 MacBook Pro with 16GB RAM
>
> Some benchmarks and claims change as I revisit projects and may become out of date

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
    <td>0 files</td>
    <td>Texture and map assets shipped with DigDice - every texel and every world is generated from a seed</td>
    <td>dig-dice</td>
  </tr>
  <tr>
    <td>1 bit</td>
    <td>A wall in the raycaster's chunked world map (a vertical stack of 16 walls fits in 2 bytes)</td>
    <td>chunked-z-level-raycaster</td>
  </tr>
  <tr>
    <td>1 byte</td>
    <td>Snibble's custom event protocol size</td>
    <td>snibble / snibble-bench</td>
  </tr>
  <tr>
    <td>5 keys</td>
    <td>DigDice's entire control mapping scheme (←↑→↓␣) handling 10+ actions and movement</td>
    <td>dig-dice</td>
  </tr>
  <tr>
    <td>18 bytes</td>
    <td>Maze-solving Neural Network solving 99% of unseen mazes</td>
    <td>maze-solver</td>
  </tr>
  <tr>
    <td>20MB</td>
    <td>Total size for a 100×100×10 chunk ray-casted world with O(1) lookup performance</td>
    <td>chunked-z-level-raycaster</td>
  </tr>
  <tr>
    <td>44 bytes</td>
    <td>Tether's entire memory: a maze walker with no map and no coordinates, on any grid under 67 million cells</td>
    <td>tether</td>
  </tr>
  <tr>
    <td>100 bytes</td>
    <td>Typical Snibble replay size for a 5 minute game (entire state)</td>
    <td>snibble / snibble-bench</td>
  </tr>
  <tr>
    <td>369 bytes</td>
    <td>Microlex's entire syntax-highlighting engine; each language adds a 37-178 byte state machine</td>
    <td>microlex</td>
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
    <td>Speed of Microlex JavaScript lexical classifier vs PrismJS under equivalent benchmark (99.6% per-character agreement)</td>
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
    <td>89.9%</td>
    <td>Unseen mazes (up to 161×161, plus 1,600+ step game-map routes) Tether solves within 10× the shortest route, from four wall bits and one goal-direction bit - ahead of every Bug algorithm tested, all of which are told their position</td>
    <td>tether</td>
  </tr>
  <tr>
    <td>97.3%</td>
    <td>Blink link navigation prediction accuracy with a 10 byte Neural Network (best hand-written heuristic: 66.2%)</td>
    <td>blink</td>
  </tr>
  <tr>
    <td>100%</td>
    <td>Exact replay accuracy for Snibble replays</td>
    <td>snibble / snibble-bench</td>
  </tr>
</table>
