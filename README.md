# fsync_manual_trigger
Example codes for Camera Fsync Manual Trigger mode

Note:
In Fsync Manual Trigger mode, the performance and the precision depends on the program as well as the system load. Fsync Auto Trigger mode is much more precise than manual trigger mode.

## Bash Shell Script Examples

Make sure to run trigger program before starting the camera stream. 

### For RQX-59G and RQX-59F

```bash
cd fsync_manual_trigger/src/bash
chmod +x ./camera_trigger_rqx590.sh

sudo ./camera_trigger_rqx590.sh -r 10
```

### For RQX-58G:

```bash
cd fsync_manual_trigger/src/bash
chmod +x ./camera_trigger_rqx58g.sh

sudo ./camera_trigger_rqx58g.sh -r 10
```