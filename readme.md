# macp: Machine Poetry

Takes a textual description and produces an animated video


## Examples

```shell
$ ./render.sh examples/pix0.macp -o pix0.mp4 -hz 15 -w 360 -h 240
```

## Software Used

  * [https://github.com/CompVis/taming-transformers](https://github.com/CompVis/taming-transformers): VQGAN (aka taming transformers) for GAN-based image synthesis
  * [https://github.com/openai/clip](https://github.com/openai/clip): CLIP for steering image synthesis
