
## Installation 
Whether you are in `MACOS`, `windows` or `Linux`, you have to check first if git has been installed on your pc:

**Windows**
 - open your cmd(command prompt), then type `git --version`
 - If not found, install it 

**LINUX/MACOS**
 - Open your terminal, then type `git --version`
 - If the version is stated, there is no need to install git. Better still, you can upgrade it if you feel like.
 - If git command is not found, then we can begin the installation process
 - Most Linux system may tend to come with git out of the box

### 1. Installing Git on Different Operating Systems

#### **Windows**
1. Download the Git installer from the official [Git website](https://git-scm.com/download/win).
2. Run the installer and follow the instructions. You can keep the default options or customize them if needed.
3. After installation, open Git Bash (which comes with the installer) and check the installation:
   ```bash
   git --version

4. f you see the Git version, installation was successful.


### **macOS**

1. The easiest way to install Git on macOS is through Homebrew:
- First, install Homebrew (if you haven't already) by running this command in Terminal:
```bash

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
- Then, install Git:
```bash

brew install git
```
2. After installation, verify Git with:
```bash

git --version
```
3. Alternatively, you can also install Git using the Xcode command line tools:
```bash

xcode-select --install
```
### **Linux**

 - Ubuntu/Debian-based systems
1. Open the terminal and update your package list:
```bash

sudo apt update
```
2. Install Git with:
```bash

sudo apt install git
```
3. Verify the installation with:
```bash

git --version
```

 - Fedora-based systems
1. Open the terminal and run:
```bash

sudo dnf install git
```

2. Verify the installation with:
```bash

git --version
```

 - Arch-based systems
1. Run the following command in the terminal:
```bash

sudo pacman -S git
```
2. Verify the installation with:
```bash
Copy code
git --version

```