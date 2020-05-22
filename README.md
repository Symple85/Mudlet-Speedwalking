# Mudlet-Speedwalking
Generic Speed Walking Package that allows for custom lists and complex command inputs.

Searchable list, echos back a clickable link to start speedwalking with and customizable notes as tooltips.

Please use issues to report any bugs and new ideas!

To install -
  1. Download the .mpackage to an easily accessible location.
  2. Click Package Manager in Mudlet.
  3. Click Install.
  4. Find your downloaded package and select it.
  5. Click Open.
  
To use this package - 

Aliases are
  1. speed add
  
    -Will start the editor and proccess to add an entry to your list.
    
    ***Use done to to cancel the process once you are in addition mode**
    
  2. speed list
  
    -Will list all of your current custom speedwalking locations with your notes as tooltips when you hover over them.
    
   2a. speed list *
   
    -Will search through your list for anything matching * and display it with tooltips.
    
  3. speed remove *
  
    -Will remove anything matching * from your list.
    
    ***Use caution as it will remove all matches currently, its best to list what you want then copy it exactly into the command line***
    
    ***It might be worth adding a respose check, or even a list option but with the click callback being the deletion trigger*** 
    
  3. speed note
  
    -Will enter the editor prompt you to add or remove notes from any of your listed entries.
    
  4. speed clear
  
    -Will clear ALL of your custom speedwalks.
    ***Use with caution**
    
  5. go to * or goto *
  
    -Will search for the first thing to match * and display it with notes as tooltips
    
    ***when you click this it will send your speedwalking path to the mud with the delay you setup during addition***
    
   5a. go to * or goto list *
   
    -Will search anything that matches * and display it with notes as tooltips
    
    ***when you click this it will send your speedwalking path to the mud with the delay you setup during addition***
    
  6. go to/goto or speed stop
  
    -Will stop your walking early.
     
     ***You can set up triggers or hotkeys to stop speedwalking by putting "stopSW = true" in the script box***

 v1.2
   -Added a list command to goto in case people wanted more than one reported back for clicking
   
   -Fixes to the note system.
   
    -Had plans to do an addition/removal selection but decided it wasnt needed so took out the prompt telling you to do so. 
    -Was accepting entry names in the editor only if it was an exact match, otherwise would cause issues. It will now search for what   you enter and attempt to find it. Also handles and reports if it's not found in any form.
    -Saving and discarding wasnt working properly. I had it calling to the original table instead of making a temp one for editing. It will now appropriatly only save your notes when you end with save and discard any changes if you end with done.
    -Realized that you can't highlight clickable links so made the speed list click function send the name of the area to the command input line for easy copy pasting of entry names.
  
 v1.1 
  -added break check in the speedwalk function to stop it early if needed.
  -changed autosave from 1 second to 5 seconds. Just felt like it was overkill, might still be...


<a href="https://ibb.co/m4Hqtx8"><img src="https://i.ibb.co/bXrBLfJ/Speed-Walk.png" alt="Speed-Walk" border="0"></a>
<a href="https://ibb.co/v1TfpKn"><img src="https://i.ibb.co/WnM7ZYJ/Speed-Walk2.png" alt="Speed-Walk2" border="0"></a>
