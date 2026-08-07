# Me

I build weird, small, fast projects.
 
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
  <a href="https://github.com/con-dog/chunked-z-level-raycaster/blob/master/README.md">
    <img src="" width="100%" />
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


| Compression     | Description                                                                            | Project                   |
| :-------- | :-------------------------------------------------------------------------------------- | :------------------------- |
| 1 byte    | Snibble's custom event protocol size                                                   | snibble / snibble-bench   |
| 14 bytes  | Maze-solving Neural Network solving 96.5% of unseen mazes                              | maze-solver               |
| 20 MB     | Total size for a 100×100×10 chunk ray-casted world with O(1) lookup performance        | chunked-z-level-raycaster |
| 100 bytes | Typical snibble replay size for a 5 minute game (entire state)                         | snibble / snibble-bench   |


| Performance     | Description                                                                            | Project                   |
| :-------- | :-------------------------------------------------------------------------------------- | :------------------------- |
| 1 byte    | Snibble's custom event protocol size                                                   | snibble / snibble-bench   |
| 14 bytes  | Maze-solving Neural Network solving 96.5% of unseen mazes                              | maze-solver               |
| 20 MB     | Total size for a 100×100×10 chunk ray-casted world with O(1) lookup performance        | chunked-z-level-raycaster |
| 100 bytes | Typical snibble replay size for a 5 minute game (entire state)                         | snibble / snibble-bench   |

| Accuracy     | Description                                                                            | Project                   |
| :-------- | :-------------------------------------------------------------------------------------- | :------------------------- |
| 1 byte    | Snibble's custom event protocol size                                                   | snibble / snibble-bench   |
| 14 bytes  | Maze-solving Neural Network solving 96.5% of unseen mazes                              | maze-solver               |
| 20 MB     | Total size for a 100×100×10 chunk ray-casted world with O(1) lookup performance        | chunked-z-level-raycaster |
| 100 bytes | Typical snibble replay size for a 5 minute game (entire state)                         | snibble / snibble-bench   |



| --------- | ----------- | -------------------------------------------------------------------------------------- | ------------------------- |
| 1 byte    | Compression | Snibble's custom event protocol size                                                   | snibble / snibble-bench   |
| 2 ms      | Performance | Snibble's average total frame time with 256 simultaneous players (logic AND rendering) | snibble                   |
| 14 bytes  | Compression | Maze-solving Neural Network solving 96.5% of unseen mazes                              | maze-solver               |
| 20 MB     | Compression | Total size for a 100×100×10 chunk ray-casted world with O(1) lookup performance        | chunked-z-level-raycaster |
| 30x       | Performance | Speed of Microlex JavaScript lexical classifier vs PrismJS under equivalent benchmark  | microlex                  |
| 97.3%     | Accuracy    | Blink link navigation prediction accuracy with a 10 byte Neural Network                | blink                     |
| 100%      | Accuracy    | Exact replay accuracy for Snibble replays                                              | snibble / snibble-bench   |
| 100 bytes | Compression | Typical snibble replay size for a 5 minute game (entire state)                         | snibble / snibble-bench   |
| 2048      | Quantity    | Simultaneous agents performing complex spatial/lexical/adversarial tasks at 60FPS      | snibble / snibble-bench   |


## How I Build

- Deriving concepts from first principles
- Building under constraints
- Simplifying concepts to hold the whole model in-memory
- Focusing on performance (highest speeds, tiniest sizes)
- Removing conventional layers (servers, databases)


