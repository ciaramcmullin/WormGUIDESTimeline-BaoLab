# WormGUIDESTimeline-BaoLab

Source code can be found at: @https://github.com/tangydoris/WormGUIDES-BaoLab

#### Main Application
WormGUIDES is a collaboration led by Drs. Zhirong Bao (MSKCC), Daniel Colon-Ramos (Yale), William Mohler (UConn) and Hari Shroff (NIH). 
For more information, visit website at http://wormguides.org.
The Timeline project was created for my internship in the Bao Lab located in Sloan Kettering Cancer center during Summer 2017. It is an
addition to the application WormGUIDES. In order to understand this addition and proper setup, please see the attached link to the source 
code.

#### About
The Timeline chart was created using IntellJ. It is used for another view of the Stories and Notes. It is unqiue to the 
application because it shows how indivual cells are connected in each Story. The Timeline Chart displays the series for each cell 
that show the Note tag name and tag contents on hover. It also actively rebuilds itself when a change is made to a Story, Note, or window.

#### Changes in Original Source
•	New folder for Timeline which contains Timeline class and CSS styleclass
•	timelineChart was added into StoriesLayer constructor
•	Timeline stage variable and Timelinechart added into rebuildSubsceneFlag listener in Window3DController
•	TimelineStage added in rootlayoutController and new method viewTimeline is created
•	ViewTimeline method added to RootLayoutController and FXML file

