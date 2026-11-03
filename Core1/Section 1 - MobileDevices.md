---
tags:
  - "#comptia"
  - a-plus
  - core1
  - mobile-devices
source: Professor Messer - CompTIA A+ Core 1
---


# 1. Laptop Hardware

A laptop is a standard computing platform that fits a lot of technology into a small space. The trade-off is that troubleshooting means dealing with very small components, built to precise specifications.

Some laptops are easier to fix than others: some are designed to make internal access and component swaps difficult. Each type has its own processes for managing and troubleshooting.

---

## Batteries

Some batteries are modular and can be removed and replaced. Others are built into the system and not designed to be swapped by the user, so they are harder to take care of.

- Types: **Li-ion** and **Li-Po**
- No **memory effect**: charging does not reduce the capacity
- The form differs for each laptop, so types and styles vary

---

## Keyboard

The keyboard is the **most-used component** of a laptop. It can be easy to replace (a few screws and a single ribbon cable), but it is not always that simple. Laptops have to be compact, so the layout is squeezed to fit everything found on a regular keyboard.

> [!tip] Diagnosis
> Plug in a **USB keyboard** to check whether the problem comes from the keyboard itself or from the OS.

### Laptop keys

A single key cap may need replacing. On desktops keys are robust, but on laptops they are **fragile**.

---

## Memory (RAM)

Internal components come in a smaller form factor.

### SO-DIMM

SO-DIMM is easy to remove and replace, but not every laptop offers this modularity.

> [!warning] Soldered RAM
> Sometimes the RAM is soldered to the system board, so you must replace the **whole board** to upgrade memory.

To add or replace it, there is usually a slot on the back: push the module in and it locks in place.

---

## Storage

Like desktops, laptops need a place to store OS files and user documents.

### Magnetic disk (HDD)

Many older laptops use a spinning hard drive. Desktops use **3.5"** drives, laptops use smaller **2.5"** drives.

### SSD

Modern laptops have moved away from spinning drives to SSDs. They have no moving parts, give fast access, and are much more reliable (no risk of a spinning drive failing).

| Type | Form factor | Notes |
| --- | --- | --- |
| HDD | 2.5" | Spinning, older laptops |
| SSD | 2.5" | No moving parts, reliable |
| SSD (M.2) | Small card | Newer laptops, plugged directly into the board |

### M.2

M.2 has a smaller form factor and is simply plugged in, so it is easy to install and replace. It is secured with **a single screw**, similar to RAM installation.

### Replacing laptop storage

Everything is internal, so you open a cover or the entire laptop.

Migrating from HDD to SSD makes the laptop more reliable and much faster, almost like getting a brand new machine. There are two ways to do it:

1. **Manual**: install a new OS on the SSD, move user documents over, and reinstall applications. This takes much more time.
2. **Cloning / imaging software**: creates an exact duplicate of the data from one drive to the new one.

Many SSD manufacturers include imaging software, or you can use a third-party tool. You can create an image on a separate device, or install both drives at the same time and clone from one to the other directly.

---

## Wireless: 802.11 and Bluetooth

Many laptops no longer have a wired network port, so connectivity relies on **802.11** (Wi-Fi) or **Bluetooth**. These are usually on the motherboard itself; older laptops used separate interface cards.

### 802.11

Used for the local network inside a building. It may be provided by a **mini PCI / PCI Express card**, designed to be modular (install and uninstall). Small connectors on the card plug into the wireless antennas built into the laptop.

- Two separate connectors: **main** and **auxiliary**
- The antennas commonly wrap around the outside of the display

### Bluetooth

Short-range communication used as a **PAN** (Personal Area Network). It can come as a separate interface card, but most newer laptops build it into the system board. A third antenna may be used for Bluetooth connections.

> [!note]
> Installation of these cards is very similar to installing memory.

---

## Biometrics

You can sign in or unlock a laptop with a **fingerprint reader** or **facial recognition**. This requires biometric hardware: a fingerprint reader, or a webcam (often built in).

