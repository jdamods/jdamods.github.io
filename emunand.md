# Set up emuNAND

1. Boot into Hekate and select **emuMMC**

    ![Hekate homescreen](/assets/images/emunand/nyx20230203_122437.png)

1. Select **Create emuMMC**

    ![emuMMC before creating](/assets/images/emunand/nyx20230203_122447.png)

1. Choose **SD File** or **SD Partition**
    - **SD File** will create an image file of your current sysnand that will be stored on your SD card
    - **SD Partition** will create an additional partition on your SD card and copy your current sysnand to the new partition

    ![](/assets/images/emunand/nyx20230203_122452.png)

## SD File

1. Wait approximately 15-30 minutes for your sysnand to be imaged

    ![](/assets/images/emunand/nyx20230203_133512.png)

## SD Partition

**BACK UP YOUR SD CARD BEFORE DOING THIS**

1. You'll get an error saying an applicable partition hasn't been found. Select **Continue**

    ![](/assets/images/emunand/nyx20230203_133139.png)

1. Select how much SD card space you want to dedicate to the emuNAND partition by moving the **Red** slider

    ![](/assets/images/emunand/nyx20230203_133207.png)

2. You'll be asked to confirm by selecting **Start** and you'll then have to confirm again by pressing the **Power** button

    ![](/assets/images/emunand/nyx20230203_133238.png)

## Finishing setup

1. After creating an emunand image, the emuMMC page should now say **Enabled**, but you'll still need to tell Hekate to use this image when launching emuNAND. To do this, select **Change emuMMC**

    ![](/assets/images/emunand/nyx20230203_130729.png)

1. Choose your emuNAND image according to how you set it up in the previous steps
    
    -**SD Partition** - Select **SD RAW 1**
    
    -**SD File** - Select the file on the right side of the screen

    ![](/assets/images/emunand/nyx20230203_133522.png)

1. Return to the Hekate home screen and from the **Launch** screen, select **EMUMMC**. Your console will now boot into emuNAND!