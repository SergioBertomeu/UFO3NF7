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


Escollirem l’opció 2 ja que estem utilitzan Ubuntu com a servidor

![Selecció_1757](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/9368bd31-37d7-4cb3-a0bb-24880f22996f)


configurat i li indicarem com a DHCP la direcció de la nostra xarxa interna

![Selecció_1758](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/8aa5d058-7748-4964-b490-b7786e77567e)


Ens sortiran les dades de tot el que hem configurat, en veure que està tot correcte continuarem

![Selecció_1759](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/29aac43c-84fc-4892-ab1a-aec40f88b2cd)


Ens sortirà l’adreça on configurarem el fog de forma gràfica

![Selecció_1760](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/e10a5446-f92e-4e0d-bcd6-205fc562d408)


Accedirem a aquesta adreça i li donarem a Install

![Selecció_1761](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/568e3ffe-9f35-4c12-97e6-004a43079f51)


Un cop instal·lat li donarem a Enter per continuar

![Selecció_1762](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/aa281571-76c8-4f99-acde-bad2979e7427)



Un cop està tot instal·lat ens donarà les dades per accedir dins del fog

![Selecció_1763](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/857d4e0c-9616-4924-a5ba-adeae1f4b53b)



Accedirem al panel del fog i posarem les dades de l’usuari que ens han donat

![Selecció_1764](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/21c84e76-2a79-44fd-a733-2056a7714c4f)




I ja estem dins del panel

![Selecció_1765](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/65bce335-d5dd-40ea-ae7f-e1a9d21fb769)



Ara crearem les imatges de l'Ubuntu i del Windows, ens anirem a Images i Create New Image

![Selecció_1766](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/e3f8f523-a25c-450c-9b32-36366b56a558)


Per a la de Windows li posarem de nom Windows10 i seleccionarem que sigui Multiple Partition Image Single Disk

![Selecció_1767](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/b49868bd-3d65-4c3b-bc0c-c266a298064b)



Afegirem la màquina Windows de forma manual, anirem a Hosts i Create New Host

![Selecció_1768](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/9ab2500f-ff2d-477a-927e-bb1ba48acad5)



Li posarem de nom Windows 10 i la seva adreça MAC
![Selecció_1769](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/7f525423-5ca3-41aa-b6b1-094115794fba)



Li donarem a la icona groga que és la de capture, farà que ens copie la imatge de la màquina Windows

![Selecció_1770](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/6c9dc3bb-529c-4c01-870f-f4efb8e39492)



Confirmarem la tasca donant-li a Task

![Selecció_1771](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/11fbe954-9dbd-45a6-8e93-6739aa421318)



I ja tenim creada la tasca per a que ens copie la imatge del Windows 10

![Selecció_1772](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/28244c97-d211-4f64-bfcf-751e49f81ae4)


Aquí farem el mateix però amb la màquina ubuntu, primer vaig fer la màquina Windows i després la Linux més abaix veurem com es creen les imatges


![Selecció_1773](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/be7a0d7b-c294-4a12-8af4-f98f5caf20ba)




![Selecció_1774](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/a4465957-3b57-42d6-b14e-b9ecff739dda)




![Selecció_1775](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/23ad3747-afa0-42d8-953e-6e4c85f9d9b2)


![Selecció_1776](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/2c34d0ca-6e8d-4321-9e32-d775b266a231)


##  Capturar des del client un Windows <a name="ref2"></a>

Amb els passos anteriors de la creació de la imatge iniciarem la màquina Windows per lan

![Selecció_1777](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/94b95653-ab36-4b37-9071-ae0294bdde81)



Ens sortirà aquesta finestra on podem veure que el servidor fog funciona

![Selecció_1778](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/3c79bb9d-c0ed-4d6e-98a0-1d047daa1754)


El servidor fog automàticament començarà fer la imatge del client

![Selecció_1779](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/9887645a-8fdf-4974-8d49-53eb33012ef4)



Un cop acabi es reiniciarà la màquina

