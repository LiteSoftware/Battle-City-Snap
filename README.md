# Battle-City-Snap

## Build snap

1. Install snap
```bash
sudo apt update
sudo apt install snapcraft
```
2. Clone repository
```bash 
git clone git@github.com:LiteSoftware/Battle-City-Snap.git
```
3. Build snap package

```bash
cd Battle-City-Snap
snapcraft
```

4. Run snap package

### devmode: 
```bash
sudo snap install --devmode --dangerous <your_snap_file>.snap
```

### strict mode:
```bash
sudo snap install --dangerous <your_snap_file>.snap
```

