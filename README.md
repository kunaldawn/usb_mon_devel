USB MON v0.3 devel
=======================================
A small tool to
- List all available USB devices
- Start/Stop a process when particular usb device is attached or detached

### Usage :
Make it executable
$chmod +x usbmon

To list all available devices just run
$usbmon

To run a command/script/program on specified usb device is attached or detached just run
$usbmon vendor_id product_id command

example:
$usbmon XXXX XXXX gedit
Will summon gedit when ever usb device is attached and will close already opened gedit when ever usb device is detached with specified ids. 

### Dependency
Depends on PyUSB < http://sourceforge.net/projects/pyusb/ >

### LICENSE : GPLv3, 29 June 2007 
USB MON v0.3 devel
Copyright (C) 2014  Kunal Dawn <kunal.dawn@gmail.com>

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
