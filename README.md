# thumbnail_generator_V2
Developed for specific work. More improvement will be done in future.

## very brief tutorial:
 must be run from command prompt or powershell.<br>
 syntax format: <br><p>`thumbnail_generator.exe <command>`</p><br>
              There are two commands:
              <ul>
                <li>
                command1: `fix` <br>
                    This option tries to fix the text formatting of slides as much as possible.<br>
                    (Can successfully change all english fonts of a pptx file. but no luck with bangla fonts)
                 </li>
                <li>
                command2: `export` <br>
                    This option exports all the presentation files of a specific folder to images and creates one folder per presentation that contatins all the exported images.
                 <br>Currently user can choose between jpeg or png format.
                <br>(Stable and works fine)
               </li>
              </ul>
              Sample execution: `thumbnail_generator_v2.exe export`
