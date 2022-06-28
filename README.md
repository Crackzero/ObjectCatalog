# UNDER CONSTRUCTION
# Landmarks for Object-Based Visual Outdoor Localization Approaches of Automated Ground Vehicles

This page contains several information for the object based localization methods by using landmarks:

* A mindmap for the overview of all proposed attributes for object description, georeferencing for the creation of future datasets.

* A table with objects, attributes and suitability in comparsion of their suitability for object-based localization methods. The suitability is claculated by the object-based norm
* * [Download full object catalog in excel format](/Objektkatalog_20220207_7.xlsx)


**Mindmap with object attributes**
<p float="center">
    <img src="mindmap.PNG" width="100%" title="Object attributes for Localization"/>
</p>


**Table with object attributes and suitability**

|Nummer   |Class   |Object  |distance|distance|dimension 2D|a_obj   |spatial plane|frustum volume|a_norm  |dimension|shape   |normed obj|material|surface |LOO     |persistence|Environment|AI dataset|distribution around vehicle|suitability|Camrea bis Fahrbahnrand rechts|1,75    |        |Street length in Germany [km]|627000  |
| --------|--------|--------|--------|--------|--------    |--------|--------     |--------      |--------|-------- |--------|--------  |--------|--------|--------|--------   |--------   |--------  |--------                   |--------   |--------                      |--------|--------|--------                     |--------|
|         |        |        |min     |max     ||||||handling|||||||||||Höhe camera [m]|1,2||Area of Germany [km²]|357386|
||||[m]|[m]|[cm x cm]|[m²]||[m³]|[m²]|[2D/3D]|||||[1/km]|[yr]|||||||||||
|1|buildings|buildings|1,5|300|h=1000 x w=1000|100|YZ|66,33333333|0,222222222|3D / 2D|Haus|nein|Holz, Beton, Metall, Glas, Plastik|regelmäßig / Unregelmäßig|30,7814992|60|City, Rural, Highway|-|360°|68,40333156|||||||
|2|vegitation|tree|3|300|h=50 - 3000|69|YZ|22,77|0,076666667|3D||nein|Holz|unregelmäßig, -, matt|22,02316647|200|City, Rural, Highway, Forest, Natural|~|360°|16,88442762|||||||
|3|ground objects|lane|10|300|l=30000 x w=300||XY|53,94|0,1798|2D|Rect|ja|Asphalt, Beton, Schoter|Regelmäsig, rau|3,333333333|30|-|x|Fahrtrichtung|5,993333333|||||||
|4|landscapes|edge of forest|5|300|w=20000 x 18000|360|YZ|70,8|0,24|3D||nein|Erde, Grad|unregelmäßig,-, matt|1,958537827|100|City, Rural, Highway, Forest, Natural|-|360°|4,700490786|||||||
|5|infrastructure|electricity pylon|20|300|h=2000 - 5100 x b=800|200|YZ|9,333333333|0,033333333|3D||nein|Holz, Beton, Metall|regelmäßig, glatt, matt|2,461161551|80|Rural, Highway|-|360°|0,820387184|||||||
|6|traffic sign|lane markings|10|300|w=12 - 30 x l=600-1200||XY|5,394|0,01798|2D||ja|Plastik, Glas|regelmäßig, rau, refelktierend|3,333333333|5|City, Rural, Highway |x|360°|0,299666667|||||||
|7|traffic sign|sign|3|300|d=42 - 120|0,64|YZ|0,2112|0,000711111|2D||ja|Blech|regelmäßig, glatt, refelktierend|37,4800638|16|City, Rural, Highway, Forest, Natural|x|360°|0,266524898|||||||
|8|buildings|church spires|15|300|h=40 x w=8m|320|YZ|20,26666667|0,071111111|2D/3D||nein|Holz, Beton, Metall|regelmäßig, glatt, matt|0,357201812|100|City, Rural, Highway |-|360°|0,254010178|||||||
|9|traffic restraint systems |traffic barrier|1,5|300|b=310 - 370,Upper edge=75|| XZ |54,24864375|0,180828813|2D/3D||ja|Metall|regelmäßig, glatt, matt|0,102073365|50|City, Rural, Highway|~|360°|0,184578054|||||||
|10|street lights|street lights|5|300|d_pole=8 |0,96|YZ|0,1888|0,00064|3D|Punkt / Kügel / Planar|nein|Metall, Glas|regelmäßig, glatt, matt|15,15151515|40|City|~|360°|0,096969697|||||||
|11|animal buildings|anthill|5|300|h=20 - 200|0,6|YZ|0,118|0,0004|3D||nein|Erde, Holz|unregelmäßig,-, matt|14,83239697|15|Forest, Natural|-|360°|0,059329588|||||||
|12|traffic restraint systems|noise barrier|5|300|h=3,5 x l=300||XY|125,965|0,419883333|2D||nein|Holz, Beton, Metall|regelmäßig, glatt, matt|0,003827751|80|City, Highway|-|Fahrtrichtung|0,016072089|||||||
|13|city furniture|trashcan|2|300|w=30 x h=60|0,18|YZ|0,0894|0,0003|3D||nein|Holz, Beton, Metall|regelmäßig / Unregelmäßig, glatt, matt|5,187082956|12|City|x|360°|0,015561249|||||||
|14|city furniture|advertising pillar|5|300|d=140 x h=310|4,34|YZ|0,853533333|0,002893333|2D/3D||nein|Holz, Beton, Metall|regelmäßig, glatt, matt|0,468640795|100|City|~|360°|0,01355934|||||||
|15|traffic sign|delinator|1,5|300|w=12 x h=100|0,12|YZ|0,0796|0,000266667|3D|Trieder|ja|Plastik,Reflektor|regelmäßig, glatt, refelktierend - matt|9,728867624|5|Rural, Highway|x|360°|0,012971823|||||||
|16|water bodies|river|5|300|l=30000 x w=500||XY|450000|1500|2D||nein|Water|unregelmäßig,-, matt|0,000629571|100|City, Rural, Highway, Forest, Natural|-|360°|9,443570817|||||||
|17|light signal systems|traffic lights|1,5|300|d=10 - 30|0,3|YZ|0,199|0,000666667|2D/3D|Rund(2D)|ja|Plastik, Glas|regelmäßig, glatt, matt|0,079744817|10|City, Rural, Highway|x|360°|0,000531632|||||||
|18|obstacles|big plant pot|1,5|300|h=60 x w=100|0,6|YZ|0,398|0,001333333|3D|Topf, rechteck|nein|Holz, Beton, Metall|regelmäßig, glatt, matt|-|-|City, Rural, Highway, Forest, Natural|-|360°|0|||||||
|19|miscellaneous|bale storage|5|300|d=150||YZ|||2D/3D||nein|-|-|-|-|-|-|360°||||||||
|20|orientation object|Mercedes star|2|300|d=100-300||YZ|||3D||nein|Holz, Beton, Metall|unregelmäßig, -, -|-|-|City, Rural, Highway, Forest, Natural|-|360°||||||||
|21|water bodies| waterway |3|300|w=2000||XY|||2D/3D||nein|Wasser|unregelmäßig, -, refelktierend-matt|0,011923445|100|City, Rural, Highway, Forest, Natural|-|360°||||||||
