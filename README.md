# NASA-meteorite-analysis

![alt text](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/Hoba_meteorite_%2815682150765%29.jpg/330px-Hoba_meteorite_%2815682150765%29.jpg)

This is a quick python based analysis of NASA meteorite dataset.

The aim of this file is to analyse a dataset that compiles the characteristics of all known meteorite landings. For each landing, the type of meteorite, mass, year of landing and position of landing are given. In addition to this, identification (a name and number) are provided for each meteorite along with whether the meteorite has weathered and become unclassifiable (relict) since landing and if the meteorite was observed falling or was found after it fell.


Following is the description of the column heading of the dataset:


* **name:** the name of the meteorite
* **id:** a unique identifier for the meteorite
* **nametype:** one of:
-- valid: a typical meteorite
-- relict: a meteorite that has been highly degraded by weather on Earth
* **recclass:** the class of the meteorite; one of a large number of classes based on physical, chemical, and other characteristics (see the Wikipedia article on meteorite classification for a primer)
* **mass:** the mass of the meteorite, in grams
* **fall:** whether the meteorite was seen falling, or was discovered after its impact; one of:
-- Fell: the meteorite's fall was observed
-- Found: the meteorite's fall was not observed
* **year:** the year the meteorite fell, or the year it was found (depending on the value of fell)
* **reclat:** the latitude of the meteorite's landing
* **reclong:** the longitude of the meteorite's landing
* **GeoLocation:** a parentheses-enclose, comma-separated tuple that combines reclat and reclong


I encourage you to fork it out and add more analysis and let me know. There's always more to learn!
