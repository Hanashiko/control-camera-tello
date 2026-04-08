# Control Camera Tello

Keyboard-controlled DJI Tello drone with live video feed using OpenCV.

## Controls

| Key | Action |
|-----|--------|
| `T` | Takeoff |
| `L` | Land |
| `W` / `S` | Forward / Backward |
| `A` / `D` | Left / Right |
| `Up` / `Down` | Ascend / Descend |
| `Left` / `Right` | Rotate left / right |
| `+` / `#` | Increase / Decrease speed |
| `Esc` | Quit |

## Requirements

```
pip install djitellopy opencv-python keyboard
```

## Usage

```bash
# Basic flight with live video
python main.py

# Save frames to disk
python main.py --save_session --save_path session/
```
