# Me

I build weird, small, fast projects.
 
> If it has already been done before, I'm (probably) not interested.
>
> If you tell me it can't be done, I will try to find a way to do it.

<table>
<tr>
<td width="50%">
  <a href="https://github.com/con-dog/tiny-neural-network">
    <img src="https://github.com/con-dog/tiny-neural-network/blob/e426e5697f03a2b58130dd5c4fa71ba16e0884e2/media/maze-solver-fast-small-loop.gif" width="100%">
  </a>
</td>
 <td width="50%">
  <a href="https://github.com/con-dog/snibble">
    <img src="https://github.com/con-dog/snibble/blob/af25b8c61e08a45a558e1af1746428e854fffd53/media/snibble-fast-small-loop-2.gif" width="100%" />
  </a>
</td>
</tr>
 <tr>
 <td width="50%">
  <a href="https://github.com/con-dog/chunked-z-level-raycaster/blob/master/README.md">
    <img src="https://github.com/con-dog/chunked-z-level-raycaster/blob/f3dd23af294a8b27476607e5b45a053c368c94c5/_media/chunked-raycaster-fast-small-loop.gif" width="100%" />
  </a>
</td>
<td width="50%">
  <a href="https://github.com/con-dog/snibble-bench-demo">
    <img src="https://github.com/con-dog/snibble-bench-demo/blob/fec8dd84ab1e5d14a746dbf5200cec76ef294474/media/snibble-bench-fast-small-loop.gif" width="100%">
  </a>
</td>
</tr>
</table>

## Stats for Nerds 

> All benchmarks performed on a 2021 MacBook Pro with 16GB RAM

| Value     | Category    | Description                                                                            | Project                   |
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


