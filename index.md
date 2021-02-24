### Setting Up Your Computer For Python 
This guide attempts to give you all the instructions to be followed to setup your computer. It might happen that your system is unique in terms of the Operating System or existing configuration and that some of these instructions will simply not work. We hope you will be able to take help of your colleagues and friends to overcome such hurdles.

The main language to be used is Python 3.6 or higher. It is definitely possible for you to install Python from scratch and every single package manually but unless you have vast prior experience in doing this we strongly discourage you to do this. Instead, we will say thank you to the kind folks at Continuum Analytics for providing us with Anaconda!

Anaconda is a big bundle of goodies which when installed will give you direct access to Python, R and Scala - the leading languages of Data Science. The bundle also has several 3rd party libraries pre-installed thus saving you the effort of manually installing these. We have provided below instructions for installing Anaconda on Windows and Linux. Note that you will need at least 2GB of free hard disk space wherever you install Anaconda.

### Installing Anaconda on Linux

1. Go to: [https://www.anaconda.com/products/individual](https://www.anaconda.com/products/individual)
2. Scroll to the bottom of the page and download Anaconda for Python version 3.8. Choose the appropriate version depending on whether your system is 32 bit or 64 bit.
3. Once the shell script 'Anaconda3-2020.11-Linux-x86_64.sh' (name might change depending on whether you are using 32 or 64 bit machine) is downloaded, open a Terminal.
4. Using command line, navigate to the directory where it is download. We are going to assume that it is downloaded in your Home folder's Download directory.
5. `cd ~/Downloads `
6. Next, execute the script by saying, `bash Anaconda3-2020.11-Linux-x86_64.sh`
7. When prompted to read license agreement and press Enter, do so.
8. The license agreement is displayed. If you wish, read it else quit by pressing 'q'.
9. To the question of whether your approve type 'yes' and press Enter.
10. You will be asked to confirm the installation path, we recommend the default but if you are a power user, feel free to change the path.
11. The installation will continue for a while.
12. When prompted regarding modification of .bashrc, go ahead and type 'yes', followed by Enter. (You may want to note that the original .bashrc has been backed up so you can compare and see what changes were made.)
13. Now, our current terminal does not reflect the new .bashrc changes, we can either close the Terminal and start a new one so that it uses the latest additions made by Anaconda to the .bashrc OR to update existing terminal, we can say `source ~/.bashrc `  YOU NEED TO DO THIS ONLY ONCE. FUTURE TERMINAL INSTANCES WILL NOT NEED THIS.
14. Type `jupyter notebook` and play around. Get a feel for this environments.

### Installing Anaconda on Windows

1. Go to: Go to: [https://www.anaconda.com/products/individual](https://www.anaconda.com/products/individual)
2. Scroll to the bottom of the page and download Anaconda for Python version 3.6. Choose the appropriate version depending on whether your system is 32 bit or 64 bit.
3. Go to the folder where the file was downloaded.
4. Locate 'Anaconda3-2020.11-Windows-x86_64.exe' and double click it. 
5. Click Next
6. Click 'I Agree'
7. Choose 'Just Me' (does not require administrator privileges, hence safe) and click "Next".
8. You will be asked the destination folder - a default is already selected for you. Unless you need to change, just click "Next". Make sure both checkboxes (for PATH settings and for setting Python 3.8 as default) are checked. Click 'Install'.
9. Once it is done, click Finish (may open a page explaining the Anconda Cloud - we will not need this but feel free to browse).
10. Run Command Prompt, type "jupyter notebook" and press Enter. This will launch a browser and run Jupyter Notebook interface. Play around and when done, close the browser window, go to the Command Prompt window which you used to open the notebook program and press Ctrl+C to shutdown the notebook server. You can then close the Command Prompt.


****
