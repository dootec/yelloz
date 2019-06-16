## yelloz
yelloz is a lightweight and fast script that aims to improve Bluetooth connectivity with the Bluez application without requiring PPA. It is very simple to use and does not require any dependence. Just download the yelloz script.

### Git
```sh
git clone https://github.com/dootec/yelloz
```

---

### 1. Quick Configuration
These methods are easy but will require `curl` dependency.
```sh
sudo apt install curl
```

### 2. Installation
#### Install Stable Version [Recommended]
```sh
curl -sL https://raw.githubusercontent.com/dootec/yelloz/master/yelloz | sudo bash -s 1 -y
```
#### Uninstall Stable Version (Restoring Default Setting)
```sh
curl -sL https://raw.githubusercontent.com/dootec/yelloz/master/yelloz | sudo bash -s 2 -y
```

#### Install Experimental Version
In the experimental version, `Bluez 5`, `pulseaudio` and `blueman` applications are run. If the stable version does not work properly on your device, then I recommend using the experimental version.
```sh
curl -sL https://raw.githubusercontent.com/dootec/yelloz/experimental/yelloz | sudo bash -s 1 -y
```
#### Uninstall Experimental Version (Restoring Default Setting)
```sh
curl -sL https://raw.githubusercontent.com/dootec/yelloz/experimental/yelloz | sudo bash -s 2 -y
```

---

### 3. Successful Messages
#### Installation:
```sh

Installation is successfully.
Now, you have to reboot your computer.

Have a nice day.

```

#### Uninstallation:
```sh

Uninstallation is successfully.
Now, you have to reboot your computer.

Have a nice day.

```
