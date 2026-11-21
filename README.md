# Me

I build 山乇丨尺ᗪ <sub>small</sub> <em>fast</em> projects.

## Current Project



## Small Showcase

<p>
  <a href="https://github.com/con-dog/dwarves-and-dice/blob/master/README.md">
    <img src="https://github.com/con-dog/dwarves-and-dice/blob/bcd2c5702a6a93168555fa517f148308d9c32b89/media/gifs/hatch-tpv.gif.png" width="100%" alt="DigDice: eggs crack open at the foot of a pyramid and dwarves burst out among the dice">
  </a>
</p>

<p>
  <a href="https://github.com/con-dog/clingon/blob/master/README.md">
    <img src="https://github.com/con-dog/clingon/blob/36d52c17fe6a16b1cff577e3c94bab55336d9bc3/media/films/19-ai-pretty-log.gif.png" width="100%" alt="Clingon: its AI is asked for the last ten commits as a graph, finds the command in the menu and runs it in the shell">
  </a>
</p>

<p>
  <a href="https://github.com/con-dog/tiny-neural-network/blob/master/README.md">
    <img src="https://github.com/con-dog/tiny-neural-network/blob/ba3df3072b7e05a409ddd7ddc62054cd44798329/media/films/05-net18-obstacles-25x25-s5000186-duo.gif.png" width="100%" alt="Minimio: an 18-byte neural network finds its way across a field of obstacles, its neurons shown firing beside the maze">
  </a>
</p>

<p>
  <a href="https://github.com/con-dog/snibble/blob/master/README.md">
    <img src="https://github.com/con-dog/snibble/blob/d35e4fad87aa6aa0601ec546ed555a1028e2a615/media/films/16-submit-quandary-22pts-s59b8.gif.png" width="100%" alt="Snibble: a snake spells QUANDARY, eats its own tail to hand it in, and scores 22">
  </a>
</p>

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
