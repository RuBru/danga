---
title: Kur atrast Dangas tējas?
---
Dangas zāļu tējas iespējams iegādāties pirts lietu, garšvielu un citos vietējo ražotāju veikalos un tūrisma informācijas centros Daugavas kreisajā krastā. Regulāri braukājam arī pa gadatirgiem visā Kurzemē.

Un, protams, vienmēr priecājamies par ciemiņiem, kas iegriežas pie mums Kazdangā!

<link rel="stylesheet" href="https://unpkg.com/leaflet@1.4.0/dist/leaflet.css"
    integrity="sha512-puBpdR0798OZvTTbP4A8Ix/l+A4dHDD0DGqYW6RQ+9jxkRFclaxxQb/SJAWZfWAkuyeQUytO7+7N4QKrDh+drA=="
    crossorigin=""/>
<script src="https://unpkg.com/leaflet@1.4.0/dist/leaflet.js"
    integrity="sha512-QVftwZFqvtRNi0ZyCtsznlKSWOStnDORoefr1enyq5mVL4tmKB3S/EnC3rRJcxCPavG10IcrVGSmPh6Qw5lwrg=="
    crossorigin=""></script>

<div id="mapid" style="height: 380px;"></div>
<script>
    var mymap = L.map('mapid').setView([57.0000000, 22.6000000], 8);
    L.tileLayer('https://api.tiles.mapbox.com/v4/{id}/{z}/{x}/{y}.png?access_token={accessToken}', {
        attribution: 'Map data &copy; <a href="https://www.openstreetmap.org/">OpenStreetMap</a> contributors,<a href="https://creativecommons.org/licenses/by-sa/2.0/">CC-BY-SA</a>, Imagery © <a href="https://www.mapbox.com/">Mapbox</a>',
        maxZoom: 20,
        minZoom: 7,
        id: 'mapbox.streets',
        accessToken: 'pk.eyJ1IjoicnVicnUiLCJhIjoiY2pyMXNlNng4MHJjNjQ5cnVwOG42bjVrdSJ9.6liGxxe_Nday1-Vlyvqqpg'
    }).addTo(mymap);
// Home ikona
    var myIcon = L.icon({
	iconUrl: '/images/home_map.png',
	iconSize: [40, 40],
    iconAnchor: [25, 40],
    popupAnchor: [-6, -35]
    });
// Veikali
    var marker = L.marker([57.03697, 22.77587], {riseOnHover: true
    }).addTo(mymap);
        marker.bindPopup("<b>Dāvanu veikals</b><br>Kandava, Ūdens iela 2-2").openPopup();
    var marker = L.marker([56.92451, 24.10311], {riseOnHover: true
    }).addTo(mymap);
        marker.bindPopup("<b>Garšu bode</b><br>Rīga, Mūkusalas iela 72B").openPopup();
    var marker = L.marker([56.94260, 24.08025], {riseOnHover: true
    }).addTo(mymap);
        marker.bindPopup("<b>Latvijas brīnumzālītes</b><br>Rīga, Smiļģa iela 5").openPopup();
    var marker = L.marker([56.96827, 21.96544], {riseOnHover: true
    }).addTo(mymap);
        marker.bindPopup("<b>Baļļas</b><br>Kuldīga, Liepājas iela 24").openPopup();
    var marker = L.marker([56.72144, 21.60267], {riseOnHover: true
    }).addTo(mymap);
        marker.bindPopup("<b>Mētras māja</b><br>Aizpute, Pasta iela 1A").openPopup();
    var marker = L.marker([56.50771, 21.01234], {riseOnHover: true
    }).addTo(mymap);
        marker.bindPopup("<b>Liepājas reģiona tūrisma informācijas birojs </b><br>Liepāja, Rožu laukums 5/6").openPopup();
    var marker = L.marker([57.39758, 21.56631], {riseOnHover: true
    }).addTo(mymap);
        marker.bindPopup("<b>Amatu māja</b><br>Ventspils, Skolas iela 3").openPopup();
    var marker = L.marker([56.51560, 21.01372], {riseOnHover: true
    }).addTo(mymap);
        marker.bindPopup("<b>Bitīte un medutiņš </b><br>Liepāja, Raiņa iela 9").openPopup();
// Razotne
    var marker = L.marker([56.72957, 21.72763], {
        icon: myIcon,
        riseOnHover: true
        }).addTo(mymap);
        marker.bindPopup("<b>Dangas tēju ražotne</b><br>Dārza gatve 4, Kazdanga").openPopup();
</script>

<hr class ="mt-5 mb-5">
<div class ="post-page text-center"><h3 id="Kontakti">Kontakti</h3></div>
<p>Aija Brūna
aija.bruna<span style="display:none">foo</span>@inbox.lv
Dārza gatve 4, Kazdanga,
Kazdangas pag., Aizputes nov.,
LV-3457</p>