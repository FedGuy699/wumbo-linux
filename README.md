# 1. Clone the linux kernel:

    https://kernel.org

# 2. Download the Bore scheduler:

    https://github.com/firelzrd/bore-scheduler/tree/main/patches/stable

# 3. Put the config in the kernel folder

# 4. Apply the patch:

    patch -p1 < 0001-linux6.19-rc1-bore-6.6.1.patch

# 5. Now you can build the kernel :)
