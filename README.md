# ssw_345_bot
Repo for the ssw 345 bot for Brendan Probst, Amit Bhatnagar, and Christian Huang. 

## Installation
Please note that this app requires the user to have Google Chrome installed along with a basic understanding of how to use Chrome extensions.

1. Clone the repo into your desired directory
2. Using the command line, do the following:
```
cd extension
npm install
```

3. From this point, you can either run the app as a website or build it for use as a Chrome extension. Please note it is **highly recommended** to build it as a Chrome extension, although this step may take longer. The first method is mainly for quick development changes.
### Method 1: Run as website (for quick dev changes, *NOT* for production!):

Simply use `npm start` and React should handle the rest. Your local machine will be running a development server on the localhost, and your default browser window should automatically open with the app.

### Method 2 **(RECOMMENDED)**: Build as a Chrome extension

Note: This has not yet been tested on macOS.
1. While in the extension directory, run `npm run build` in your command line
2. After running the above command, you should now have a build folder (extension/build). 
3. Navigate to your Chrome extensions. To do this, you can type chrome://extensions/ in your Chrome address bar.
4. You should see a "Developer mode" switch in the top right. Make sure it is enabled.
  
    ![image](https://user-images.githubusercontent.com/61301423/152060625-6d9653c3-623a-41cb-891a-270e16116dfe.png)

6. After switching on Developer mode, you should see "Load unpacked" on the top left. Click on it.

    ![image](https://user-images.githubusercontent.com/61301423/152060525-fa423da3-d363-4a1c-be85-8e3d09150a0d.png)


6. Navigate to the build folder you just created and select it.

    ![image](https://user-images.githubusercontent.com/61301423/152060891-5afc0d5a-fc80-4035-b696-2c0dc133cb3d.png)

7. You should now see the extension and some information associated with it.

    ![image](https://user-images.githubusercontent.com/61301423/152060955-c3ab9bae-8c23-47f2-9e42-412561ad2b2e.png)
    
8. That's it! The extension should be successfully installed to your Chrome browser. Please note that any time you make any changes and want to view them this way, you will need to rebuild the app (repeat step 1) and click on the refresh icon (as seen below) to update the extension with the new changes.

    ![image](https://user-images.githubusercontent.com/61301423/152061377-18cc2675-f8d6-40e6-a36e-ba9ce19162bd.png)
