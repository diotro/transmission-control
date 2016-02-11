
## 1. Manual linux command-line instructions. ##
  * Login to Transmission server;
  * Execute the following command:
```
cd /
wget https://transmission-control.googlecode.com/files/tr-control-easy-install.sh
sh tr-control-easy-install.sh
```
---

## 1. Automatic Installation (Linux) ##
  * Login to Transmission server;
  * Execute the following command:
```
cd /
wget https://transmission-control.googlecode.com/files/tr-control-easy-install.sh
sh tr-control-easy-install.sh
```
  * This script is based on [the list](https://transmission-control.googlecode.com/svn/resouces/checkfolders.lst) automatically find Transmission Web Interface directory, if a match is found directory, the script will automatically download and install the latest content to the Web Interface directory;
  * If there is no matching directory, you will be prompted installation fails. Please try to manually install

## 2. Manual Installation (Windows) ##
  * Download and install [WinSCP](http://winscp.net/eng/download.php)
  * Download [Transmission  Web Control compressed package](https://transmission-control.googlecode.com/svn/resouces/transmission-control-full.tar.gz)
  * Run WinSCP and connection to Transmission server
  * Find Transmission web interface directory, like this: /usr/local/transmission/share/transmission/web/
  * Rename "index.html" to "index.original.html"
  * Upload compressed package to this parent directory (If you Transmission web interface directory is "/usr/local/transmission/share/transmission/web/", you need to upload the compressed package to "/usr/local/transmission/share/transmission/" directory)
  * UnTar this compressed package to the current directory:
![https://lh4.googleusercontent.com/-rZuClBaqFvo/UjfBYMJH3YI/AAAAAAAAAOo/OdPtYxX3DFA/w529-h561-no/%25E6%259C%25AA%25E5%2591%25BD%25E5%2590%258D.jpg](https://lh4.googleusercontent.com/-rZuClBaqFvo/UjfBYMJH3YI/AAAAAAAAAOo/OdPtYxX3DFA/w529-h561-no/%25E6%259C%25AA%25E5%2591%25BD%25E5%2590%258D.jpg)