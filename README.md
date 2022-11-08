![fmIDE Logo](https://raw.githubusercontent.com/wiki/fmIDE/fmIDE/images/fmide.png)
# fmIDE
[A FileMaker Integrated Development Environment]

[fmIDE](https://github.com/fmIDE/fmIDE) is a module for FileMaker files which it makes it possible for tools to 'deep link' into the FileMaker Development Environment.

# CrossCheck™

[CrossCheck™](http://www.fm-crosscheck.com) is a FileMaker analysis tool from [[x] cross solutions GmbH](https://www.cross-solutions.de/).

# Script "fmIDE-Go to Thing from CrossCheck"

[The `fmIDE-Go to Thing from CrossCheck` script](Script-fmIDE-Go-to-Thing-from-CrossCheck.txt) is the bridge between CrossCheck™ and your database solutions (using the [fmIDE-'Name-that-Thing' API](https://github.com/fmIDE/fmIDE/wiki/fmIDE-'Name-that-Thing'-API))

In one click it jumps from the thing you are currently looking at in CrossCheck™ directly to that thing in your database.

# Installing

1. Get the tools
   - Get the [latest version of Cross Check](http://www.fm-crosscheck.com/Download.html) - [licence required](http://www.fm-crosscheck.com/Purchase.html) - or get a free trial serial number by [email request](mailto:info@cross-solution.com?subject=Trial%20licence&body=Hello%20Mr.%20Egginger%2C%0D%0DI%20have%20come%20across%20MrWatson's%20%5BfmIDE%20Integration%20for%20CrossCheck%5D(https:%2F%2Fgithub.com%2FfmIDE%2FfmIDE%2Fwiki%2FfmIDE-Integrations%23crosscheck)%2C%20and%20would%20like%20to%20try%20out%20CrossCheck%E2%84%A2%EF%B8%8F%20for%20the%20trial%20period.%0D%0DPlease%20could%20you%20send%20me%20a%20trial%20license.%0D%0DWith%20thanks%2C%0D%0D)
   - Get the [latest version of fmIDE](https://github.com/fmIDE/fmIDE/releases) - [free](http://fmworkmate.com/donate)

2. Prepare your databases for fmIDE-Integration
   - Follow the [fmIDE Installation instructions](https://github.com/fmIDE/fmIDE/wiki/Home#installing-fmide) to
     - paste the `fmIDE` script into your database files
     - tell fmIDE how you name your tables & layouts
     - tweak security
     

3. Prepare CrossCheck™ for fmIDE-Integration
   - Rename one of CrossCheck™'s empty custom scripts to `fmIDE-Go to Thing`
   - Paste the steps into it
     - Copy the xml contents of the [fmxmlsnippet.xml](fmxmlsnippet.xml) script steps file
     - Convert the xml to FileMaker objects with any FM-XML conversion tool like [fmWorkMate's fmCheckMate](https://github.com/mrwatson-de/fmWorkMate/releases/latest), or [fmAutoMate's PaXte function](https://github.com/mrwatson-de/fmAutoMate/releases/latest), or whatever your favourite clipboard conversion tool is.
     - Paste the steps into the script.

3. Perform a CrossCheck™ analysis of your database
   - Create a DDR of your database
   - Import the DDR into CrossCheck™

4. Click, 💥 Bang! 👀 Goggle!
   - Navigate to any record in the analysis in CrossCheck™, for example to a script step
   - Run the "fmIDE-Go to Thing" script
     - or press the shortcut key
   - You suddenly find yourself (more or less) looking at that thing in FileMaker, for example in the Script Workspace editing the script at exactly the script step.

Cool? Find out more about [fmIDE](https://github.com/fmIDE/fmIDE/wiki)

Enjoy & be productive!

MrWatson

---

P.S. Do you have a developer tool you'd like to integrate closer into the FileMaker Developer environment? Learn More about the [fmIDE-'Name-that-Thing'-Project](https://github.com/fmIDE/fmIDE/wiki/fmIDE-'Name-that-Thing'-Project)
