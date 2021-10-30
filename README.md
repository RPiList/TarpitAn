# TarpitAn
Tarpit Analyse in Kotlin

This is just a collection of a few tools to analyse your Tarpit Logfile.

When you have your Tarpit (see https://pypi.org/project/ssh-tarpit/) up and running 
you can instruct Tarpit to write a log file.

If you just started and don't have a log file yet, you could download my demo-data
and play with it first: https://github.com/RPiList/TarpitAn/releases

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

![mymaps](https://user-images.githubusercontent.com/56664851/139542602-e8eadd7a-b6e5-4d37-b552-da25faddd7f6.png)

4. Step: Start java -jar tarpitangeo.jar

to get a Google Maps .kml file, to get a graphical presentation of each attacker. 
You can write your own geo-coordinates to geo.txt to adjust the attacked geo-coords 
to your actual location.

5. Step: Start java -jar tarpitancc.jar

to get a different CSV formatted file to create Google Spreadsheet Heatmaps.

![chart](https://user-images.githubusercontent.com/56664851/139542918-e412f305-1ff9-4cf2-92c5-3214a614f7ff.png)

6. That's it.


