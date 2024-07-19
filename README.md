# harp_demos
A repository with Harp device demos


## Getting started

- Run `setup.cmd` from `./bonsai` to install a portable version of Bonsai along with all necessary dependencies.
- Run `bonsai.exe` and open any of the workflows in the `./src` folder.

Further instructions on how to setup and interact with Harp devices can be found in the [harp-tech documentation website](https://harp-tech.org/articles/about.html).


## Demos

### `demo.bonsai`

- Connect a Harp Behavior board.
- Connect an LED to `DOPort0` (or just use the poke board). Connect a noseport to `DIPort0` (or just use the poke board). Connect a speaker to `DO0`.
- Connect an optional second LED to `LED1`. This will mimic optogenetic stimulation. Opto stimulation is automatically triggered when the led light is turned on or can be manually triggered using the button in the `Visualizer` node.
- Set the COM port
- Run the workflow
- Open the visualizers by double clicking the `Visualizer` node.

### `demo_withcamera.bonsai`

- Same setup as `demo.bonsai` but additionally connect a camera trigger line to `DO1`. 
- Set the COM port
- Run the workflow
- Open the visualizers by double clicking the `Visualizer` node.