# test-glfs
Test Git Large File Storage (LFS) 

# PR erste commit
Sarawak_Orang_Ulu_leg_tattoo_examples_(29151787612).jpg als Git LFS
Source: https://commons.wikimedia.org/wiki/File:Sarawak_Orang_Ulu_leg_tattoo_examples_(29151787612).jpg

# Doku
https://git-lfs.github.com/

# PR zweite test commit, Bild oben mit git modifiziert

# PR drite test commit, Bild oben mit git modifiziert.
Wenn man von woanderes clone schein nur die letzte Bild download zu sein. Wenn man ein git checkout zu erste Bild Version, download from Github LFS die alte Version. Aber die locale .git Repository groß zu viel, als es local die Bilder auch hätte. Auch auf der enferne Rechner. 

# PR neue clone von andere Server, wo die Bilder nicht modifiziert würden.
Die neue clone .git sind 13M, 26 das ganze Ornder.
Die original repository wo die Bilder geändert würden dagegen: 39M in.git, 52M das ganze Ornder. 
Es bring schon was. Aber nicht so viel wie git-annex, wo die Bilder nicht git locale git landen. 
Aber für der Betribsystem ist transparent, anderes als die symbolische Links von git-annex. 
Wir könnten also gut nutzen.

# PR: clon von ein Server ohne git-lfs Package installiert. Keine Fehlermeldung, so sieht es das Bild aus:

   cat Sarawak_Orang_Ulu_leg_tattoo_examples_\(29151787612\).jpg 
   version https://git-lfs.github.com/spec/v1
   oid sha256:83d31fb14cd9c01992aa6bed5e5775e701c445dda792ec7ec7cbd8289f565ec2
   size 13209334

Das wäre für die Dev Laptops evtl. ein Vorteil. Die .git Repository hat jezt keine Bilder, 
man sieht es im locale Browser nicht, aber dafür nimmt das ganze ganz wenig Platz. 
