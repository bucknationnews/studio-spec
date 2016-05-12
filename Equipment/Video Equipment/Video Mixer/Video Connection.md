# Video Connection

Connecting video inputs/outputs to your video mixer.

## BlackMagic ATEM Television Studio

**Video Inputs:**

- 2 HDMI Inputs
- 2 HDMI/SDI Inputs (these inputs are special - you can use them with their SDI plug or their HDMI plug, but not both!)
- 2 SDI Inputs

All these inputs are SD/HD switchable.

**Program Outputs:**

- 2 SDI Outputs
- 1 HDMI Output

It also includes a multi-view preview feature, shown below:

![](https://images.blackmagicdesign.com/images/products/atem-television-studio/main/multi-view.jpg?_v=1460999805)

**Multiview Outputs:**
- 1 HDMI
- 1 SDI

All inputs and outputs are clearly labelled on the mixer.

---

### Connecting a consumer HDMI camcorder

1. Connect the appropriate adapter cables to obtain an HDMI output from your camcorder. You will probably need a miniHDMI adapter cable. Read more about this in the "Camera Equipment" section.
2. Connect the HDMI output to an open HDMI input on the ATEM TVS.
3. Verify you are getting the output you want by checking the multi-view monitor

### Connecting an SDI Camcorder

Follow the same basic procedure, simply using SDI instead of HDMI. Buckhorn High does not currently use any SDI inputs, so I cannot provide any more detailed instructions on this.

### Connecting/Configuring Multi-View Monitor

We recommend using a large TV for multi-view, with at least 720p resolution. 16:9 Widescreen is a must.

1. Connect the "MULTI-VIEW 1" HDMI output to an HDMI input on your TV.
2. Power up the mixer and television and be sure you get a signal. (Make sure your TV is on the right input!)
3. Configure your multi-view source arrangement from the BlackMagic ATEM Control Software.

### Connecting program output

Couldn't be simpler; just connect your HDMI/SDI cord from one of the outputs on the mixer to an input on another device. Everything just works!

### Connecting a PC or other presentation device

The easiest way to connect a PC (for ScreenMonkey, for example) is via HDMI. Most modern graphics cards have an HDMI output, so start by connecting an output from your GPU to an open input on your mixer.

Once you have connected the two, open the "Screen Resolution" settings in Windows. A new monitor (with a name like "BlackMagic") should be detected. Configure your extended desktop as desired, but set the resolution to 720p (1280x720). In our experience, this is the resolution that works best with the mixer. If your resolution is excessively high, it will simply ignore the signal.