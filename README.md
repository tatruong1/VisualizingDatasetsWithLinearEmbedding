## Covid 3D - Visualization of Cases of Covid & Their Relations

An HTML file used to view cases of covid within the dataset directory: Israel & Portugal. The dataset is split into 2 filetypes: excel (.xlsx) files and csv files. 

### Instructions

**Tested with the latest versions of Chrome & Firefox**

**The HTML file depends on CDNs (Content Delivery Networks) and so may require internet to function.**

Open the HTML file in your browser and in the top left, you will see a place to input a metadata (.xlsx) file and a csv file. Both filetypes can be found within the dataset directory. 

The metadata must be inputted first before the csv file, otherwise the console will throw an error. (we would have liked this part to be automated, however due to CORS and same-origin policy, we couldn't; this manual input method works just as well). The two datasets **CANNOT** be mixed together (as in one cannot input Israel's xlsx file along with Portugal's csv file); both files must be of the same country.

Once the csv file is inputted and read, the 3D Environment will render in the main window. Certain parameters about the scene can be manipulated using the top interface whilst points within the environment can be clicked or hovered on to get their respective metadata entry.

Besides user input at the top, one can also press the 'E' key when a point is selected (as in their metadata is displayed) to change the camera's point of rotation to be on that point.