---

## NFC (Near Field Communication)

NFC is a very short-range wireless technology, usually **4 cm or less**.

- Payments at a point-of-sale terminal with a phone or smartwatch
- Authentication with an access card or NFC device, for example nurses on a hospital workstation
- Also used in warehouses, manufacturing, and shipping and receiving

---

## Camera / Webcam

The camera is usually at the **center top** of the screen. It is used to capture video to a file or for real-time video in conference calls. Most laptops also have a microphone on each side of the camera.

Built-in cameras are convenient, but if you need a higher definition or more functionality, you can attach an **external camera** to the top of the display.
ut some of the componenets 

different processes for managin and troubleshooting their systems

# 2. Mobile Device Configuration

## 1. Connecting mobile devices

Mobile devices can connect ot other devices using two main types of connectivity :
- **Wired connectivity** : Use physical cable and connector
- **Wireless connectivity :** Uses radio signals to communicate without cable
These connections are used for more than just charging a device. They can also be used to :
- Transfer and synchronize data
-  Back up device information
- Connect peripherals and external devices
- Identify or authenticate a device

### 1. 1 USB (Universal Serial Bus)

USB is one of the most common standards used to connect mobile devices to computers and other equipment.

Over time different USB connector types have been introduced : 

**Common USB connectors**:

Connector      Description
___
USB Type-A    Traditional rectangular conencotr, commonly found on computer
___
Mini-USB         Older, relatively small connector used on some mobile devices
___
Micro-USB       Smaller connector widely used in older smartphones and other portable devices
___
USB Type-C     Modern, reversible connecotr used by many current devices. 24 pins

### 1.2 USB-C

modern USB connecotr designed to be easier to use and more versatile than older connecotrs.

**Key characteristics:**
- Reversible design : can be inserted in either orientation
-  24 pins
- Multiple capabilities : data transfer, power delivery and HDMI
- Different protocols : DisplayPort and ThunderBolt

This can easily replace the older USB 2.0 connection all the way up to the latest standard of USB, and we can even put different types of signals on this wire, even though they are all using the same type of connector as its physical interface. For example, you might find that this USB connection is used for more than just serial connectivity. You could see DisplayPort, HDMI, and thunderbolt all can use that single connector to be able to transmit video, data and other information.

it's a physicial connector, not a specific USB version. its actual speed and cpaabilities depend on the supported USB standard, cable and connected devices.

2 different USB-C cable smay look similar but support differents data transfer speeds and power levels
### 1.3 LIghtning

Lightning was introduced by Apple to resolve a number of problems with the older USB connection standard. Its commonly used on older Apple device and was designed to replace Apple's older 30-pin connector

**Key characteristics:**
- 8 pins 
- Reversible design : can be inserted in either orientation
-  24 pins
- Multiple capabilities : data transfer and power delivery 

Smaller and more convenient connecotr accross several mobile devices, but supporting devices from different manufacturers can require multiple types of cables and connector.

### 1.4 NFC - Near Field Communication

 NFC is often built into your device. 

**Common uses** :
- **Contactles payment :** paying at a point-of-sale terminal using smartphone or watch
- **Access control :** use it as identification to be able to gain access trought a door 
- **Identification :** Using your phone as a digitak card
- **Data exchange :** Transferring smal amounts of info from one phont to another
 
### 1.5 Bluetooth

Bluetooth allows us to connect devices over a high-speed network at relatively short distances. Often, we refer to this as a **Personal Area Network** or a **PAN**.

**Common uses :**
- connecting wireless headphones, headset, wireless keyboards or mice
- transferring data between devices
- tethering your smartphone to connect wirelessly

Bluetooth allow connexion between multiple devices to communicate wirelessly.

### 1.6 Hotspot and Tethering

Hotspot:  many people connecting to our mobile phone for internet access

Tethering : simply have one device that is connecting to this mobile phone, and that is the only device that’s able to use that phone

 This is functionality that’s commonly associated with the software in your phone and the capabilities from your phone provider.