# Google-Analytics
This repository contains a demonstration of JADE's integration with Google Analytics.

## Documentation Guide
*None yet?*

## Getting Started
These instructions will get a copy of the JADE Google Analytics Demo up and running on your local machine.

### Prerequisites

**Before you can load the schemas, you will need JADE 2018 installed:**

1. Grab a FREE Developer's license at https://secure.jadeworld.com/devlicense/
2. Download the JADE 2018 release at https://www.jadeworld.com/solutions-for/dev-partners/ 
3. Open the installer and follow the instructions in the easy install wizard.
4. JADE is now installed, and a shortcut has been placed in your Start menu. You're good to go!

> For more detailed instructions for installing JADE, visit https://www.jadeworld.com/downloads/tech/manuals/2016/InstallConfig.pdf

**You will also need a Google Analytics account:**

1. Visit <a href="https://www.google.com/analytics/">Google Analytics</a> and create a free account.
2. Edit your jade.ini file, adding the following to it:
[GoogleAnalytics]
GoogleID=UA-*Your Google Analytics ID*

### Loading the schema using JADE Git Integration

**Step 1: Setting your Username and Email**

1. In the Options menu, select the **Preferences** option.
2. Select the **Source Management** tab
3. Enter your name and email address into **Commit Details** section of the **Source Control** section.
4. Select a valid working directory (This can be whatever you like so long as you will remember it)
5. Click the **OK** btton

**Step 2: Cloning the Repo**

1. In the **Browse menu**, select **Git Source Control Client** -> **Clone…**  
(The local path will be filled in for you as the path you selected in Step 1)
2. For the Repository URL, enter https://github.com/jadesoftwarenz/JADE-Google-Analytics
3. Click on the **Clone** button.

**Step 3: Importing the Google Analytics demo**

1. In the **Schema menu**, select the **Load** option.
2. For the **Schema File Name** field, select **GoogleAnalytics.scm** in the **GoogleAnalytics** folder inside your working directory.
3. Click in the **Forms File Name** field, **GoogleAnalytics.ddx** should be entered for you automatically.
4. Click the **OK** button, and the Google Analytics schema will be loaded into your Schema Browser ready for use.

## Using the Google Analytics demo schema
1. Run the AnExampleApp application.
2. It should display "Google ID set to UA-0123456789-1" (with your Google ID) at the bottom. If not, ensure the GoogleAnalytics is set properly in your ini file.
3. To view analytics information, click the Open GA in Browser button. It should show that there is an active user while you have the app open, and zero active users when you don't. *Note: It may take a minute or so to update.*

## Frequently Asked Questions
**Q.** Can I contribute to or change these schemas?
> The schemas contained in this repository are for demonstration purposes and as such are not open to pull requests. However, you are welcome to create a fork and make changes to your own copy, subject to our license ([LICENSE](LICENSE))

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
