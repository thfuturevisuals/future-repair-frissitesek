# Future Repair – frissítések

Innen frissül magától a telepített Future Repair (The Future Visuals Kft.): a program induláskor és
6 óránként megnézi a `manifest.json`-t, és ha újabb verziót talál, letölti, ellenőrzi az aláírását,
kipróbálja, majd a következő indításkor már azt használja.

- `manifest.json` – a legújabb kiadás aláírt leírása (a programok csak érvényes aláírásút telepítenek)
- `kiadasok/vX.Y.Z/` – a kiadások: a program kódja (`FutureRepair-app-X.Y.Z.zip`) és a leírása

Új gépre a telepítővel kerül fel a program (Windows: `FutureRepair-Telepito-X.Y.Z.exe`,
Mac: `FutureRepair-X.Y.Z-Mac.zip`), utána innen frissül.
