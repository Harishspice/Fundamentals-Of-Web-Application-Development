# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:
Write your own steps here.
### Step 2:
Create a new Django project
### Step 3
Write the needed HTML code.
### Step 4
Run the Django server and execute the HTML files.

## Code:
```
map.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>My City</title>
</head>    
<body>
<h1 align="center">
<font color="red"><b>Ariyalur-Cement City</b></font> 
</h1>
<h3 align="center">
<font color="blue"><b>Hemadharshini M (22003738)</b></font>
</h3>
<center>
<img src="/static/images/map.png" usemap="#MyCity" heigth="420" width="1100">
<map name="MyCity">
<area shape="circle" coords="190,50,20" href="/static/html/ghs.html" title="Govt.Higher Secondary School">
<area shape="rectangle" coords="230,30,260,60" href="/static/html/rto.html" title="RTO Office">
<area shape="circle" coords="400,350,50" href="/static/html/vk.html" title="Washerman's Lake">
<area shape="circle" coords="400,200,75" href="/static/html/bus.html" title="Hi-Tech Bus Stand">
<area shape="rectangle" coords="490,150,870,320" href="/static/html/park.html" title="Eco-Park">
</map>
</center>
</body>
</html>

bus.html
<!DOCTYPE html>
<html lang="eo">
<head>
<title>Bus Stand</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="red"><b>Ariyalur-Cement City</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Hi-Tech Bus Stand</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Courier New" size="5">
<b>
Ariyalur district is an administrative district,one of the 38 districts in the
state of Tamil Nadu in India.The district headquaters is located at Ariyalur,
The district encompasses an area of 1,949.31sq.km.Gangaikonda Cholapuram,
build by king Rajendra Cholan of Chola Empire,is a UNESCO World Heritage Site
situated in this district.THe district is also known for its rich prehistoric
fossils.Many fossils of gigantic molluses and jawed fishes,at least one
fossilized dinosur egg,and several fragmentary fossils of sauropod and theropod
dinosaurs have been discovered here.An on-site museum is being set up at
keelapazhur to preserve and conserve fossils.Ariyalur is noted for its cement
induatries and Jayankondam has huge reserves of lignite. 
</b>    
</font>
</p>
</body>
</html>

park.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>Eco-Park</title>
</head>    
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>Ariyalur-Cement City</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Eco-Park</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Tahoma" size="5">
A very nic park near Ariyalur bus stand.It is located surrounding the Chetty Lake.
Very superb calm place in ariyalur.Best for walking.Nice playing place for kids.
Well maintained with jogging tracks.Source of ground water.
Good place play with children.In Banyan Treelot of parrot stay likie house.
good sound and Air.Lake view park looks awesome.
Very nice place at Ariyalur.
Simple and relaxe with play area. 
</font>
</p>
</body>
</html>

rto.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>RTO Office</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>Ariyalur-Cement City</b></font> 
</h1>
<h3 align="center">
<font color="blue"><b>RTO Office</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Arial" size="5">
<b>
RTO office or the Regional Transport Office is a government body specifically established to oversee 
all transport-related operations in the country.RTOs are located throughout the country in each
state and union territory.RTOs are responsible for enforcing the rules as laid down by the Motor
Vehicle Act of 1988.

The department also maintains a database of all the vehicles operating in the country as well as
issues licenses for drivers.Besides,the RTO office also collects road taxes,supervises pollution
checks,and ensures the enforcement of all road transportation rules.If you own or drive a vehicle in
India,you will need to visit the RTO to get your vehicle registered,obtain a driver's license or renew
your driver's license,etc.

RTOs are also responsible for improving road and vehicle safety,especially to avoid accidents.
</b>
</font>
</p>
</body>
</html>

ghs.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>Govt.High.Sec.School</title>
</head>
<body bgcolor="lime">
<h1 align="center">
<font color="red"><b>Ariyalur-Cement City</b></font> 
</h1>
<h3 align="center">
<font color="blue"><b>Government Higher Secondary School</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
The main objectives of Ariyalur Government Higher Secondary School are
<ul>
<li>To improve proper and qualified training to teachers and give them an attractive salary and
incentives so that they are not tempted to quit and look elsewhere for job.</li>  
<li>To provide financial aids and grants wisely and judiciousl.</li>
<li>To frame of syllabus and curriculum.</li>
<li>To set aims and objectives of education.</li>  
</ul>    
</font>
</p>
</body>
</html>

vk.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>Washerman's Lake</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="red"><b>Ariyalur-Cement City</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Washerman's Lake</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
The uses of Washerman's Lake in Ariyalur District are
<ol type="1">
<li>Lake is used for rain water harvesting.</li>
<li>it is used for drinking.</li>
<li>Pisculture.</li>
<li>For bathing,washing clothes etc.</li>
</ol>
</font>
</p>
</body>
</html>
```
## Output:
![244092567-2c32f3fa-30e8-42a8-b209-6e1e87b021e0](https://github.com/Harishspice/places-around-me/assets/117935868/f4bfd424-8a13-48b6-a9c5-0183e20f878b)
![244092739-3f2909c7-7879-4861-9473-06c463df64de](https://github.com/Harishspice/places-around-me/assets/117935868/a5d74587-73c2-40fb-8f0a-d148bce12d5b)
![244092781-44d7292b-fbf7-486f-9d10-9ee2684a74ef](https://github.com/Harishspice/places-around-me/assets/117935868/e39a235b-94dc-4f15-8b40-27b6871395ed)
![244092888-ebeebe38-da7e-44f0-8edb-6144e82e417e](https://github.com/Harishspice/places-around-me/assets/117935868/6846d6dd-d121-4b0f-8310-af069f270316)

## Result:
The program for implementing image map is executed successfully
