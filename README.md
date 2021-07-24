# RPi CM4 - LiM Carrier Board series

The LiM Carrier Board series is a series of minimalistic Raspberry Pi (RPi) Compute Module 4 (CM4) Carrier Boards. Less-is-More (LiM) refers to the minimalistic design only providing the most rudimentary functionality to the CM4 such as 5V power via USB-C power connector and two status (power/activity) LEDs for the original LiM Carrier Board version. Additional + versions of the LiM Carrier Board will/might feature additional functionality such as flashing capability and SD card slot (see conceptual table below).

This is meant for CM4 boards with onboard storage (a future LiM version might sport a SD card slot for CM4 Lite modules) and wifi as this carrier board provides no other functionalty other than power and status LEDs.

![Picture of LiM Carrier Board with CM4 side by side](https://raw.githubusercontent.com/l00nix/rpi-cm4-LiM-board/main/images/LiM-CM4_sidebyside.png)
_**PIC1 - LiM Carrier Board with CM4 side by side**_

The first version of the LiM Carrier Board has been prototyped and more information can be found [here](pages/LiM_Board.md). The second version, the LiM+ Carrier Board has also been prototyped, more info can be found [here](pages/LiM+_Board.md).

The LiM carrier board took about two months from idea (May 22nd, 2021) to delivery (July 14th, 2021). Special thanks to [Anish Verma](https://www.linkedin.com/in/anish-verma-a5a05a8b/){:target="_blank"} for working with me on the CAD designs of the carrier board.

The idea for such a minimalistic board was born from a conversation with [Jeff Geerling](https://www.jeffgeerling.com/) when I asked him if he knew of a more minimalistic design than [this board](https://www.tindie.com/products/dronecz/minimal-carrier-board-for-compute-module-4/)? He pointed me to to uptime.lab's [Upberry](https://www.instagram.com/p/CPGakesLwBo/).

Neither of these boards are exactly what I was looking for for my use case. So insipired by Jeff I decided to design my own, customized board to my specs and that's how the Less-is-More board came to be. 

I forked this board design from [Shawn Hymel](https://github.com/ShawnHymel/rpi-cm4-base-carrier). He has a two part youtube series where he goes through how to design a CM4 Carrier Board.

- [Part 1 - How to Make a Raspberry Pi Compute Module 4 Carrier Board in KiCad](https://www.youtube.com/watch?v=ypcPJC_umPQ)
- [Part 2 - How to Make a Raspberry Pi Compute Module 4 Carrier Board in KiCad](https://www.youtube.com/watch?v=ge6gYIENo8Q&t)

Feel free to modify this design for your own application. 

Other iterations of the LiM board, inlcuding SD card tray and flashing capability are in the conceptual or prototype stages.

Here is the current conceptual list of planned boards:

Model | Power (5V USB-C) | LEDs (Power/Activity) | Flashing Capability | SD card slot | Development Stage
:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
LiM Board | &#10004; | &#10004; | &#10060; | &#10060; | [prototype](pages/LiM_Board.md)
LiM+ Board | &#10004; | &#10004; | &#10004; | &#10060; | [prototype](pages/LiM+_Board.md)
LiM++ Board | &#10004; | &#10004; | &#10004; | &#10004; | conceptual


You can read more about my RPi musings and projects on my [l00nix's RPi Musings Blog](https://rpi.loonix.ca/).

## About

[//]: # "[![GitHub Stats](https://github-readme-stats.vercel.app/api/pin?username=l00nix&repo=rpi-cm4-LiM-board&show_icons=true&hide_border=true&show_owner=true&theme=graywhite)](https://github.com/l00nix/rpi-cm4-LiM-board)"
[![GitHub Stats](https://github-readme-stats.vercel.app/api/pin?username=l00nix&repo=rpi-cm4-LiM-board)](https://github.com/l00nix/rpi-cm4-LiM-board)

This project is maintained by [Alexander Rau](https://rpi.loonix.ca). The Raspberry Pi Compute Module 4 is a product of [Raspberry Pi (Trading) Limited](https://www.raspberrypi.org/about/).

## License

Schematic and PCB layout files are licensed under the [CC BY 4.0](https://creativecommons.org/licenses/by/2.0/) license.

Individual components and footprints found in the CM4IO library are licensed as per the Design Files license found [here](https://datasheets.raspberrypi.org/license.html).

THE DESIGN IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS DESIGN INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS DESIGN.
