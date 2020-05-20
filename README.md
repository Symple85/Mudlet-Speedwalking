# Mudlet-Speedwalking
Generic Speed Walking Package that allows for custom lists and complex command inputs.
Searchable list, echos back a clickable link to start speedwalking with and customizable notes as tooltips.

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
  
  


<a href="https://ibb.co/m4Hqtx8"><img src="https://i.ibb.co/bXrBLfJ/Speed-Walk.png" alt="Speed-Walk" border="0"></a>
<a href="https://ibb.co/v1TfpKn"><img src="https://i.ibb.co/WnM7ZYJ/Speed-Walk2.png" alt="Speed-Walk2" border="0"></a>