![Selecció_1780](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/77c03b4f-c661-4551-9586-69b4c6ba4036)



I des del servidor fog en anar a Images, podem veure com tenim creada la imatge


![Selecció_1781](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/b4882097-79d1-497a-be54-870a2b3d2864)




##  Capturar des del client un Ubuntu <a name="ref3"></a>

Com hem fet amb el Windows, iniciarem l’Ubuntu per lan

![Selecció_1782](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/82939437-e966-4489-82fc-3fcb3c63dbdc)


Ens tornarà a sortir la finestra del fog funcionant

![Selecció_1783](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/1e66367e-d45f-4d58-a428-225f685a69da)


I com a acabat de fer la imatge


![Selecció_1784](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/b2ee961a-51b9-401f-b990-be3c517bc3b9)






##  Instal·lar imatge Windows <a name="ref4"></a>

Per instal·lar les imatges he creat unes màquines virtual noves sense cap sistema operatiu, le iniciat amb lan com les anteriors

![Selecció_1785](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/64c168ea-3e2f-4756-a037-4bba555e8a82)



Ens tornarà a sortir la finestra del fog funcionant

![Selecció_1786](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/82b86844-2692-4ae8-8cca-cb828619c271)



Ens sortirà aquest menú i li donarem a Deploy image

![Selecció_1787](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/85f97b08-e4c5-4563-b8ef-6c194c0aeee1)



Ens demanarà l’usuari i la contrasenya del fog

![Selecció_1791](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/e6c078bd-253d-4c7f-8a20-3da6fde8bc9b)



