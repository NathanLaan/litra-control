# litra-control

Command-line tool for controlling the Logitech Litra Glow and Litra Beam lights.

## Setup

1. Download or clone the `litra-control` repository.
2. Download the [hidapitester](https://github.com/todbot/hidapitester) [release](https://github.com/todbot/hidapitester/releases) for your platform.
3. Copy the `hidapitester` binary to the `litra-control` folder.
4. Open the command prompt
5. Navigate to the 'litra-control' directory.

  ```bash
  cd /path/to/litra-control
  ```

6. Make the `litra-control` script executable.

  ```bash
  chmod +x litra-control
  ```

7. Run the `litra-control` script with no options to see the list of available options.
8. Options can be chained like this:

  ```bash
  litra-control glowon glowmid glowcold
  ```

## References

- [hidapitester](https://github.com/todbot/hidapitester)
- [Controlling the Logitech Litra on MacOS](https://ultracrepidarian.phfactor.net/tag/mac/)
- [Logitech Litra Glow Aliases](https://github.com/kharyam/litra-driver/issues/13)
