# Choosing and ordering a board - standard or micro?

AgOpenGPS boards come in two flavours - Standard or Micro. Functionally, they are the same - they only differ in size. Whether you want single-GPS or dual, either board is fine; and you can simply add another GPS module at a later date if you so wish, no need for another board.

## HOW TO ORDER/BUILD A PCB

We use the JCLPCB service to manufacture our PCBs, but you can use another supplier if you prefer.

1.- Click on [Order Now ](https://cart.jlcpcb.com/quote)to access the page to place the order, and that'll take you to a page that looks like this:

![](<../../.gitbook/assets/image (16).png>)

These files are located in AgOpenGPS/Support/TeensyModules/Board and pick either your Micro or Std design. Inside each folder we will find three files that we are going to use, the ZIP file is your Gerber file, so pick that first:

![](<../../.gitbook/assets/image (4) (1).png>)

It'll process for a bit, and you'll see a summary view:

![](<../../.gitbook/assets/image (5).png>)

Down to the bottom of the page, and slide the "PCB Assembly" switch over.

![](<../../.gitbook/assets/image (17).png>)

Here, you should select "assemble top side", and other important things are PCBA quantity, you can choose 5 full PCB (with SMD components soldered) or only 2 full PCB and 3 empty. If you choose Confirm Parts placement an JCLPCB engineer will correct your part placement and polarity (this action will need your confirmation).

Click Confirm when you're happy, and then add the BOM file and CPL file (they are in the same folder as the ZIP file - make sure you didn't accidentally move from the Standard to the Micro folder, or vice-versa!)

<img src="../../.gitbook/assets/image (12).png" alt="" data-size="original">

![](<../../.gitbook/assets/image (10).png>)

Now comes the fun part - it'll go and check with the JLCPCB inventory and see if any parts you need are missing. Here's a sample, it's likely yours will be different tho.

![](<../../.gitbook/assets/image (6) (2).png>)

![](<../../.gitbook/assets/image (20).png>)

![](<../../.gitbook/assets/image (9).png>)

First off, starting from the bottom - it's expected that they can't supply some of the components. The SimpleRTK2B, the Cytron, the Teensy, various connectors etc, the BNO085 - they're all fine to omit and you can get them elsewhere. If you can find alternatives, now would be a good time to try that, but if not, just Save to Cart again and get the cool 3D rendered output.

![](<../../.gitbook/assets/image (7).png>)

### TODO: list of alternatives for missing components

