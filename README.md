# MTGO to Moxfield Deck Converter

This script will attempt to convert a CSV from MTGO to a TXT that can be uploaded to Moxfield, while retaining the exact versions (and foil/nonfoil) from MTGO. 

Requires Python and the requests module (use `pip install requests` from the terminal to install it)

# Instructions

1. Download m2m.py
2. Put it in a folder with a .csv file named "deck.csv"
3. Run m2m.py from the terminal
4. Upload the resulting deck_fixed.txt to Moxfield

# Downloading CSV from MTGO

1. Open MTGO and go to your collection or deck.
1. On the bottom left of the window, right-click on the collection name and click Export.
    
    ![MTGO Export](/docs/export_button.png)
1. *NOTE: Make sure to select "Spreadsheet CSV format" as the file type.*

    In the file dialog, save the CSV file.
    
    ![MTGO Save CSV](/docs/export_type.png)
  