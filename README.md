# SO-101_smolVLA

SO-101 robot arm project using smolVLA for vision-language-action control.

---

## Demo

https://github.com/user-attachments/assets/b833c1d3-0475-4a1a-8e3f-a1d6a5a18c8c

---

## Results

Single-arm pick-and-place task (select blue battery among multiple objects → move to box):  
**~70% success rate** with 100 training episodes.

---

## Structure

### `so-101/`
SmolVLA-based control code for the SO-101 robot arm.  
Based on [ggand0/vla-so101](https://github.com/ggand0/vla-so101), modified for our SO-101 setup.

### `IsaacSim/`
NVIDIA Isaac Sim environment used for rendering tests.

---

## Tech Stack

`smolVLA` · `SO-101` · `LeRobot` · `NVIDIA Isaac Sim` · `Python`
