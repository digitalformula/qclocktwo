# QClockTwo for Conky

No credit to me for creating this.  Original artwork created by [mowgli-writes on DeviantArt](https://www.deviantart.com/mowgli-writes/art/qlocktwo-conky-470067388).

This repo only exists to provide an updated version of the `.conkyrc` file that doesn't throw errors on later version of Conky.

## Usage

I'm on Pop OS (Ubuntu variant), so here's how to use this file there.

- Install Conky:

  ```
  sudo apt-get install conky
  ```

- Open the `qclocktwo` file in this repo, making sure you open the **raw** version
- Save the `qclocktwo` file as `.conkyrc` in your user's home directory i.e. `~/.conkyrc`
- Run Conky:

  ```
  conky &
  ```

- Conky should run, with the `qclocktwo` theme displayed at the top left of your screen
- If you want to change the position of the `qclocktwo` widget, edit `~/.conkyrc` and look for the following settings:

  - alignment
  - gap_x
  - gap_y

- Conky should detect changes in `~/.conkyrc` and reload when the file is saved

![Screenshot](./screenshot.png)