I seleccionarem la del Windows 10 (només apareix aquesta perquè vaig fer tot el Windows seguit


![Selecció_1792](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/02925e98-192e-4eb2-8bfe-1be6a21a312f)



Ens sortirà aquesta finestra com quan hem fet la imatge

![Selecció_1793](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/dd3d186e-ef63-4b4e-a3d6-fb72dc767091)


I es reiniciarà la màquina en acabar

![Selecció_1794](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/1c8b8498-a819-487d-b86f-674f8c85fc89)



Aquí veiem les màquines que hem usat per crear la imatge i per restaurar-la




![Selecció_1795](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/91f8d70b-5a83-419b-a1cc-d2c5f696fa9d)






##  Instal·lar imatge Ubuntu <a name="ref5"></a>


Com he fet amb la màquina Windows, he creat una nova màquina sense sistema operatiu i le iniciat per lan

![Selecció_1796](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/f18d6f3c-67d9-4b93-a87e-dd780b5e8211)



Ens tornarà a sortir la finestra del fog funcionant

![Selecció_1797](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/4df5c0fd-b94f-4565-a833-69f2da63be73)


Ens sortirà aquest menú i li donarem a Deploy image

![Selecció_1798](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/148a5f3b-adc2-42ea-9c24-97456f29c82b)


Ens demanarà l’usuari i la contrasenya del fog

![Selecció_1799](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/437230b7-89b1-459a-9089-3aaf0bfca50d)


I seleccionarem la del Ubuntu


![Selecció_1800](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/27659ffd-87b8-4b77-8109-442fbf57ec6a)


![Selecció_1801](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/67ae1ea8-7765-4b0d-8848-4f4e543f0451)



I es reiniciarà la màquina en acabar

![Selecció_1802](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/761db7ba-dae2-46ca-996b-47db17bf50aa)



Aquí veiem les màquines que hem usat per crear la imatge i per restaurar-la


![Selecció_1803](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/aca7922d-b169-4d4b-a4ea-453ac42560a6)













##  Llençar un paquet per a que s’instal·li als clients <a name="ref6"></a>

Primer que res per al client Windows haurem d'instal·lar el client fog perquè ens funcioni

![Selecció_1804](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/c4b9903b-d7cd-40e0-a5ca-8106b0ddc66a)

![Selecció_1805](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/36acfd5e-03b6-40bc-a74d-abce26a8a9fa)



Haurem de posar l’adreça IP que té el nostre servidor fog i continuarem

![Selecció_1806](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/29d37ce1-e3c9-46cf-acf9-7187fc55e798)


![Selecció_1807](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/8445c1c2-52ad-46a2-afa6-fdb1a13697dd)


Un cop instal·lat comprovarem que el servei fog està activat

![Selecció_1808](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/6dae4063-b032-4a6c-b94b-a56f63f88f68)


Ara que tenim el client instal·lat anirem al servidor fog, anirem a Snapis, Create New Snapin, seleccionarem de tipus MSI i li posarem un paquet msi que ens hem baixat

![Selecció_1809](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/68b7a487-4084-4c24-ac05-11ffc2c74c28)


Anirem a Hosts i entrarem dins del Windows 10

![Selecció_1810](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/9381cd9f-bf4a-4d7c-a106-993b07ca615a)



Anirem dins de Snapins i afegirem el que acabem de crear

![Selecció_1811](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/f7aae252-ec98-48df-9d11-3556abacfb56)


Després anirem a tasques i Single Snapin

![Selecció_1812](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/400f9c9b-bc8e-4eeb-92f1-5f24ac9208d6)


Seleccionarem el snapin que acabem de crear i li donarem a Task

![Selecció_1813](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/66fae795-b9f0-419b-b9b9-945c5b0e6b80)


I es crearà la tasca per instal·lar aquest snapin

![Selecció_1814](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/4a509e0c-c9ff-47f2-89aa-ed962f3efa7d)

Anirem a tasques i esperarem

![Selecció_1815](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/159d6430-9c2e-410b-82e7-a959de83b05b)


Al cap d'uns intents al final va funcionar

![Selecció_1816](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/99b4854e-23d4-4f91-9ba7-c81b49454af8)


I al entrar al client podem veure que s’ha instal·lat el Mozilla

![Selecció_1817](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/c8003e2b-e69b-4984-b6a3-31cdcfc57b2d)


Per al client Ubuntu també haurem d'instal·lar el client fog perquè ens funcioni, primer haurem d'instal·lar l'aplicació mono per poder executar el .exe del client fog

![Selecció_1818](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/d070ba46-8129-4bc1-b299-bdb4263f8abb)


![Selecció_1819](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/f82501c8-975f-484b-9fa7-9cb460be390f)

![Selecció_1820](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/ab6c7eb7-b2a4-47b2-940f-1c9dffa21d96)



Un cop tenim el mono instal·lat amb un wget baixarem el client del fog del nostre servidor i executarem el client amb el mono

![Selecció_1821](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/c1b17f82-4ee5-4fc8-b011-f9e2780433bf)


Li posarem l’adreça IP del nostre servidor i ens preguntarà si volem iniciar el servei fog quan acabi la configuració

![Selecció_1822](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/ba7b0667-6108-4f50-825b-136f26cc9ddb)

Ens sortirà aquest error del certificat, però ell mateix instal·larà aquest certificat

![Selecció_1823](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/5326ae45-af31-4394-8ebf-1802965a6e30)



Un cop tenim el client preparat anirem al servidor i ens descarregarem el .deb que volem instal·lar, el posarem dins del directori on està l'apache perquè el puguem enviar al client

![Selecció_1824](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/e6d19703-e102-4719-8207-338451d74c03)


També crearem un script per a poder instal·lar el paquet al client, aquest script el que farà serà enviar el paquet .deb del servidor al client i instal·lar-lo

![Selecció_1825](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/e9b6adf8-55f1-4fbe-88ac-5165d7a9653f)



Anirem dins del host del Ubuntu

![Selecció_1826](https://github.com/SergioBertomeu/UFO3NF7/assets/91250228/25d6ab43-df48-4b6d-b60a-7bffea9c98c9)


Dins de snapins seleccionarem el snapin que hem creat l’afegirem al client



Anirem dins de les tasques del client, seleccionarem el snapin i iniciarem la tasca



No em funcionava perquè el client tenia un nom diferent del nom de la màquina registrada al server fog i em donava un error, ha sigut posar-lo igual i funcionar!










