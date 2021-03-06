# Azure Blob Storage demo for Unity3d
Contains a Unity 5.5 project featuring several demo scenes for Azure Blob Storage.  

1. Capture PNG screenshot (image blob)  
2. Record .WAV audio clip (audio blob)  
3. Save and Load .unity Asset Bundles (binary blob) 
  - Save/Load XML file to load Asset Bundle prefabs to scene
  - Save/Load JSON file to load Asset Bundle prefabs to scene  
4. List and delete blobs 

[![Blob storage Unity demo video](https://j.gifs.com/98zOxZ.gif)](https://youtu.be/0gpg2xwusjM)

# Setup Azure Storage Service for Unity3d
1. Create [Azure Storage Service](https://portal.azure.com/)  
![Azure Storage account](https://cloud.githubusercontent.com/assets/1880480/23862813/e480f950-0805-11e7-8ada-52acbf197874.png "New Storage > Storage account")
2. Select 'Containers' under Settings section    
![Azure Storage account](https://cloud.githubusercontent.com/assets/1880480/23959558/65ee06d4-099d-11e7-9e5d-00aab6a0a7a5.png "Settings > Containers")
3. Select add Container button  
![Add Container](https://cloud.githubusercontent.com/assets/1880480/23959561/686e5a08-099d-11e7-9e87-8de1938d2c8a.png "+ Container")
4. Select 'Blob' Access type container (as public read access is required for this demo)  
![Blob Access type](https://cloud.githubusercontent.com/assets/1880480/23862822/eab8f21e-0805-11e7-96f0-2d8e7bcb368b.png "Blob")
5. Select 'Keys' under Settings to copy blob storage details for Unity Editor inspector  
![Storage Keys](https://cloud.githubusercontent.com/assets/1880480/23958521/4ea59a80-099a-11e7-9795-e7421ece544c.png "Settings > Keys")

# Credits
- Sound effects from [downloadfreesound.com](http://www.downloadfreesound.com)

# Dependencies included
- [StorageServices](https://github.com/Unity3dAzure/StorageServices) for Unity
- [TSTableView](https://bitbucket.org/tacticsoft/tstableview) is used to display recyclable list of results.

# Notes
The Storage Services library used in this demo is currently in early beta, so not all APIs are supported yet and some things may change.
Questions or tweet #Unity #Azure [@deadlyfingers](http://twitter.com/deadlyfingers)
