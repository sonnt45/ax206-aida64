# AX206 3.5-inch LCD Screen

I bought a 3.5" LCD screen from an online store, that comes with poor packaging and without any model name or instructions. I spent some days to figure out how to use it, so I write this guide for myself and anyone like me.

## Product Model

You could find your model name on your box, back of the PCB or the startup image like me. There are many 3.5" LCD screen variants from different or noname brands. They look very similar but their protocols can be different.

Make sure that your model is **AX206 3.5" LCD screen**, otherwise, this guide can be useless.

## Driver

After you connect the screen to your PC via a USB A to C cable, you have to install the driver to let your PC controls the screen.

1. Download Zadig from [the official website](https://zadig.akeo.ie/), it's free.
2. Run it as admin privilege, you should see the GUI like this.
3. If Zadig can't recognize your device, click on **Options** -> **List All Devices** then select it manually.
4. Click on the down arrow to select **libusb-win32**.
5. Click on the **Install Driver** button. I've installed so it becomes **Reinstall Driver**.
6. Verify in **Device Manager**, there should be a **USB-Display** under **libusb-win32 devices**.

## AIDA64

I'm using AIDA64 Extreme, which is the most popular software for sensor panels. I tried to test with some others like [Turing Smart Screen](https://www.turzx.com/) or [an open-source alternative software](https://github.com/mathoudebine/turing-smart-screen-python), but they didn't work.

1. Download AIDA64 from [the official website](https://www.aida64.com/downloads), you may need to buy a key or active the trial version.
