# anki_colab_test

this is a test of anki collaborate. Later, when tests have been sucessful (hopefully), there will be created a new repo with actual decks. The decks will be related to subjects at ntnu, for electronic system design.

it is using the crowd anki plugin: https://ankiweb.net/shared/info/1788670778

# how to use
## to download
1. install anki: https://apps.ankiweb.net
2. install cowd anki: https://ankiweb.net/shared/info/1788670778 (in anki go to  tools-> add ons -> get add ons -> code: 1788670778 -> ok, then restart anki)
3. in anki go to file -> crowd anki: import git repository -> url: https://github.com/ben1mit/anki_colab_test -> ok

## to upload
1. Select the deck (note: export of "All decks" is not supported, you need to select a specific deck) and the export format "CrowdAnki JSON representation". After pressing the Export button - select directory where the result should be stored.
2. open a terminal in the folder which you downloaded and type "git commit -a -m "\<your changes>", then type "git push origin main" (this last step will be refined at a later point and is a temporary solution)
  
