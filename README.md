# luminosity-vba
Luminex antibody data visualisation tool written in Visual Basic for Application (VBA)

## Download the repository files
Click __Clone or download__ on the GitHub page [(https://github.com/machnine/luminosity-vba)](https://github.com/machnine/luminosity-vba) then click [__Download ZIP__](https://github.com/machnine/luminosity-vba/archive/master.zip) to download the repository to your local PC. 

## Unzip the file
Unzip the downloaded file __luminosity-vba-master.zip__ and extract the files in a new folder (name it _luminosity_ if you like)

## Update luminosity.conf file
Using a text editor (Notepad) to open the luminosity.conf file and change the contents with angle brackets to your actual settings:

      DATABASE_SERVER: <fusion_server_name>

      DATABASE_FILE: <fusion_datafile>

      USER_ID: <fusion_server_username>

      PASSWORD: <password>


      ### example:

      DATABASE_SERVER: \\LabPC\SQL_EXP14

      DATABASE_FILE: antibody_010117

      USER_ID: sa

      PASSWORD: pa$$w00d

## Launch luminosity.xlsb
Launch luminosity.xlsb to run the application, acknowledge the risk warnings when prompted - this is standard for any Excel file with macro. Enable edit if you want to edit the file.

## Bug Report, Feedback and Comments
If you have any bug report, feedback and comments please raise an issue on GitHub. If you don't want to register a GitHub account or don't know what GitHub is about, please email me: mianchen <at> gmail.com, with a subject title beginning "luminosity-vba".
