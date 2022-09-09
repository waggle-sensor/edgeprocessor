# Edge Processor

The *edge processor* is a single-board Linux computer providing additional computing as an extension of a [Node Controller](https://github.com/waggle-sensor/nodecontroller). Like a [Node Controller](https://github.com/waggle-sensor/nodecontroller), this compute unit uses container-based isolation technologies to run user applications on the dedicated CPU-GPU resources.

# Current Generation Edge Processors

There are currently 2 Edge Processor platforms supported.
1. [Jetson Xavier NX](https://www.nvidia.com/en-us/autonomous-machines/embedded-systems/jetson-xavier-nx/)
2. [Raspberry Pi 4](https://www.raspberrypi.com/products/raspberry-pi-4-model-b/)

These compute units are automatically leveraged by the [Waggle Edge Stack](https://github.com/waggle-sensor/waggle-edge-stack) running on the [Node Controller](https://github.com/waggle-sensor/nodecontroller) to add computing power to a node.

## Source Code

- Jetson Xavier NX: https://github.com/waggle-sensor/wildnode-image
- Raspberry Pi 4: https://github.com/waggle-sensor/waggle-rpi-pxeboot

# Previous Generation Edge Processor

The legacy ARM32 based edge processor is kept for reference only and is no longer supported.

* [ARM32 Based Edge Processor](https://github.com/waggle-sensor/edgeprocessor-v1)
