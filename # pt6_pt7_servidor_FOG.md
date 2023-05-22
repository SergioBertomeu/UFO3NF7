# pt6_pt7_servidor_FOG

![Selecció_1751](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/5ce3cb27-35e2-43f5-afff-11ec129c8f02)


## Servidor d’Imatges

1. [Instal·lar i configurar un servidor FOG](#ref1)
2. [Capturar des del client un Windows](#ref2)
3. [Capturar des del client un Ubuntu](#ref3)
4. [Instal·lar imatge Windows](#ref4)
5. [Instal·lar imatge Ubuntu](#ref5)
6. [Llençar un paquet per a que s’instal·li als clients](#ref6)



##  Instal·lar i configurar un servidor FOG <a name="ref1"></a>

Per començar afegirem un altre adaptador de xarxa a la màquina client, on la posarem amb Xarxa interna.
![Selecció_1752](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/a04d367e-4306-4459-915d-7afd6907689e)


Per aquesta xarxa interna li assignarem una direcció IP estàtica.

![Selecció_1753](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/31a2e133-8077-4650-b19c-8c07d9ab39f6)


Un cop tenim la interfície configurada anirem a la pàgina oficial del fog i ens el descarregarem

![Selecció_1754](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/544f496c-0900-493c-ae7f-b211fb4ee6fc)


Descomprimirem el fitxer que ens hem baixat i l’executarem.
![Selecció_1755](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/1d5bf925-d24f-4569-b82e-122fbf5c255a)

![Selecció_1756](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/61424f74-d052-4a31-9bf8-3a1c58b6b457)


Escollirem l’opció 2 ja que estem utilitzan Ubuntu com a servidor.

![Selecció_1757](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/4177994b-d3d2-400e-ab7b-ef3953bc26f5)


configurat i li indicarem com a DHCP la direcció de la nostra xarxa interna.

![Selecció_1533](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/5716020a-2442-4624-b5a0-56a5b1eb2cf5)

Ens sortiran les dades de tot el que hem configurat, en veure que està tot correcte continuarem.

![Selecció_1534](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/597907d1-9f4d-499e-ad65-f259cf7c7e73)


Ens sortirà l’adreça on configurarem el fog de forma gràfica.

![Selecció_1535](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/840d05fd-5fc1-490d-a9e6-c26f71985007)

Accedirem a aquesta adreça i li donarem a Install.

![Selecció_1536](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/0791f8a5-0904-488f-961f-48dfc301fb3a)

Un cop instal·lat li donarem a Enter per continuar.

![Selecció_1537](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/07abb038-6961-47ba-b2e3-f4eedc050041)

Un cop està tot instal·lat ens donarà les dades per accedir dins del fog. 

![Selecció_1538](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/13b82ef0-726c-4d33-a12b-7acc71892658)

Accedirem al panel del fog i posarem les dades de l’usuari que ens han donat.

![Selecció_1539](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/d85b041a-c1d9-4fb5-ab4d-bea6cec1cce9)

I ja estem dins del panel.

![Selecció_1540](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/8a2d786b-7e71-4239-8117-22df76104a38)


Ara crearem les imatges de l'Ubuntu i del Windows, ens anirem a Images i Create New Image.


![Selecció_1541](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/446788d1-5d8d-4b04-9243-0c5d564aa0fb)


Per a la de Windows li posarem de nom Windows10 i seleccionarem que sigui Multiple Partition Image Single Disk.

![Selecció_1542](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/bd05682f-f0ec-4249-8721-bead0e9c12c9)


Afegirem la màquina Windows de forma manual, anirem a Hosts i Create New Host.

![Selecció_1543](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/cf0ffe9f-8c2f-47bc-a7d9-3ea78a1b7748)


Li posarem de nom Windows 10 i la seva adreça MAC.


![Selecció_1544](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/519570fb-3b54-4b12-abc5-7f962bc6f4e1)

Li donarem a la icona groga que és la de capture, farà que ens copie la imatge de la màquina Windows.

![Selecció_1545](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/6143e06d-441e-4968-aee3-0b5c7cdafb27)

Confirmarem la tasca donant-li a Task.

![Selecció_1546](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/42a5aef8-75d8-4f67-9973-d70398d0cb59)


I ja tenim creada la tasca per a que ens copie la imatge del Windows 10.


![Selecció_1547](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/31771a12-5124-4794-8e1b-d4268ae6a65b)

Aquí farem el mateix però amb la màquina ubuntu, primer vaig fer la màquina Windows i després la Linux més abaix veurem com es creen les imatges.

![Selecció_1548](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/6a35b0f8-1058-4776-9116-ea75d9bf1325)


![Selecció_1549](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/89756894-c622-406a-a777-df73b3a1725f)

![Selecció_1550](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/c52fc63a-fb8d-43f7-b040-814138fa7f22)

![Selecció_1551](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/0f0e6814-bb4f-4ca0-a6b8-42318c5bd828)



##  Capturar des del client un Windows <a name="ref2"></a>

Amb els passos anteriors de la creació de la imatge iniciarem la màquina Windows per lan.

![Selecció_1595](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/b5b7dfd9-1b84-42fe-8f58-312fe8e0badb)



Ens sortirà aquesta finestra on podem veure que el servidor fog funciona

![Selecció_1596](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/930ff562-7003-40f1-907f-44a99314bf69)


El servidor fog automàticament començarà fer la imatge del client

![Selecció_1597](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/266d06b7-3b83-4dcb-9804-c2a2c30b4911)

Un cop acabi es reiniciarà la màquina

![Selecció_1598](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/27c6b8a4-2a99-453d-bd49-cb0c306f1648)

I des del servidor fog en anar a Images, podem veure com tenim creada la imatge.

![Selecció_1599](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/7678be40-0bb2-4031-9e69-1ad1bcf43da3)



##  Capturar des del client un Ubuntu <a name="ref3"></a>

Com hem fet amb el Windows, iniciarem l’Ubuntu per lan

![Selecció_1600](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/d869539f-fe93-45db-be82-3d58e43b777c)

Ens tornarà a sortir la finestra del fog funcionant

![Selecció_1601](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/8e630df3-49b9-4c21-9699-14fe2da5c202)


I com a acabat de fer la imatge

![Selecció_1602](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/56b830d3-45b7-4fc7-942b-a27cd0147d6d)




##  Instal·lar imatge Windows <a name="ref4"></a>

Per instal·lar les imatges he creat unes màquines virtual noves sense cap sistema operatiu, le iniciat amb lan com les anteriors.

![Selecció_1609](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/114019cc-9256-4e5f-a57e-1b10540b7512)

Ens tornarà a sortir la finestra del fog funcionant

![Selecció_1610](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/ff554ab2-57fb-43e9-91f8-27561af5ca5b)


Ens sortirà aquest menú i li donarem a Deploy image

![Selecció_1611](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/cf71592e-7589-4f2d-aa53-504e582e8d1a)


Ens demanarà l’usuari i la contrasenya del fog

![Selecció_1612](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/20d2cf5b-cf2f-4910-a490-581fd0e7d6b5)

I seleccionarem la del Windows 10 (només apareix aquesta perquè vaig fer tot el Windows seguit

![Selecció_1613](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/0bd23dc9-1eb5-47b0-87d0-ce307f667e71)


Ens sortirà aquesta finestra com quan hem fet la imatge

![Selecció_1614](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/92c25187-9438-44ac-88d7-350963b3fa65)


I es reiniciarà la màquina en acabar

![Selecció_1615](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/672eb688-a32a-418b-af4f-c94acb25e253)

Aquí veiem les màquines que hem usat per crear la imatge i per restaurar-la

![Selecció_1616](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/80c7031c-3569-4389-b6c0-0735131ff1eb)




##  Instal·lar imatge Ubuntu <a name="ref5"></a> 

Com he fet amb la màquina Windows, he creat una nova màquina sense sistema operatiu i le iniciat per lan

![Selecció_1617](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/c95a367e-dc09-435f-a9c0-a9050fb63fe2)

Ens tornarà a sortir la finestra del fog funcionant

![Selecció_1618](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/06947403-8df6-4d93-94c2-4f6e270c05a5)


Ens sortirà aquest menú i li donarem a Deploy image

![Selecció_1619](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/16805d64-51bd-49c0-bead-6d167492f353)


Ens demanarà l’usuari i la contrasenya del fog

![Selecció_1620](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/60143444-b5ed-4dbf-b936-d65a1bce3a3c)


I seleccionarem la del Ubuntu

![Selecció_1621](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/782d6817-1efb-4d16-be73-dc3ed0de41cd)

![Selecció_1622](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/5a0aac52-00a6-4759-9e41-788fb76e053c)

I es reiniciarà la màquina en acabar

![Selecció_1623](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/856901c3-5f8f-44a3-9f30-08a7043ea457)

Aquí veiem les màquines que hem usat per crear la imatge i per restaurar-la

![Selecció_1624](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/80d10230-18eb-41e7-ab46-09a3f57ba1af)




##  Llençar un paquet per a que s’instal·li als clients <a name="ref6"></a>


Primer que res per al client Windows haurem d'instal·lar el client fog perquè ens funcioni

![Selecció_1625](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/e387bbe4-46b0-4996-8710-e0df112b6091)

![Selecció_1626](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/924208a0-9b96-4df2-8452-c4747244bd1a)

Haurem de posar l’adreça IP que té el nostre servidor fog i continuarem

![Selecció_1627](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/2a5c168d-8dfa-4c56-85ee-d62727c479b8)

![Selecció_1628](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/58349790-7da2-476b-b9de-a49101f0df19)


Un cop instal·lat comprovarem que el servei fog està activat

![Selecció_1629](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/597608c3-8351-4941-8cc8-229ca9ec4449)


Ara que tenim el client instal·lat anirem al servidor fog, anirem a Snapis, Create New Snapin, seleccionarem de tipus MSI i li posarem un paquet msi que ens hem baixat

![Selecció_1630](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/f6cdfe56-d41c-465b-9538-91390721b7fe)


Anirem a Hosts i entrarem dins del Windows 10

![Selecció_1631](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/0808f9e6-3834-4125-94b8-83bc3176f5f0)

Anirem dins de Snapins i afegirem el que acabem de crear


![Selecció_1568_2023](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/b2265ab1-9c95-4c6e-94c2-ddadda34822a)

Després anirem a tasques i Single Snapin

![Selecció_1632](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/aaec9631-ab22-49c3-ae40-da59fe98856f)

Seleccionarem el snapin que acabem de crear i li donarem a Task

![Selecció_1633](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/481fb431-7885-4b9b-8ef0-5c2f2f8ab3eb)

I es crearà la tasca per instal·lar aquest snapin

![Selecció_1634](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/5e2c653d-0f86-4bf0-a3ea-2dff6c770ec3)

Anirem a tasques i esperarem


![Selecció_1569_2023](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/19336359-6ec5-47fd-a5b1-2d95d0706c69)

Al cap d'uns intents al final va funcionar


![Selecció_1570_2023](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/ab5147d5-4536-4650-87e8-4a8be909660f)


I al entrar al client podem veure que s’ha instal·lat el Mozilla

![Selecció_1635](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/00c99c20-4413-499f-af60-a8cd3fa91b37)


Per al client Ubuntu també haurem d'instal·lar el client fog perquè ens funcioni, primer haurem d'instal·lar l'aplicació mono per poder executar el .exe del client fog

![Selecció_1636](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/470854c5-fe39-4e5f-95a2-95c3306e063e)

![Selecció_1637](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/d92b2e6a-0cd2-4275-a70b-f9127c4b4a67)

![Selecció_1638](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/127ae190-b0c6-478f-9475-8da764c201e0)

![Selecció_1639](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/4845efdb-4bcb-4fdf-a104-d6dddc782667)

Un cop tenim el mono instal·lat amb un wget baixarem el client del fog del nostre servidor i executarem el client amb el mono

![Selecció_1640](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/5aa85c6b-049f-4725-a6ff-7be0f42b607d)

Li posarem l’adreça IP del nostre servidor i ens preguntarà si volem iniciar el servei fog quan acabi la configuració

![Selecció_1641](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/fa756e38-cc16-4f0e-82be-632f29cd4a9d)


Ens sortirà aquest error del certificat, però ell mateix instal·larà aquest certificat


![Selecció_1571_2023](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/5e7fab72-148e-4981-95c8-904a7a50e605)

Un cop tenim el client preparat anirem al servidor i ens descarregarem el .deb que volem instal·lar, el posarem dins del directori on està l'apache perquè el puguem enviar al client

![Selecció_1642](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/59a1bdea-c828-488d-9b29-accf1f429fd5)

També crearem un script per a poder instal·lar el paquet al client, aquest script el que farà serà enviar el paquet .deb del servidor al client i instal·lar-lo

![Selecció_1643](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/8d90b033-8c5c-4eca-acab-d45798690d2a)


![Selecció_1644](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/2deec6b9-b507-49bb-bffd-2dfb010356ac)


Anirem dins del host del Ubuntu


![Selecció_1572_2023](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/c06ca6d1-b12e-4ae8-aa22-61528c6d541f)

Dins de snapins seleccionarem el snapin que hem creat l’afegirem al client



![Selecció_1573_2023](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/01528dd4-7194-4231-9eff-18ea8972a5e5)


Anirem dins de les tasques del client, seleccionarem el snapin i iniciarem la tasca

![Selecció_1645](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/914b6d70-55e8-4c53-abf7-e3db99f0d74c)

No em funcionava perquè el client tenia un nom diferent del nom de la màquina registrada al server fog i em donava un error, ha sigut posar-lo igual i funcionar!

![Selecció_1575_2023](https://github.com/SergioBertomeu/UF1MP3mkdocsmarkdown/assets/91250228/76f3224a-eaf0-4d66-b80b-3043d526f8cf)







