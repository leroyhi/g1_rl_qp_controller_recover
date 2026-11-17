# Real G1, 2026-11-17 17:21:36: weak policy vibrates, then QP fails

84 s, mode_machine 5, MCControlG1 in torque mode. recovery_v0 until 38 s, weak from 51 s (operator switch), QP failure
at 83.98 s (QLD code 395 after `right_wrist_roll_joint` breached its torque limit; then `left_ankle_roll_joint` out of
its position limit as the robot fell).

The log is xz-compressed and split in parts below GitHub's 100 MB limit. Rebuild it with:

```bash
cat mc-control-G1RLQPController-2026-11-17-17-21-36.bin.xz.part* | xz -d > mc-control-G1RLQPController-2026-11-17-17-21-36.bin
sha256sum -c SHA256SUMS
```
