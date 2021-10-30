# TarpitAn
Tarpit Analyse in Kotlin

This is just a collection of a few tools to analyse your Tarpit Logfile.

When you have your Tarpit (see https://pypi.org/project/ssh-tarpit/) up and running 
you can instruct Tarpit to write a log file.

Copy your log file to the same directory, where the TarpitAn files already are. 
1. Step: Rename your log file to log.txt (It will not work otherwise).
2. Step: Start java -jar tarpitconv.jar in your CMD or Terminal.

Your log file might contain data of a longer period. You can user config.txt file to 
narrow time period. The first line has to contain the start date and time, while the 
second line has to contain stop date and time. Check out demo config.txt to learn more 
about the date time format.

3. Step: Start java -jar tarpitan.jar

to get a CSV formatted file, which can be further analysed in a spreadsheet.
Additionally you get a result.txt with a few summeries.

4. Step: Start java -jar tarpitangeo.jar

to get a Google Maps .kml file, to get a graphical presentation of each attacker.

5. Step: Start java -jar tarpitancc.jar

to get a different CSV formatted file to create Google Spreadsheet Heatmaps.

6. That's it.


