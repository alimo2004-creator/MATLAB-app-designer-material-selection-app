# MATLAB-app-designer-material-selection-app
simply this app is designed to aid in choosing a material(theoretical or existing) for car rims , which is very vital in our life nowadays, by using a previously prepared csv file that include materials and their properties .
firstly, in the first tab, choose the type of car required (normal, sport, luxury, EV or even a custom one) , it will display the considerations and their weights ,ranks the top 10 chosen materials and displays the properties and requirements,  also when you choose any material it displays the stress-strain curve(to be more realistic ,it just plot the fracture point ,slope and yield point).

the second tab, it shows how we choose the materials, by making screening and ranking for the material included in the csv file ,it shows the passed and failed materials then make a score to them based on the ashby chart and other factors.

third tab, it shows Ashby chart(it isn't exactly an Ashby chart but a strength to density chart) ,it indicated the chosen material and the other materials as well.

4th tab, it has the real Ashby charts

5th tab, it shows an interactive 3d model of the car rim and the stresses applied on the rim, it also shows ,in this tab, the manufacturing process and constrains of the chosen material, (any material in the csv file) .

6th tab, it is the calculator tab that you can calculate the index in it, enter values for the vehicle and it will calculate the radial and lateral stresses on each rim , also it will change the values in the screening and scoring and in the first tab it will show the new ranked materials based on the new stresses, also ,there are sliders in this tab to indicate the new weights.

finally, i want to add more features in the future like a heat map for stresses on the car rim and many more features.
