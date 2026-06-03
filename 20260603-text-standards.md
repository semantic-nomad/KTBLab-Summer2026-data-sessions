


# The data: Soil Core Profile (ID: S2026-04)

* **Profile ID:** S2026-04
* **Location:** Field Site Alpha
* **Classification:** Mollisol (Order)
* **Coordinates:** Latitude -40.35, Longitude 175.61
* **Horizons (The nested array/list part):**
  * **Horizon 1:** Name: "A", Depth: 0–15 cm, SOC (Soil Organic Carbon): 3.2%
  * **Horizon 2:** Name: "Bw", Depth: 15–45 cm, SOC: 1.1%
* **Site Notes:** "Crumb structure prominent; high root density, especially in top 10cm."

---

### 1. JSON 

```json
{
  "profile_id": "S2026-04",
  "location": "Field Site Alpha",
  "classification": "Mollisol",
  "coordinates": {
    "lat": -40.35,
    "lon": 175.61
  },
  "horizons": [
    { "name": "A", "top_cm": 0, "bottom_cm": 15, "soc_pct": 3.2 },
    { "name": "Bw", "top_cm": 15, "bottom_cm": 45, "soc_pct": 1.1 }
  ],
  "site_notes": "Crumb structure prominent; high root density, especially in top 10cm."
}
```

### 2. YAML 

```
profile_id: S2026-04
location: Field Site Alpha
classification: Mollisol
coordinates:
  lat: -40.35
  lon: 175.61
horizons:
  - name: A
    top_cm: 0
    bottom_cm: 15
    soc_pct: 3.2
  - name: Bw
    top_cm: 15
    bottom_cm: 45
    soc_pct: 1.1
site_notes: "Crumb structure prominent; high root density, especially in top 10cm."
```

### 3. TOML

```
profile_id = "S2026-04"
location = "Field Site Alpha"
classification = "Mollisol"
site_notes = "Crumb structure prominent; high root density, especially in top 10cm."

[coordinates]
lat = -40.35
lon = 175.61

[[horizons]]
name = "A"
top_cm = 0
bottom_cm = 15
soc_pct = 3.2

[[horizons]]
name = "Bw"
top_cm = 15
bottom_cm = 45
soc_pct = 1.1
```

### 4. XML
```
<?xml version="1.0" encoding="UTF-8"?>
<soil_profile id="S2026-04">
    <location>Field Site Alpha</location>
    <classification>Mollisol</classification>
    <coordinates>
        <lat>-40.35</lat>
        <lon>175.61</lon>
    </coordinates>
    <horizons>
        <horizon>
            <name>A</name>
            <top_cm>0</top_cm>
            <bottom_cm>15</bottom_cm>
            <soc_pct>3.2</soc_pct>
        </horizon>
        <horizon>
            <name>Bw</name>
            <top_cm>15</top_cm>
            <bottom_cm>45</bottom_cm>
            <soc_pct>1.1</soc_pct>
        </horizon>
    </horizons>
    <site_notes>Crumb structure prominent; high root density, especially in top 10cm.</site_notes>
</soil_profile>
```

### 5. DSVs

CSV (long format)
```
profile_id,location,classification,lat,lon,horizon_name,top_cm,bottom_cm,soc_pct,site_notes
S2026-04,Field Site Alpha,Mollisol,-40.35,175.61,A,0,15,3.2,"Crumb structure prominent; high root density, especially in top 10cm."
S2026-04,Field Site Alpha,Mollisol,-40.35,175.61,Bw,15,45,1.1,"Crumb structure prominent; high root density, especially in top 10cm."
```

TSV (long format)
```
profile_id	location	classification	lat	lon	horizon_name	top_cm	bottom_cm	soc_pct	site_notes
S2026-04	Field Site Alpha	Mollisol	-40.35	175.61	A	0	15	3.2	Crumb structure prominent; high root density, especially in top 10cm.
S2026-04	Field Site Alpha	Mollisol	-40.35	175.61	Bw	15	45	1.1	Crumb structure prominent; high root density, especially in top 10cm.
```