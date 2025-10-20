### 4ms Linux Kernel based on Radxa rk356x Kernel

The first commit was made to simplify building the Radxa kernel by following Radxa's guide
for building the kernel, and then checking in the changes that their script makes. 

This makes it much easier to use.

Here are all the steps that were performed:

- Go here: [Radxa BSP](https://docs.radxa.com/en/rock5/rock5b/low-level-dev/kernel)
- Do step 1.1
- Run this command:
`./bsp linux rk356x --no-build`
- `cd .src/linux`
- Commit changes
